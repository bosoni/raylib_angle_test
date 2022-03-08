# raylib_angle_test
raylib + ANGLE test (32bit only)

raylib: https://github.com/raysan5/raylib


open ./VS2019.ANGLE/raylib.sln and run. 

It uses ./projects/VS2019.ANGLE/lib/x86/libGLESv2.lib  and ./projects/VS2019.ANGLE/lib/x86//libEGL.lib, 
and starts with Direct3D11 (using libGLESv2.dll, libEGL.dll and d3dcompiler_47.dll, 
those are already in 
./projects/VS2019.ANGLE/examples/core_basic_window/Debug/ directory, with compiled .exe).

![Screenshot (167)](https://user-images.githubusercontent.com/2569545/155713998-0d388a04-69a9-43e6-95cd-0316a5a0604a.png)


NOTE: noticed that if there are spaces in directory (ie   ./PROGAMMING/raylib_angle (copy)/   then compilation failed (happened VS2022). So dont use spaces in directories' names (which is good advice always, spaces can be replaced with _ and windows/linux softwares cant complain)
