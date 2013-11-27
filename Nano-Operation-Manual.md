***Safecast bGeigie Nano Operation Manual***

*Nov 24, 2013 –. verbose user guide draft needs editing. Excerpts from website, devices group, app, etc. hopefully in context, usually without attribution. Community-edited wiki page. (needs more input, photos, log file, LEDs diagrams, etc.  Please check [??]=unsure*

**Orientation**:  Surf the Safecast website http://blog.safecast.org/ and the links on the home page. Join the [[Safecast Devices Discussions and Support group|https://groups.google.com/forum/?hl=en#!forum/safecast-devices]]. For support, contact info@safecast.org.  Read these [[Nano wiki pages|https://github.com/Safecast/bGeigieNanoKit/wiki/_pages]] (in various stages of community drafting):
* [[Features/specifications|https://github.com/Safecast/bGeigieNanoKit/wiki/bGeigieNano-Features_specifications]]
* [[How to setup build environment on Mac OS X|https://github.com/Safecast/bGeigieNanoKit/wiki/How-to-setup-build-environment-on-Mac-OS-X]] (+Nano firmware upgrade on MS-Windows)
* [[Nano Wiki Home|https://github.com/Safecast/bGeigieNanoKit/wiki]] (index page in the NanoKit wiki folder)
* [[NANO MANUAL|https://github.com/Safecast/bGeigieNanoKit/wiki/NANO-MANUAL]] (Kit assembly, connecting the pieces)
* [[Nano Operation Manual|https://github.com/Safecast/bGeigieNanoKit/wiki/Nano-Operation-Manual]] (this page)
* [[Parts and accessories|https://github.com/Safecast/bGeigieNanoKit/wiki/Parts-and-accessories]] (including tools and options)
* [[Safety in radiation detection|https://github.com/Safecast/bGeigieNanoKit/wiki/Safety-in-radiation-detection]]

**Contents Operation Manual:**

**01.  Safety tips for radiation detection** *(moved to its own Nano wiki page [[Safety|https://github.com/Safecast/bGeigieNanoKit/wiki/Safety-in-radiation-detection]])*

**02.  Model name, description, uses (agendas?)**

**03.  Parts (names, functions, diagram) incl switches**  *(Parts list moved to [[Parts and accessories|https://github.com/Safecast/bGeigieNanoKit/wiki/Parts-and-accessories]] page)*

**04.  Tools, accessories, options**  *(Tools-options list moved to [[Parts and accessories|https://github.com/Safecast/bGeigieNanoKit/wiki/Parts-and-accessories]] page)*

**05.  Parameter Settings; Data Log; MicroSD Files**

**06.  LED display fields, Toggle Modes**

**07.  Start: Boot sequence**

**08.  How to measure in logging mode**

**09.  How to measure in surface mode**

**10.  Mounting on person, vehicle, stand, etc.**

**11.  API, uploading sharing data to Safecast**

**12.  Uploading data to other datasets (comparative note)**

**13.  Downloading data from Safecast**

**14.  iOS app -- Safecast Geiger Bot**

**15.  Troubleshooting: Firmware, Hardware, Bugs, Cleaning, etc.**

**16.  Warranty, Certification, Calibration, reliability, validity, units**

**17.  Hardware Cautions**

**18.  Resources, links, support**

---- 
 
**01.  Safety tips for radiation detection**
*This section has been moved to its own Nano wiki page [[Safety|https://github.com/Safecast/bGeigieNanoKit/wiki/Safety-in-radiation-detection]]*

**02. MODEL NAME, SAFECAST HISTORY, DESCRIPTION, USES/AGENDAS**

Safecast bGeigie Nano kit is a **geo-tagged mobile sensor of ionizing radiation** with internet data sharing format and optional wireless capability. It follows from the earlier, larger Bento Geigie. The word “bento” is Japanese for lunchbox; Geigie is cute for Geiger counter; nano followed the mini model. Together with the distributor Medcom Safecast released the nano kit in May [??] 2013.

Although Safecast is best described by its website [[Safecast/About pages|http://blog.safecast.org/about/]], meanwhile a few paragraphs of background (which may move to en.wiki).

 Safecast is a civilian, citizen, non-governmental, non-profit organization which began in April 2011 as an initiative to monitor radioactive contamination from the Fukushima nuclear accident.  The Safecast organization in Japan began developing car-borne geo-tagged radiation measurement devices and crowd-sourced maps which are mainly open-design, open-source hardware and software. Safecast Japan has coordinated the work, mainly at the Tokyo Hackerspace, with inputs of friends from around the world. (For Adrian Storey’s [[3 minute film|http://vimeo.com/51823402]] on Safecast see [[the 14.11.2012 blog|http://blog.safecast.org/2012/11/safecast-short-film/]].

Safecast’s purpose dictated the development and design of the Nano kit mobile sensor. If the non-partisan Safecast organization has an agenda, it is in its **“open data” banner**. The homepage header states, ***“Safecast is a global sensor network for collecting and sharing radiation measurements to empower people with data about their environments.”*** 

On the continuing development of open-source software, quoting a thread on Nano software which began 10-Nov-2013, https://groups.google.com/forum/?hl=en#!topic/safecast-japan/ne5xjGk0lOQ
Rob (roubouden) wrote: …>”Basically Lionel, Robin, Kalin, Joe and me are in charge for software development of the bGiegies. Pieter is coordinating most of the development. Most software is on Github. Intermediate releases are kept off line. Akiba(Chris) is the person who started with Pieter to make the hardware with his company FreakLabs. Naim made the boards for the bGiegienano. Talk with Pieter or Sean about what needs to be done.”  *[the history of safecast and nano is outside scope of manual. Move delete]*

**Uses of the bGeigie Nano**: mobile, static or spot radiation detection. The main use is as a mobile geo-tagged sensor of radiation especially from car windows. It can also be used in static and spot measurements. 

These are some of the **Onyx Applications** in common to nano uses? 

>Documenting the effectiveness of decontamination and safety programs. 

>Sharing radiation measurements with a global mapping system developed by Safecast with MIT Media Lab. 

>Monitoring possible radiation exposure while working around radionuclides or in contaminated environments. 

>Alerting the user with an audible indicator if radiation goes above a pre‐set Alert level. 

>Detecting noble gases [??] and low energy radionuclides. 

>Continuous logging of radiation levels.<

The Nano follows the prototype bento Geigie, and is followed by [or concurrent to] the Safecast Onyx. The Nano has the shape of a car window sensor box, the Onyx a touch button pocket cigarette lighter. They are more similar than they look as they have the same sensor. Where the Nano has self-contained GPS, the Onyx requires the GPS of connecting device (e.g. iOS apple phone). The Nano’s do it yourself, connect it yourself kit allows for customization, for cost savings and user learning. Modular options include an XBee socket, firmware reprogramming and an unassigned button. Options and extra tools are mentioned later in “More Parts”. 

As Pieter wrote: “bGeige Nano [is] the only device with GPS and Wifi/Bluetooth option,… versatile system with a high quality sensor that can do GPS based logging, iPhone interface, measures gamma, beta, alpha, has uSV and Bq/m2 measurement, is fully configurable, is water tight, and is fully open source…. Most importantly, the nano is a fairly simple kit comprised of readily available off the shelf parts. …you can build the Nano Kit in an evening, and be Safecasting the next day. You can take individual spot readings, or attach it to your car and drive around collecting geotagged radiation data that can be uploaded to Safecast via our API upload page.

The Nano is designed as a mobile sensor, to hang outside on a car’s side window. Outside so as not to be shielded by the car. The Nano is hung at the top of the window to be far enough from the ground to get a good background average. The parameter setting of 100 cm is set in the Sensor Height field. This contrasts with close specific surface contamination monitoring (which we do when we find a hotspot thanks to an increased average). The radiation measured on the car window is not areal or airborne gas per se. It's radiating out from radioactive solid stuff (also from liquids ??) on the asphalt, ground, walls, leaves, etc... The Nano is pre-set to monitor radiation from nuclide Cs137. 

Inside the case the Nano measures [[gamma rays|https://en.wikipedia.org/wiki/Gamma_ray]]; outside the case, it can measure [[alpha-, |https://en.wikipedia.org/wiki/Alpha_particle]]/[[beta-, || https://en.wikipedia.org/wiki/Beta_particle]] and gamma-radiation. The grid glued to Nano’s Geiger-muller sensor only blocks a couple percent of radiation and serves to protect the sensitive pancake sensor. As the plastic case blocks alpha- beta- particle radiation, a hole can be cut in a plastic case for a custom alpha-, beta-window. A BoPET (Mylar) film provides protection and allows for alpha, beta and gamma radiation measurement. Optionally the Nano can be fitted with a beta/gamma only window, which is less fragile. [There is a Safecast video of this cut-open case [URL??]. This custom nano hangs in the same place on the car’s side window, with the thin film covered a/b window facing out [??] to measure airborne radioactive particles while driving.] The mylar a/b window is only useful where there are sufficient airborne particles. (Compared to the nuclear particles, the speed and direction of car is negligible. The slowest particle, the high mass alpha has a speed of 15,000 km/s or about 5% of the speed of light. The speed of the beta particle approaches c, the speed of light.) 

The Safecast Dataset is represents mobile background readings, not spot measures of items that happens to be in front of you. Hence the two modes on the device - one for logging and one for spot measurements. Monitoring use and data submission to gets further mention below: in Mode uses; in Uploading data via your API to Safecast dataset. *[Perhaps this should be more clearly stated on the api webpage. Hopefully a guide to monitoring and submitting logs to data-shared projects or successive revisions of this operation manual will explain this point clearly enough for novice Nano users. For reliability of the Safecast dataset, perhaps need guide rules for mobile monitoring in api web page?]*

Removing the nano from its case allows detection of nearby beta activity [within a few [X??] centimeters]. The pancake is actually much more sensitive to beta than gamma, so any beta source should give a clear response. Carefully hold the sensor close to the surface as beta particles lose much of their energy in air. In anycase leave the glued metal grill on the pancake sensor. (Again, the grid only blocks a few per cent of radiation. Be careful not to get any water on the sensor itself as it will damage it. This is repeated in the section Hardware Cautions, water not in the nano and not in the sensor.)

Although the bGeigie Nano is designed to measure alpha- and beta-radiation in addition to gamma-radiation, its detection of radiation from a liquid is at best an indication. Fluid actually blocks radiation. As water shields everything coming to the sensor from below, water typically measures lower than its actual level. The only radiation that will reach the sensor will be from above, and a certain amount of activity coming from decay of atoms in the sensor itself. 

It is very difficult to detect radioactive contamination in food or drink. Food monitoring is best done by a laboratory scintillation counter with chemically processed samples. The Nano’s spot monitoring method of holding nano very close to the food source for at least a one minute provides only a rough indication.-??. 

Although Nano features and parts have their own wiki pages, the sensor gets repeat mention here.
* The sensor is the 2” pancake GM tube [[LND 7317|http://www.lndinc.com/products/17/]], capable of measurement of alpha- and beta- as well as gamma- radiation (referenced for Cs-137 nuclide check source data efficiency). Nano's maximum operating range is to about 350,000cpm, or 1mSv/h (1 millisievert per hour dose rate or 1000µSv/h microsieverts per hour)  (micro sometimes written with u, uSv=µSv).  (Radiation detection units are mentioned further in this guide, see Calibration, reliability. Radiation measurements are averaged, approximate; the more accurate the more complicated?? “Go learn nuclear physics.”)


**03. PARTS (NAMES, FUNCTIONS)** [needs diagram]
*(Parts list moved to [[Parts and accessories|https://github.com/Safecast/bGeigieNanoKit/wiki/Parts-and-accessories]] page)*

**04. TOOLS, ACCESSORIES, OPTIONS** *(this section moved to [[Parts and accessories|https://github.com/Safecast/bGeigieNanoKit/wiki/Parts-and-accessories]] page)*

**05. PARAMETER SETTINGS; DATA LOG; microSD FILES**

* The micro-SD card that ships with the bGeigie Nano contains two pre-set ﬁles, CONFIG.TXT for communication and SAFECAST.TXT for certain user, data parameters. Copy the two root files to any additional Nano microSD card. If the files are corrupted or deleted from the micro-SD, the Nano will not work properly. Keep a backup of your 2 files. Default settings are available online at: https://github.com/Safecast/bGeigieNanoKit/tree/master/SD%20card

The end user should modify user fields like user-name-text and time zone fields. Expert users may customize the efficiency calibration data fields like cpmf (counts per minute factor) with cpmn (counts per minute nuclide) -- but only after study and informing the safecast api database. [Possibly there is a table of alternative calibrated nuclide efficiencies??] Edit the parameters carefully. 

>*”The SD card can't be read over the USB port - instead please use an micro SD card reader“*< Meaning: [Use a USB micro SD card reader to read and edit the micro SD card on your computer.. The micro SD card cannot be read on an microSD card slot.]?? 

The following lists of parameters is taken from the [[NanoSetup.cpp|https://github.com/Safecast/bGeigieNanoKit/blob/master/NanoSetup.cpp]]. The parameters are further mentioned with Data Log Format [ below in 6 – LED Display Fields, Toggle Modes].)

**CONFIG.TXT**: default is: 9600,26,3,2. (Change baud according to hardware customization.) 9600 Baud rate; 26 Data bits; 3 Mark Parity (3=>bit is always logical 1); 2 stop bits (disables use of MARK parity)

**SAFECAST.TXT**

>**nm=** User Name API User Name (or your any text) which appears on data log header line (and up to 15 characters appears on the 10 seconds start up LED display)

>**did=** #### Device ID (bGeigie Nano ####) the serial number on the top plate (or on the purple PCB?)

>**gt=** 0 Geiger Type [??]

>**gm=** 0 Geiger Mode [??]

>**cpmf=** 334 NANO_CPM_ FACTOR (Counts per Minute Detector Efficiency fFactor) 

>**cpmn=** Cs137 CPM Nuclide [Detector Efficiency for Cs137 reference Nuclide]

>**bqmf=** 37 NANO_BQM2_FACTOR (Bequerel Detector Efficiency per Meter Squared, Bq/M^2 Factor] (Bq. Eff.) preset value for counting efficiency for the Nano 

>**bqmn=** Cs137 BQM2 Nuclide [Detector Efficiency for Cs137 reference Nuclide]

>**al=** 150 Alarm threshold (in cpm)  The setting can be left blank (turned off), or set up to a maximum 99,999 CPM. [??]

>**tz=** +/-## Time Zone (local offset to UTC [without daylight savings time ??]) 
e.g. Japan +9; Los Angeles -10 

>**cn=** ABC Country code [your 3-character string, eg. JPN] 

>**st=** 0 Sensor Type

>**ss=** 0 Sensor Shield

>**sh=** 100 Sensor eight (cm) [when if ever can should SH= be modified??]

>**sm=** 0 Sensor Mode

>**cw=** 60 Character width
 
SAFECAST.TXT, setup parameters file on the micro sd card 

Search the web for discussion of questions like: Where did radiation originate – from natural sources (earth and space) or from man-made (medical, military, industrial, nuclear power sources]? What is normal background radiation level? What is safe level -- for whom, when and where? 

The alarm indicators include:
- small Red LED “Log/Alarm” flickers on pulse, remains lit on alarm;
- the small Blue LED “Count” (pulse flicker) and Speaker "clicks" ;
- the Piezo buzzer [??]
The first two can be dimmed (turned off).

- small Red LED “Log/Alarm” will only glow if: GPS is locked, SD card is present, battery has more than 10% charge left, unit is on for one minute, geiger tube is providing a pulse). It can be dimmed by putting the DIP switch #2 Off.

- Speaker "clicks" and small Blue LED “Count” blinks for each pulse from the geiger tube. It can be dimmed by putting the DIP switch #1 Off.

- Piezo buzzer [??] [on hitting a high score, the buzzer will wake up??] 

**DATA LOG**

* The data log file is written to the micro-SD card. 

A key to the fields of the Data Log is given in the [[bGeigie library README.md by fukufuku|https://github.com/Safecast/SafecastBGeigie]]. Below is excerpt of example there of a logged Radiation Data Sentence with Device #300. (The github README also gives an example of **Device Status Sentence**, which hardware message is only mentioned here in passing.) 

>**DATA LOG FILE FORMAT**

>The data is formatted similarly to NMEA sentences that GPS uses. It always starts with a $ and ends with a*. Following the star is a checksum.

>RADIATION DATA SENTENCE: This is the basic message containing the geo-located radiation measurement.

>EXAMPLE:

>$BNXRDD,300,2012-12-16T17:58:31Z,30,1,116,A,4618.9612,N,00658.4831,E,443.7,A,5,1.28,1*1D

**KEY**

>01. **Header**: BNXRDD

>02. **Device ID**: Device serial number. 300

>03. **Date**: Date formatted according to iso-8601 standard. Usually uses GMT. 2012-12-16T17:58:31Z

>04. **Radiation 1 minute**: number of pulses given by the Geiger tube in the last minute. 30

>05. **Radiation 5 seconds**: number of pulses given by the Geiger tube in the last 5 seconds. 1

>06. **Radiation total count**: total number of pulses recorded since startup. 116

>07. **Radiation count validity flag**: 'A' indicates the counter has been running for more than one minute and the 1 minute count is not zero. Otherwise, the flag is 'V' (void). A

>08. **Latitude**: As given by GPS. The format is ddmm.mmmm where dd is in degrees and mm.mmmm is decimal minute. 4618.9612

>09. **Hemisphere**: 'N' (north), or 'S' (south). N

>10. **Longitude**: As given by GPS. The format is dddmm.mmmm where ddd is in degrees and mm.mmmm is decimal minute. 00658.4831

>11. **East/West**: 'W' (west) or 'E' (east) from Greenwich. E

>12. **Altitude**: Above sea level as given by GPS in meters. 443.7

>13. **GPS validity**: 'A' ok, 'V' invalid. A

>14. **Number of Satellites**: Number of satellites in view. 5

>15. **HDOP**: Horizontal Dilution of Precision (HDOP), relative accuracy of horizontal position. 1.28

>16. **Fix Quality**: 0 = invalid, 1 = GPS Fix, 2 = DGPS Fix. 1

>17. **Checksum**: *1D

*A data log or section starts with several #-lines# NEW LOG ; # format=1.1.1nano;  deadtime=on ; etc. *[bring example]*

Other Files on the MicroSD Card:  The micro-SD card is delivered with apple disc system files and folders. [non Apple devices users can delete or leave these on micro-SD? Plenty of space to leave them on the 2gb Micro-SD card.] 


**06. LED display fields, Toggle Modes** [needs photos, enlarged explicit text?]

* The bGeigie Nano has two operating (display and recording) modes, controlled by the toggle switch at upper right. Label on the transparent top panel: (to the right) "bq/m^2; uS/h", (to left) "log; cpm".

+ The “up” position (to the right) switches the unit into geiger counter mode without recording (no logging). Fields displayed on the OLED are indicators for uSv/h dose-rate (Cs137), max dose-rate, dosimeter, Bq/m2 display (Cs137), time stamp and Alarm LED. 

+ The “down” position puts the Nano into recording (logging, mobile tracing) mode. Displayed on the OLED are indicators for CPM and µSv/h, number of satellites locked, altitude (height m), distance traversed (km), total duration of measurement (h:m) and time stamp (dd:hh:mm:ss). When bGeigie Nano is switched to recording mode, the display shows whether a micro SD memory card is inserted or not. [The photo] displays the “NO SD CARD” message, meaning no card is inserted. When a card is inserted properly, this message will disappear. 


**07. Quick Start: Boot sequence**

* The power switch is a sliding switch at the lower right. To turn the unit on, slide it to the up position. First the SAFECAST logo will appear on the display as the splash screen for about one second. 

* The next start-up screen has these the name of model “bGeigie Nano”, the firmware version number, battery charge level, basic settings, and the user’s name (or other customizable information) are indicated.  

**08. How to measure in logging mode**
* In recording (logging) mode the display also shows a lock GPS indication. When the device locks onto GPS, it show the number of satellites found, and a small red LED will glow. The picture shows the “No GPS” message. In this case, GPS lock can be achieved by placing the device near a window and waiting for a few minutes

- small Red LED will only glow if: GPS is locked, SD card is present, battery has more than 10% charge left, unit is on for one minute, geiger tube is providing a pulse). It can be dimmed by putting the DIP switch #2 Off.

- Speaker "clicks" and small Blue LED blinks for each pulse from the geiger tube. It can be dimmed by putting the DIP switch #1 Off.

- Red LED on GPS unit blinks every 1 second in case the GPS is not locked. After that blinks every 10 seconds once locked.

- The date/time stamp on the display is in UTC (formerly called GMT) and not in local time. The time stamp is refreshed when a log data is written to the card. The time stamp is used to create the LOG file name. The UTC log filename may be +/- one day off from the local date of the measurement given time zones and IDL (International Date Line). The local time zone offset appears with the parameters in the top header line of the log file.

**09. How to measure in surface mode** (using the Nano taken outside of its case for α- and more β-detection)

- removal from its case (with or without the rubber liner)

- photo how to best take unit out of case by using both thumbs to push in and swivel out the unit. (Can be reinserted into case as above or inside the removable rubber liner.)

- in uSv/Bq mode display also shows Peak dose rate (in uSv/h) and total accumulated dose (in uSv) and CPM 

- uSv dose rate (put in case, hold 1m above ground, tilt around 45 degrees, wait for 1 minute for stable reading)

- bQ (take out of case, keep within 5cm to 1cm from surface, 1 minute for stable reading, read value on second line in Bq/m2, speaker sound to aid in finding hotspots)

- provides indication but has limitations  

Kalin wrote: “The grid on the pancake sensor is only useful when you take the unit out of the Pelican to look for surface contamination (alpha/beta). The grid itself has a very small shielding effect, mostly for alpha/beta and weak gamma. Given the standard +/- 15% accuracy of the unit, you can ignore it.”

“Averaging two different Nanos --you should only compare long-term counting (e.g. number of counts for 10 minutes). “ 


**10. Mounting on person, vehicle, stand, etc.**

Mobile sensor -- the Log mode display also shows height (m), distance traversed (km) and duration of measurement (hh:mm) The log file UTC date/time, TZ header, GPS coordinates, readings,… *[Mounting examples need editing and photos.]*

**Car** Close window on straps. Tie straps to interior anchor, inside bar over window. In a blog there’s mention of child inadvertently opening back seat window and the bGeigie falling off the care, but it was recovered without damage. Don’t rely on window lock, but tie the strap to anchor.

**Bicycle ** (See photos and film clip with bGeigie Nano with extra options (wireless, air quality sensors, bicycle exercise sensors) http://www.youtube.com/watch?feature=player_embedded&v=nHpVq1szhz0  at Tokyo Maker Faire Nov 3rd-4th 2013 https://groups.google.com/forum/?hl=en#!topic/safecast-japan/2DqAoqkWAn8

**Carry, bag or pack attachment** 

**Underwater** 

**Helicopter drone** http://blog.safecast.org/2013/05/safecast-air-force-drone-program/

**Airplane passenger** - strap onto utility tray near a window.  Pieter wrote: >”Some of you have asked how to mount a bGeigie [as a passenger in commercial flight]. The attached pictures are self explanatory. In this case the unit remained GPS lock even with the tray in the downward position. The key trick is to get the nano to lock onto the GPS -- this only works as long as you have a window seat and typically requires the unit to be very near to the window to get a good lock and may take a few minutes - after that the unit can be a little further a way (30-40cm) as long as there's a good 'view' from the unit to the window. Airplanes are very well shielded, and the ease of getting a good lock may vary from airplane model to exact seat location. Like use of all electronic equipment, please follow the instructions of the airline during take off, in flight and landing. < Pieter IMG_7688.jpg  ; IMG_7689.jpg

**Snow** http://blog.safecast.org/2012/02/measuring-radiation-in-snow/ 

**Baby carriage** (Baby can kick Nano out when you’re not looking. Keep Nano fastened.. The height from ground setting is preset at 1 meter for car window. (On 2nd thought the Nano is not a baby toy given possible contamination in sampling.)


**11. Safecast API, uploading sharing data to Safecast**

Where once data logs were sent by email, now this is done by the safecast API

The Safecast Dataset is meant to represent mobile background readings, not spot measures of items that happens to be in front of you. Hence the two modes on the device - one for logging and one for spot measurements. Monitoring use and data submission to gets further mention below: in Mode uses; in Uploading data via your API to Safecast dataset. *[Perhaps this should be more clearly stated on the api webpage. Hopefully a guide to monitoring and submitting logs to data-shared projects or successive revisions of this operation manual will explain this point clearly enough for novice Nano users. For reliability of dataset, perhaps need guide rules for mobile monitoring in api web page?]*

You should not submit any readings that are samples of "items" or stationary static logs. *[need something here about the approval of data criteria ? guide to mobile logging? datasets ;  make API account ;   steps  ??]*

**12. Uploading data to other datasets (comparative note)**

You can submit Nano measures to other radiation mapping datasets,. (The more the merrier. In any comparative note Safecast might stand out for its mobile monitoring, open datasets, mappings, visualization, reliability of measures, -- but that is separate study)

Of course you need to configure the Nano sensor and your data with the other datasets. An exception may be the Cosm/Pachube setting in the Safecast geigerbot. (Theoretically you can upload to the mobile Safecast and the static Cosm/Pachube datasets simultaneously. However you’re either mobile or static. [??])  


**13. Downloading data from Safecast** whole dataset.csv in zip  * [Safecast] (Download Free)  CC0 legal status: web entry by joi. “The legal and ethical reasoning behind using CC0 for Safecast data”. Sept 5, 2011  http://creativecommons.org/publicdomain/zero/1.0/ 
Creative Commons Zero, CC0 (occasionally written as CC Zero) is a public domain dedication that allows copyright holders to place works in the public domain to the extent legally possible, worldwide. “all rights granted” space of the public domain.

Uses of data. analysis mapping , etc, mapped track of recording device..
* https://github.com/bidouilles/safemaps Safecast interpolation tools … 


**14. iOS app: Safecast Geiger Bot app**

* Safecast Geiger Bot app works in iOS devices. 

Although there’s occasional talk on the web about working on an android version, the porting of geigerbot into android is unlikely. See “Android / Platform Support Mini-FAQ” in https://sites.google.com/site/geigerbot/docs , The app author Nick Dolezal writes, "The majority of what Geiger Bot does is heavily tied to iOS-specific frameworks. It would almost all have to be rewritten."

Nick Dolezal  on Oct 12: 

>“The server update process for the app's map data runs every 4 hours starting at midnight GMT, and takes about 10 minutes to run on the server. It will not run if there weren't any new measurements since the last update, so you can have periods greater than 4 hours where the app will not update with the message "You already have the most recent data". It is not really ideal but at least it's working and it will be some time before I can come back to it.

>Generally I would recommend only uploading data via the logfile to the Safecast website directly if possible. When the app does analog click counting, when properly configured it can be quite accurate, but a perfect digital copy of the data already exists. Uploading it as a "drive" also provides a context and metadata for more in-depth analysis later that individual measurement uploads do not have.

>In principle the app's analog click counting is quite simple -- it simply looks for samples in the recording buffer from the OS that exceed threshold X.

>But there are many, many factors that can affect it. As a starting point I recommend verifying the output of the pulse with an oscilloscope; make sure the voltage is in the consumer line-level range (http://en.wikipedia.org/wiki/Line_level) and make sure the pulse width (duration) is at least 2 samples at 44.1 khz. (http://en.wikipedia.org/wiki/Nyquist%E2%80%93Shannon_sampling_theorem). Finally, verify the pin-out is correct -- both at the unit and at the end of the cable. The cable or device must also short mic and ground with a resistor of a certain impedance to be detected by the iPhone. If you overdo that or it's done with the cable and unit you won't see any input at all. (I don't know if the bGeigie does this on the unit like the Onyx does) If you don't have an oscilloscope, a DSO Nano is pretty cheap on eBay or Amazon.

>Software factors that may affect input include: app settings, OS settings (such as accessibility features), the iOS 7 microphone permissions, etc. To remove all doubt of software issues, there is at least one free oscilloscope app you can download off the App Store. (it is not a replacement for a hardware oscilloscope though if the signal isn't getting to the iPhone)

>Hardware factors include differing impedance in electronics or cables, non-voltage regulated output + low battery, noise from external power (really messes up gamma spectroscopy, actually), etc. There may be configuration settings affecting audio output or level as well; I don't know if the DIP switch for the speaker volume on the Nano affects the line out or not.

>The most common issues I've seen from users are:
>1. Wrong cable (one user had some equivalent of a "null modem" cable which swapped wires internally -- should be straight/passthrough)
>2. Cable not wired correctly (either pin-wise or the short resistor the iPhone needs)
>3. Too high of input voltage (results in no audio route available and the audio engine's watchdog timer freaking out)

>Note if the mic-ground in the cable isn't shorted correctly, the app will report an audio route change to "Headphones" on the console. The audio route required for a line input cable is "Headset".

>Finally, while I have not tested this, it's possible a paired Bluetooth headset could override the line input cable as an input source. I'm honestly not sure offhand how these get prioritized by iOS.<<  

>>Nick Dolezal 	
>The magi behind all things iOS in Safecast Land, Nick Dolezal, is working hard on the new version of the Safecast app (which will allow on demand refreshing of the map data) decided to whip up these alternate visualizations of the Safecast data. These maps show the frequency of samples taken – NOT READINGS OF THOSE SAMPLES – just showing how often a specific place has been measured. In this example, a location (like Fukushima) that has been measured repeatedly would show hot. Thought this was a really interesting look at the work Safecast has done over the last 2+ years

{{May 4 * Safecast Device Discussions and Support ›
Onyx - iPhone Connection Guide
[There’s instructions for app with ONYX but some might be relevant to app on NANO?]

app-API Troubleshooting
>2.1 Further, on the main numeric display of the app, you can tap on the top part of the screen to show a console with detailed log messages regarding connection attempts and which input device is selected. If successful, the API upload will return HTTP 201 CREATED.

>3. Verify Input : 
>A. Tap the min/max arrow button in the lower-right hand corner of the map to resize it into a small window.
>B. The interface of the app has now changed. It is now split between fixed buttons at the bottom, and four possible display screens at the top, of which the map is 4 of 4. If you've used HP calculators and know what "Pipboy 3000" means, you can probably just stop reading right here. These four screens are: [Main Numeric Display] - [CPS/CPM graph] - [Audio input monitor graph] - [Map]

>C. Tap the "<" button next to the white page dots under the map. You are now looking at the audio input monitor.

>D. Verify you are correctly seeing counts from the Onyx appear. The black line represents the input. The red line which never moves is the threshold the input volume must exceed for it to be counted. The black line will be colored blue when it has been counted as a pulse.

>E. The two problems I've heard about so far preventing this from working are a bad serial cable, and a "Geiger Pulse" setting on the Onyx of something other than 6, which is the default. Confusingly, a bug in the Onyx release firmware prevents the Geiger Pulse from displaying properly. (it will always show 0) TL;DR: the Geiger Pulse setting on the Onyx will be fine unless changed from the default.

>4. Configure Safecast Settings
>A. Now tap the "Settings" icon on the fixed button panel, which is a machine gear. Scroll to the bottom of the list and select "Safecast".
>B. Enter your API key. Change the upload interval as desired, but you shouldn't change the Safecast device.<< back to nano 


**15.  Troubleshooting:** Firmware, Hardware, Current bugs, Cleaning**
**Current bugs** Open issues are processed in the devices discussion group. could also be mentioned here in manual – under troubleshooting or separate item.?*)

* Oct 2013. GPS model Adafruit “Ultimate GPS”. Failed on 7 recent builds. Manufacturer support forum thread opened on 28 Oct 2013. http://forums.adafruit.com/viewtopic.php?f=22&t=45198  Issue resolved with firmware fix, group threads https://groups.google.com/forum/?hl=en#!topic/safecast-devices/iRlxIvspjkE
Fix V.1.3.2 firmware fix , 11.11.? 

Other known bugs: 
* an overflow at high rates ?

*(Piezo electric buzzer? It's odd that it's got quieter over time, we're investigating changing the drive frequency of the buzzer which may help make the buzzer louder in general.

*Datestamp in log file names? “One other thing I have noticed, is when you are doing readings the date stamp is the log number for the filing system so you can load it to the site. If you was to go out a second time in the same day you will see that the new file will be loaded to the all 0 file and not the date file. With this it writes over the all 0 file. if you try and go out a third time watch out, have your file downloaded because you will lose the prior history of your travels that was logged in the all 0 file, as it will over write again. So keep things backed up before you head out. It seems the only file that maybe loaded onto the site more then once is the all 0 file. because the date file for the event would have already been uploaded if you are consistent in uploading. I am not sure if there is a way to force a new file to be made to not overwrite old files while out in the field.”

Please check all solder joints carefully - you must have missed a joint or have a cold solder joint. It can cause the display to act unpredictably.

**Firmware: github; upgrades; troubleshooting****

* for the current version of firmware see the description of file bGeigieNano in https://github.com/Safecast/bGeigieNanoKit [V1.2.9 on 24-10-2013] 

* Firmware upgrades of FIO via FTDI: [see wiki page "How to setup build environment..."]

* more questions: go to nano.safecast.org, devices support and discussion google group or email info@safecast.org

**Cleaning ** 
(First remove the nano from the case .Never wet the Nano interior.) 

*. Use a soft brush and air blower can be used o the Nano, carefully. (Vacuum?) (Electronics labs use unheated air blowers for dusting off parts)

* The liner may be rinsed in clean water. 

*The case may be rinsed with clean slightly damp microfiber coth. [Last rinse preferably in filtered or even distilled water-??]

*LED wipe?  Work with the screen display turned off and cool.  Wipe the screen using light pressure.  Use clean, lint free cotton, microfiber cloths or low-lint wipes. ( 

**16. Warranty, Certification, Calibration, reliability, validity**

**Warranty**. This is a kit. See kit fulfillment in the Nano Manual Kit Assembly. email contact@safecast.org. 

**Certification** “The nano itself will go through official certification for gamma reading inside and outside of the pelican case. Once this has been done and we find any variance, the nano allows for easy recallibration in the parameter file that's on the nano's SD card. ; the Onyx certification we found accuracy within 2% over a wide range of radiation. itself (like the Onyx with the same GM pancake sensor) Source” [[Information, Misinformation, Disinformation (or, these aren’t the droids you’re looking for)|http://blog.safecast.org/2012/12/information-misinformation-disinformation-or-these-arent-the-droids-youre-looking-for-part-1/ ]] Part 1 December 29, 2012, which blog article compares different kinds of radiation detectors, radiation units..…  

**Calibration**: jam wrote in some blog or thread, the following:
“The sensor is pre-calibrated so nothing needs to be done on that end. The calibration of the unit for Bq for Cs assumes the grid is in front of the pancake. The difference is around 5%. For gamma only, the grid has negligibly effect on the measured value.

“The uSv/h conversion from CPM is calibrated assuming the grid is on the tube. As all Safecast measurements are done with the pancake WITH grid, please keep the grid on the tube. The grid itself will not block alpha or beta, but reduces the sensitivity a little bit as the grid covers a small portion of the sensor. In practice the difference with and without grid will be around 4-5% for a beta source, and less for a gamma source.

“Geiger counters are very simple devices, the tube detects the particles flying through and counts them - this is the raw CPM count. The software we have preloaded the device with takes into account the sensor type and calibrates readings for Cs137 so all bGeigie Nano's have the same configuration and can be compared against each other.

“So basically the only reason other devices like the inspector, has a calibration pot on them is to adjust for other type of isotopes accurately. Most devices are calibrated for Cs137. If you were interested in an accurate account of a different isotopes, then calibrating would be needed. The nano is set up to yes read for everything in CPM, but when talking about sieverts the math for the conversion only works for Cs137, Like most other units. Sieverts is the concentration of ionizing radiation absorbed per unit of a material's mass. Comparable to units of specific energy. If you wanted to know the amount of energy you are being blasted with of say, Sr90. The individual would have to find an accurate check source to recalibrate the device and input the correct math for the conversion. 

“In the bad old days of analog Geiger counters, the pulses coming from the tube were fed to an integrator and that was used to generate a proportional current that would deflect the needle on the unit's display. As you might imagine, there were several ways that might not scale perfectly. Each integrator and amplifier was different as was the spring in the meter. And, they could change with time or temperature. Consequently, it was necessary to regularly feed them a pulse train of a known frequency and then adjust something until the needle pointed to the proper reading.

“Digital technology alleviates all that. We count every pulse with a microprocessor and calculate the corresponding dose rate mathematically. The sensitivity of the sensors themselves is very consistent and stable. As is the time base for the processor. Unless something gets broken, a bGeigie Nano's calibration should never change. And if it does get broken, it is very likely to be obvious. 

“Old analog clocks had a way to adjust their regulator too, but when have you ever heard of a digital quartz wristwatch needing adjustment? Never? Me neither.” - jam

That said, e.g. example Univ of Maryland, Chapter II, Radiation Instrumentation http://www.des.umd.edu/rs/material/tmsg/rs4.html

>>GM counters are usually calibrated against a specified reference standard at a fixed distance from the detector (usually 1 centimeter) and a variable pulse generator.
Efficiencies for instruments expressing results in terms of counts rates can be calculated from the following formula,: Divide the observed sample count rate by the detector efficiency to obtain the actual disintegration rate, when efficiency is calculated:
Efficiency = Observed Standard Count Rate (cpm)
Known standard Disintegration Rate (dpm)
<<

Data interpretation, data sharing, interpretation, reliability, robustness, presentation, mapping, analysis, validity, reliability (learn to use correctly)… 

* On radiation units* (borrowing from Kalin comparing bGeigie against droids): >”…there’s a reasonable degree of variation that can be caused by the slight differences in the specs of the various devices. Though grays (Gy) are the technically correct unit to use for measuring activity in terms of “absorbed” dose, sieverts (Sv), which represent a conversion of this to “equivalent” dose, are more familiar to most people. When we are looking at gamma or beta activity, grays and sieverts are essentially equivalent numerically, despite their different meanings (much like how 1 liter of water weighs 1 kilo), and the labeling of the droid’s display might be confusing to some citizens. …accuracy range of 20% and a detection range of from 0.01 microsievert/hr to 5.0 Sievert/hr, uses Geiger-Muller sensors placed at 1 meter height, displaying averaged samples updated every 60 seconds, etc.. It also states clearly that the readings are intended as a general guideline only. 

**17. Cautions, hardware protection** 

* The Pelican micro case is shockproof and water-resistant. However it is not waterproof and it cannot be used underwater. Condensation can build up in the case due to temperature differences. This condensation will evaporate with time, or can simply be removed by opening the unit and drying it {with fibrefree cloth}. Closed-up inside its case the Nano can be used on bicycles without problem.

* Do not use the unit outside of its water resistant case with wet hands, when in the rain, or where too close to a dripping tap. 

- The MICRO-SD CARD cannot be read over the USB port [??] -- instead use a micro SD card reader

**BATTERY Cautions:** (also see [[Nano Manual Kit Assembly|https://github.com/Safecast/bGeigieNanoKit/wiki/NANO-MANUAL]] (Charge via micro USB cable, yellow LED will dim once fully charged, full charge takes 5-6 hours, bGeigie nano runs approx 35-40 hours on a full charge in LOG mode. Battery indicators: icon in bottom right of display, and; Per cent of battery charged appears on startup screen.)

+ **NEVER charge the bGeigie while the unit is in ON.** Power MUST be turned OFF before charging to avoid permanent damage to the charge circuit. 

+ Replace a broken (detached wire) battery with the same rating (2000mAh 3.7V Lithium Polymer (Li-Po, Li-Poly). The Nano charge circuit may overheat if larger batteries are used.

+ A Li-Po battery can be hazardous if mylar membrane is punctured. Handle carefully! 


**SENSOR Cautions:**

- NEVER touch the membrane of the pancake sensor! (It can damage the sensor!) 

Inside its closed Pelican micro-case the Nano sensor is very well protected from shock and from pressure transients.
-- the only air flight issue is if the geiger is in your check-in luggage, the non pressurized storage area may cause pressure swings that under some circumstances can damage the sensor. If in checked bag it is more likely to be broken, lost, confiscated,or stolen. Best to take the Geiger in your carry-on luggage

-. Sudden changes in pressure, like slamming a car door, can possibly damage the sensor. The pressure on the inside of the tube is very low. The membrane is under constant tension from atmospheric pressure. Being at altitude *reduces* the strain on it. 
But, the membrane is basically extremely thin glass. Mica to be precise, so it's low density and very brittle. Any sharp shock can shatter it. And of course anything that pokes it will pop it like a party balloon. 

[[Some of Onyx hardware precautions|http://medcom.com/wp-content/uploads/2013/03/Safecast-X-Kickstarter-Onyx-12.91.pdf]] , relevant for Nano??:
> Precautions To keep the Onyx™ in good condition, handle it with care, and observe the following precautions:

> Do not contaminate the Onyx™ by touching it to radioactive surfaces or materials. Instead, hold it just above the surface that is suspected of contamination to take readings. 

> Do not leave the Onyx™ in temperatures over 122° F (50° C) or in direct sunlight for extended periods of time. 

> If the surface of the mica on your pancake detector becomes scratched or loses its coating, avoid making measurements with the detector window in direct sunlight; this could affect the readings. 

> Do not put the Onyx™ in a microwave oven. It cannot measure microwaves, and you may damage it or the oven. 

> Measuring and learning about radiation is interesting. Please remember to not treat radiation sources casually. Exposure to even relatively low levels of radiation can result in negative health effects over time


**18. RESOURCES, LINKS, SUPPORT**: repeats on information resources for users of the Safecast bGeigie Nano mobile sensor of ionizing radiation. 

The Safecast website http://blog.safecast.org/ has articles, news, notices, API upload and open download of crowd-sourced radiation data and visualized mapping, etc

Join the Safecast Devices Discussions and Support: ([[devices group|https://groups.google.com/forum/?hl=en#!forum/safecast-devices]]. “A discussion group for the community using and hacking Safecast designed open source hardware including the Medcom Onyx and the bGeigie Nano”. It is listed among several links on the Safecast home page.

Github is a community project development archive mainly for technical users. Safecast currently has 16 public github respositories, repos or buckets, including [[bGeigieNanoKit|https://github.com/Safecast/bGeigieNanoKit/]], the more veteran firmeware [[SafecastBGeigie|https://github.com/Safecast/SafecastBGeigie]], the electronics [[Eagle repo|https://github.com/Safecast/SafecastEagleHW]], etc.

Appropriate use of the Nano has a modest learning curve. Fortunately, the end user doesn’t have to master the fields of radiation safety, health physics and environmental sciences which in contrast are huge studies. Spot and mobile monitoring and crowd data-sharing projects require a orientation and a little practice.

The Safecast end user, the volunteer civilian monitor, **the citizen scientist** is helping to collect data, environmental information, for the public and for scientists. Scientists may use this data in their research methods, possibly making science, possibly discovering new knowledge in their fields. With Nano use and contribution of data logs to web datasets, Nano users learn and teach about radiation detection, safety and many issues. 