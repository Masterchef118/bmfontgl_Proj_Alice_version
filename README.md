# bmfontgl_Proj_Alice_version
Modification of bmfontgl to prepare it for integration into Project Alice. See Project Alice here: https://github.com/schombert/Project-Alice

This program can read bitmap font files (.fnt and .tga only), generate a font from them, and render given text in that font.
The program looks in a certain directory given in the code for the files it needs. The file names the program looks for
are also given in the code. This directory must be a real location and must contain the named .fnt and .tga files for the 
program to not crash.

To enter your desired directory and file names, go to line 125 of window.cpp.

The only user-provided requirements (at the moment) are boost and the boost filesystem-vc143.

This project has been forked and modified from the original at: https://github.com/dharani811/bmfontgl
