# How to setup build environment on Mac OS X
# Build yourself
 (followed by appended stub on MS Windows firmware upgrade? -24-10.13)
## Setup for Mac OS X

1. Install the latest FTDI serial driver: [http://www.ftdichip.com/Drivers/VCP/MacOSX/FTDIUSBSerialDriver_v2_2_17.dmg](http://www.ftdichip.com/Drivers/VCP/MacOSX/FTDIUSBSerialDriver_v2_2_17.dmg)
1. Install Arduino sources: [https://arduino.googlecode.com/files/arduino-1.0.4-src.tar.gz](https://arduino.googlecode.com/files/arduino-1.0.4-src.tar.gz)
1. Install CrossPack for AVR Development (contains avrdude command and AVR cross-compiler): http://www.obdev.at/products/crosspack/index.html
1. Edit your environment $HOME/.bashrc to add the following lines:

         export ARDUINODIR=$HOME/arduino-1.0.4/
         export BOARD=fio

1. Restart a new terminal window

## Build and upload the bGeigieNano software

1. Download latest software: [https://github.com/Safecast/bGeigieNanoKit/archive/master.zip](https://github.com/Safecast/bGeigieNanoKit/archive/master.zip)
1. Build and upload the software:

         cp -r libraries $HOME/arduino-1.0.4/
         make
         make upload

# Use prebuild image

## Setup for Mac OS X

1. Install the latest FTDI serial driver: http://www.ftdichip.com/Drivers/VCP/MacOSX/FTDIUSBSerialDriver_v2_2_17.dmg
1. Install CrossPack for AVR Development (contains avrdude command and AVR cross-compiler): http://www.obdev.at/products/crosspack/index.html

## Upload the bGeigieNano software

From a terminal type the following commands, 

1. to find which usb device the arduino is connected on (you should get something like /dev/tty.usbserial-A700eYeV)

         ls /dev/tty.usbserial*

1. to download the lastest firmware for Arduino Fio

         wget https://github.com/Safecast/bGeigieNanoKit/raw/master/bGeigieNano.hex

1. to upload the firmware to the Arduino Fio

         /usr/local/bin/avrdude -DV -p atmega328p -P /dev/tty.usbserial-A700eYeV -c arduino -b 57600 -U flash:w:bGeigieNano.hex:i




# How to setup build environment on MS Windows
[for pc users, Stub-draft, note query, appended here to above firmware on MAC page, 24-10-2013]

For firmware setup in MS Windows, apparently one has to modify the above MAC instructions with the following recommendations (quoting from Jul 21 and Aug 6 comments from a thread which began on 2013-07-06 entitled "V1.2.6" as posted on the Safecast Device Discussions and Support group,   https://groups.google.com/forum/?hl=en#!topic/safecast-devices/106n-Bs3v-Q

>>Jul 21> You will need to have FTDI driver from here;
http://www.ftdichip.com/Drivers/VCP.htm

>>Then, you will have to follow something similar to this instruction from Adafruit;
http://ladyada.net/learn/avr/avrdude.html

>>You will need avrdude;
http://savannah.nongnu.org/projects/avrdude

>>Aug 6> For a Windows PC it is very easy to upload an HEX file into a bGeigeiNanao.
http://xloader.russemotto.com/
<<


[A few notes, newbie interpretation of above)]

Download the xloader.zip ; unzip. (The XLoader folder includes avrdude files and DEVICES.TXT which provide hardware options for the XLoader menu.)

The FTDI driver is for communication between pc and nano via the USB cable. (Besides recharging the battery, the Nano's usb cable does file transfer, here for loading ﬁrmware from pc to the Arduino FIO.  (Not to be confused with the audio cord which can be used for data transfer to API on iPhone, iPad, or Mac...)

[When stuck RTM and ask support. If still in doubt ask your local help?)] 