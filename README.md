# bmfontgl_Proj_Alice_version
Modification of bmfontgl to prepare it for integration into Project Alice. See Project Alice here: https://github.com/schombert/Project-Alice

This library (the files 'bmfont.cpp' and 'bmfont.h') can read bitmap font files (.fnt and .tga only) and generate a font from them for a program to then use. The library creates OpenGL textures containing each character. The final rendering of the text in a window is up to the program using the library, and is not done by the library.

There are NO user-provided dependencies. All dependencies are providing in this repository. 'bmfont.cpp' and 'bmfont.h' contain the library. The rest of the files are dependencies.

This project has been forked and modified from the original at: https://github.com/dharani811/bmfontgl
