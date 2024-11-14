![dosbox-logo_banner](https://github.com/user-attachments/assets/d0c8332a-0377-4579-9ece-2c6c6f192b61)

# DOSXBox360 Browser
DOSXBox360 Browser by begal is an application to aid in using the Xbox360 port of DOSBox

https://github.com/mLoaDs/DOSXBox360

Anybody that has ever used DOSBox on their Jtag/RGH/XDK know that its kind of a pain to copy each .config file 
every time you want to launch a game (if you want it to auto execute that is) ,, this app solves the issue

Features:
---------
-Lists all game folders in the "DOS" directory

-On launch, the selected games .config file is copied to app root for proper auto execution.

-App auto selects "regular" or "dev" version based on the kernel running on the x360 (only dif is devkits have mouse support, see readme.nfo)
  
Usage:
------
-Add your game folders to the "DosBox 360 BrowserV0.01\DOSXBox360\DOS" directory, ensure your folder includes an edited .config file for proper auto execution 

*NOTE: Game folders must be 8 characters﻿ or less, otherwise you will get errors when loading game!!!﻿

Here is a .config example,,edit your games folder name and .exe name﻿ 

Lines in this section will be run at startup.

[autoexec]

@ECHO OFF

MOUNT C GAME:\DOS -freesize 500

C:

cls
 
cd C:\DOOM

cls

DOOM.exe

From now on you can launch the game from the browser without having to copy or edit any more files, or type any boot commands in dosbox! 

Seeing that I cannot include any game content as examples, if you have any issues getting your games .config files setup, or any other issues please feel free to ask
