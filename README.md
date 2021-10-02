# KQ4SCI AGI Egg Port
 
### Three eggs from the AGI version of KQIV ported to the more common SCI version:

### EGGS

WIP - incomplete and expect minor issues

Typing PIRATE at the copy protection prompt displays one of two random images, plays a few bars of drunken sailor and accuses the player of being a pirate before exiting the game. In the AGI version you needed to press ALT-D at the copy protection promt to enter the debugger, then type Pirate.  

During the end game sequence returning to the cell and typing RAP KQ in the center of the room will make Rosella brakedance to some complaints by the developers about 'berta. Notice with this patch the first visit to the cell has SCI graphics, normally during the SCI endgame when opening the door you get the following message: 

<code>You wouldn't really want to visit your old cell, would you?</code>

This patch allows you to OPEN DOOR from the hallway and enter an AGI version of the cell with slightly differnt text messages. It copies Rosella's brakedancing animations cel for cel from the AGI CGA graphics. Though, don't expect 100% accuracy here. 

Beam me - coming soon

Special thanks to Kawa for the font & sq1window fix, and to the extremely knoledgeable sciprogramming.com community. Developed using SCICompanion.com and other tools. 

## INSTALLATION

Copy all of the patch files into your KQ4 game folder and start under DOSBox or SCUMMVM. This file and the SRC folder are not required. Removed the files from your game folder to uninstall.

### EGG PATCH FILES

Required for Pirate - font.605, sound.599, script.701, script.702, sound.599, view.582, vocab.000

Required for Rap - font.605, pic.703, script.703, script.086, view.703, view.705, vocab.000

Requred for Beam me - coming soon

