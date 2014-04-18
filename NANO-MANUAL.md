##  bGeigie Nano Kit Assembly - ideas and guide 


![](https://raw.github.com/Safecast/bGeigieNanoKit/master/nano%20manual%20named%20pics/bGeigie_Nano_side.jpg)

#### bGeigie Nano kit assembly instructions, v6 (revised April 18, 2014)
To the new users of the bGeigie Nano, congratulations and welcome to the Safecast community. We're happy to be able to deliver this high-performance geiger counter with GPS logging and memory, which has been developed and field-tested by Safecast volunteers. 

The kit format allows for cost savings and for DIY learning. The assembly can take as little as 3-4 hours depending on electronics skill and experience level, but beginners should probably allot about 8 hours. This assembly manual is for all users including novices, so we are trying to make these instructions clear, graphic and explicit. For some we're explaining the obvious, for others this still may not be helpful enough. If you're very experienced at assembling electronic devices, feel free to modify the order of the steps. 

**For Nano SUPPORT**: catch-all landing page [[http://nano.safecast.org/]]; these community-edited [[nano wiki pages|https://github.com/Safecast/bGeigieNanoKit/wiki/_pages]]; the links on the home page of Safecast website http://blog.safecast.org/;  the [[Safecast Devices Discussions and Support group|https://groups.google.com/forum/?hl=en#!forum/safecast-devices]]. Contact info@safecast.org. 

-----


![](https://raw.github.com/safecast/bGeigieNanoKit/0fe74739db57eaff2645784c28dcb78e88a4b2f0/nano%20manual%20named%20pics/Pieter_frustrated.jpg)


#### BEFORE YOU START: 
The LND_7317 pancake sensor is very delicate, although it looks robust. It has a thin mica covering on one face, inside of which there is a partial vacuum. The mica is easily punctured, rendering the tube useless. Since it's the single most expensive component, it would be a shame to trash it. We recommend that you leave it in the box until you're ready to attach it (as described in Step 04). And as with any work, before you start take time to gather tools, clear space, read the manual and turn off distractions. The assembly is not difficult but there are little details to pay attention to. Take a breath and enjoy the build.

#### WARNINGS: 
Solder iron temperature should be about 200-350 degrees Celsius (400-650 degrees Fahrenheit). We hate to be a nanny, but smoke from solder is dangerous for your health, so work in a well-ventilated area please. Wear safety glasses when cutting off leads. They become needle-like projectiles that could blind you or your cat. Do not puncture the Li-Po battery. Be gentle with the kit. Some of the components are fragile, e.g. it's possible to break the wire leads from the battery accidentally. 
 
### Essential Tools: 
* soldering iron or gun
* solder 60/40
* screwdriver (small Phillips-head/plus)
* needle-nosed pliers
* nippers (for cutting component leads)
* double-sided foam tape 

___

![]
(https://raw.github.com/Safecast/bGeigieNanoKit/master/nano%20manual%20named%20pics/assembly.jpg)

##STEP 00: SORT AND CHECK PARTS 
The parts are packed in several smaller bags. Identify, count and check the parts against the "kitting parts list" which should be included in the kit package. Also check them against the three placement diagrams in this manual, relevant photos, and the [[kit contents wiki page|https://github.com/Safecast/bGeigieNanoKit/wiki/Parts-and-accessories]].  If parts are missing or damaged, see the Kit Order Fulfillment (at end of manual) and Support addresses (at top of manual). 

####POLARITY NOTE: 
What is polarity and why should you care? Basically, several types of electronic components are designed to work with the current ﬂowing in one set direction only, while others can work either way. Putting a component that has polarity in the wrong way will usually only prevent the device from working properly, but in some circumstances it could fry a few things as well. So make sure your components are oriented correctly! 

---
***
![]
(https://raw.github.com/Safecast/bGeigieNanoKit/master/nano%20manual%20named%20pics/overviewpics/bGeigie Nano manual v5.3big_Page_03_Image_0002.jpg)

##STEP 01: MAIN BOARD (PCB)
Almost all the components get attached to the main board (PCB), so itʼs a good place to start. Weʼve arranged the assembly steps in a logical order as based on our experience. Of course you can change the order of some steps. Most questions can be resolved by referring to the three large diagrams, the Large Parts, Small Parts and Back Parts placement diagrams in step 01-1 and 01-2. (A paper printout of these diagrams can be handy.)

While we suggest starting from components that lie close to the board before the taller ones, the order of assembly is partly a matter of preference. Similarly, some builders place all the components first and then solder them, others place and solder each in turn as they go.

Because dirt and oils can inhibit the solder bonds, it's a good idea to first wipe both sides of the PCB with isopropyl alcohol using a lint-free cloth. Handle the PCB by the edges whenever possible and avoid touching the board surfaces with your fingers.

To begin and to make handling easier, attach 4 black plastic standoffs through the holes in the corners of the main board ﬁrst. At each corner, insert a 10mm standoff from the upper face of the board, then screw corresponding 8mm one to it from the bottom. (Relevant photos: see the standoffs in the 4 corners of the panels in the finished product.)

***
***
![]
(https://raw.github.com/Safecast/bGeigieNanoKit/master/nano%20manual%20named%20pics/v1.0r2_page1.jpg)

##STEP 01-1: SMALL COMPONENTS: 
All of these will go on the main board. Place and solder them, nipping off the leads. Refer to the Small Parts Placement Guide! You can secure most components in place before soldering them by bending the leads slightly outward; this will allow you to turn the PCB over to solder without the parts falling out.

**Resistors** (R1-R10, R12): The kit contains  6 types, 11 resistors in all as listed on the Small Parts Placement Guide. (There is no R11.)  Resistors have no polarity so either side can go in either hole. (Be especially careful not to confuse the 4.7k resistor, which has a red stripe, with the 47k one, which has an orange stripe). Pay close attention to the color ID stripes as listed on the placement guide. (Doublecheck correct placement against the diagram before you solder. Soldered components are much easier to install than to remove.) If in doubt, measure them with a ohm meter. (A working multimeter is an inexpensive tool for electronics. One can master a voltmeter's basic functions with a little wiki, youtube or coaching. Search for tutorial, e.g. via http://en.wikipedia.org/wiki/Multimeter#External_links.)  If still in doubt, ask for help. 


![]
(https://raw.github.com/Safecast/bGeigieNanoKit/master/nano%20manual%20named%20pics/wiki_small_components_1.jpg)


* Diode (D1): Take care with the polarity (see polarity note). The little black stripe on one end of the small orangish glass part should align with the small white stripe on the component outline on the board. 

* Capacitors (C1- C3): (The ones in the photo are blue, but the ones in the kit might not be) They have two leads. These have no polarity, and can go in either way. Take care not to split them in two by bending the leads outward too much. Itʼs ok for them to ride a little high off the board. 

* LEDs ("COUNT"; "LOG/ALARM"): One each: Blue and Red. (NOTE: In the photo, the "case" or "package" of the blue LEDs is blue, while the red one is clear. Both may be clear in your kit, though, with the color indicated by marker pen. You can also try powering them up with a 3V battery to check.) 
LEDs have polarity and must go in the proper orientation. One lead is longer than the other. This longer lead is the positive (+) lead. It goes in the hole marked "+" on the board. Also, if you look carefully, one side of the plastic case is ﬂattened -- that's the negative (-) side. Take care not to overheat the LEDs when soldering! Wrong polarity is the most common mistake. 
    *     Blue LED: goes in the "COUNT" spot 
    *     Red LED: goes in the "LOG/ALARM" spot 

* Transistor (T1): Goes in the "T1" spot. It has three leads, which need to be spread a bit to ﬁt. It needs to be mounted matching the shape on the board, with the ﬂat side of the case aligned with the ﬂat side of the diagram. 
 
![]
(https://raw.github.com/Safecast/bGeigieNanoKit/master/nano%20manual%20named%20pics/wiki_small_components_2.jpg)
**Switches:** (There are four switches. Some have labels above them on the top panel, nearby on the PCB board or on the component itself. Once the Nano is built, the labels are more readable when the case is open and the power is off.) 

* Dual DIP switch (SW1) goes in the "SW1" spot. It has 4 pins. It should be positioned with the side labeled "ON" toward the top of board, aligned under the "SW1" label on the board. The correct orientation is necessary for the switch to work. [Function: dims the alarm indicators (#1: Speaker "clicks" and small Blue LED “Count” blinks; #2: small Red LED “Log/Alarm”).] 

* Toggle switch: It ﬁts above the rectangular outline between transistor "T1" and the blue "COUNT" LED. It has three leads, and a mounting clip with 2 pins. Solder them all in place. [Function: switches between bGeigie and xGeigie modes. Label on the transparent top panel: "bq/m^2 uS/h", "log cpm". (mode features are mentioned on the Specifications wiki page. See [[Operation Manual|https://github.com/Safecast/bGeigieNanoKit/wiki/Nano-Operation-Manual]].]

* Shift switch (S1): goes in spot "S1." It has 3 leads which need to be soldered in place, plus 2 pins on the aluminum case which need to be nipped off. The 3 leads go in the 3 center holes in the board; the two outer holes are unused. (You could try ﬁling the aluminum case pins down enough to ﬁt in these holes, but it's secure enough attached by just the 3 leads.) [Function: "0 power 1"] 

* Push button switch: goes in the "Fn" spot. (Early versions of the kit had two leads; now shipped with four short legs.The actual color varies based on what is available.)  [Function: user assignable, optional, currently without use. ("Feel free to add code for custom function".)]

**Audio:** there are two items, but only one goes in now: 
* NOW: Piezo buzzer: Goes in the large circular spot in the upper left quadrant of the main board, and has two leads.  It can go in any orientation.

* LATER and OPTIONAL (no longer included): Audio jack: This is actually for sending click data to an external device, such as an iPhone. If you have obtained one yourself, itʼs best to wait until the next step, *“Headers and Breakouts”* for this. 
(This part can currently be ordered from Sparkfun as part # 11570 : TRRS 3.5mm Jack Breakout)
https://www.sparkfun.com/products/11570

***
***

This is how the main board should look with all the small components installed: 

![]
(https://raw.github.com/Safecast/bGeigieNanoKit/master/nano%20manual%20named%20pics/overviewpics/bGeigie Nano manual v5.3big_Page_07_Image_0001.jpg)
***
***
##STEP 01-2: HEADERS and BREAKOUTS: 

![]
(https://raw.github.com/Safecast/bGeigieNanoKit/master/nano%20manual%20named%20pics/wiki_small_components_3.jpg)
![]
(https://raw.github.com/Safecast/bGeigieNanoKit/master/nano%20manual%20named%20pics/wiki_small_components_4.jpg)

The "headers" are long black components with pins or legs. They are provided in several types and lengths of rows, several which need to be cut to the proper size (wire-cutters work well for this). They are used for attaching the breakouts to the board. The breakouts in the kit include what's needed for the OLED display, the Arduino Fio, the GPS module (a 9-pin male header for this should be in the GPS module bag), and the OpenLog memory unit (there should be enough for the audio connector as well if you're installing one). Their installation is detailed further below. Breakouts sometimes are called “daughter boards” or “shields”. Most of the headers go on the front face of the main board, but two go on the backside as discussed below. Refer to the placement guides. 

Be careful when cutting the long headers to length. Refer to the Large Parts Placement Guide guide and to the relevant photos in this Manual. As mentioned above, cutting is done easily with wire-cutters, but is also possible by scoring with a knife and snapping them off. Some people prefer to cut them all to length ﬁrst, some prefer to cut them as needed.

The long headers included in the kit need to be cut to length as follows:

* One 40-pin (or “leg”) length, straight, male header: Cut this into four pieces to mount the Arduino Fio (14-pin and 8-pin), the OpenLog memory unit (6-pin), and the GPS (9-pin) if necessary (i.e., you can't find a 9-pin length in the GPS module bag) 

* One 20-pin length, male header:  Cut four (x4) 2-pin lengths from this row; these are also needed for the Arduino FIO. (OPTIONAL: Cut one (1x) 4-pin length for mounting an audio out jack, which will be attached on the back side of the main board).

* One 10-pin length, angled, male header: Cut a 6-pin length, which will be attached to the Arduino Fio for connecting to an external cable for loading ﬁrmware, etc.. From the remainder cut a 3-pin length which will be attached to the backside of the board as part of the “triple connector.”

* One 8-pin length male header: One should be included in the OLED bag, and an extra with the other parts.  Use as-is for mountimg the OLED.

* One 8-pin length, female header: also used for mounting the OLED display. (It should already be the right length, no need to cut it)

* One 3-pin length, female header: Use as-is for connecting the iRover cable to the triple connector (see Step 02)

The male headers have long pins on one side and short pins on the other. In most cases they can go either way, but we advise orienting the so the short pins will go in the holes on the main board and the long ones project above, to be soldered to the breakouts. To visualize the fit of the parts, study the relevant photos and diagrams and the parts, and do a few dry test fits each way to see. The breakout boards can usually be used as placement aids for the headers. Also we advise soldering the pins at each end ﬁrst, and then checking to make sure the header is perpendicular and properly aligned before soldering the rest.

**NOTE:** It's possible to either solder the headers to the main board ﬁrst, and then to each of the breakouts, or attach them to the breakouts ﬁrst and then to the main board. We've found it easier to attach them to the main board ﬁrst, and these instructions describe that method. Installation order is not critical, but because of the heights and placement of the breakouts, we recommend following the sequence weʼve laid out. 


![](https://raw.github.com/Safecast/bGeigieNanoKit/master/nano%20manual%20named%20pics/v1.0r2_page12.jpg) 


***
***
###BACKSIDE 
Although most of the headers and breakouts get attached to the front of the main board, two components need to be attached to the backside. Itʼs easier for several reasons to do these ﬁrst. Trust us.... 

![](https://raw.github.com/Safecast/bGeigieNanoKit/master/nano%20manual%20named%20pics/overviewpics/bGeigie Nano manual v5.3big_Page_10_Image_0001.jpg)
**iRover connector a.k.a. “triple connector”**
(This connector is for connecting 3 wire leads from the iRover sensor controller and HV (high voltage) supply board to the main board)
* Solder a 3-pin angled header to the bottom of the board, in the position labeled “JP1.” This means, insert the 3-pin connector from the underside of the main board, in the spot marked "JP1," and solder it from the upper side of the board. Note this iRover connector must be attached before attaching the OpenLog!! 

![]
(https://raw.github.com/Safecast/bGeigieNanoKit/master/nano%20manual%20named%20pics/overviewpics/bGeigie Nano manual v5.3big_Page_10_Image_0002.jpg)

**OPTIONAL: Audio Out jack **
(This is for connecting an audio cable to an iPhone or other device)
* Solder a 4-pin male header to the holes marked “audio out.” This means inserting the header from the backside and soldering the short pins from the front face. 
* Attach a thin piece of double-sided foam tape to the black plastic jack housing, and use it to hold the jack in place on the board. Double-check the orientation to make sure itʼs the same as in the photo!
* Solder the four header pins to the audio jack. 
* The audio connector might bump against a few of the OLED breakout pins on the rear of the main board; it's probably best to snip those pins off or file them down. 

![](https://raw.github.com/Safecast/bGeigieNanoKit/master/nano%20manual%20named%20pics/v1.0r2_page13.jpg)
***
***
##STEP 01-2: HEADERS and BREAKOUTS, contʼd: 
####FRONTSIDE 
![](https://raw.github.com/Safecast/bGeigieNanoKit/master/nano%20manual%20named%20pics/overviewpics/bGeigie Nano manual v5.3big_Page_12_Image_0002.jpg)
(Location of the Fio on PCB)

**Arduino Fio:** The Arduino Fio is a microcontroller board based on the Atmel AVR ATmega328P microcontroller. This is the programmable brain of the Nano. (Fio is the name of this version of Arduino board. FIO also stands for Funnel Input/Output. For background, see the [[Fio home page|http://arduino.cc/en/Main/ArduinoBoardFio]] on the [[arduino.cc website|http://arduino.cc/]]; also see the [[Sparkfun page|https://www.sparkfun.com/products/10116]] and [[wikipedia table of Arduinos|http://en.wikipedia.org/wiki/List_of_Arduino_boards_and_compatible_systems]].) 
 
NOTE: It has a small switch on the bottom side which should be turned OFF before soldering! 
* There are four pairs of holes in the main board labeled CHG, BATT, SW, and DTR-CTS. Each gets a 2pin male header. Make sure you install these before you solder the the Fio to the board 
*  A 14-pin length of male header goes on the left side of the Fio outline on the main board. 
*  An 8-pin length of male header goes on the upper right side of the Fio outline. 
*  A 6-pin length of angled male header goes on the Fio itself, in the row of holes beginning with GNDBLK and ending with DTR GRN. It is inserted from the top and soldered on the bottom (see photo). This is used to connect the Fio to a computer for programming. 
* You can go ahead and solder the header pins to the top of the Fio now, or wait until all the headers are in place to solder the breakouts. You can use the Fio itself as an alignment guide to position the headers on the board properly. Soldering the end pins ﬁrst makes it easier to be sure everything is properly aligned. 

![](https://raw.github.com/Safecast/bGeigieNanoKit/master/nano%20manual%20named%20pics/overviewpics/bGeigie Nano manual v5.3big_Page_12_Image_0001.jpg)

Proper location of the angled male header on the Fio-- note it is inserted from the top!

![](https://raw.github.com/Safecast/bGeigieNanoKit/master/nano%20manual%20named%20pics/fio_placement.jpg)

Using the Fio as an alignment guide for the headers.

***
***
##STEP 01-2: HEADERS and BREAKOUTS, contʼd: FRONTSIDE 

![](https://raw.github.com/Safecast/bGeigieNanoKit/master/nano%20manual%20named%20pics/gps_placement.jpg)

caption:Placement of GPS. 

**GPS:** 
(Global Positioning System receiver, which makes it possible to precisely locate where a reading was taken) 
* A 9-pin length of male header (included in the GPS module bag) goes into the holes at the top of the "GPS" spot on the main board.
* It's helpful to attach the GPS board with two 5mm stainless steel standoffs (long hex nuts), using two stainless steel screws and two nuts, to help keep the header properly positioned while soldering it.
* Leaving the standoffs in place, solder the 9 pins to the top of the GPS breakout. 
* NOTE:  The GPS unit comes with a metal battery clip. It's not needed, and in fact can cause problems if it's installed, so it's best to ignore it.

**Open Log:**
(This writes the data to a micro-SD card) 
* A 6-pin length of male header goes into the 6 holes at the top of the "OPEN LOG" spot on the main board; the long pins should be facing up with the OpenLog breakout held flat against the foam tape on the board.
* Foam tape needs to be put on the main board beneath the OpenLog. This helps secure it, and prevents the microSD card from accidentally being inserted into the space between the logger and the main board. Also very importantly, it will insulate the metal face of the OpenLog from the pins of the 3-pin angled connector attached to the bottom of the mainboard, and prevent it from shorting! 
* Once the OpenLog is secured with foam tape, solder the 6 pins of the header to the OpenLog from above (the other 4-holes remain unused).
 (The microSD card is inserted into the microSD slot with the card's gold terminals facing up. Gently push the card in until it clicks into place.)


![](https://raw.github.com/Safecast/bGeigieNanoKit/master/nano%20manual%20named%20pics/back_headers_top.jpg)
caption: Three exposed pins need to be insulated from the OpenLog.


![](https://raw.github.com/Safecast/bGeigieNanoKit/master/nano%20manual%20named%20pics/openlog_tape.jpg)
caption: It will probably take 2 or 3 layers of foam tape to cover the exposed pins and secure the OpenLog. 


![](https://raw.github.com/Safecast/bGeigieNanoKit/master/nano%20manual%20named%20pics/iRover_placement.jpg)
caption: Placement of OpenLog, in relation to GPS breakout.

***
***

**OLED display:** 
(Organic Light-Emitting Diode display) There's more than one way to do this, but this is the method that has worked best for us: 
* Solder the 8-pin female header to the holes on the main board at the top of the "LCD" spot (the leftmost one is marked DATA). 
* Insert the long pins of an 8-pin male header (included with the OLED module) into the female header, and attach the OLED board to the main board using two 10mm stainless steel standoffs, screws, and nuts. Screw a nut to each standoff ﬁrst before placing the display on top of them which brings the OLED to its proper height. Care is needed in attaching the remaining two nuts as not many threads of the standoff will protrude above the OLED then. 
* Solder the 8-pin male header to the OLED board from the top. The display will be easily removable. 

![](https://raw.github.com/Safecast/bGeigieNanoKit/master/nano%20manual%20named%20pics/lcd_header_placement.jpg)
caption: Placement of headers and standoffs for OLED 

![](https://raw.github.com/Safecast/bGeigieNanoKit/master/nano%20manual%20named%20pics/lcd_placement_back.jpg)
caption: Placement of OLED using nuts. 

![](https://raw.github.com/Safecast/bGeigieNanoKit/master/nano%20manual%20named%20pics/lcd_placement_top.jpg)
caption: Note nuts used as spacers under OLED. 


![](https://raw.github.com/Safecast/bGeigieNanoKit/master/nano%20manual%20named%20pics/fully_assembled_top.jpg)

caption: Completed main board, front view (OLED display removed to show components beneath it) 


Now is a good time to do a test powerup. See **“TEST RUN and DIAGNOSTICS”** section 

***
***
##STEP 02: iROVER 
(The iRover is the controller board and HV (high voltage) supply for the pancake sensor) 

####TRIPLE CONNECTOR : 
(This is for connecting 3 wire leads from the iRover to the main board) 
* Cut 3 wires to about 8 cm length, and strip both ends to leave about 5mm exposed. Tin the ends with solder to make the next steps easier. A “third hand” will deﬁnitely make these steps easier! 



![](https://raw.github.com/Safecast/bGeigieNanoKit/master/nano%20manual%20named%20pics/iRover_wiring.jpg)

* Solder all three wires to the gold thin gold posts on the iRover. The wires may be different colors than shown in the photo; the important thing is to keep track of which one is connected to the positive post, which to the negative, and which to the middle. Make sure theyʼre attached in the conﬁguration shown in the picture. Itʼs easier if you bend the exposed end of the wire into a “U” shape and hook it around the post. 



![](https://raw.github.com/Safecast/bGeigieNanoKit/master/nano%20manual%20named%20pics/iRover_headers.jpg)

* Cut a 3-pin length of female header (there should be a 6-pin female header available for this at this point). Solder the other ends of the three wires to the header pins. Make sure the colors match the way you've attached them to the iRover.. 



![](https://raw.github.com/Safecast/bGeigieNanoKit/master/nano%20manual%20named%20pics/attaching_iRover.jpg)

* The 3-pin female header will be a socket for connecting the wires to the triple-connector attached to the backside of the main board earlier (labeled “JP1”). When you connect it, make sure the wire colors are oriented correctly. Itʼs designed to be easily detachable, so you can connect it now, or wait until the following step. 


***
***
##STEP 02: iROVER, contʼd 




![](https://raw.github.com/Safecast/bGeigieNanoKit/master/nano%20manual%20named%20pics/three_plates.jpg)
caption: Left to right: Rear plate,  Middle plate,  Front plate 

Both the battery and the iRover get attached to the middle acrylic plate (the one with an etched outline of the pancake sensor on it). This can actually be done in any order, but weʼll continue with mounting the iRover ﬁrst. 


![](https://raw.github.com/Safecast/bGeigieNanoKit/master/nano%20manual%20named%20pics/iRover_positioning.jpg)
caption: Standoffs for iRover attached to middle plate 

* Remove the paper backing from the middle plate and orient it as shown in the photo. Attach two 5mm stainless steel standoffs to the two small holes near the bottom of the plate (not the corner holes!). Attach them with stainless steel screws inserted from the back of the plate. 

![](https://raw.github.com/Safecast/bGeigieNanoKit/master/nano%20manual%20named%20pics/iRover_attachment.jpg)
caption: iRover installed in proper orientation. 

* Position the iRover board on the standoffs, and attach it with two nuts. Make sure the side of the iRover that has the label is facing up, and the thick red wire with the black connector is to the left. 
* We find it works best to attach the stainless-steel standoffs to the middle plate by inserting the screwpost through the plate and attaching a nut from the rear.  The iRover itself can be connected to the posts using the screws afterward.  This makes it easier to adjust its position slightly if desired. [Note the current photo shows it differently, with the nuts on top -- but this photo will be updated soon.]

* Now is a good time to attach the front plate (the one with the SAFECAST logo, which covers the front side of the main board). Use plastic screws through the four holes in the corner to attach it to the black plastic standoffs. Use pliers to tighten all the standoffs. 
***
***
[NEW BATTERY PHOTO GOES HERE]

##STEP 03: BATTERY 
The battery is a Lithium Polymer (Li-Po, Li-Poly). Older kits shipped with a 2000mAh version, newer kits use a smaller 1200mAh one (see photo). Attention: the battery is encased in a mylar membrane. If punctured, the battery can be hazardous. Handle carefully!  The battery's red and black wires may be reinforced with electrical insulation tape to prevent their falling off or being pulled out. (Some say DIY reattaching a loose wire to the battery is possible, but first see the cautions and potential hazards in datasheet https://www.sparkfun.com/products/8483.)  Charging the new battery full with the first use is recommended. Percentage of battery charge appears in the start-screen and a graphic indicator is displayed in the bottom right during use. (In addition the PCB has a white 'reflective' pad that shows its charge thus allowing check without having to turn on the unit.) 

The 2000mAh battery gives over 40 hours of continuous use and is rated for over 300 recharging cycles. Recharging is via a cable between the miniUSB port on bottom of the Fio to a USB on a computer or a correctly rated miniUSB recharger (such as https://www.sparkfun.com/products/10401).  

Caution: NEVER charge the Nano while the unit is ON. The Nano Power switch MUST be turned OFF before charging to avoid permanent damage to the charge circuit. (Do not connect a miniUSB cable from a power-ON USB source without first turning Power OFF on the Nano.) Replace a broken battery with the same rating. If larger batteries are used the Nano charge circuit may overheat. 

This step is a little tricky, so do a dry run ﬁrst before actually attaching the battery with foam tape! 

![](https://raw.github.com/Safecast/bGeigieNanoKit/master/nano%20manual%20named%20pics/battery_location.jpg)

* Place the partly assembled Nano face down, i.e. with the backside of the main board facing up. Orient it as shown so the triple connector is at the bottom. Cut the thin protective plastic sheet to a appropriate size, and lay it on top of the main board to prevent the battery from accidentally getting punctured.
* Place a couple of strips of the double-sided foam tape on the battery as shown on photo. Stick one side of tape to the battery, but DO NOT peel the other side of the tape yet! Lay the battery on the main board with the wires extending to the left. 


![](https://raw.github.com/Safecast/bGeigieNanoKit/master/nano%20manual%20named%20pics/iRover_placement_over_battery.jpg)

* Test-ﬁt the middle plate, using the black plastic corner standoffs for positioning. The iRover should be facing up. Make note of the position of the battery. 
* When youʼre sure the battery will be located properly, remove the middle plate, peel the foam tape, and carefully put the middle plate back in place sticking it to the battery. Make sure the thin plastic protective sheet is between the battery and the circuit board. Push on the plate gently to get the tape to stick. Remove the taped together plate and battery from over the circuit board and press them together firmly to make the tape connection secure. 


![](https://raw.github.com/Safecast/bGeigieNanoKit/master/nano%20manual%20named%20pics/iRover_wire_feedthrough.jpg) 

* Thread the wires for the triple connector through the slot in the middle plate. Itʼs easier if you give the wires a couple of twists ﬁrst. Connect the 3-pin female header/socket to the triple connector on the back of the main board, as described in the “triple connector” step on p. 16: make sure itʼs oriented so the red wire connects to the positive pin, the black to the negative, and the green in the middle. 
* Thread the battery cable down so it will be easy to connect to the battery port on the Fio. But DO NOT connect the battery yet! (The Nano power switch is down, off.)

![](https://raw.github.com/Safecast/bGeigieNanoKit/master/nano%20manual%20named%20pics/back_plate_install.jpg)

* Attach the remaining black plastic standoffs to the corners of the middle plate, and tighten them. 
* Position the rear plate on the standoffs, but donʼt attach it yet. It will be used to help position the pancake sensor in the following step.

***
***
##STEP 04: PANCAKE SENSOR 

![](https://raw.github.com/Safecast/bGeigieNanoKit/master/nano%20manual%20named%20pics/sensor_box.jpg)

The pancake sensor is very delicate. Keep it in the box until you're ready to install it. Take care to protect sensor membrane during the assembly process! It should be stored face-down on a smooth surface or in the box between steps.
Once it's been connected to the battery it also presents an slight electric shock risk (about 500 volts! Yow!), so be very careful about touching it, particularly at the iRover connection where the bare wire is soldered. And take care not to let the bare wire touch the silver metal connector. 

![](https://raw.github.com/Safecast/bGeigieNanoKit/master/nano%20manual%20named%20pics/sensor.jpg)
This is how the sensor should look. 

![](https://raw.github.com/Safecast/bGeigieNanoKit/master/nano%20manual%20named%20pics/broken_sensor.jpg)
Wrecked sensor. The parts inside sure looks cool though! (Thatʼs the anode...) 

![](https://raw.github.com/Safecast/bGeigieNanoKit/master/nano%20manual%20named%20pics/sensor_placement.jpg)
* The sensor will also be attached to the middle place with double-sided foam tape. The etched outline on the plate itself may be enough to help you position it accurately, but we recommend you do a test ﬁt using the opening in the rear plate as a guide. Attach a couple of pieces of foam tape either to the middle plate or to the bottom of the sensor, and drop the sensor into place. When youʼre sure you can do it accurately, peel the tape and drop it in place for real. Then remove the rear plate for the following steps. 

It's a good idea to cover the exposed silver metal of the sensor post with shrink tubing, electrical tape, or something else that can act as an insulator, to help guard against electrical shock and shorts. [Photo to be added]

![](https://raw.github.com/Safecast/bGeigieNanoKit/master/nano%20manual%20named%20pics/attaching_sensor_to_iRover.jpg)
* The sensor gets two connections to the iRover: the anode connection, which is the thick red wire with black connector, and the cathode connection, which is a thin, uninsulated silver wire. Unroll this carefully!


![](https://raw.github.com/Safecast/bGeigieNanoKit/master/nano%20manual%20named%20pics/soldering_sensor_ground.jpg)
* Carefully bend the silver wire around the thick post that comes out of the sensor, making sure it doesnʼt touch the bare metal surface. 
* Depending on the version included, the iRover may have one of three kinds of attachment points for the cathode: a small wire loop, a small hole, or a metal bump. The photo shows the cathode wire soldered to a bump-type connector. If your iRover has a hole-type anode connection, it's better to try to insert the wire through it from the bottom.  If it's pushed in from the top it might accidentally puncture the battery.
* The black connector is simply pushed onto the metal post, and should have a tight friction ﬁt. 

![](https://raw.github.com/Safecast/bGeigieNanoKit/master/nano%20manual%20named%20pics/back_plate_install.jpg)
* Now is a good time to attach the rear plate, using 4 black plastic standoffs and nuts. 

#### Sensor cover:  
![]
(https://raw.github.com/Safecast/bGeigieNanoKit/master/nano%20manual%20named%20pics/nailpolishtrick.jpg)
The copper mesh cover should be attached to the pancake sensor so that it protects the membrane. We've found that a thin coat of clear acrylic nail polish carefully applied to the edge of the mesh works well as an adhesive. It can also easily be removed later if needed by using nail polish remover. 

Use clear nail polish or "nail top coat," without glitter or other anything like that in it. Only a thin coat is needed. You should apply it to the edge of the mesh because it's easier to handle than the sensor. Carefully position it on the sensor as shown in the photo, and press down on it lightly with your finger for a minute or so until the polish starts to set. Let it dry for about 5 minutes. 

NOTE:  Early versions of the bGeigie Nano included a clear plastic cover for the pancake sensor. These are no longer used.

***
***

##STEP 05: PLATES AND SCREWS 

Check all the plates, standoffs, screws, and nuts now to make sure everything is where it should be. It all disassembles fairly easily if you need to change something. 

![](https://raw.github.com/Safecast/bGeigieNanoKit/master/nano%20manual%20named%20pics/stackimage01.jpg)


![](https://raw.github.com/Safecast/bGeigieNanoKit/master/nano%20manual%20named%20pics/spacers_and_screws.jpg)
caption: The front plate should have clear plastic screws. 

![](https://raw.github.com/Safecast/bGeigieNanoKit/master/nano%20manual%20named%20pics/spacers_and_nut.jpg)

caption: The rear plate should have clear plastic nuts. 
***
***
##STEP 06: PELICAN CASE 
The Pelican case is a standard Pelican Micro Case 1010 model. (The sticker, the manufacturer's logo label, can be peeled- and cleaned-off.) The case has a (black, yellow, blue or red) removable rubber liner. A hole must be cut in this removable rubber liner to ﬁt the pancake sensor, as follows: 

![](https://raw.github.com/Safecast/bGeigieNanoKit/master/nano%20manual%20named%20pics/cutting_liner.jpg)
* Itʼs easiest to use the opening in the rear plate as a hole-cutting template. Push it snugly into the rubber liner, and trace the circular opening with a pen, pencil, or thin marker. Remove the liner from the case before cutting the hole in the rubber liner.

* Use an X-acto, Olfa, or similar knife to cut the liner hole. (Joeʼs half a sawed beer can of correct diameter also works as a sensor window cutter!)

#### NICE! Joe's can cutter hack:
![]
(https://raw.github.com/Safecast/bGeigieNanoKit/master/nano%20manual%20named%20pics/beercantrick.jpg)
* Joe came up with an ingenious hack to simplify cutting nice holes for the sensor in the rubber lining of the Pelican case, which takes advantage of the fact that the sensor is almost exactly the same diameter as a standard aluminum drink can. Basically, you remove the top face of the can, using a sturdy knife or other method (actually Joe uses a razor saw), and sharpen the thick aluminum edge a bit as shown in the photo. It doesn't have to be extremely sharp to work. Place the rubber liner on a block of wood or similar surface, and use the rear acrylic plate (the one with the hole for the sensor) to gauge or mark the position of the hole. Align the can carefully, push down hard with your palm, and rotate it a couple of time slowly. This method requires a bit of a knack, but it makes the best holes!

![](https://raw.github.com/Safecast/bGeigieNanoKit/master/nano%20manual%20named%20pics/front_plate_assembly.jpg)
* Replace the liner into the plastic case, and gently but ﬁrmly insert the assembled bGeigie Nano into the liner. Check that the sensor is properly aligned with the opening in the liner. (Alternatively place the Nano into the liner and insert them together into the case.) It should be a very snug ﬁt. Close the case. The case closes properly when the clasp shuts tightly with click. (If initially the case cannot be completely closed, check carefully for any jammed point, fix and try again.)

* 8 clear neoprene feet or runners are provided in the kit to stick on the 4 corners of the top and bottom sides of the case. Theyʼre not absolutely necessary, but these pads make it easier to mount the device in many situations. 

* Strap(s)are provided to make it easier to mount the Nano on a car or other vehicle. (Meanwhile [[#10 “Mounting tips” in Operation Manual|https://github.com/Safecast/bGeigieNanoKit/wiki/Nano-Operation-Manual]].)

In this conﬁguration, the Nano is fully operational for most types of data gathering.

An optional beta window can be made if desired. [See in #2 Uses in the Operation Manual, or in Options in the Parts List page].

An Apple audio cord is provided for iGeigie mode update to online databases. See the "Safecast API User Manual". (In draft [[#11 “API, uploading data to Safecast” in Operation Manual|https://github.com/Safecast/bGeigieNanoKit/wiki/Nano-Operation-Manual]].)

####Congratulations, your Nano kit assembly is finished! 

![](https://raw.github.com/Safecast/bGeigieNanoKit/master/nano%20manual%20named%20pics/closed_front.jpg)

![](https://raw.github.com/Safecast/bGeigieNanoKit/master/nano%20manual%20named%20pics/bGeigie_Nano_bottom.jpg)

![](https://raw.github.com/Safecast/bGeigieNanoKit/master/nano%20manual%20named%20pics/bGeigie_Nano_side2.jpg)

***
***

##STEP 07: TEST RUN and DIAGNOSTICS 
**MID-ASSEMBLY TEST POWERUP: **

!! IMPORTANT: Make sure you're running the most recent firmware. You can download it at:
https://github.com/Safecast/bGeigieNanoKit

If you've just ﬁnished assembling the main board, including the breakouts, it's a good idea to do a test power up. We recommend this because it's much easier to ﬁx problems that might be due to misplaced or poorly connected components before the unit is fully assembled. The same sequence can be used for diagnostics after the entire nano is assembled. 
1. Before connecting the battery: 
 1a.There is a small ON/OFF switch on the underside of the Fio. Make sure that it is in the OFF position. If you didn't remember to do this  before attaching the Fio, it's accessible (barely!) on the assembled unit. [photo]  If this switch is in the ON position, the unit will power up as soon as the battery is connected, and power switch attached to the main  board will not function. 
 
1b. Remove the SD card if it has been inserted  
1c. Set the switches on the main board:  
1c1. DIP switch: both in ON position  
1c2. Toggle switch: Can be in either position, but we suggest moving it to the down position (log/cpm)  
1c3. Slider switch (power): in OFF position  

Plug the battery connector to the Fio. 

Turn the power switch to ON 

What appears on the display may change with ugrades to the ﬁrmware. With ﬁrmware version XXXX, in a moment, the display should show: 

4a. The splash screen, with the word SAFECAST.  

4b. The welcome screen:  Unit version number  Unit ID number  Battery charge level  Mode indicator  Alarm setting  Customizable text string (useful for putting a name)  

4c. The main screen  

4c1. With the toggle switch in the down position (logging mode/CPM), (during a mid-assembly test, with the sensor not connected),  the main screen should display [photo]:  Left column:  0 CPM  0 uSv/hr  NO SD CARD (when the SD card is installed, this should display Date/time).  Right column:  battery charge indicator  No GPS (probably, though in certain conditions it may lock quickly and show the number of GPS satellites it's  receiving signals from)  ---m (height)  XXhXXm (elapsed time) 
 
4c2. With the toggle switch in the up position (Bqm2/uSv/h), the display should show:  Only one column:  0uSv/hr  0CPM 0Bq/m2, alternating with Mx=0 (max reading since reset) Ds=0 (cumulative dose since reset)  NO SD CARD, etc, as above  
  
4d. Several LEDs should illuminate:  

4d1. the red power light should be glowing visibly glow beneath the upper end of the Fio;  

4d2. A small red LED on the GPS breakout should blink;  

4d3. A small blue LED on the OpenLog light should blink 

This completes the basic test. The following steps describe additional tests: 

***
***

##STEP 07: TEST RUN and DIAGNOSTICS, contʼd: 
 
**ADDITIONAL TESTS:** 

5. To test the counter function with the sensor not connected, use a knife blade or other small piece of metal to make a brief connection between the plus and middle pins on the triple connector. The blue COUNT LED should light, the speaker should click softly, and the display will show counts each time the pins are touched. (If the blue LED does not blink, it was probably installed with the polarity reversed. Another possibility is that the polarity of the diode (D1) is wrong. Check those, and if necessary remove and solder them again.) 
 
6. Test the SD card:  
6a. Since the card is only detected at startup, switch the power off ﬁrst.  

6b. Insert the card  

6c. When the unit powers up, a date/time reading should appear at the bottom of the left column (where NO SD CAD was before), but it will not be correct until the GPS has locked. 

7.Test the GPS lock: Put the unit near a window while it is powered up. In a minute or two (maybe longer) the "No GPS " indicator will change to indicate the number of satellites it has locked to (such as "4 [upcaret]"). A height reading should also appear, such as "3m." 

8. Test charging the battery: Attach a mini usb cable to the Fio, then to a computer or USB charger. A yellow charge light should glow visibly underneath the Fio. It will go out when the battery is fully charged. 

***
***

##MISCELLANEOUS: 

***PARAMETER SETTINGS:*** The micro-SD card that ships with the bGeigie Nano contains two pre-set ﬁles, CONFIG.TXT for communication rate and SAFECAST.TXT for certain operating parameters. The parameters are defined in [[source|https://github.com/Safecast/bGeigieNanoKit/blob/master/NanoSetup.cpp]] and to be listed elsewhere in this [[nano-wiki|https://github.com/Safecast/bGeigieNanoKit/wiki/_pages]] -- in the [[Nano Operation Manual|https://github.com/Safecast/bGeigieNanoKit/wiki/Nano-Operation-Manual]]. Edit the parameters accordingly.    Keep a backup of your 2 files in case the micro-SD card becomes damaged or corrupted. Default settings are available online in their [[safecast github folder|https://github.com/Safecast/bGeigieNanoKit/tree/master/SD%20card]].

***TROUBLESHOOTING:*** Search, query and report the problem in the [[Safecast Devices Discussions and Support group|https://groups.google.com/forum/?hl=en#!forum/safecast-devices]]. Also contact info@safecast.org.

***SCHEMATICS:*** available in Eagle format in their [[Safecast github repository|https://github.com/Safecast/SafecastEagleHW/tree/master/bGeigieNanoKit]] (For help locating circuit, query the cognoscenti in the [[devices discussion and support group|https://groups.google.com/forum/?hl=en#!forum/safecast-devices]].)

***KIT ORDER FULFILLMENT:*** to request missing/replacement kit part(s) by air mail, contact info@safecast.org, as given in contacts on the safecast.org home page. (If you're in a hurry, search your local and web DIY electronics sources, e.g. [[sparkfun|https://www.sparkfun.com/categories]].) See the [[Parts List|https://github.com/Safecast/bGeigieNanoKit/wiki/Parts-and-accessories]] (wiki page draft).

***DISTRIBUTOR:*** [[Medcom bGeigie Nano Kit|http://medcom.com/radiation-monitors/geiger-counters/bgeigie-kit/]]. As of 7 Mar 2014, the Nano Kit is also available through [[Amazon|http://bit.ly/bgeigie]] from Geiger Counters. 
Alternatively you can acquire parts separately and source your own kit. All parts are available off the shelf. A purple-color [[bGeigie Nano PCB|http://blog.safecast.org/2013/09/bgeigie-nano-pcb-available-now/]] is available at [[OSH PARK|http://oshpark.com/shared_projects/EElEjLq3]]. The [[IMI iRover board and LND 7317 GM tube|http://nanoxpress.com/nano-parts-accessories/]] are available at [[IMI Medcom|http://medcom.com/contact-international-medcom/]]. See [[Parts and accessories|https://github.com/Safecast/bGeigieNanoKit/wiki/Parts-and-accessories]].

***CONGRATULATIONS!*** Report your build in the Devices discussion group. Help in Safecast efforts. Make good, safe use of this new tool. Enjoy!

---

p.s. How long did your build take? Click on the photo for Peter Blakely's time-lapse "bGeigie nano assembly in 2 min" (29-3-2013). 



[![ScreenShot] (https://raw.github.com/Safecast/bGeigieNanoKit/master/nano%20manual%20named%20pics/assembly.jpg)](http://vimeo.com/62926075)

***
Resources: **nano catch-all landing page [[http://blog.safecast.org/bgeigie-nano/]]**