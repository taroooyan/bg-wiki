#  bGeigie Nano 
![]
(https://raw.github.com/Safecast/bGeigieNanoKit/master/nano%20manual%20named%20pics/bGeigie_Nano_side.jpg)

## Assembly ideas and guide 
#### bGeigie Nano assembly instructions, v5a 
Congratulations on obtaining a SAFECAST bGeigie Nano kit. This high-performance geiger counter with GPS logging and memory has been developed by SAFECAST volunteers and thoroughly tested in the ﬁeld. We're happy to be able to make it available in kit form for radiation enthusiasts everywhere to build on their own. 
Depending in your skill and experience level, assembly should take about 3-4 hours. We've tried to anticipate possible bumps and snags along the way, and have tempted to make these instructions as helpful as possible for novices. So if it seems like we're explaining the obvious from time to time, that's why. If you're very experienced at assembling electronic devices, feel free to modify the order of the steps.Docs, including the schematic, parts list, and a copy of these instructions as well as the user's manual will be downloadable soon from: www.safecast.org 

![](https://raw.github.com/safecast/bGeigieNanoKit/0fe74739db57eaff2645784c28dcb78e88a4b2f0/nano%20manual%20named%20pics/Pieter_frustrated.jpg)

#### BEFORE YOU START: 
The LND7317 pancake sensor looks robust but is very delicate! Please handle it carefully! It has a thin mylar covering on one face, and inside is a partial vacuum. The mylar is easily punctured, rendering the tube useless. Since it's the single most expensive component, it would be a shame to trash it. May we recommend that you leave it in the box until you're ready to attach it? (That would be step D...) 

#### WARNINGS: 
Solder iron should be 200-350 degrees Celsius 400-650 degrees Fahrenheit?]We hate to be a nanny, but smoke from solder is dangerous for your health, so work in a well-ventilated area please.Wear safety glasses when cutting off leads. They become needle-like projectiles that could blind you or your cat.Many of the small components are not very robust, and it's possible to yank the wire leads out accidentally. 
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
It's a good idea to check the parts against the parts list to make sure you know what everything is and that it's all there. 

####POLARITY NOTE: 

What is polarity and why should you care? Basically, several types of electronic components are designed to work with the current ﬂowing in one set direction only, while others can work either way. Putting a component that has polarity in the wrong way will usually only prevent the device from working properly, but in some circumstances it could fry a few things as well. So make sure! 

---
***
![]
(https://raw.github.com/Safecast/bGeigieNanoKit/master/nano%20manual%20named%20pics/overviewpics/bGeigie Nano manual v5.3big_Page_03_Image_0002.jpg)

##STEP 01: MAIN BOARD 
Almost all the components get attached to the main board, so itʼs a good place to start. Weʼve broken it down for you logically based on our experience, but you might have areas on to change the order of some steps. Most questions can be resolved by referring to the component placement diagrams on pp. 4, 9, and 11.While we suggest working from components that lie close to the board to the higher ones,we understand that this is a matter of preference. The same goes for whether you place all the components and then solder them, or place one or two at a time and solder them as you go.It's a good idea to attach 4 black plastic standoffs through the holes in the corners of the main board ﬁrst, to make handling easier. At each corner, insert a 10mm standoff from the upper face of the board, then screw an 8mm one to it from the bottom. 
***
***
![]
(https://raw.github.com/Safecast/bGeigieNanoKit/master/nano%20manual%20named%20pics/v1.0r2_page1.jpg)

##STEP 01-1: SMALL COMPONENTS: 
All of these will go on the main board. Place and solder them, nipping off the leads. Refer to the placement guide! 

**Resistors** (R1 through R12-- but no R11): There are 6 types, 11 in all. It can get confusing! They have no polarity so they can go in either way (Be especially careful not to confuse the 4.7k resistor, which has a red stripe, with the 47k one, which has an orange stripe). Pay close attention to the color ID stripes as listed on the placement guide. 


![]
(https://raw.github.com/Safecast/bGeigieNanoKit/master/nano%20manual%20named%20pics/wiki_small_components_1.jpg)

[needs a callout: Black stripe]
* Diode (D1): Take care with the polarity (see polarity note). The little black stripe on one end of the small orangish glass part should align with the small white stripe on the component outline on the board. 
* Capacitors (C1- C3):They're blue with two leads. These have no polarity, and can go in either way. Take care not to split them in two by bending the leads outward too much. Itʼs ok for them to ride a little high off the board. 
* LEDs: One each, red (the case is clear, though),and blue. These have polarity and must go in the proper orientation. One lead is longer than the other; this is the positive (+) lead. It goes in the hole marked "+" on the board. Also, if you look carefully, one side of the plastic case is ﬂattened; that's the negative (-) side. Take care not to overheat the LEDs when soldering! Wrong polarity is the most common mistake. 

    *     Red (clear): goes in the "LOG/ALARM" spot 
    *     Blue: goes in the "COUNT" spot 

* Transistor (T1): Goes in the "T1" spot. It has three leads, which need to be spread a bit to ﬁt. It needs to be mounted matching the shape on the board, with the ﬂat side of the case aligned with the ﬂat side of the diagram. 
 
![]
(https://raw.github.com/Safecast/bGeigieNanoKit/master/nano%20manual%20named%20pics/wiki_small_components_2.jpg)
**Switches:** there are four of them: 
* Dual DIP switch (SW1) goes in the "SW1" spot. It has 4 pins. It should be positioned so that the side with the"ON" label points towards the top of the board, i.e. the "ON" label aligns with the "SW1" label on the board(This is not because of polarity, but it needs to go in this way to work. 
* Toggle switch: No label on the case. It ﬁts above the rectangular outline between transistor "T1" and the blue"COUNT" LED. It has three leads, and a mounting clip with 2 pins. Solder them all in place. 
* Shift switch (S1): goes in spot "S1." It has 3 leads which need to be soldered in place, plus 2 pins on the aluminum case which need to be nipped off. The 3 leads go in the 3 center holes in the board; the two outer holes are unused (Ok, you could try ﬁling the aluminum case pins down enough to ﬁt in these holes, but it's plenty secure enough attached by just the 3 leads. 
* Black or yellow push switch: goes in the "Fn" spot. The black ones have 2 leads which need to be mounted in the holes that are setback from the edge of the board. The leads can be bent so the switch lays ﬂat if desired. Yellow ones have 4 leads, and fit the holes precisely.

**Audio:** there are two items, but only one goes in now: 
* NOW: Piezo buzzer: Goes in the large circular spot in the upper left quadrant of the main board, and has 
* LATER: Audio jack: This is actually for sending click data to an external device, such as an iPhone. Itʼs best to wait until the next step, *“Headers and Breakouts”* for this. 

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

The "headers" are long black components with many pins, or legs. They are used for attaching the
breakouts (also sometimes called “daughter boards” or “shields”) for the OLED display, the Arduino FIO, 
the GPS module, and the OpenLog memory unit, as well as for the audio connector. Most of them go on the
front face of the main board,but two go on the backside. Refer to the placement guides. 
They are provided in several types and lengths: 

* One 40-pin (or “leg”) length, straight, male. It will be cut into three pieces used for mounting the Arduino FIO (14-pin and 8-pin), the GPS (9-pin), and the OpenLog memory unit (6-pin). 
* One 19-pin length, male. A 4-pin length will be cut and used for mounting the audio out jack, which will be attached on the back side of the main board. Four 2-pin lengths will also be cut from this. 
* One 10-pin length, angled, male. It will be cut, making a 6-pin length which will be attached to the Arduino FIO for connecting to an external cable for loading ﬁrmware,etc., and a 3-pin length which will be attached to the backside of the board as part of the “triple connector.” 
* One 8-pin length, female, which will be used for mounting the OLED display. 
* One 6-pin length, female. A 3-pin length will be cut and used to connect the iRover cable to the triple connector (see step 2) 

Be careful cutting the long headers to length. Refer frequently to the placement guide and photos. Cutting is done easily with nippers, but is also possible by scoring with a knife and snapping them off. Some people prefer to cut them all to length ﬁrst, some like to cut them as needed. The short pins usually go in the holes in the board and the long ones project above and are soldered to the breakouts. It helps to have a placement aid of some sort, and usually it's possible to use the breakout board itself for this. Also, we advise soldering the pins at each end ﬁrst, and then checking to make sure the header is perpendicular and properly aligned before soldering the rest. 

**NOTE:** It's possible to either solder the headers to the main board ﬁrst, and then to each of the breakouts, or attach them to the breakouts ﬁrst and then to the main board.We've found it easier to attach them to the main board ﬁrst, and these instructions describe that method. 
Installation order is not critical, but because of the heights and placement of the breakouts, we recommend following the sequence weʼve laid out. 


![](https://raw.github.com/Safecast/bGeigieNanoKit/master/nano%20manual%20named%20pics/v1.0r2_page12.jpg) 


***
***
###BACKSIDE 
Although most of the headers and breakouts get attached to the front of the main board, two components need to be attached to the backside. Itʼs easier for several reasons to do these ﬁrst. Trust us.... 

![](https://raw.github.com/Safecast/bGeigieNanoKit/master/nano%20manual%20named%20pics/overviewpics/bGeigie Nano manual v5.3big_Page_10_Image_0001.jpg)
**iRover connector aka “triple connector”**

(This is for connecting 3 wire leads from the iRover sensor controller 
board to the main board)
* Solder a 3-pin angled header to the bottom of the board, in the position labeled “JP1.” This means, insert the 3-pin connector from the underside of the main board, in the spot marked "JP1," and solder it from the upper side of the board. This must be done before attaching the OpenLog!! 

![]
(https://raw.github.com/Safecast/bGeigieNanoKit/master/nano%20manual%20named%20pics/overviewpics/bGeigie Nano manual v5.3big_Page_10_Image_0002.jpg)

**Audio Out jack **
(This is for connecting an audio cable to an iPhone or other device)
* Solder a 4-pin male header to the holes marked “audio out.” This means inserting the header from the backside and soldering the pins from the front face. 
* Attach a thin piece of double-sided foam tape to the black plastic jack housing, and use it to hold the jack in place on the board. Double check the orientation to make sure itʼs the same as in the photo!
* Solder the four header pins to the audio jack. 

![](https://raw.github.com/Safecast/bGeigieNanoKit/master/nano%20manual%20named%20pics/v1.0r2_page13.jpg)
***
***
##STEP 01-2: HEADERS and BREAKOUTS, contʼd: 
####FRONTSIDE 
![](https://raw.github.com/Safecast/bGeigieNanoKit/master/nano%20manual%20named%20pics/overviewpics/bGeigie Nano manual v5.3big_Page_12_Image_0002.jpg)
(needs indication circle)

**Arduino FIO:** (This is the programmable brain of the device.) 
NOTE: It has a small switch on the bottom side which should be turned OFF before soldering! 
*  A 14-pin length of male header goes on the left side of the FIO outline on the main board. 
*  An 8-pin length of male header goes on the upper right side of the FIO outline. 
*  A 6-pin length of angled male header goes on the FIO itself, in the row of holes beginning with GNDBLK and ending with DTR GRN. It is inserted from the top and soldered on the bottom (see photo). This is used to connect the FIO to a computer for programming. 
* There are four pairs of holes in the main board labeled CHG, BATT, SW, and DTR-CTS. Each gets a 2pin male header. Make sure you install these before you solder the the FIO to the board 
* You can go ahead and solder the header pins to the top of the FIO now, or wait until all the headers are in place to solder the breakouts. You can use the FIO itself as an alignment guide to position the headers on the board properly. Soldering the end pins ﬁrst makes it easier to be sure everything is properly aligned. 

![](https://raw.github.com/Safecast/bGeigieNanoKit/master/nano%20manual%20named%20pics/overviewpics/bGeigie Nano manual v5.3big_Page_12_Image_0001.jpg)
(needs indication circle)

caption: Proper location of the angled male header on the FIO. 

![](https://raw.github.com/Safecast/bGeigieNanoKit/master/nano%20manual%20named%20pics/fio_placement.jpg)

caption: Using the FIO as an alignment guide for the headers.

***
***
##STEP 01-2: HEADERS and BREAKOUTS, contʼd: FRONTSIDE 

![](https://raw.github.com/Safecast/bGeigieNanoKit/master/nano%20manual%20named%20pics/gps_placement.jpg)

caption:Placement of GPS. 

**GPS:** 
(Global Positioning System receiver, which makes it possible to precisely locate where a reading was taken) 
* A 9-pin length of male header goes into the holes at the top of the"GPS" spot on the main board.
* It's helpful to attach the GPS board with two 5mm stainless standoffs (long hex nuts), using two stainless screws and two nuts, to help keepthe header properly positioned while soldering it.
* Leaving the standoffs in place, solder the 9 pins to the top of the GPS breakout. 



**Open Log:**
(This writes the data to a mini-SD card) 
* A 6pin length of male header goes into the 6 holes at the top of the"OPEN LOG" spot on the main board; the long pins should be facing up. 
* Foam tape needs to be put on the main board beneath the OpenLog.This helps secure it, and prevents the SD card from accidentally beinginserted into the space between the logger and the main board. Also very importantly, it will insulate the metal face of the OpenLog from the pins of the 3-pin angled connector attached to the bottom of the mainboard, and prevent it from shorting! 
* Once the OpenLog is secured with foam tape, solder the 6 pins of the header to the OpenLog from above. 

![](https://raw.github.com/Safecast/bGeigieNanoKit/master/nano%20manual%20named%20pics/back_headers_top.jpg)
caption: Three exposed pins need to be insulated from the OpenLog.


![](https://raw.github.com/Safecast/bGeigieNanoKit/master/nano%20manual%20named%20pics/openlog_tape.jpg)
caption: It will probably take 2 or 3 layers of foam tape to cover the exposed pins and secure the OpenLog. 


![](https://raw.github.com/Safecast/bGeigieNanoKit/master/nano%20manual%20named%20pics/iRover_placement.jpg)
caption: Placement of OpenLog, in relation to GPS breakout.

***
***

**OLED display:** 
(Organic Light-Emitting Diode display)There's more than one way to do this, but this is the method that has worked best for us: 
* Solder the 8-pin female header to the holes on the main board at the top of the "LCD" spot (the leftmost one is marked DATA). 
* Insert the long pins of an 8-pin male header into the female header, and attach the OLED board to the main board using two 10mm stainless standoffs, screws, and nuts. Screw a nut to each standoff ﬁrst before placing the display on top of them to bring it to the proper height. Note that not many threads will protrude above the OLED then, so care is needed in attaching the remaining two nuts. 
* Solder the 8-pin male header to the OLED board from the top. The display will be easily removable. 

![](https://raw.github.com/Safecast/bGeigieNanoKit/master/nano%20manual%20named%20pics/lcd_header_placement.jpg)
caption: Placement of headers and standoffs for OLED 

![](https://raw.github.com/Safecast/bGeigieNanoKit/master/nano%20manual%20named%20pics/lcd_placement_back.jpg)
caption: Placement of OLED using nuts. 

![](https://raw.github.com/Safecast/bGeigieNanoKit/master/nano%20manual%20named%20pics/lcd_placement_top.jpg)
caption:Note nuts used as spacers under OLED. 


![](https://raw.github.com/Safecast/bGeigieNanoKit/master/nano%20manual%20named%20pics/fully_assembled_top.jpg)

caption: Completed main board, front view (OLED display removed to show components beneath it) 


Now is a good time to do a test powerup. See **“TEST RUN and DIAGNOSTICS”** section 

***
***
##STEP 02: iROVER 
(The iRover is the controller board for the pancake sensor) 
####TRIPLE CONNECTOR : 
(This is for connecting 3 wire leads from the iRover to the main board) 
* Cut 3 wires to about 8 cm length, and strip both ends to leave about 5mm exposed. (The red will be positive, the black negative, and the green or yellow in the middle). Tin the ends with solder to make the next steps easier. A “third hand” will deﬁnitely make these steps easier! 



![](https://raw.github.com/Safecast/bGeigieNanoKit/master/nano%20manual%20named%20pics/iRover_wiring.jpg)

* Solder all three wires to the gold thin gold posts on the iRover. Make sure theyʼre attached in the conﬁguration shown in the picture. Itʼs easier if you bend the exposed end of the wire into a “U” shape and hook it around the post. 



![](https://raw.github.com/Safecast/bGeigieNanoKit/master/nano%20manual%20named%20pics/iRover_headers.jpg)

* Cut a 3-pin length of female header (there should be a 6-pin female header available for this at this point). Solder the other ends of the three wires to the header pins. Again, make sure theyʼre in the right order: red on one side, green in the middle, and black on the other side. 



![](https://raw.github.com/Safecast/bGeigieNanoKit/master/nano%20manual%20named%20pics/attaching_iRover.jpg)

* The 3-pin female header will be a socket for connecting the wires to the triple-connector attached to the backside of the main board earlier (labeled “JP1”). When you connect it, make sure itʼs oriented so the red wire connects to the positive pin, the black to the negative, and the green or yellow in the middle. Itʼs designed to be easily detachable, so you can connect it now, or wait until the following step. 


***
***
##STEP 02: iROVER, contʼd 




![](https://raw.github.com/Safecast/bGeigieNanoKit/master/nano%20manual%20named%20pics/three_plates.jpg)
caption: Left to right: Rear plate,  Middle plate,  Front plate 

Both the battery and the iRover get attached to the middle acrylic plate (the one with an etched outline of the pancake sensor on it). This can actually be done in any order, but weʼll continue with mounting the iRover ﬁrst. 


![](https://raw.github.com/Safecast/bGeigieNanoKit/master/nano%20manual%20named%20pics/iRover_positioning.jpg)
caption: Standoffs for iRover attached to middle plate 

* Remove the paper backing from the middle plate and orient it as shown in the photo. Attach two 5mm stainless standoffs to the two small holes near the bottom of the plate(not the corner holes!). Attach them with stainless screws inserted from the back of the plate. 

![](https://raw.github.com/Safecast/bGeigieNanoKit/master/nano%20manual%20named%20pics/iRover_attachment.jpg)
caption: iRover installed in proper orientation. 

* Position the iRover board on the standoffs, and attach it with two nuts. Make sure the side of the iRover that has the label is facing up, and the thick red wire with the black connector is to the left. 

* Now is a good time to attach the front plate (the one with the SAFECAST logo, which covers the front side of the main board). Use plastic screws through the four holes in the corner to attach it to the black plastic standoffs. Use pliers to tighten all the standoffs. 
***
***
##STEP 03: BATTERY 
Attention: The lithium-ion battery is encased in a mylar membranewhich can be punctured, causing damage. Handle it carefully! 

This step is a little tricky, so do a dry run ﬁrst before actually attaching the battery with foam tape! 

![](https://raw.github.com/Safecast/bGeigieNanoKit/master/nano%20manual%20named%20pics/battery_location.jpg)

* Place the partly assembled Nano face down, i.e. with the backside of the main board facing up. Orient it as shown so the red audio connector is at the top and the triple connector is at the bottom. 
* Put a couple of strips of foam tape on the battery as shown, but donʼt peel the exposed side of the tape yet! Lay the battery on the main board with the wires extending to the left. Place the thin square protective plastic sheet between the battery and the circuit board. 


![](https://raw.github.com/Safecast/bGeigieNanoKit/master/nano%20manual%20named%20pics/iRover_placement_over_battery.jpg)

* Test-ﬁt the middle plate, using the black plastic corner standoffs for positioning. The iRover should be facing up. Make note of the position of the battery. 
* When youʼre sure the battery will be located properly, remove the middle plate, peel the foam tape, and carefully put the middle plate back in place. Make sure the thin plastic protective sheet is between the battery and the circuit board. Push on the plate gently to get the tape to stick. Remove the plate and battery again and make the tape connection secure. 


![](https://raw.github.com/Safecast/bGeigieNanoKit/master/nano%20manual%20named%20pics/iRover_wire_feedthrough.jpg) 

* Thread the wires for the triple connector through the slot in the middle plate. Itʼs easier if you give the wires a couple of twists ﬁrst. Connect the 3-pin female header/socket to the triple connector on the back of the main board, as described in the “triple connector” step on p. 16: make sure itʼs oriented so the red wire connects to the positive pin, the black to the negative, and the green in the middle. 
* Thread the battery cable down so it will be easy to connect to the battery port on the FIO.But donʼt connect it yet! 

![](https://raw.github.com/Safecast/bGeigieNanoKit/master/nano%20manual%20named%20pics/back_plate_install.jpg)

* Attach the remaining black plastic standoffs to the corners of the middle plate, and tighten them. 
* Position the rear plate on the standoffs, but donʼt attach it yet. It will be used to help position the pancake sensor in the following step. 
***
***
##STEP 04: PANCAKE SENSOR 

![](https://raw.github.com/Safecast/bGeigieNanoKit/master/nano%20manual%20named%20pics/sensor_box.jpg)

The pancake sensor is very delicate. Take care to protect sensor membrane during the assembly process! 
Once it's been connected to the battery it also presents an slight electric shock risk (about 500 volts! Yow!) so be very careful about touching it. Especially the iRover connection where the bare wire is soldered. And take care not to let the bare wire touch the silver metal connector. 

![](https://raw.github.com/Safecast/bGeigieNanoKit/master/nano%20manual%20named%20pics/sensor.jpg)
caption: This is how the sensor should look. 

![](https://raw.github.com/Safecast/bGeigieNanoKit/master/nano%20manual%20named%20pics/broken_sensor.jpg)
caption: Wrecked sensor. The parts inside sure looks cool though! (Thatʼs the anode...) 

![](https://raw.github.com/Safecast/bGeigieNanoKit/master/nano%20manual%20named%20pics/sensor_placement.jpg)
* The sensor will also be attached to the middle place with double-sided foam tape. The etched outline on the plate itself may be enough to help you position it accurately, but we recommend you do a test ﬁt using the opening in the rear plate as a guide. Attach a couple of pieces of foam tape either to the middle plate or to the bottom of the sensor, and drop the sensor into place. When youʼre sure you can do it accurately, peel the tape and drop it in place for real. Then remove the rear plate for the following steps. 

[ADD IMAGE: Wrap the bare metal on the post with tape, or thin rubber insulation.] 

![](https://raw.github.com/Safecast/bGeigieNanoKit/master/nano%20manual%20named%20pics/attaching_sensor_to_iRover.jpg)
* The sensor gets two connections to the iRover: the anode connection, which is the thick red wire with black connector, and the cathode connection, which is a thin, uninsulated silver wire. 


![](https://raw.github.com/Safecast/bGeigieNanoKit/master/nano%20manual%20named%20pics/soldering_sensor_ground.jpg)
* Carefully bend the silver wire around the thick post that comes out of the sensor, making sure it doesnʼt touch the bare metal surface. 
* Depending on the version included, the iRover may have one of three kinds of attachment points for the cathode: a small wire loop, a small hole, or a metal bump. The photo shows the cathode wire soldered to a bump-type connector. 
* The black connector is simply pushed onto the metal post, and should have a tight friction ﬁt. 

![](https://raw.github.com/Safecast/bGeigieNanoKit/master/nano%20manual%20named%20pics/back_plate_install.jpg)
* Now is a good time to attach the rear plate, using 4 black plastic standoffs and nuts. 


![](https://raw.github.com/Safecast/bGeigieNanoKit/master/nano%20manual%20named%20pics/sensor_cover.jpg)
* Circular metal mesh and thin clear plastic covers are provided for protecting the sensor membrane. Put the mesh in place, then add the plastic one on top of it. Both are removable. The clear plastic cover will need a small notch cut into it for clearance for the sensor post. If you want you can use a small piece of cellophane or other tape to hold it in place. 

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
The Pelican case is a standard 1010 model, which has a removable rubber liner. A hole must be cut in this to ﬁt the pancake sensor. 

![](https://raw.github.com/Safecast/bGeigieNanoKit/master/nano%20manual%20named%20pics/cutting_liner.jpg)
* Itʼs easiest to use the opening in the rear plate as a hole-cutting template. Push it snugly into the rubber liner, and trace the circular opening with a pen, pencil, or thin marker. 
* Use an X-acto, Olfa, or similar knife to cut the hole. 

![](https://raw.github.com/Safecast/bGeigieNanoKit/master/nano%20manual%20named%20pics/front_plate_assembly.jpg)
* Replace the liner into the plastic case, and gently but ﬁrmly insert the assembled iGeigie Nano.It should be a very snug ﬁt. Check to see that the case closes properly, and that the sensor is properly aligned with the opening in the liner. 

ADD: Joeʼs sharpened beer can sensor window cutter! 

####Congratulations, youʼre done! 

However...... 
* Straps are provided to make it easier to mount the Nano to a car or other vehicle. See “Mounting tips.”[need to add!!] 
* Clear neoprene feet are also provided. Theyʼre not absolutely necessary, but make it easier to mount the device in many situations. See “Mounting tips.” 
* Finally, in this conﬁguration, the Nano is fully operational for most types of data gathering, but an optional beta window can be made if desired. See “Options.” 


![](https://raw.github.com/Safecast/bGeigieNanoKit/master/nano%20manual%20named%20pics/closed_front.jpg)

![](https://raw.github.com/Safecast/bGeigieNanoKit/master/nano%20manual%20named%20pics/bGeigie_Nano_bottom.jpg)

![](https://raw.github.com/Safecast/bGeigieNanoKit/master/nano%20manual%20named%20pics/bGeigie_Nano_side2.jpg)

***
***
##STEP 07: TEST RUN and DIAGNOSTICS 
**MID-ASSEMBLY TEST POWERUP: **
If you've just ﬁnished assembling the main board, including the breakouts, it's a good idea to do a test power up. We recommend this because it's much easier to ﬁx problems that might be due to misplaced or poorly connected components before the unit is fully assembled. The same sequence can be used for diagnostics after the entire nano is assembled. 
1. Before connecting the battery: 
 1a.There is a small ON/OFF switch on the underside of the FIO. Make sure that it is in the OFF position. If you didn't remember to do this  before attaching the FIO, it's accessible (barely!) on the assembled unit. [photo]  If this switch is in the ON position, the unit will power up as soon as the battery is connected, and power switch attached to the main  board will not function. 
 
1b. Remove the SD card if it has been inserted  
1c. Set the switches on the main board:  
1c1. DIP switch: both in ON position  
1c2. Toggle switch: Can be in either position, but we suggest moving it to the down position (log/cpm)  
1c3. Slider switch (power): in OFF position  

Plug the battery connector to the FIO. 

Turn the power switch to ON 

What appears on the display may change with ugrades to the ﬁrmware. With ﬁrmware version XXXX, in a moment, the display should show: 

4a. The splash screen, with the word SAFECAST.  

4b. The welcome screen:  Unit version number  Unit ID number  Battery charge level  Mode indicator  Alarm setting  Customizable text string (useful for putting a name)  

4c. The main screen  

4c1. With the toggle switch in the down position (logging mode/CPM), (during a mid-assembly test, with the sensor not connected),  the main screen should display [photo]:  Left column:  0 CPM  0 uSv/hr  NO SD CARD (when the SD card is installed, this should display Date/time, )  Right column:  battery charge indicator  No GPS (probably, though in certain conditions it may lock quickly and show the number of GPS satellites it's  receiving signals from)  ---m (height)  XXhXXm (elapsed time) 
 
4c2. With the toggle switch in the up position (Bqm2/uSv/h), the display should show:  Only one column:  0uSv/hr  0CPM 0Bq/m2, alternating with Mx=0 (max reading since reset) Ds=0 (cumulative dose since reset)  NO SD CARD, etc, as above  
  
4d. Several LEDs should illuminate:  

4d1. the red power light should be glowing visibly glow beneath the upper end of the FIO;  

4d2. A small red LED on the GPS breakout should blink;  

4d3. A small blue LED on the OpenLog light should blink 

This completes the basic test. The following steps describe additional tests: 

***
***

##STEP 07: TEST RUN and DIAGNOSTICS, contʼd: 
 
**ADDITIONAL TESTS:** 

5. To test the counter function with the sensor not connected, use a knife blade or other small piece of metal to make a brief connection between the plus and middle pins on the triple connector. The blue COUNT LED should light, the speaker should click softly, and the display will show counts each time the pins are touched(If the blue LED does not blink, it was probably installed with the polarity reversed. Another possibility is that the polarity of the diode (D1) is wrong. Check those, and remove and resolder them if necessary). 
 
6. Test the SD card:  
6a. Since the card is only detected at startup, switch the power off ﬁrst.  

6b. Insert the card  

6c. When the unit powers up, a date/time reading should appear at the bottom of the left column (where NO SD CAD was before), but it will not be correct until the GPS has locked. 

7.Test the GPS lock: Put the unit near a window while it is powered up. In a minute or two (maybe longer) the "No GPS " indicator will change to indicate the number of satellites it has locked to (such as "4 [upcaret]"). A height reading should also appear, such as "3m." 

8. Test charging the battery: Attach a mini usb cable to the FIO, then to a computer or USB charger. A yellow charge light should glow visibly underneath the FIO. It will go out when the battery is fully charged. 

***
***

##TO BE ADDED: 

SCHEMATICS 

OPERATION 
--Basic functions --connect to app --how to use API 

MOUNTING TIPS 

OPTIONS 

Optional beta window WiFi 

TROUBLESHOOTING 

PARAMETER SETTINGS 
The MiniSD card that ships with the bGeigie Nano contains a settings ﬁle that has been pre-set by SAFECAST. While werecommend retaining the default settings, the parameters can be changed if desired. Itʼs best to make a copy of the ﬁle and keep it handy it handy, in case the SD card becomes damaged or corrupted. 
The ﬁle is also available online at: <https://docs.google.com/spreadsheet/ccc?key=0Ag8Z8O-yL
