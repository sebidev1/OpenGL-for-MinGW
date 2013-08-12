OpenGL MinGW for Windows

Install
 
Download the zipfile or Checkout the source and install it.
Go into the folders and fetch the ".h" and ".a" files out.
 
include ->  C:\MinGW\include\GL\
lib ->  C:\MinGW\lib\

Compiling without GLEW32
g++ test.cpp -o test -lglu32 -lopengl32 -lfreeglut
gcc test.c -o test -lglu32 -lopengl32 -lfreeglut

Comiling with GLEW32
g++ testgl3.cpp -o testgl3 -lopengl32 -lglu32 -lglew32 -lfreeglut
gcc testgl3.c -o testgl3 -lopengl32 -lglu32 -lglew32 -lfreeglut