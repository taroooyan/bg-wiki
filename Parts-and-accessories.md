###Nano contents and options: lists and links
*(initial stub -- incomplete list, needs "A3. More small pieces") 27-nov*

1) Parts (Nano kit contents) -- to list with link to a supplier page when known [draft]

2) Accessory Tools and Options (another place to note source of extra tools and hardware)

Sources: in github and mainly the kit assembly Nano Manual. See photos there in [[Nano Manual|https://github.com/Safecast/bGeigieNanoKit/wiki/NANO-MANUAL]].


####A. Nano Kit PARTS

#####1. Large parts 

* [[LND-7317 pancake Geiger|http://www.lndinc.com/products/17/]] Also see Medcom http://nanoxpress.com/nano-parts-accessories/
* [[Medcom iRover HV board|http://nanoxpress.com/nano-parts-accessories/]]. ([[Contact Medcom|http://medcom.com/contact-international-medcom/]])
* [[bGeigieNanoKit v.1.0.l PCB|http://oshpark.com/shared_projects/EElEjLq3]] (Printed Circuit Board). See the [[blog announcement|http://blog.safecast.org/2013/09/bgeigie-nano-pcb-available-now/]] of Nano's purple-color Community PCB available from OSH Park. (The color of the PCB that comes with the kit is blue.)
* [[Arduino Fio|https://www.sparkfun.com/products/10116]]
* [[OpenLog |https://www.sparkfun.com/products/9530]]
* [[Adafruit Ultimate GPS|https://www.adafruit.com/products/746]]
* [[Monochrome 128x32 SPI OLED graphic display|https://www.adafruit.com/products/661]]
* [[2000mAh 3.7V 7.4Wh Lithium Polymer battery (Li-Po)| https://www.sparkfun.com/products/8483]]
* [[Audio cable with 3.5mm jack (white bidirectional stereo)| http://store.apple.com/us/product/HA829ZM/A/belkin-35mm-retractable-stereo-cable-1-m33-ft?fnode=3a]]
* [[Pelican 1010 micro-case|http://www.pelican.com/cases_detail.php?Case=1010]]: strong, tight, transparent plastic, crush proof, water resistant. Opaque colors, [[i1010 micro case|http://www.pelican.com/cases_detail_specs.php?Case=i1010]], are also available from manufacturer. 


#####2. Small Parts 
*(need part specification?)*

* Switch on/off 
* Toggle Switch  
* Dual-Dip-switch . 
* LED R  (Log/alarm)
* LED B  (Count)
* Piezo Buzzer (B1)
* 3.5 mm Audio port connector 
* microUSB port for power charging 


#####3. More small pieces
*(specific description and source to be added here)* 

* __Headers:__  

* __Fasteners:__ 

* __Spacers__:

####B. TOOLS, ACCESSORIES, OPTIONS

•	**Wireless Low-voltage Bluetooth option**: [[BLEBee v1.0.0 board|http://www.seeedstudio.com/depot/bluetooth-bee-p-598.html]]  and iOS app [[BLExplr|https://itunes.apple.com/us/app/blexplr/id524018027?mt=8]] designed by Dr. Michael Kroll. Also see the [[product page|http://www.mkroll.mobi/?page_id=1070]]; the [[BLEBee product forum|http://forum.mkroll.mobi/]], and; [[Safecast announcement|https://www.facebook.com/media/set/?set=a.628182673894097.1073741830.196772350368467&type=1]]. (Although BLE can talk to any Bluetooth 4.0, the BLExplr iOS apps work only in BLE-enabled apple devices. Similarly the Safecast Geigerbot is only in iOS.)

•	**FTDI breakout board 3.3V**, for example this [[one| https://www.sparkfun.com/products/9873]] or that [[one|https://www.adafruit.com/products/284]] for loading firmware upgrades. See the Nano wiki page [[How to setup build environment on Mac OS X|https://github.com/Safecast/bGeigieNanoKit/wiki/How-to-setup-build-environment-on-Mac-OS-X/_edit]].

•	**Pocket AVR Programmer** for technical users to program the Nano firmware. See the  [“Setup System on Mac OS X”](https://github.com/Safecast/SafecastBGeigie “Setup System on Mac OS X”) on the [[bGeigie README.md|https://github.com/Safecast/SafecastBGeigie]].

•	**[[BoPET (Mylar) film|http://en.wikipedia.org/wiki/BoPET]] and/or cut-away case for alpha-/beta-window or beta/gamma window**: As the plastic case blocks alpha- beta- particle radiation, a hole can be cut in the case for a custom alpha-/beta-window. A BoPET (Mylar) film is strong enough to provide wind protection and thin enough to allow for alpha- and beta-radiation measurement. Optionally the Nano can be fitted with a beta/gamma only window, which is less fragile. [??] 
[There is a Safecast video of cut-open case with what looks like aluminum foil taped over it. [URL??]. This custom nano hangs in the same place on the car’s side window, with the thin film covered a/b window facing out [??] to measure airborne radioactive particles while driving.] "The mylar a/b window is only useful where there are sufficient airborne particles."

•	**[[Wireless charger (5V 500mA)|http://smart-prototyping.com/index.php?route=product%2Fproduct&path=65_80&product_id=211]]**, see devices thread [[Wireless charger for bGeigieNanoKit...|https://groups.google.com/forum/?hl=en#!topic/safecast-devices/rENAKdDvgMM]] (Kalin prefers [[Qi|http://www.qiwireless.com/]].)

####C. EXTRAS: OTHER POSSIBLE USES, FORMATS, OPTIONS
*(customized needs and tricked-out prototypes)*

* GPS antenna option ? 

* additional environmental sensors on the BZee socket (instead of the BLEBee), i.e. noise level; air quality chemistry; meterologic barometry, humidity, temperature, etc.

* Parallel to radiation monitoring, Safecast is developing air pollution monitoring devices. See the [[Safecast Air Quality Discussion group|https://groups.google.com/forum/?hl=en#!forum/safecast-air]].

* Safecast has experimented with various uses and various formats of the bGeigie series (i.e. underwater, helicopter drone born, long-life stationary radiation sensors). Search the Safecast website and consult the the [[Safecast Device Discussions and Support|https://groups.google.com/forum/?hl=en#!forum/safecast-devices]] group about your possible customization -- modular XBee socket, specialized data log formats, programming etc

Reportedly all Nano parts are separately available from suppliers.  
As stated by Medcom, the price of [[bGeigie Nano Kit order|https://medcom.com/product/bgeigie-nano-geiger-counter-kit/]] from the distributor includes a $75.00 donation to Safecast.

**For SUPPORT**:  these community-edited [[Nano wiki pages|https://github.com/Safecast/bGeigieNanoKit/wiki/_pages]]; relevant  [[bGeigieNanoKit|https://github.com/Safecast/bGeigieNanoKit/]] github repositories; the http://blog.safecast.org/ website and home page links. Join the [[Safecast Devices Discussions and Support group|https://groups.google.com/forum/?hl=en#!forum/safecast-devices]]. 
Contact info@safecast.org and suppliers...
