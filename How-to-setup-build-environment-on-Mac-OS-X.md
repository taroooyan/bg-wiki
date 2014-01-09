#####**How to load Nano firmware upgrades & fixes (from filename "How to setup build environment on Mac OS X")**

- **1a. MAC - Build (from master by) yourself**
- **1b. MAC - Use prebuild image**
- **1c. MAC - Use uploader app**
- **2.  Linux**
- **3.  MS Windows 7 - Nano firmware installation**

**bGeigie Nano firmware loading (installation) requires:**
- an **FTDI breakout board 3.3V** (a small accessory tool: i.e. this [[one| https://www.sparkfun.com/products/9873]]; that [[one|https://www.adafruit.com/products/284]], or; combined in USB cable [[another one|http://www.amazon.com/GearMo%C2%AE-3-3v-Header-like-TTL-232R-3V3/dp/B004LBXO2A]]);
- a short length **USB-to-miniUSB cable**;
- the Nano power switch turned **OFF** before connecting (powers up from the FTDI breakout connection to computer's USB);
- **FTDI and AVR drivers** and the current version **Nano firmware**, which is the .hex file in the [[bGeigieNanoKit repository|https://github.com/Safecast/bGeigieNanoKit]]. ((1c)-mac uploader app automatically retrieves all software; (2) MS-Win XLoader includes AVR).

(See relevant photos at Sparkfun [[Arduino Fio |https://www.sparkfun.com/products/10116]], Arduino [[Fio Programming|http://arduino.cc/en/Main/ArduinoBoardFioProgramming]] or at Setup System programming bGeigie [[README.md|https://github.com/Safecast/SafecastBGeigie]].) 

Note for v.1.3.2 and higher: After you have applied the new firmware, you will need to reset the GPS unit to factory settings. To do so, remove the SD card and power on the nano. Wait for a minute, and then switch off the nano. The display will show a warning "No SD Card/GPS reset".  Insert the SD card and then switch on the nano and take it outside. The first GPS lock may take some time (a couple of minutes is typical but can be longer) Once locked, the next time you switch on, the lock should be immediate. *(Also in the [[Operation Manual|https://github.com/Safecast/bGeigieNanoKit/wiki/Nano-Operation-Manual]], see #4. Logging Mode: GPS Reset general re-initialization.)* 

## 1a) Build yourself (Mac OS X)
*(For learning to compile source code, see http://www.ladyada.net/learn/avr/setup-mac.html.)*

1. Install the latest FTDI serial driver: [http://www.ftdichip.com/Drivers/VCP/MacOSX/FTDIUSBSerialDriver_v2_2_17.dmg](http://www.ftdichip.com/Drivers/VCP/MacOSX/FTDIUSBSerialDriver_v2_2_17.dmg)
1. Install Arduino sources: [https://arduino.googlecode.com/files/arduino-1.0.4-src.tar.gz](https://arduino.googlecode.com/files/arduino-1.0.4-src.tar.gz)
1. Install CrossPack for AVR Development (contains avrdude command and AVR cross-compiler): http://www.obdev.at/products/crosspack/index.html
1. Edit your environment $HOME/.bashrc to add the following lines:

         export ARDUINODIR=$HOME/arduino-1.0.4/
         export BOARD=fio

1. Restart a new terminal window

### Build and upload the bGeigieNano software

1. Download latest software: [https://github.com/Safecast/bGeigieNanoKit/archive/master.zip](https://github.com/Safecast/bGeigieNanoKit/archive/master.zip)
1. Build and upload the software:

         cp -r libraries $HOME/arduino-1.0.4/
         make
         make upload

## 1b) Use prebuild image (Mac OS X)

1. Install the latest FTDI serial driver: http://www.ftdichip.com/Drivers/VCP/MacOSX/FTDIUSBSerialDriver_v2_2_17.dmg
1. Install CrossPack for AVR Development (contains avrdude command and AVR cross-compiler): http://www.obdev.at/products/crosspack/index.html

### Upload the bGeigieNano software

From a terminal type the following commands, 

1. to find which usb device the arduino is connected on (you should get something like /dev/tty.usbserial-A700eYeV)

         ls /dev/tty.usbserial*

1. to download the lastest firmware for Arduino Fio

         wget https://github.com/Safecast/bGeigieNanoKit/raw/master/bGeigieNano.hex

1. to upload the firmware to the Arduino Fio

         /usr/local/bin/avrdude -DV -p atmega328p -P /dev/tty.usbserial-A700eYeV -c arduino -b 57600 -U flash:w:bGeigieNano.hex:i


## 1c) Use uploader app (Mac OS X)
This uploader app will retrieve necessary software including the fdti driver, so it's a one button utility.
  
1. with the nano power OFF, connect the nano to mac with usb cable and the FTDI breakout board 3.3V;

2. on Mac browse to https://github.com/Safecast/bGeigieNanoKit/blob/master/bGeigeiNano_V1.3.5_uploader.app.zip and click on view RAW to download the executable zip file; 

3. Click on the downloaded file, bGeigeiNano_V1.3.5_uploader.app.zip, to Unzip the app;

4. Find and doubleclick on the "bGeigeiNano_V1.3.4_uploader" or current version "bGeigieNano_V1.#.#_uploader". (8-Jan-2014, the 1.3.5 app uses 1.3.4 version because of rollback of a data format change.)

The nano should soon power up with the new firmware version number displayed in the top line of splash screen "bGeigie 
Nano 1.#.#". If not, try again. (Report on devices group. Edit this wiki.)

(This uploader app for Mac users was written by Rob Oudendijk and first posted on 3 Jan 2014 in devices thread [["Successful Nano build, need help w/ GPS, Mac connection"|https://groups.google.com/forum/?hl=en#!topic/safecast-devices/QgIqj7bMzQI]].)

----
## 2) Linux
*Although Linux users may not need a guide to load nano firmware, ftdichip.com has [[ftdi driver installation guides|http://www.ftdichip.com/Support/Documents/InstallGuides.htm]] including [[Linux|http://www.ftdichip.com/Support/Documents/AppNotes/AN_220_FTDI_Drivers_Installation_Guide_for_Linux%20.pdf]].*

---- 
## 3) MS Windows 7: Nano firmware installation
This firmware loading stub for MS Windows 7 follows above on MAC OS X build. To quote 3 helpful posts for pc users  in thread which began on [[2013-07-06 entitled "V1.2.6"|https://groups.google.com/forum/?hl=en#!topic/safecast-devices/106n-Bs3v-Q]] in the Safecast Device Discussions and Support group, from Jul 21, Aug 6 and Oct 25 2013:

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


***
Another novice's notes on above: 

The ftdi company provides many drivers and [ftdi driver installation guides|http://www.ftdichip.com/Support/Documents/InstallGuides.htm]] for various systems and versions. Here see the [[FTDI Drivers Installation_Guide for ms win win7|http://www.ftdichip.com/Support/Documents/AppNotes/AN_119_FTDI_Drivers_Installation_Guide_for_Windows7.pdf]].

The FTDI driver allows for communication between the Nano Fio and the computer over the breakout board and a usb cable. (Not all USB cables are equal in length or in qualities.  A 100cm long usb to usb mini cable did power the nano and lit lights -- but wasn't recognized for driver transfer. A shorter 50cm cable did succeed with ftdi driver or Xloader.)

Download the xloader.zip. The unzipped XLoader folder includes the avrdude files and also the DEVICES.TXT file which provides the hardware options for the XLoader menu. There are only 4 fields on the XLoader menu: the hex file, the Device (ATmega328), the COM port, and the Baud Rate (57600). 

The hex file contains the firmware. Its github address has been noted above in the Oct win-7 thread ,  link and location of the firmware hex file (the **current version of the Nano firmware**  which is the [[bGeigieNano.hex file|https://github.com/Safecast/bGeigieNanoKit/blob/master/bGeigieNano.hex]] in the [[bGeigieNanoKit repository|https://github.com/Safecast/bGeigieNanoKit]]. The Xloader uses a copy of that file on your drive. So first browse to that current bGeigieNano.hex in the github archive. Press RAW button to see just the text. With notebook or some plain ASCII text editor, copy all that text into some  anyfilename.hex on your drive, a TXT file with the extension “.hex”, the nano firmware file for XLoader.  The easiest location for the hex file is in the same XLoader folder.

The Arduino Fio uses ATmega328, according to the [[Sparkfun page|https://www.sparkfun.com/products/10116]] and this [[Arduino list|http://en.wikipedia.org/wiki/List_of_Arduino_boards_and_compatible_systems]].

The [[arduino.cc website|http://arduino.cc/]] has well recommended guides and help. For history  orientation see [[en.wikipedia on Arduino|http://en.wikipedia.org/wiki/Arduino]].

*Miscellaneous (extraneous and superfluous) alternatives may include system reconfiguration via the microSD card and wireless programming over an optional pair of XBee radios...* 

(end)
***
**p.s. [[http://blog.safecast.org/bgeigie-nano/|http://blog.safecast.org/bgeigie-nano/]] (nano links, catch-all landing page)**

*(draft rev.08.Jan.2014)*