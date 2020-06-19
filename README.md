# ENGR101Project3
Group AVC project for ENGR101 at Victoria University

## AVC Plan 
### Team Name: SUP (Something Unoriginal Probably) Team 21


### Team Members & contact info: 

Amy Broeders – broedeamy@myvuw.ac.nz 

Conrad Draper – draperconr@myvuw.ac.nz

Harrison Taylor – taylorharr3@myvuw.ac.nz 

Joaquin Ramos – ramosjoaq@myvuw.ac.nz 


### Communication tool: 

Gmail, Discord 


### Roles: 

Joaquin Ramos - Project Manager (organising team meetings, reporting regularly on progress)

Harrison Taylor - Software Architect (writing core code and extending functionality) 

Amy Broeders - Software writing, testing and documentation (debugging software and committing to git, writing test cases and documenting performance against milestones) 

Conrad Draper - Software writing, testing and documentation (debugging software and committing to git, writing test cases and documenting performance against milestones) 


Github: [https://github.com/AmyBroeders/ENGR101Project3](https://github.com/AmyBroeders/ENGR101Project3)


## Tasks 
### 4 June:

- [x] All] Complete AVC plan

- [x] Amy and Conrad - Tests all installations. Write test cases for the team 

- [x] Joaquin - Ensures Plan is done. Help to install SFML on all team computers 

- [x] Harrison - Get/save pictures from the robot camera


### 11 June:

- [x] [All] Write code so robot 1 & 2 moves through 

- [x] [All] Intro & Background for report progress report started

- [x] Harrison - In charge of Q1 code

- [x] Harrison - In charge of Q2 code

- [x] Joaquin - Check report, plan meetings for the following week

- [x] Amy and Conrad - Checks code for Q1 & 2 enables robot to complete circuit, debug/fix if necessary


### 19 June:

- [x] Challenge version complete

- [x] Challenge version tested

- [x] Core, Completion, and Challenge compiled into one .cpp file

### 24 June: 

- [ ] Group log complete

- [ ] Individual logs complete


### Important Deadlines:

Harrison (Software Architect):

- 7th June: Core Code finished by midnight 

- 11th June: Completion finished 

- 15th June: Challenge Complete 

Sub-deadlines are the touch ups, things that Amy & Conrad couldn’t fix, those deadlines are recommended. Given 2-3 days spare before the deadline to double check everything or in case we fall behind schedule. (See Updated Project Schedule).


(Notes: Please write clear annotations on your code for Amy & Conrad to easily understand, finishing code for them to test and debug is more important than the touch ups as we have a few days in the end should we need to use it) 


Amy & Conrad (Software writing, testing and documentation):

- 6th June: Testing regime is finished (I’ll help review) 

- 10th June: Core all tested and debugged as much as possible before returning to software architect Harry. 

- 14th June: Completion all tested and debugged as much as possible before returning to software architect Harry. 

- 17th June: Challenge all tested and debugged as much as possible before returning to software architect Harry. 

The Blue above are guidelines for you guys to start and work. (again referencing picture in Updated Project Schedule).


(Notes: Please make sure the testing is thorough and try to debug as much as possible to keep load off Harry as he has a very big load, if there are any problems or non clear requirements for testing speak to me and I’ll contact Arthur for you.) 


My Note(Joaquin): I tried to take into consideration the ecs calendar such as cybr due and tried to spread the deadlines apart to allow time however our schedule is very tight especially for 1 software architect to do most of the code, the earlier we get things done the more room we have for mistakes or last minute touch ups. Sorry for the tight schedule please bear with me and help each other out!!! Even though we are mostly at home team work will be a key factor to our efficiency and final project. If there is anything I missed do not hesitate to contact me. 


## Install Instructions for Team 21 Project 3 Code

These are the install instructions specifically for a 64-bit Windows machine.


### Installing Geany and MinGW

First you need to install the compiler that will allow the computer to be able to understand and run the code. If you already have a C compiler installed, it may not work with this code, so it is best to follow the instructions below.


1.	Open your browser.

2.	Go to https://www.geany.org/.

3.	Click ‘Download Geany 1.36’. If this page doesn’t have a button saying this, go to https://download.geany.org/ instead, and scroll to find ‘geany-1.36_setup.exe’ and ‘geany-1.36_setup.exe.sig’, and click both of these to download them.

4.	Go to https://sourceforge.net/projects/mingw-w64/files/Toolchains%20targetting%20Win64/Personal%20Builds/mingw-builds/7.3.0/threads-posix/seh/x86_64-7.3.0-release-posix-seh-rt_v5-rev0.7z/download.

5.	This website will automatically download the latest version of MinGW as a .7z file. 

6.	Go to the Windows store and download ‘BreeZip: Rar, Zip & 7z Extractor’ (or a 7z extractor equivalent that you trust).

7.	Right-click the .7z file you downloaded in step 4 (it will be in the Downloads folder of your directory) and go to Open With > BreeZip (or equivalent) and click. This will open the application (close any ads that pop up as possible).

8.	Click ‘Extract’ at the top (if you are using BreeZip, otherwise find an equivalent button to extract the files) and specify where you would like it to be extracted to. Just set this to ‘C:\\MinGW’ (put it in its own folder called MinGW in the C: drive).

