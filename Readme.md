# About DLLPluginLoader
This is a very simple .dll that'll load various other dll's.
This can be used if an application/game tries to load a certain DLL which is not actually being used/required.

# Installation

1. Download the precompiled "ddraw.dll" and place where the application/game tries to load the non-available dll from and, if necessary, rename it to the filename the application/game tries to load.
    Example for Borderlands 2:
    The game tries to load "ddraw.dll" so this dll is placed into "C:\Steam\steamapps\common\Borderlands 2\Binaries\Win32".

2. Create a new folder called "Plugins", in the same folder where you placed this dll in.

3. Place any Plugin-Dll in that "Plugins"-folder.

 
# Support
If you enjoy my work and would like to support me, feel free to do so here :)

[![Donate](https://img.shields.io/badge/Donate-PayPal-green.svg)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=CRVHLK9MURS9Q)
