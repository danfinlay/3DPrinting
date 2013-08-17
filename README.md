# SudoRoom 3D Printing

3D Printing models, projects and more from Oakland's SudoRoom

https://sudoroom.org/wiki/3DPrinting (the instructions on the wiki are currently out of date)

![SudoRoom Creating](http://farm9.staticflickr.com/8242/8633341218_353edd10bb_n.jpg)

# How to print!

We have a Type A Machines printer and a Linux desktop running KDE that is attached to it. Anyone can use these to print!

###Extrusion 3D Printing
This printer extrudes 0.2-0.5mm of melted plastic at 185c onto a print while being controlled by a 3-axis cartesian (grid) robot.  The robot is controlled by the computer to extrude cross section after cross section building up into a three-dimensional shape.

### Turn on the printer

The power switch is on the back.

![powerswitch.png](img/powerswitch.png)

Since the e.g. if right-side up pyramids print very well, but upside-down pyramids don't print very well because the 3D printer can't very easily print things floationg in air with no supports.

### Get a 3D model

Try to get your 3D model as an `.stl` format.

A good place to find 3D models is http://www.thingiverse.com/.

### Slice your model

Open up the program called KISS Slicer and load your STL file into it. This program takes the model and 'slices' it up into a path for the printer head to take. It saves a file in the `.gcode` format.

![kissslicer.png](img/kissslicer.png)

### Print your gcode

Open up the program called Pronterface, connect to the printer and then load your `.gcode` file.

![pronterface.png](img/pronterface.png)

Some things to be aware of:

- You can pause the print from Pronterface and then use the Z control to get the height of the print head correct. This is the most important thing to do! If it looks like the print head is smashing down too hard on the print surface your print will be lower quality, but it also will be lower quality if it is too high off of the print surface.

![printbed.png](img/printbed.png)

- Keep an eye on the temperature. If something gets clogged or stuck the print head could overheat and the printer could get damanged, but if you keep an eye on it you can stop the print from Pronterface before the head has time to overheat.

- Make sure the plastic spools don't get stuck and pop out of the print head. Keep the pipes a flowin!

![spool.png](img/spool.png)

Have fun!