9.	Go inside the ‘MinGW’ folder (or if you didn’t rename it it will be called ‘x86_64-7.3’) and go into the ‘mingw64’ folder. Here, select all the contents, right-click and select ‘Cut’. 

10.	Return to the main ‘MinGW’ folder (if you haven’t renamed it yet, you should), right click and select ‘Paste’. Then delete the now empty ‘mingw64’ folder.

11.	Go to the search bar in Windows (bottom left corner of your screen, the magnifying glass icon), and type ‘path’. Click ‘Edit the system environment variables’. This will bring up a new window. 

12.	Click ‘Environment Variables…’ in the bottom right hand corner of the new window. In the top box, select the ‘Path’ variable and click ‘Edit…”.

13.	In this new window, select ‘New’, and paste in the path to your MinGW bin folder, which  should be ‘C:\MinGW\bin’ if you’ve been following along correctly.


### Installing the SFML Library

Next, you need to download the library that our code works with. This means that the compiler will recognise new commands (from this library) that it doesn’t currently have installed.


1.	Go to https://www.sfml-dev.org/download/sfml/2.5.1/.

2.	Download ‘GCC 7.3.0 MinGW (SEH) – 64-bit’ from this website.

3.	Once it has finished downloading, unzip the file by right-clicking on it in the ‘Downloads’ folder of your file system and clicking ‘Extract All’. This will bring up a window asking you where to extract the files to. Put it into a new folder. This is where we will also put the code.

4.	Go inside the ‘SFML-2.5.1’ folder and select all of the contents.

5.	Right-click and select cut.

6.	Go into the main ‘SFML’ folder, right-click and select ‘Paste’.

7.	Delete the ‘SFML-2.5.1’ folder (it should be empty now). Do this by right-clicking on it and selecting 


### Downloading the Files

Now that you have the compiler set up, you need to have the files to open in it.


1.	Download the AVC_robot.zip and AVC_server.zip files from the Team 21 GitHub repository (https://github.com/AmyBroeders/ENGR101Project3).

2.	Right click AVC_robot.zip in your Downloads folder and select Extract All, and extract it to the folder where you put the SFML library. Repeat for the AVC_server.zip file.


### Setting up the makefile Files

Next we need to get the computer to understand where to find the files it needs to make the project.


1.	Go into the AVC_robot folder and right-click the file called makefile. Select ‘Open with Geany’. 

2.	Go into your file explorer and find the ‘include’ folder within the SFML folder. 

3.	Right-click it and select ‘Properties’.

4.	Click and drag over the entire Location and press Ctrl + C to copy it.

5.	Where it says ‘C:\\SFML\include’ on the makefile in Geany, replace it with the location you just copied (select it and press Ctrl + V).

6.	Go into your file explorer again and find the ‘lib’ folder within the SFML folder.

7.	Right-click it and select ‘Properties’.

8.	Click and drag over the entire Location and press Ctrl + C to copy it.

9.	Where it says ‘C:\\SFML\lib’ on the makefile in Geany, replace it with the copied location (select and press Ctrl + V).

10.	Close the makefile.

11.	Go into the AVC_server folder and find the makefile for that folder. Select ‘Open with Geany’.

12.	Replace the path ‘C:\\SFML’ with the location again, taking off the ‘\include’ on the end entirely.


### Compiling/Building

Here we specify how the computer should translate the code into stuff it can understand and run.


1.	Right click on the robot.cpp file in the AVC_robot folder and select ‘Open with Geany’.

2.	Click the arrow next to the build button in the menu at the top.

3.	Select ‘Set Build Commands’ from the drop down list.

4.	Under ‘Independent commands’ in the ‘Command’ column and the ‘Make’ row, write ‘mingw32-make’.

5.	Again under ‘Independent commands’ in the ‘Command’ column and the ‘Make Object’ row this time, write ‘mingw32-make %e.o’.

6.	Click ‘OK’ in the bottom right corner of the window.

7.	Click the arrow next to the build button.

8.	Select ‘Make All’ from the drop down list.

9.	The compiler should say ‘Compilation finished successfully.’ At the bottom of the Geany window.

10.	Right click on the server3.cpp file in the ‘AVC_server’ folder and select ‘Open with Geany’.

11.	Repeat steps 7 and 8 for the server.cpp file.


### Running

Finally, we have to deal with the server and client setup to make the application run with both components (the maze and the robot).


1.	Close Geany and open the directory, going into the ‘AVC_server’ folder.

2.	Double click on the ‘server3.exe’ application (it may just say ‘server3’, but check the file type says Application).

3.	A window should start up with the graphics pane, and a terminal with the bottom line reading ‘Listening…’.

4.	Go into the ‘AVC_robot’ folder.

5.	Double click on the ‘robot.exe’ application (as above, it probably just says robot but check the file type).

6.	Reopen the graphics pane, the program should be running.

7.	To switch between mazes for the robot to run, open the ‘AVC_server’ folder, find the ‘config.txt’ file, and edit the first line of it (in a text editor, or Geany will do) where it says ‘core.txt’ to say either ‘completion.txt’ or ‘challenge.txt’, or revert it to ‘core.txt’ from there as you like. The robot is set to run whichever algorithm you want by asking you in the command line, but it won’t work as well if it is mismatched to the maze, so you should change this to run it properly.
