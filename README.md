# Cycles Mineways #

--------

### Version 1.2.3, 4/11/16 ###

### Copyright © 2016 ###

**Supports Minecraft 1.9.2 and Mineways 4.16**

Please send suggestions or report bugs at https://github.com/JMY1000/CyclesMineways/.

--------

## License ##

This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation under version 3 of the License. This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details at http://www.gnu.org/licenses/gpl-3.0.en.html


Distributed with Mineways, http://mineways.com

--------

## How to Use ##

First, you must edit this script a tiny bit. You need to change the PREFIX value listed in the CONSTANTS section. Change PREFIX="" to whatever your save file name is. For example, if it's castle.obj, then do this: PREFIX="castle". Optionally, you can change the other constants as described by the comments to modify the scene. Note that clouds and animation are not supported yet, and that the sky shader currently only handles day and night


To use the script within Blender, for use with the Cycles renderer:

To the right of the "Help" menu in the upper left, click on the "keys" icon next to the word
Default" and pick "Scripting". Optionally, you can simply change any window to the text editor.

At the bottom of the gray window you'll see a menu "Text"; click it and select "Open Text
Block". Go to the directory where this file "CyclesMineways.py" is and select it. You should now
see some text in the gray window. Optionally, you can also paste in the text.

To apply this script, click on the "Run Script" button at the bottom right of the text window.

To see that the script did something, from the upper left select "Window" and "Toggle System Console".
If you are running OS X, you will need to follow a different set of instructions to do this.
Find you application, right click it, hit "Show Package Contents".
Navigate to Contents/MacOS/blender.
Launch blender this way; this will show the terminal.
It isn't critical to see this window, but gives you a warm and fuzzy feeling that the script has worked. It also helps provide debug info if something goes wrong.
