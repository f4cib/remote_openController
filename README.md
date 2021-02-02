# Firmware for openController hardware from http://www.remoteQTH.com
This is the openControl for the remoteQth.com 
If you need help, feel free to contact DM5XX@gmx.de
Sketch is developed with IDE Version 1.6.4 and later

This is free software. You can redistribute it and/or modify it under the terms of Creative Commons Attribution 3.0 United States License if at least the version information says credits to remoteQTH.com :P

To view a copy of this license, visit http://creativecommons.org/licenses/by/3.0/us/ 
or send a letter to Creative Commons, 171 Second Street, Suite 300, San Francisco, California, 94105, USA.

Tribute to OL7M!
LLAP!

February 2021 ; F4CIB mycallsign@r-e-f.org
In my tentative to design a remote antenna switch controller for F6KNB station, i think Mike code is probably the closest to what i expect:
Default case: i use an antenna on the main antenna matrix, (let's call it Tx Ant labeled 1) everything is handled by existing hardware and Band decoder.
When I want to transmit on another antenna than the one on the matrix (let's call it On demand antenna) then I select Tx set, then 2, 3 or 4 and again Tx set.
On Rx, i want to be able to ear on either Tx Ant, On demand antenna 2, 3, 4 or beverages.
If beverages are selected i have an additionnal choice other the 6 directions.
Up to now, i can do it by myself, and i'll share my progress, but at anytime i can request help, i will shout loud just like when i'm working a DX :) 
Done: html ; css & javascript
TBD: javascript test on cm.js and Arduino code to hnndle these additional features 
