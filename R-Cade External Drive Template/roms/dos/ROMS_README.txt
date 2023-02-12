## SYSTEM DOS (X86) ##
- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - 
ROM files extensions accepted: .pc .dos .bat .img

There are a few different ways to load DOSBOX machines. R-Cade will try and figure out which you are doing automatically.

NOTE: Windows 95 and up will only work on Dosbox-X (at the time of this writing).

The libretro-dosbox-pure core works differently than the stand-alone cores. It will start to a screen that can be controlled by a gamepad that lets you select an image to mount or a file to run. It is also capable of loading ZIP files as the root filesystem without extracting it first.


All other cores are stand-alone (non-libretro) cores. There's multiple supported ways to setup your games/dos machines.

- Method 1 (Most common and recommended) -
Create and populate a folder that will be treated as C:\ when the emulator starts. This folder should be named with either a .PC or .DOS extension (example folder name: windows31.pc). 
Inside that folder create either a dosbox.bat or an autoexec.bat file to be executed when the system starts. BAT files are dos scripts and can also include dosbox specific commands to mount folders and images.
You can optionally create a custom config file in this folder for the game with the same name as the emulator. This is not required and if the config file does not exist in the game's folder then the global config file for the core will be used. For example: the config file for the dosbox-staging core should be named "dosbox-staging.conf"

- Method 2 -
Launch a .BAT file directly and it will run when the emulator starts. BAT files are dos scripts and can also include dosbox specific commands to mount folders and images.
The folder where the BAT file is run from will be treated as the C drive.
You can optionally create a custom config file in the same folder as the BAT file to be run. This config file should be named the same as the BAT file. For example, if you are launching "MYGAME.BAT" then the config file would be named "MYGAME.conf". If this config isn't found then RCade will also search for a config in the same folder named after the emulator (same as method 1).

- Method 3 -
Launch an .IMG file directly and it will be mounted as drive C and attempt to boot from that image.
You can optionally create a custom config file in the same folder as the IMG file to be run. This config file should be named the same as the IMG file. For example, if you are launching "MYGAME.IMG" then the config file would be named "MYGAME.conf". If this config isn't found then RCade will also search for a config in the same folder named after the emulator (same as method 1).
