Nano Operation Manual Outline
version July 23 2013

Opening info: What's the Nano for?  What can you do with it? [add text]

Quickstart guide
      Base this on the guide done for Hong Kong
           Boot sequence
1. The power switch is a sliding switch at the lower right. To turn the unit on, slide it to the up position. The SAFECAST logo will appear on the display. 

2.Next, the bGeigie Nano’s firmware number, battery charge level, basic settings, and the user’s name (or other customizable information) are indicated. 

The bGeigie Nano has two operating (display and recording) modes, controlled by the toggle switch at upper right. Label on the transparent top panel: (to the right) "bq/m^2; uS/h", (to left) "log; cpm".
+    The “up” position (to the right) switches the unit into geiger counter mode without recording (no logging). Fields displayed on the OLED are indicators for uSv/h dose-rate (Cs137), max dose-rate, dosimeter, Bq/m2 display (Cs137), time stamp and Alarm LED. 
+    The “down” position puts the Nano into recording (logging, mobile tracing) mode. Displayed on the OLED are indicators for CPM and µSv/h, number of satellites locked, altitude (height m), distance traversed (km), total duration of measurement (h:m) and time stamp (dd:hh:mm:ss). When bGeigie Nano is switched to recording mode, the display shows whether a micro SD memory card is inserted or not. [The photo] displays the “NO SD CARD” message, meaning no card is inserted. When a card is inserted properly, this message will disappear. 

In recording (logging) mode the display also shows a lock GPS indication. When the device locks onto GPS, it show the number of satellites found, and a small red LED will glow. The picture shows the “No GPS” message. In this case, GPS lock can be achieved by placing the device near a window and waiting for a few minutes
      - small Red LED will only glow if: GPS is locked, SD card is present, battery has more than 10% charge left, unit is on for one minute, geiger tube is providing a pulse). It can be dimmed by putting the DIP switch #2 Off.
      - Speaker "clicks" and small Blue LED blinks for each pulse from the geiger tube. It can be dimmed by putting the DIP switch #1 Off.
      - Red LED on GPS unit blinks every 1 second in case the GPS is not locked. After that blinks every 10 seconds once locked.
      - the time stamp on the display is in UTC (formerly called GMT) and not in local time. The time stamp is refreshed when a log data is written to the card. The time stamp is used to create the LOG file name. The log filename may not match the date of the measurement in local time (e.g. maybe +/- one day off) given time zone variance.


           What are the switches for?

How to measure in logging mode.
         Mounted
            car - photo how to put on a car window (strap)
            bicycle, motor cycle, etc
         Carried - how to use walking (clip)
	 Plane - photo how to use in airplane (strap onto utility tray near a window)
      - in Log mode display also shows height (m), distance traversed (km) and duration of measurement (hh:mm)

How to measure in surface mode (including using the Nano taken out of case for α- and more sensitive β-detection)
-       removal from its case (with or without the rubber liner)	- photo how to best take unit out of case by using both thumbs to push in and swivel out the unit. (Can be reinserted into case as above or inside the removable rubber liner.)
-     - in uSv/Bq mode display also shows Peak dose rate (in uSv/h) and total accumulated dose (in uSv) and CPM    
-       uSv dose rate (put in case, hold 1m above ground, tilt around 45 degrees, wait for 1 minute for stable reading)
-       bQ (take out of case, keep within 5cm to 1cm from surface, 1 minute for stable reading, read value on second line in Bq/m2, speaker sound to aid in finding hotspots)
-       Do not use the unit outside of its water resistant case with wet hands, when in the rain, or where too close to a dripping tap. 

Cautions

Battery charging
+      (micro USB cable, yellow LED will dim once fully charged, full charge takes 5-6 hours, bGeigie nano runs approx 35-40 hours on a full charge in LOG mode, battery indicator in top right of display, per cent level charged appears on startup.)
+       cautions- **NEVER charge the bGeigie while the unit is in ON.** Power MUST be turned OFF before charging to avoid permanent damage to the charge circuit. 
+       Replace a broken (detached wire) battery with the same rating (2000mAh 3.7V Lithium Polymer (Li-Po, Li-Poly). The Nano charge circuit may overheat if larger batteries are used.
+       A Li-Po battery can be hazardous if mylar membrane is punctured. Handle carefully! (See the Manual on kit assembly for more on battery.) 

Uploading data
After recording measurements, you can upload your data through Safecast API site. 
It will be reflected to the Safecast map http://map.safecast.org/ and also iOS application [Safecast] (Download Free)

       make API account
       steps

Other cautions: 
     - NEVER touch the membrane of the pancake sensor!
     - NEVER touch the membrane of the pancake sensor! (again)
     - replacing the SD card with another SD card will not work unless the CONFIG.TXT and SAFECAST.TXT files are copied. Download from nano.safecast.org
     - The SD card can't be read over the USB port - instead please use an micro SD card reader
     - Outer Pelican case is shock proof and water resistant, however not water proof and can't be used under water. Due to temperature differences, condensation can build up in the case which will go away with time, or can simple be removed by opening the unit and drying it. bGeigie can be used on bicycle frames without problem.

    - more questions: go to nano.safecast.org, google group xyz or mail us at info@safecast.org

Parameter settings: The SD card contains a setting file which must not be deleted from the card or the Nano wll not work properly.  In addition, it must be copied to any additional cards which will be used with the nano (This information can be edited to modify the device’s operation, but this is only recommended for expert users)  
Troubleshooting


Extras
      WiFi