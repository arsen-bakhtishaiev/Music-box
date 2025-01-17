# Music-box
Simple DY-SV5W board-based music box.

3xAAA batteries are used to power the circuit, the voltage is converted to 5V using a boost converter. 

You would need 8xM4 brass inserts and 8xM4 10mm screws to assemble the box.

The case was designed in Freecad, you would need to export the files into 3MF files and print them. Clean 3MF files without printer settings could be added later.
I've printed it with PETG, 15% infill, it was enough to withstand a very curious 2-year-old. Tree supports are used to ensure holes on the side are printed properly.
Any battery case that can hold 3xAAA batteries would work, although I've designed and printed a holder myself to keep the costs down(which, in the end, was not the best idea).
All the boards are hot-glued to the bottom, this worked out to be much more reliable than screws.
The hole on the side is for the 32x22 mm switch that turns the damn thing off, the holes on top are for momentary switches with 28mm outer diameter.

DY-SV5W should be switched to I/O Independent Mode 0, this means configuration pin 2 should be switched to position 1.
The board will play mp3. and .wav files with a bitrate up to 48kbit/s, however in my experience it can play files with a higher bitrate, but this requires research.
Files should be have names in 0000x.(mp3|wav) format. Decreasing the voltage level of IO0-7 to low would trigger playback of corresponding file.


Created by an amateur clown.
Note that I have no idea what I am doing.
