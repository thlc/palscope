PalScope -- PAL to X-Y-Z Oscilloscope Raster
============================================

About
-----

PalScope is a KiCad version of the very nice schematic made by
![W2AEW](https://www.qsl.net/w2aew/), which converts a PAL signal into 
a 3-channel X-Y-Z raster that oscilloscopes can use to display a raster image.

Components
----------

The board is based around an LM1881 IC that extracts vertical and horizontal
sync pulses from the PAL signal. Those pulses are used to drive capacitors
that produce a 0-9V signal for the X and Y channels.

The Z channel is used to dim parts of the screen using an inverting opamp.
While W2AEW used an AD8032, I had to use an AD844 because I couldn't find
the 8032. This opamp isn't the best, especially since it's current-based.
If you can get hold of a 8032, go this way!

Pictures
--------

Schematic:

![The Schematic](https://github.com/thlc/palscope/blob/master/misc/schematic.png?raw=true)


3-D rendering of the board:

![3-D Rendering](https://github.com/thlc/palscope/blob/master/misc/board.png?raw=true)

An early working version of the PCB:

![PCB](https://github.com/thlc/palscope/blob/master/misc/builtboard.jpg?raw=true)

My Apple //e running Ultima IV:

![Apple 2 running Ultima IV](https://github.com/thlc/palscope/blob/master/misc/ultima4.jpg?raw=true)


Acknolwedgements
----------------

Thanks to Alan / W2AEW for publishing this design!
Make sure to check out his YouTube channel at https://www.youtube.com/@w2aew
