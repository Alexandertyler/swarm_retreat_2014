swarm_retreat_2014
==================

teensy+cc3000+sensors


Hello and welcome to the swarm lab retreat.  In order to get your device up and running please download and install the following programs to your computer:

Arduino version 1.0.5 NOT 1.5.6-r2 BETA.  Version 1.0.5 can be found here:

http://www.arduino.cc/en/Main/Software#toc2

The teensyduino (Along with the serial program for windows or the udev rules for linux can be found here:

https://www.pjrc.com/teensy/td_download.html

Download and install teensyduino according to the instructions found on that page.

Then finally install the CC3000 libraries:

https://github.com/PaulStoffregen/Adafruit_CC3000_Library/archive/master.zip

This library needs to go into your arduino libraries folder.  See here:

http://arduino.cc/en/Guide/Libraries

The wireless section of your code will look like:

    #define WLAN_SSID       "EECS"        // cannot be longer than 32 characters!
    #define WLAN_PASS       ""            //add the password here
    // Security can be WLAN_SEC_UNSEC, WLAN_SEC_WEP, WLAN_SEC_WPA or WLAN_SEC_WPA2
    #define WLAN_SECURITY   WLAN_SEC_WEP

Here is an info page on the Bjoern Key Value Store:

http://husk.eecs.berkeley.edu:8080/help
