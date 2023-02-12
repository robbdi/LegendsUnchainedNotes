## SYSTEM DAPHNE ##
- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - 
ROM files extensions accepted: .daphne .singe

Daphne games need to be in their own folder, and that folder should have an extension of .daphne or .singe (depending on the type of game it is).

Within the game folder you should have:
 1) A "roms" folder that contains the needed firmware for the game, usually saved in a zip file.
 2) A ".txt" file that contains the frame info

Singe games should also have a script file with a ".singe" extension.

The name of the folder and files needs to match the game being loaded. For example, the game "Dragons Lair" uses "lair" for the name of the folder ("lair.daphne"), 
the name of the firmware zip ("lair.zip") in the roms folder, and the name of the frame file ("lair.txt"). The ".singe" file should also use this name for singe games.

Here is an example of the full path to the described files and folders for Dragons Lair (not including the game content files):
  /rcade/share/roms/daphne/lair.dapnhe
  /rcade/share/roms/daphne/lair.daphne/roms/lair.zip
  /rcade/share/roms/daphne/lair.daphne/lair.txt

You have the advanced option of creating a ".commands" file in the game folder that will be used to call the game instead, 
allowing you to name the files within the folder anything you want and pass any additional parameters you need. 
This .commands file must have the same name as the game folder. You can use "$DAPHNE_DIR" in the commands file to reference the path to the game being loaded.
