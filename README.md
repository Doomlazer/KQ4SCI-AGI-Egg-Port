# KQ4SCI AGI Egg Port
 
## Three Easter eggs from the AGI version of KQIV ported to the more common SCI version:

WIP Feature complete - testing then polish

## EGGS

### PIRATE
Pirate Typing PIRATE at the copy protection displays one of two random images, plays a few bars of drunken sailor, and accuses the player of being a pirate before exiting the game. In the AGI version you needed to press ALT-D at the copy protection to enter the debugger, then type pirate to see the easter egg. Because it's not possible to trigger it in the same way with the SCI debugger, simply type 'pirate' instead of the answer from the manual.  

### RAP KQ
During the end game sequence, return to Lolotte's torture cell and type RAP KQ to see Rosella brakedancing to complaints by the developers about 'berta. 

Notice: When using this patch the first visit to the cell has SCI graphics. Normally, during the SCI endgame, when opening the door you get the following message: 

<code>You wouldn't really want to visit your old cell, would you?</code>

This patch allows you to OPEN DOOR from the hallway and enter an AGI version of the cell with slightly differnt said spec messages from the AGI verison. It copies Rosella's brakedancing animations cel for cel from the CGA graphics. Though, don't expect 100% accuracy here. 

### BEAM ME

From the hallway outside Lolotte's cell type BEAM ME. Rosella is teleported to a room with... you guessed it, devs! The SCI Rosella beam out anmiation is a rough draft and will be updated.

Special thanks to Kawa for the PxPlus CGA font & the sq1window solution, EricOakford for the SCI Decompile Archive, as well as everyone else in the extremely knoledgeable sciprogramming.com community. Developed using SCICompanion.com and other tools. 

## INSTALLATION

Copy all of the patch files into your KQ4 game folder and start under DOSBox or SCUMMVM. This file and the SRC folder are not required. Removed the files from your game folder to uninstall.

### EGG PATCH FILES

Required for Pirate - font.605, sound.599, script.701, script.702, sound.599, view.582, vocab.000

Required for Rap - font.605, pic.703, script.703, script.086, view.703, view.705, vocab.000

Requred for Beam me - font.605, pic.704, script.704, view.581, script.083, vocab.000

