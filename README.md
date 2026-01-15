# graphic-_lab_opengl
To install OpenGL (FreeGLUT) on your system, follow these step-by-step instructions based on your operating system.
For Windows :

Download VS Code (https://code.visualstudio.com/download)

Download MSYS2 (https://www.msys2.org/)

Generate and Download Glad (https://glad.dav1d.de/) with the latest version(4.6)

Install VS Code

Install MSYS2

Put Glad on MSYS2

Edit Environment Variables for MSYS2

System Variable:

Variable Name : MSYS2
Variable Value : C:\msys64
Go to Path > Edit > New > C:\msys64\mingw64\bin

Configure VS Code

Install Extension(C++)
Install Extension Run++
Code Runner
Add IncludePath
MSYS2 MINGW command:

$ pacman -Syu

$ pacman -S mingw-w64-ucrt-x86_64-gcc

$ gcc --version

$ pacman -S mingw-w64-x86_64-glew

$ pacman -S mingw-w64-x86_64-glfw

$ pacman -S mingw-w64-x86_64-freeglut

$ pacman -S mingw-w64-x86_64-toolchain

Go to settings in Vs Code > write includepath >

${env:MSYS2}/mingw64/include/ > add item
Download code Zip from my repository
here is the drive link 
https://drive.google.com/drive/folders/1Ifam1ftJ9OtvxzzYPrH4-DMuz2PteHuN?usp=drive_link
