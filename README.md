# RoundSquare
This is a tileset for Freeciv designed to have clean un-cluttered graphics. 
30x30 pixel size, Overhead view.

## History
Playing a Longturn game recently, I found out two important things:

* Viewing a map this large requires a 30x30 tileset.
* Trident makes my eyes bleed 

So I embarked on an epic quest of graphics editing, and lost a weekend or two in the seductive "Save changes, Reload tileset, Make new changes" production loop. Textures were remixed, pixels were tweaked, graphics transplanted, borders modified, layers were reverse-engineered, and countless changes were undone and redone. Everything was done with the purpose: Does this make the screen easier to read?

The result is a modified version of Trident with the rough edges smoothed, and some terrain graphics simplified, to reduce "Visual Clutter".
See if you can spot the difference!

![Preview](preview.png?raw=true)

# Install

## Windows

Download the files from Github and unpack them in the `/Freeciv-2.6-???/data` folder, to make the tileset part of that Freeciv install.
Alternately, locate your `/UserName/AppData/Roaming/.freeciv/2.6` folder, and unzip the files into there to make them available to all Freeciv installs for that user.

## Linux

Same as Windows but the target folder is `/usr/share/freeciv` (or `/usr/games/freeciv`) for a system-wide install, and `~/.freeciv/2.6` to install for one user only.

# License

Just like the originial Freeciv, this tileset is made available under the terms of the GNU General Public License as published by the Free Software Foundation; either version 2, or (at your option) any later version.
