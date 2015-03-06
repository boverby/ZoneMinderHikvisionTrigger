# ZoneMinderFoscamHDTrigger
Using Foscam HD inbuilt HW motion detection instead of Zoneminder's SW motion detection

 A trigger script that uses Foscam HD camera inbuilt motion detection
to start ZoneMinder recordings. When motion is detected, it records for 20 seconds
(configurable).

Author: ARC
License: GPL
Version: 0.1
Date: Mar 6 2015

*** Please read the Wiki for setup instructions. ***

The code consists of 3 files:
a) arc_zmtrigger.pl --> a modified version of the default zmtrigger.pl (and a .sh file to restart it when it fails)
b) arc_zm_foscamHDmotion.pl --> the code for detecting motion on foscam HD cameras



