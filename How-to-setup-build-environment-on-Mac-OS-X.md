# How to setup build environment on Mac OS X

>>a) MAC - Build (from master by) yourself, or;

>>b) MAC - Use prebuild image.

>>c) MS Windows - Nano firmware installation

*[Load firmware with the Nano power switch off and with correct FTDI driver via FTDI-FIO 6-pin breakout adapter (https://www.sparkfun.com/products/9873), or; also [perhaps possible??] via recharging mini-USB port. See http://www.ftdichip.com/FTDrivers.htm.*]

*On programming Nano firmware, possibly see Setup System in the README.md at bottom of https://github.com/Safecast/SafecastBGeigie for photos and instructions on the bGeigie model ??]*

# a) Build yourself
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

# b) Use prebuild image

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
  
  
----
---- 
# c) MS Windows: Nano firmware installation
This firmware loading stub for MS Windows follows above on MAC build. To quote 3 helpful posts for pc users from Jul 21, Aug 6 and Oct 25, in thread which began on 2013-07-06 entitled "V1.2.6", in the Safecast Device Discussions and Support group, https://groups.google.com/forum/?hl=en#!topic/safecast-devices/106n-Bs3v-Q

>>Jul 21> You will need to have FTDI driver from here;
http://www.ftdichip.com/Drivers/VCP.htm

>>Aug 6> For a Windows PC it is very easy to upload an HEX file into a bGeigeiNano.
http://xloader.russemotto.com/

>>Oct 25> I used a Windows 7 64-bit system to do the upgrade. I downloaded and installed X-loader. I did not use the USB charging port on the Nano, but the 6 pin FTDI connector on the edge of the FIO. Purchase an FDTI breakout adapter https://www.sparkfun.com/products/9873      
 
>>When you plug this little FDTI breakout board onto the 6 pin header and then plug the recharging usb cable into your computer, the Nano will power up by itself (even though the Nano power switch is off).
 
>>I monitored device manager com ports to see the device appear and what com # Windows assigned to the device.
 
>>Then Run X-loader, select com port, browse to HEX file, and I'm pretty sure I selected in the drop down Duemilanove/nano(ATmega328) device.  I left the baud rate at 57600 and hit upload.   If I remember correctly when it was done, the Nano rebooted/restarted all by itself and was running the new code.

(Newbie notes on above: Download the xloader.zip ; unzip. The XLoader folder includes the avrdude files and also the DEVICES.TXT file which provides the hardware options for the XLoader menu. The FTDI driver is for communication between pc and nano best via the "6-pin length of angled male header on the FIO... which connects the FIO to a computer for programming". (The FTDI Basic Breakout for Arduino FIO 3.3V is not to be confused with the audio cord which is used for data transfer to API on iPhone, iPad, or Mac; nor with the mini-USB cable [which is mainly for power to battery??].)