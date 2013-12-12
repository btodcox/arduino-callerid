arduino-callerid
================

Arduino-based YAC/NCID Caller ID Display.

Combining an ethernet Arduino (or a Uno R3 + ethernet shield) with an 
Adafruit LCD Shield Kit that has a 16x2 Character LCD provides a solid hardware
platform for a network based Caller ID display.  This code turns this hardware
combination into a YAC listener (Yet Another CallerID Program http://sunflowerhead.com/software/yac).

This project requires that you have a YAC Server or NCID Server (ncid.sourceforge.com) 
on your local network to monitor your phone line.  When the phone rings and Caller ID 
information is present, the YAC or NCID server captures the information and forwards
it over your network to display devices such as this project.
