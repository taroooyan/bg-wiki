draft soon

**Parts list (Nano kit contents)** [draft]

**Accessories**

**Options, hardware upgrades**


**03. PARTS (NAMES, FUNCTIONS)** [needs diagram]
*(Parts list moved to [[Parts and accessories|https://github.com/Safecast/bGeigieNanoKit/wiki/Parts-and-accessories]] page)*

Nano parts are listed in github, in kit assembly manual, in specifications. (A complete Nano wiki parts page is still to do. The following draft list is incomplete.)

Contents list is handy in the connecting the kit. It might also be useful for the technically advantaged who package their own kit, collect the Nano parts which are reportedly are all individually available on the shelf at their sources.). 

**Large parts**

* [[LND-7317 pancake Geiger|http://www.lndinc.com/products/17/]]
* [[Medcom iRover HV board (TBA)|http://medcom.com/imi-international-medcom-response-to-fukushima-daichi-event/ ]]
* PCB bGeigieNanoKit v.1.0 the kit has blue PCB. There is also a purple color PCB (community Printed Circuit Board ) http://oshpark.com/shared_projects/EElEjLq3  Aslo see  http://blog.safecast.org/2013/09/bgeigie-nano-pcb-available-now/
* [[Arduino Fio|https://www.sparkfun.com/products/10116]]
* [[OpenLog |https://www.sparkfun.com/products/9530]]
* [[Adafruit Ultimate GPS|https://www.adafruit.com/products/746]]
* [[Monochrome 128x32 OLED screen (or 128×64 high contrast, two display sizes supported|https://www.adafruit.com/products/661]]
* [[2000mAh 3.7V 7.4Wh Lithium Polymer battery (Li-Po)| https://www.sparkfun.com/products/8483]]
* [[Audio cable with 3.5mm jack (white bidirectional stereo)| http://store.apple.com/us/product/HA829ZM/A/belkin-35mm-retractable-stereo-cable-1-m33-ft?fnode=3a]]
* [[Pelican 1010 micro-case|http://www.pelican.com/cases_detail.php?Case=1010]]  is a strong, tight, transparent plastic, crush proof, water resistant [[Pelican 1010 micro case|http://www.pelican.com/cases_detail.php?Case=1010]]. The case has strap holders at its two ends, a lanyard or [[carabiner|https://en.wikipedia.org/wiki/Carabiner]], and neoprene feet on top and bottom. The kit can be easily attached to vehicles. (See examples of mountings later.) User who may possibly prefer an opaque case can order the [[i1010 micro case|http://www.pelican.com/cases_detail_specs.php?Case=i1010]] from manufacturer.  It’s customary to see the lanyard carabiner as top of case with hinge on left so that power button is on the open right. Whatever direction is your up or down, the pancake sensor goes into the liner’s hole. It’s easier to replace the nano together inside the liner back into the case.  


**Small Parts**

* Switch on/off 
* Toggle Switch  
* Dual-Dip-switch . 
* LED R  (Log/alarm)
* LED B  (Count)
* Piezo Buzzer (B1)
* 3.5 mm Audio port connector 
* microUSB port for power charging 
* (+data upload FTDI-capable??) 

**More small pieces**, like headers, fasteners, spacers… Their specific description and online source catalog numbers could be included in the nano wiki parts list. 

**BATTERY USE, RECHARGING** (redundant, see [[Nano Manual Kit Assembly|https://github.com/Safecast/bGeigieNanoKit/wiki/NANO-MANUAL]]; & below Cautions)

+ (micro USB cable, yellow LED will dim once fully charged, full charge takes 5-6 hours, bGeigie nano runs approx 35-40 hours on a full charge in LOG mode, Battery indicator in bottom right of display, and; Per cent level charged appears on startup.)

+ **NEVER charge the bGeigie while the unit is in ON.** Power MUST be turned OFF before charging to avoid permanent damage to the charge circuit. 

+ Replace a broken (detached wire) battery with the same rating (2000mAh 3.7V Lithium Polymer (Li-Po, Li-Poly). The Nano charge circuit may overheat if larger batteries are used.

+ A Li-Po battery can be hazardous if mylar membrane is punctured. Handle carefully! (See the Manual on kit assembly for more on battery.) 

**04. TOOLS, ACCESSORIES, OPTIONS** *(this section largely to [[Parts and accessories|https://github.com/Safecast/bGeigieNanoKit/wiki/Parts-and-accessories]] page)*


**The [[Safecast bGeigie Library|https://github.com/Safecast/SafecastBGeigie]]** is the code including the firmware building blocks, such as SD card logger, GPS parser, power management, etc in the form of an Arduino library.

End users can install upgrades of the firmware with an accessory FTDI breakout board 3.3V, for example this [[one|https://www.sparkfun.com/products/9873]] or that [[one| https://www.adafruit.com/products/284]]. See the Nano wiki page [[How to setup build environment on Mac OS X|https://github.com/Safecast/bGeigieNanoKit/wiki/How-to-setup-build-environment-on-Mac-OS-X]]. 

Technical users can program the Nano firmware with an Pocket AVR Programmer. See the section “Setup System on Mac OS X” the [[bGeigie README.md|https://github.com/Safecast/SafecastBGeigie]].

Data transfer is via the micro SD card, via the audio cord to geiger bot iOS app, or, as additional option there is since Oct 2013 a wireless data transfer option. See the BLEBee v1.0.0 breakout board http://www.seeedstudio.com/depot/blebee-v100-p-1632.html and the iOS app BLExplr https://itunes.apple.com/us/app/blexplr/id524018027 designed by Dr. Michael Kroll. Also see http://www.mkroll.mobi/?page_id=1070 ; and the BLEBee product forum http://forum.mkroll.mobi/. Although BLE can talk to any Bluetooth 4.0, the BLExplr iOS apps work only in BLE-enabled apple devices. (Similarly the Safecast Geigerbot is only in iOS.)

**OPTIONS** (to list in nano wiki parts + options page?) 
? GPS antenna option
? additional environmental sensors on the BZee socket (instead of the BLEBee), i.e. air quality, noise level, barometric, meterological, etc. ? Safecast has experimented with various custom formats of the bGeigie series. (i.e. underwater, helicopter drone born, long-life stationary). Consult the devices group about your wants and options, modular XBee socket, specialized data log formats, programming etc  


**For SUPPORT**:  Read these community-edited [[Nano wiki pages|https://github.com/Safecast/bGeigieNanoKit/wiki/_pages]] including this Parts list. See the relevant files within the Safecast [[bGeigieNanoKit|https://github.com/Safecast/bGeigieNanoKit/]] github repositories. 
Surf the Safecast website http://blog.safecast.org/ and the links on the home page. Join the [[Safecast Devices Discussions and Support group|https://groups.google.com/forum/?hl=en#!forum/safecast-devices]]. 
Contact info@safecast.org and/or the suppliers of particular part.
