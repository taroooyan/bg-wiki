bGeigieNanoKit features, specifications, description list, updated with community editing, here in https://github.com/Safecast/bGeigieNanoKit/wiki/_pages
Initially copied from June 2013 version on http://medcom.com/radiation-monitors/geiger-counters/bgeigie-kit/ 

**Three system modes in one:**
*	**bGeigie mode** – mobile radiation sensor logging with display indicators for CPM and µSv/h, number of satellites locked, altitude (m), distance traversed (km), total duration of measurement (h:m) and time stamp (dd:hh:mm:ss)
*	**xGeigie mode** – geiger counter (no logging) with display indicators for µSv/h dose-rate (Cs137), max dose-rate, dosimeter, CPM, Bq/m2 (Cs137), time stamp and Alarm LED
*	**iGeigie mode** – iPhone compatible output for Safecast iOS app. iPhone app shows dose rate and can upload data realtime to Safecast API.
*	Hot switch between bGeigie and xGeigie modes (recording is paused in xGeigie)
*	**Sensor**: 2” pancake GM tube LND 7317 with Medcom iRover controller and HV (high voltage) supply; capable of measuring alpha, beta and gamma radiation. Maximum range to about 1mSv/h dose rates. URL: http://www.lndinc.com/products/17/
*	**Dual use modular design** – main unit can be taken out of case for α-, β-detection, e.g. use as surface contamination survey meter
*	High quality **GPS** receiver with external booster antenna connector
*	**Dual CPU**: Atmel, Arduino. Open-source software.
*	OLED display: 128×64 high contrast, two OLED display sizes supported
*	Blue Indicator LED for every nuclide detected (with cool afterglow)
*	Red Indicator LED for “recording” (bGeigie mode) or “alarm” (xGeigie mode) indicators
*	Orange indicator LED for charge status
*	Buzzer (can be switched off)
*	Battery status indicator on OLED display, with low Battery alarm.
*	**2000mAh 3.7V 7.4Wh Lithium Polymer battery** (Li-Po) for about 40-hours nonstop operation in bGeigie mode. mini-USB rechargeable
*	Memory: 2Gb micro-SD card  (included)
*	Many parameters configureable through config file on µ-SD card (e.g. user name, conversion factor for µSv/h and Bq/m2, time interval, Safecast API format, fields of added options such as barometer's, etc.)
*	Audio data communication cable for Apple iPad or iPhone
*	Realtime clock
*	**Pelican 1010 micro case**:  Clear plastic, hinged cover and strong latch. Water resistant (not for submerging), crushproof, and dust proof. Removable liner (in yellow, black, blue or red). With strap, plastic buckle and carabiner (spring hook) for easy carry or secure mounting on vehicle. (Compact size fits some bicycle cases.) 
*       Dimensions: see http://www.pelican.com/cases_detail_specs.php?Case=1010 
*       Weight (without added option in Xbee socket):  ?? gr
*	Function button (user assignable)
*	Wireless option – BLE-enabled bluetooth, 802.15.4 or Wifi supported through Xbee socket – send data wirelessly to bGeigie Ninja or smartphone. Wireless components not included in this kit. (On experimental developments, various options, supplemental upgrades: follow the news and links on the Safecast website http://blog.safecast.org and the *Safecast Device Discussions and Support* group:  e.g. thread entitled *"enticing looking socket on gbeigie Nano"* which began 2013-06-29  https://groups.google.com/forum/?hl=en#!topic/safecast-devices/ZUurezK2aaE)
*       Safecast logo and serial number on top panel

For other wiki pages, **Nano Manual**, see Nano wiki home https://github.com/Safecast/bGeigieNanoKit/wiki -- On **firmware history**, see https://github.com/Safecast/bGeigieNanoKit/commits/master -- For **technical summary, specifications, licenses**, see README.md at bottom https://github.com/Safecast/bGeigieNanoKit 