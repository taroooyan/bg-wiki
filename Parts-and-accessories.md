###Nano contents and options: lists and links
*(initial stub -- incomplete list, please check and add missing specifications, esp. small and misc pieces)*

**A) Parts (Nano kit contents)** -- to list with link to a supplier page when known [draft]

**B) Accessory Tools and Options** (another place to note source of extra tools, hardware, customizations)

**C) Extras: other possible uses, formats, options, functions: also requested desired

*See the kit assembly [[Nano Manual|https://github.com/Safecast/bGeigieNanoKit/wiki/NANO-MANUAL]] for item definition, placement guides and photos. (Part supplier links also copied from safecast blog, devices group and (googled?). (Elsewhere in the github nano repository there may be some technical specifications...)*

####A. Nano Kit PARTS

#####__1. LARGE PARTS__

* [[LND-7317 pancake Geiger|http://www.lndinc.com/products/17/]] Also available through Medcom http://nanoxpress.com/nano-parts-accessories/
* [[Medcom IMI iRover HV board|http://nanoxpress.com/nano-parts-accessories/]]. ([[Contact Medcom|http://medcom.com/contact-international-medcom/]])
* [[bGeigieNanoKit v.1.0.l PCB|http://oshpark.com/shared_projects/EElEjLq3]] (Printed Circuit Board). See the [[blog announcement|http://blog.safecast.org/2013/09/bgeigie-nano-pcb-available-now/]] of Nano's purple-color Community PCB available from OSH Park. (The color of the PCB that comes with the kit is blue.)
* [[Arduino Fio|https://www.sparkfun.com/products/10116]]
* [[OpenLog |https://www.sparkfun.com/products/9530]]
* [[Adafruit Ultimate GPS|https://www.adafruit.com/products/746]]
* [[Monochrome 128x32 SPI OLED graphic display|https://www.adafruit.com/products/661]]
* [[2000mAh 3.7V 7.4Wh Lithium Polymer battery (Li-Po)| https://www.sparkfun.com/products/8483]]
* [[Audio cable with 3.5mm jack (white bidirectional stereo)| http://store.apple.com/us/product/HA829ZM/A/belkin-35mm-retractable-stereo-cable-1-m33-ft?fnode=3a]]
* [[Pelican 1010 micro-case|http://www.pelican.com/cases_detail.php?Case=1010]]: strong, tight, transparent plastic, crush proof, water resistant. Opaque colors, [[i1010 micro case|http://www.pelican.com/cases_detail_specs.php?Case=i1010]], are also available from manufacturer. 


#####__2. SMALL PARTS__

#####Resistors: 
*The kit contains 6 types, 11 resistors. (R1-R10, R12) as listed on the Small Parts Placement Guide.*

1. 047     Ohm , x1 ;  (R7)
2. 001   k Ohm , x4 ;  (R2; R4; R10; R12)
3. 004.7 k Ohm , x2 ;  (R5; R9)
4. 009.1 k Ohm , x1 ;  (R1) 
5. 047   k Ohm , x2 ;  (R3; R8)
6. 100   k Ohm , x1 ;  (R6)


#####12 Small Parts
*on the Small Parts Placement Guide:*

1.  Capacitors, 100nF Ceramic x3  (C1, C2, C3)
2.  Diode 1N4148 
3.  Dual-Dipswitch . 
4.  iRover connector a.k.a. “triple connector”  *(Does this come with the Medcom IMI iRover HV board?)*
5.  LED Blue  (Count)
6.  LED Red (Log/alarm)
7.  microUSB port for power charging  
8.  Piezo Buzzer (B1)
9.  Push button (S5)
10.  Switch on/off  (power)
11.  Toggle Switch  (mode)
12.  Transistor 2sc1815 (T1)

#####Additional small part(s)
13. Audio port connector 3.5 mm 

#####Headers:  *(in kit before division of longer into smaller)*

1. One 40-pin length male header *(before dividing)*
2. One 19-pin length male header *(before dividing)*
3. One 10-pin length angled male header *(before dividing)*
4. One 6-pin length female header *(before dividing)* 
5. One 8-pin length female header (for OLED)

*As detailed in the Manual, these 4 header rows are to be cut, as follows:*

>* One 40-pin (or “leg”) length, straight, male header. Cut this row into four pieces to mount the Arduino Fio (14-pin and 8-pin), the GPS (9-pin) and the OpenLog memory unit (6-pin).

>* One 19-pin length, male header. Cut one (1x) 4-pin length for mounting the audio out jack which will be attached on the back side of the main board. Also cut four (x4) 2-pin lengths from this row.

>* One 10-pin length, angled, male header: Cut this row into a 6-pin length which will be attached to the Arduino Fio for connecting to an external cable for loading ﬁrmware, etc. From the remainder of the row cut a 3-pin length which will be attached to the backside of the board as part of the “triple connector.”

>* One 6-pin length, female header: Cut one 3-pin length to use for connecting the iRover cable to the triple connector (see Step 02)

#####Fasteners and Spacers:

1. Black Plastic 10mm long, (x.dim?)  HEXAGONAL STANDOFFS (x12)  
2. Clear plastic SCREWS and NUTS, to fasten black standoffs (x??)
3. various Stainless STEEL STANDOFFS, SCREWS AND NUTS, (for connecting boards  (x??) *--still to do this line*
4. TAPE, Double-sided Foam Tape (not thick, at least ?? length before division)
5. PLASTIC SQUARE  (insulation to protect battery)
6. CUT PANELS (3 cut plates: rear, middle, front)
7. Strap(s) for mounting
8. Clear NEOPRENE FEET (runners or pads) (x8)


- - - - - 
All Nano parts are available from suppliers. *(My guess: to buy all the parts retail would cost at least as much as the price of kit, even with the $75.00 donation to Safecast included in the distributor's [[bGeigie Nano Kit order|https://medcom.com/product/bgeigie-nano-geiger-counter-kit/]].-yw)*

- - - - - 
#####4. Licenses:
The [[Safecast FAQ on licenses|http://blog.safecast.org/faq/licenses/]] includes the following on hardware design:

>The hardware developed by Safecast is **open source**.
You are free to open, manipulate, hack, break and or improve anything.

>All copyrightable, non-text works, hardware reference design, etc are published under a **Creative Commons Attribution Share Alike License**.

>You are free to copy, edit and republish these, but you must make it clear we are the original source and must publish under this same license. You can’t copyright anything you make based on our work.

>All the copyrightable functional works of our hardware designs are published under **BSD**.

>All the patentable functional works of our hardware designs are published under an **XL1.0 Cross License**.
 
- - - - - 

####B. Nano TOOLS, ACCESSORIES, OPTIONS

•	**Wireless Low-voltage Bluetooth option**: [[BLEBee v1.0.0 board|http://www.seeedstudio.com/depot/bluetooth-bee-p-598.html]]  and iOS app [[BLExplr|https://itunes.apple.com/us/app/blexplr/id524018027?mt=8]] designed by Dr. Michael Kroll. Also see the [[product page|http://www.mkroll.mobi/?page_id=1070]]; the [[BLEBee product forum|http://forum.mkroll.mobi/]], and; [[Safecast announcement|https://www.facebook.com/media/set/?set=a.628182673894097.1073741830.196772350368467&type=1]]. (Although BLE can talk to any Bluetooth 4.0, the BLExplr iOS apps work only in BLE-enabled apple devices. Similarly the Safecast Geigerbot is only in iOS.)

•	**FTDI breakout board 3.3V**, for example this [[one| https://www.sparkfun.com/products/9873]] or that [[one|https://www.adafruit.com/products/284]] for loading firmware upgrades. See the Nano wiki page [[How to setup build environment on Mac OS X|https://github.com/Safecast/bGeigieNanoKit/wiki/How-to-setup-build-environment-on-Mac-OS-X/_edit]].

•	**Pocket AVR Programmer** for technical users to program the Nano firmware. See the  [“Setup System on Mac OS X”](https://github.com/Safecast/SafecastBGeigie “Setup System on Mac OS X”) on the [[bGeigie README.md|https://github.com/Safecast/SafecastBGeigie]].

•	[[BoPET (Mylar) film|http://en.wikipedia.org/wiki/BoPET]] and/or cut-away case for **alpha-/beta-window** or **beta/gamma window**: See Joe Moross' thread [["Beta window"|https://groups.google.com/forum/#!msg/safecast-devices/8a_aJ3otQCw/0dUudUVHXBEJ]] 14/9/2013 in devices group. "...As the plastic case blocks alpha- beta- particle radiation, a hole (40 to 45mm in diameter) for a custom alpha-/beta-window can be bored in the case over the sensor.  Emergency 'space blankets' are a good source for thin aluminized Mylar.  ...The thickness should be between 10 and 30 microns. Thinner than 10um and it's too fragile. Thicker than 30um and you'll block all the alpha particles and noticeably attenuate the betas as well. Optionally the Nano can be fitted with a beta/gamma only window, which is less fragile... You can use duck tape to seal the film over the hole as we did on the earliest bGeigies.  Or, if you want a neater appearance, try searching hobby stores for model airplane covering film. The "chrome" film is aluminized BoPET (expanded Mylar) usually 25um thick. It also has a thin layer (~5um) of thermoplastic adhesive.  Here's how it looks [[heat-sealed to a bGeigie3 prototype|http://plus.google.com/app/basic/photos/105805543171125420155/album/5912792455672511633]]. -- The mylar a/b window is only useful where there are sufficient airborne particles."

•       Extras to charge Nano's battery: small carbon footprint hikers might use an [[nPower® PEG hybrid kinetic powered charger|http://www.npowerpeg.com/new-how-it-works]] *(source: Kalin's thread on devices 20-12-2013)*. Alternatively, you can use [[Lithium/Iron Disulfide AA batteries (Li/FeS2)|http://www.batteryspace.com/prod-specs/CEV-L91.pdf]] and a 2xAA->USB charger such as the [[Arisuti ALICITY AD28S|http://www.yodobashi.com/%E3%82%A2%E3%83%AA%E3%82%B9%E3%83%86%E3%82%A3-ALICITY-AD28S-%E3%82%B9%E3%83%9E%E3%83%BC%E3%83%88%E3%83%95%E3%82%A9%E3%83%B3%E7%94%A8-%E3%83%AA%E3%83%81%E3%82%A6%E3%83%A0%E4%B9%BE%E9%9B%BB%E6%B1%A0%E4%BA%A4%E6%8F%9B%E5%BC%8F%E5%85%85%E9%9B%BB%E5%99%A8-%E5%8D%983%C3%972%E6%9C%AC%E3%82%B3%E3%83%BC%E3%83%89/pd/100000001001489695/]]. If you need to go wireless there's a [[wireless charger (5V 500mA)|http://smart-prototyping.com/index.php?route=product%2Fproduct&path=65_80&product_id=211]] *(devices thread [[Wireless charger for bGeigieNanoKit...|https://groups.google.com/forum/?hl=en#!topic/safecast-devices]] --Kalin prefers [[Qi|http://www.qiwireless.com/]])*. If you don't have a handy spare computer USB port there's always a [[USB LiPoly Single Cell Battery Charger|https://www.sparkfun.com/products/10161]]. (If you don't have time to recharge battery, bring a spare and the double-sided tape and gear to switch batteries.)

•	**Android?** As mentioned above, the safecast geigerbot app requires an Apple iOS device and the optional wireless BLEBee connection requiers BLE enabled recent iOS device. However, Safecast's Apple ecology may soon be less dominant. On 3 Dec 2013 on safecast google groups, Peter Franken posted a link to a new android development, https://www.facebook.com/safecast4android, "Safecast for Android is a client-server orientated environment to visualize radioactive data on interactive maps."  (Pieter wrote, "[This is] a ground up rebuild for Android. Instead of in app rendering it will use a server to do it out of app. So it is not a port [of geigerbot].") 


####C. EXTRAS: OTHER POSSIBLE USES, FORMATS, OPTIONS: REQUESTED (DESIRED?)
*(customized needs and tricked-out prototypes)*

* GPS antenna option ? 
* additional environmental sensors on the BZee socket (instead of the BLEBee), i.e. meteorology -- barometry, humidity, temperature; noise level; air quality chemistry...

* Parallel to radiation monitoring, Safecast is developing **air pollution** monitoring devices. See the [[Safecast Air Quality Discussion group|https://groups.google.com/forum/?hl=en#!forum/safecast-air]].

* Safecast has experimented with various uses and formats of the bGeigie series (i.e. underwater, helicopter drone born, long-life stationary radiation sensors). Search the Safecast website and consult the the [[Safecast Device Discussions and Support|https://groups.google.com/forum/?hl=en#!forum/safecast-devices]] group about your possible customization -- modular XBee socket, specialized data log formats, programming etc

* Additional functions desired: 1) Stealth mode (silent operation -- without lights and buzzer); 2) 

**For SUPPORT**:  these community-edited [[Nano wiki pages|https://github.com/Safecast/bGeigieNanoKit/wiki/_pages]]; relevant  [[bGeigieNanoKit|https://github.com/Safecast/bGeigieNanoKit/]] github repositories; the http://blog.safecast.org/ website and home page links. Join the [[Safecast Devices Discussions and Support group|https://groups.google.com/forum/?hl=en#!forum/safecast-devices]]. 
Contact info@safecast.org and suppliers...
