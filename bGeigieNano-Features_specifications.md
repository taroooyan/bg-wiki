Safecast bGeigieNanoKit features description list. Community edited here in [[Nano wiki pages|https://github.com/Safecast/bGeigieNanoKit/wiki/_pages]].  
*Draft 4 Nov 2013, adds from similar sensor [[Safecast-Medcom Onyx specs|http://medcom.com/wp-content/uploads/2013/03/Safecast-X-Kickstarter-Onyx-12.91.pdf]]*

**Three system modes in one:**
*	**bGeigie mode** – mobile radiation sensor logging with display indicators for CPM and µSv/h, number of satellites locked, altitude (m), distance traversed (km), total duration of measurement (h:m) and time stamp (dd:hh:mm:ss)
*	**xGeigie mode** – geiger counter (no logging) with display indicators for µSv/h dose-rate (Cs137), max dose-rate, dosimeter, CPM, Bq/m2 (Cs137), time stamp and Alarm LED
*	**iGeigie mode** – iPhone compatible output for Safecast iOS app (geiger bot): shows dose rate, mapping and can upload data realtime to Safecast API.
*	**Hot switch** between bGeigie (logging) and xGeigie (no logging) modes (recording is paused in xGeigie)
*	**Dual use modular design** – main unit can be taken out of case for α-, β-detection, for careful use as surface contamination spot meter
*	**Sensor**:  [[LND 7317|http://www.lndinc.com/products/17/]] “Pancake” Halogen-Quenched Geiger-Mueller (GM) tube; 2”; Effective diameter 1.75” (45 mm); Mica window density 1.5-2.0 mg/cm2; capable of detecting Alpha-, Beta- and Gamma-radiation. With Medcom iRover controller and HV (high voltage) supply.
*       **Operating Range**: μSv/h**: .000 to 1,000 ; mR/hr: .000 to 100 ; CPM: 0 to 350,000 
*       **Alarm LED** [and buzzer?] when warning level is set . Alert Range 0 to 99,999 CPM (maximum to about 1mSv/h dose rate).   
*       **Accuracy**: +/- 10% typical, +/- 15% maximum   [* as with Onyx ?]  
*       **Temperature Range** -20 to +50 C, -4 to +122 F   [* as with Onyx ?] 
*	High quality **GPS** receiver with external booster antenna connector for (geo-tagged logging, mapping)
*	**Dual CPU**: Atmel, Arduino. Open-source software.
*	**OLED display**: 128×64 high contrast, two OLED display sizes supported
*	**Blue Indicator LED** for every nuclide detected (with cool afterglow)
*	**Red Indicator LED** for “recording” (bGeigie mode) or “alarm” (xGeigie mode) indicators
*	**Orange indicator LED** for charge status
*	**Buzzer** (can be switched off)
*	**Battery status indicator** on OLED display, with low Battery alarm.
*	**2000mAh 3.7V 7.4Wh Lithium Polymer battery** (Li-Po) for about 40-hours nonstop operation in bGeigie mode. mini-USB rechargeable
*	**Memory**: 2Gb micro-SD card  (included)
*	**Parameters configurable** through settings file on micro-SD card (according to Safecast API geo-tagged logging format, customizations, etc)
*	 3.5 mm Apple **audio data communication cable** and jack (sends pulses to Safecast iOS app)
*	 **Realtime clock**
*	**Pelican 1010 micro case**:  Clear plastic, hinged cover and strong latch. Water resistant (not for submerging), crushproof, and dust proof -- when closed. Removable liner (in yellow, black, blue or red). With strap, plastic buckle and carabiner (spring hook) for easy carry or secure mounting on vehicle. (Compact size fits some bicycle cases.) 
*       **Dimensions**: see http://www.pelican.com/cases_detail_specs.php?Case=1010 
*       **Weight** (including battery; without added option in Xbee socket and straps):  ?? gr
*	**Function button** (user assignable)
*	**Wireless option** – BLE-enabled bluetooth, 802.15.4 or Wifi supported through Xbee socket – send data wirelessly to bGeigie Ninja or smartphone. Wireless components not included in this kit. (On wireless and other developments, see the [[Safecast Devices Discussions and Support group|https://groups.google.com/forum/?hl=en#!forum/safecast-devices]], thread entitled [["enticing looking socket on bGeigie Nano"|https://groups.google.com/forum/?hl=en#!topic/safecast-devices/ZUurezK2aaE)]] which began on 2013-06-29.  
*       **Safecast logo** and serial number on top panel
*        **Calibration** (in progress, TBA*): Cesium-137 (gamma from daughter metastable Barium) 
*        **Gamma Sensitivity** 334 CPM per uSv/h (3340 CPM per mR/hr) referenced to Cs-137
*        **Certifications**: (in progress, TBA*) 


Further information at the [[Safecast website|http://blog.safecast.org]]. Also these [[community-edited Nano wiki pages|https://github.com/Safecast/bGeigieNanoKit/wiki/_pages]] (e.g. the kit assembly NANO MANUAL, alias http://nano.safecast.org/). Within the [[github Nano repository|https://github.com/Safecast/bGeigieNanoKit]] see [[README.md|https://github.com/Safecast/bGeigieNanoKit/blob/master/README.md]]. Kit distributor: [[Medcom|http://medcom.com/radiation-monitors/geiger-counters/bgeigie-kit/]]. Contact info@safecast.org.

