# Papirus-Engine
Latest Version 0.2.4

----------------------------
Disclaimer: This project takes heavy inspiration, and code from learnopengl.com
            This is a passion project to make a complete openGL ready engine from scratch that facilitates and allows for devs that work in this framework to start                 with everything ready.
            
----------------------------
Instalation:

Chooe one: 
Method 1 (With the latest version)
Method 2 (With any version you want)
Method 3 (With any version you want, but you copy the repo (easyest))

Method 1: 
1. Go to branches
2. Select Latest and download .zip
3. extract it to wherever you want, the libraries are all included.
4. Set up VS C++. Theres a section dedicated to that, a bit lower :)

Method 2:
1. Go to branches
2. Select the version that you want to download.
3. Downlaod and extract it to wherever you want, the libraries are all included.
4. Set up VS C++. Theres a section dedicated to that, a bit lower :)

Method 3:
1. Go to branches
2. Select the version that you want to download.
3. Copy the repository's url. should be under code, and looks like an url...
4. GO to VS C++
5. Click on clone a repository from gitHub.
6. Paste the link in the first rectangle...
7. Select an install location.
8. Click clone.
9. After it finishes it should work. If it doesn't follow instructions under "Set up VS C++"

-----------------------------------
Set Up VS C++
1. Drag and drop "Papirus Engine.sln" into the first window of VS C++
2. After it finnishes loading, click on Papirus engine at the top.
3. Click on the wrench right above, or go to Project > Properties.
4. clock on VC C++ Directories and make sure that the include and library directories are set up properly.
5. If they aren't:

            i. First double-click on the arrow down on the "include Directories" row.
            ii. Click on edit.
            iii. make sure that the first file path is : ..\Papirus Engine\Libraries\include
            iv. make sure that the second file path is : ..\Papirus Engine\Papirus\Header Files
            
            v.Click ok and go to the same location in "library directories"
            vi. make sure that the first file path is : ..\Papirus Engine\Libraries\lib
            
            You are allmost done!
            
            vii. Click on the drop down of the linker tab.
            viii. Click on input.
            ix. edit the additional dependencies
            x. write at the top (space matters): 
            
            glfw3.lib
            opengl32.lib
            assimp.lib
6. For now this is all you have to do. In the future, if anyhing dowsn't work refrence this part as it causes the most ammount of problems.
7. make sure that at the top the version is x64. It is a requirement.
8. Click on "Locak Windows Debugger" to run the program.
9. You can edit any part of the code. Main.cpp is the main loop where all the rendering is happening.
10. resource files is where the models, shaders, and textures are in, at least for now.
11. header files are a package of libraries. you can add your own. if you have an older version of papirus, you will have to place them in a folder manually and edit all the code refrences manually.
---------------------------------------------

Have un with the engine. if it doesn't work for you, make sure to ask me directly in the comments. i try to ansewr any questions that you have. nothe that i am not the best programmer in the medium.

----------------------------------------------

Roadmap:

better lighting
Better graphics calculation
physycs and collisions
instancing

verry VERRY late:
PBR

to be tested:
CBR (Camera based rendering. you can find more about it on my blog on blogspot, if it even exists at this time. YOUR time.)
