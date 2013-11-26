# How to setup build environment on Mac OS X
*(draft rev.1.11.13)*

>>Load firmware with an accessory FTDI breakout board 3.3V, for example this [[one| https://www.sparkfun.com/products/9873]] or that [[one|https://www.adafruit.com/products/284]]; with correct FTDI driver; and with the Nano power switch turned OFF. 
>>(Further relevant photos can be found at [[Arduino Fio Sparkfun|https://www.sparkfun.com/products/10116]], at the guide on [[Arduino Fio Programming|http://arduino.cc/en/Main/ArduinoBoardFioProgramming]] or at Setup System programming bGeigie [[README.md|https://github.com/Safecast/SafecastBGeigie]].) 
*  For learning to compile source code, see http://www.ladyada.net/learn/avr/setup-mac.html.

>a) MAC - Build (from master by) yourself, or;

>b) MAC - Use prebuild image.

>c) MS Windows - Nano firmware installation


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
This firmware loading stub for MS Windows follows above on MAC build. To quote 3 helpful posts for pc users  in thread which began on [[2013-07-06 entitled "V1.2.6"|https://groups.google.com/forum/?hl=en#!topic/safecast-devices/106n-Bs3v-Q]] in the Safecast Device Discussions and Support group, from Jul 21, Aug 6 and Oct 25 2013:

>>Jul 21> You will need to have FTDI driver from here;
http://www.ftdichip.com/Drivers/VCP.htm

>>Aug 6> For a Windows PC it is very easy to upload an HEX file into a bGeigeiNano.
http://xloader.russemotto.com/

>>Oct 25> I used a Windows 7 64-bit system to do the upgrade. I downloaded and installed X-loader. I did not use the USB charging port on the Nano, but the 6 pin FTDI connector on the edge of the FIO. Purchase an FDTI breakout adapter https://www.sparkfun.com/products/9873      
 
>>When you plug this little FDTI breakout board onto the 6 pin header and then plug the recharging usb cable into your computer, the Nano will power up by itself (even though the Nano power switch is off).
 
>>I monitored device manager com ports to see the device appear and what com # Windows assigned to the device.
 
>>Then run X-loader, select com port, browse to HEX file (the **current version of the Nano firmware**  which is the [[bGeigieNano.hex file|https://github.com/Safecast/bGeigieNanoKit/blob/master/bGeigieNano.hex]] in the [[bGeigieNanoKit repository|https://github.com/Safecast/bGeigieNanoKit]]. *[Today's version, "HEX for 1.3.2".]*)

>>I'm pretty sure I selected in the drop down Duemilanove/nano(ATmega328) device.  I left the baud rate at 57600 and hit upload.   If I remember correctly when it was done, the Nano rebooted/restarted all by itself and was running the new code. (The startup screen displays the version number #.#.#.)

Also see Nov 16 report in "Just completed my first bGeigie build - having display problems and no GPS" [[devices thread|https://groups.google.com/forum/?hl=en#!topic/safecast-devices/UQWsWSkNBbY]] which began Nov 8 2013:
  
>All working now - followed instructions for firmware update via GitHub through Chrome browser.  Hex file found on github.com.  Downloaded Xloader and used it to flash (upload) 1.3.2.

>Sticking points (for newbies): Must use 3.3V FTDI cable and insert properly at angled header pins on FIO board - make sure to follow pinout labels for which end is black wire, which green.

>Leave Nano power switch OFF when connecting USB to PC.

>If you get the FTDI cable with the LED in the USB end, you will see light flashing when there is power and traffic while uploading happens - this helps as Xloader had a habit of getting hung up on first few attempts and would display "Uploading" when it had crashed until told to 'end task' through task manager.

>A restart was needed after drivers loaded automatically on Windows 7 Pro after first connecting FTDI cable and Nano.  Did not need drivers from mini CD that came with cable.

---------------------
Newbie notes on above: Download the xloader.zip ; unzip. The XLoader folder includes the avrdude files and also the DEVICES.TXT file which provides the hardware options for the XLoader menu. The FTDI driver is for communication between pc and nano best via the "6-pin length of angled male header on the FIO... which connects the FIO to a computer for programming".

The Arduino Fio uses ATmega328, according to the [[Sparkfun page|https://www.sparkfun.com/products/10116]] and this [[Arduino list|http://en.wikipedia.org/wiki/List_of_Arduino_boards_and_compatible_systems]].

The [[arduino.cc website|http://arduino.cc/]] has well recommended guides and help. For history  orientation see [[en.wikipedia on Arduino|http://en.wikipedia.org/wiki/Arduino]].

*Miscellaneous (extraneous and superfluous) alternatives may include system reconfiguration via the microSD card and wireless programming over an optional pair of XBee radios...* 