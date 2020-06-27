# Pump sensor recreation
I had a PIU sensor on hand one day, and decided to try and model one up as a velostat sensor. "Sensor Finished v1" is as close to a 1:1 replica of a PIU sensor as I was able to achieve. From there, I cut it up into pieces to make into a vstat sensor.

As far as vstat sensors, I generally wouldn't recommend this one for most uses. It's not overly consistent, and its length makes it a bit tricky to get a good read most of the time. Plus, The current design doesn't accomidate for any clip or similar to retain the top half, thus I've had sensors fail more than once due to the tape I was using to retain the top weakening and having the top slide out of place. 

Theoretically, these could be used to convert a PIU pad to velostat, should someone decide to make them 1. work a bit better and 2. design a board that'd be able to handle analog reads of 20 sensors at a time and report it to a PIU-IO as if it were an original pad. SMX pads can do it, perhaps it's possible!


Arguably the most important model here is "sensor rubber". It's a similarly "close to 1:1 as I could get" model that, if printed in a flexible filament, is a drop in replacement for sensor holders on DDR/PIU pads. If your sensor rubbers are hard or broken, and you have a 3D printer and a spool of SainSmart TPU, give them a shot! I've been running them in my pads for a long time now, they work extremely well.
