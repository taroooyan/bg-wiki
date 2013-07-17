bGeigieNanoKit features, specifications, description list, updated with community editing, here in https://github.com/Safecast/bGeigieNanoKit/wiki/_pages
Initially copied from June 2013 version on http://medcom.com/radiation-monitors/geiger-counters/bgeigie-kit/ 

**Three system modes in one:**
*	**bGeigie mode** – mobile radiation sensor with display indicator in CPM and µSv/h, number of satellites locked, height (m), distance traversed (km), total duration of measurement (h:m) and time stamp (dd:hh:mm:ss)
*	**xGeigie mode** – geiger counter mode (no logging) with display indicator for uSv/h dose-rate (Cs137), max dose-rate, dosimeter, Bq/m2 display (Cs137), time stamp and Alarm LED
*	**iGeigie mode** – iPhone compatible output for Safecast iOS app. iPhone app shows dose rate and can upload data realtime to Safecast API.
*	Hot switch between bGeigie and xGeigie modes (recording is paused in xGeigie)
*	**Sensor**: LND 7317 2” pancake GM tube with Medcom iRover controller and HV (high voltage) supply; capable of measuring alpha, beta and gamma radiation
*	**Dual use modular design** – main unit can be taken out of case for α-, β-detection, e.g. use as surface contamination survey meter
*	High quality **GPS** receiver with external booster antenna connector
*	**Dual CPU**: Atmel, Arduino. Open-source software.
*	OLED display: 128×64 high contrast, two OLED display sizes supported
*	Blue Indicator LED for every nuclide detected (with cool afterglow)
*	Red Indicator LED for “recording” (bGeigie mode) or “alarm” (xGeigie mode) indicators
*	Orange indicator LED for charge status
*	Battery status indicator on OLED display, with low Battery alarm.
*	Buzzer (can be switched off)
*	**2000mAh 3.7V 7.4Wh Lithium Polymer battery** (Li-Po) for about 40-hours nonstop operation in bGeigie mode. USB rechargeable
*	Memory: 2Gb SD micro card  (included)
*	Many parameters configureable through config file on SD card (e.g. user name, conversion factor for µSv/h and Bq/m2, time interval, Safecast API format, etc)
*	Audio data communication cable for Apple iPad or iPhone
*	Realtime clock
*	**Pelican 1010 micro case**:  Water resistant (not for submerging), crushproof, and dust proof. Clear plastic with Safecast Logo. Removable liner (in yellow, black, blue or red). With strap, plastic buckle and carabiner (spring hook) for easy carry or secure mounting on vehicle. (Compact size fits some bicycle cases.) Dimensions: see http://www.pelican.com/cases_detail_specs.php?Case=1010 
*	Function button (user assignable)
*	Wireless option – bluetooth, 802.15.4 or Wifi supported through Xbee socket – send data wirelessly to bGeigie Ninja or smartphone. Wireless components not included in this kit. (On experimental development, options, updates and all, see safecast-devices google group and follow the links on the Safecast website http://blog.safecast.org) 

For **Nano Assembly Manual** see  https://github.com/Safecast/bGeigieNanoKit/wiki/NANO-MANUAL

-17/7/2013