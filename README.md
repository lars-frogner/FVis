# FVis
This Python module is intended as an aid for the participants of AST3310 at the University of Oslo.

It provides an easy way of dealing with a less educational, but rather time consuming aspect of writing a fluid simulation; 
the saving and visualisation of calculated data.

#### Here is what the module can do for you:
* Run your simulation for a given amount of time and save the resulting data to binary files.
* Read data previously saved by the module.
* Add more simulation data to existing files.
* Show a 1D or 2D animation of a quantity that can be derived from the stored data.
* Save the animation as an mp4 file.
* Plot the time evolution of the average value of a quantity (useful for checking if something is conserved).

All these actions can be done with just a few function calls in your main program.

#### Installation
Download [FVis3.py](/src/FVis3.py) (if you are using Python 3.x) or [FVis2.py](/src/FVis2.py) (if you are using Python 2.x) to your working directory and you are good to go. (In the linked page, click 'Raw' and then right-click => Save as..)

#### Usage
Check out the [User guide](/User-guide/FVis_user_guide.pdf) for instructions on how to use the module.

#### Screenshots
**1D shock tube test:**

![shock tube](/Screenshots/shock_tube.png?raw=true "Shock tube")

**Sound waves in a uniform medium:**

![sound waves](/Screenshots/sound_waves.png?raw=true "Sound waves in a uniform medium")

**Solar convection cell:**

![convection](/Screenshots/convection.png?raw=true "Solar convection")
