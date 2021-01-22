# RTX-Tweak-1.9
This is my attempt at integrating DLSS2.0 into RTX 2000 and 3000 cards the same way it's done in the 3090ti.

I won't be sharing the source code on here until I feel like I need to. This repo will host executables for now.

How it works:
 - DLSS2.0 is implemented into 3090ti drivers differently than all the other RTX cards, dont ask me why, ask nVidia...
 - This tweak spoofs a part of your GPU driver as a 3090ti and recompiles DLSS2.0
 - Some games will require you to run them in DX12
 
Installation:
 - Download
 - Unzip
 - Run as Admin
 
Known Issues:
 - Windows Defender sometimes doesn't like the spoofer and 
 - Sometimes the .exe doesn't launch until you reboot after installing your GPU driver.
