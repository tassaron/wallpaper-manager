Wallpaper Manager
==============
*made by tassaron 2017-03-18*
![Screenshot](/screenshot.png?raw=true)

A super-simple GTK+ 3 app to set the wallpaper on your desktop if you are not using a desktop manager.

Requires hsetroot for setting the wallpaper, and ImageMagick for resizing/cropping images.

- Also provides a simple interface to start/stop/configure my wallpaper shuffler called "rnd-bg"
- If you want to use this you must edit the constants at the top of each file
- The wallpaper shuffler resizes and crops images in a nice way, so you can throw a bunch of randomly-sized images into a folder and not worry about making them look good together.
- The resolution can be changed by calling rnd-bg with the option **-res WIDTHxHEIGHT**, but if you set the constant in the script then no option is required for your custom resolution
- Eventually I will make it so you don't have to edit constants
