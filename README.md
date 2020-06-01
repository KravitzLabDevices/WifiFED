# wifiFED 
This is an archive of an dead project from 2016 where we tried to introduce wifi functionality to FED1 (https://github.com/KravitzLab/FED). It is maintained here for archival purposes but no further work will be done on it.  TLDR: WIFI is not the right solution for FED, it is too power hungry and problems show up when you try to connect a couple dozen devices in close proximity to a single router.  We are exploring LoRaWAN instead, which I believe is the correct solution.

The wifi functionality is currently still under development, but feel free to poke around.  Wifi FED uses a Sparkfun Thing, Adafruit v2 motor board, servo motor, and IR beam detector to log food taken to a phant server on WiFi. FeedThing runs off of a battery that provides ~10 days of use. 

We migrated FED from the Arduino Pro used in our SD-card version (https://github.com/KravitzLab/FED) to the Sparkfun Thing to take advantage of its built-in WIFI functionality and low power consumption.

The hardware directory contains the system schematics. 
The software is in FeedThingSketch.

