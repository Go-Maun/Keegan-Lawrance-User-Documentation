---
layout: default
title: Setting Up CLion
nav_order: 12
---

# Setting Up CLion
{: .no_toc }

CLion is the IDE that Cygwin will be using to compile the C language. We are using CLion due to the amount of useful features for the time limit that it is available for free to the user.

<hr>

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## Downloading the Setup .exe file

1. Go to the CLion website<br/>  
  Redirect to the [JetBrains CLion homepage by clicking here](https://www.jetbrains.com/clion/). Click on the ``Download`` button displayed on the top right to go to the download page.<br/>  
  ![CLion HomePage](https://cdn.discordapp.com/attachments/498622698050813962/695025139766525952/unknown.png "HomePage")
<br/>


2. Download the Setup<br/>  
  Click on the ``Download`` button on the middle of the screen.<br/>  
  On the right side of that button, you have an option to download a _.exe_ or a _.zip_ file. For the sake of simplicity and these instructions, you will be using the _.exe_ to install CLion.<br/>  
  ![CLion DownloadPage](https://cdn.discordapp.com/attachments/498622698050813962/695026972195028992/unknown.png "DownloadPage")
<br/>


3. Open the Setup<br/>  
  After clicking on the download button, you will be redirected to the page displayed below, and you will start downloading the CLion setup.<br/>  
  <img src="https://cdn.discordapp.com/attachments/498622698050813962/696144246062841937/download.png" alt="note" width="50"/>**NOTE:** This was downloaded in a Google Chrome browser. If your browser is different, the file may appear in a different location.<br/>  
  When the setup is done, run the program by clicking on the downloaded file.<br/>  
  ![CLion RunningDotExe](https://cdn.discordapp.com/attachments/498622698050813962/695028299470209064/unknown.png ".exe")
<br/>


## Running the Setup file

1. Starting the Setup<br/>  
  The window below will show up when you open the setup file. Click ``Next >``<br/>  
  ![CLion FirstPage](https://cdn.discordapp.com/attachments/694977588405469265/694991483794751650/unknown.png "First Page")
<br/>


2. Choosing Install Location<br/>   
  The next window displays the location of where CLion will be downloaded on your computer. If you would like to change the destination of where it will download the files, click on the ``Browse`` button to locate the folder you wish to have it saved to. Otherwise, it is fine to leave it as default.<br/>  
  Click ``Next >``<br/>  
  ![CLion SecondPage](https://cdn.discordapp.com/attachments/694977588405469265/694991527985938542/unknown.png "Second Page")
<br/>


3. Choosing Installation Options<br/>  
  The next window will display a number of boxes to be checked. The boxes to be checked are:  
  - [x] 64-bit launcher _(32-bit, depending on downloaded version)_  
  - [x] Add launchers dir to the PATH  
  - [x] Add "Open Folder as Project"  
  - [x] .c  
  - [x] .h  
  After you have checked these boxes, click ``Next >``<br/>  
  
  ![CLion ThirdPage](https://cdn.discordapp.com/attachments/694977588405469265/694991864788418600/unknown.png "Third Page")
<br/>


4. Choosing Start Menu Location<br/>  
  This next window allows you to choose a start menu folder for the program's shortcuts. If you would like, you can change the folder location. Click ``Next >``<br/>  
  ![CLion ForthPage](https://cdn.discordapp.com/attachments/498622698050813962/695551842888712201/unknown.png "Forth Page")
<br/>


5. Finishing the Installation<br/>  
  You will need to restart your computer to finish the installation of CLion.<br/>  
  <img src="https://cdn.discordapp.com/attachments/498622698050813962/696144248512446525/warning.png" alt="warning" width="50"/>**WARNING:** Clicking finish will forcibly restart your computer.<br/>  
  If you do not wish to restart your computer yet, click the ``I want to manually reboot later`` option before clicking finish.<br/>  
  ![CLion FifthPage](https://cdn.discordapp.com/attachments/694977588405469265/694992190035722300/unknown.png "Fifth Page")
<br/>


## Run CLion For The First Time

1. Open the CLion program<br/>  
  You should have the CLion shortcut on your desktop after restarting your computer. Open it and you will see this initial page.<br/>  
  As a new user, you will not have any settings to import, so click the ``Do not import settings`` option and click ``OK``<br/>  
  ![IDE FirstPage](https://cdn.discordapp.com/attachments/694977588405469265/694992613002051614/unknown.png "IDE First Page")
<br/>


2. Set up your customization<br/>  
  This window will pop-up afterwards. This is for your personal customization. If you want a dark-themed IDE, choose ``Darcula``. If you want a light-themed IDE, choose ``Light``.<br/>  
  Afterwards, click on the ``Skip Remaining and Set Defaults`` button on the bottom left side of the window.<br/>
  ![IDE SecondPage](https://camo.githubusercontent.com/a78232fd2a715e4a36374aeba9d51b1b291b7137/68747470733a2f2f63646e2e646973636f72646170702e636f6d2f6174746163686d656e74732f3439383632323639383035303831333936322f3639353035343736303839333631323038332f756e6b6e6f776e2e706e67 "IDE Second Page")
<br/>


3. Activate Your Free Trial Account pt.1<br/>  
  To activate your free trial account, click on the ``Evaluate for free`` button on the top of the window.<br/>  
  ![IDE 22Page](https://cdn.discordapp.com/attachments/498622698050813962/695056162843918336/unknown.png "IDE 22")
<br/>


4. Activate Your Free Trial Account pt.2<br/>  
  Check mark the two boxes displayed on the window and enter your email address.<br/>  
  The ``Evaluate`` button should then highlight and indicate you to click it. After clicking the button, click ``Continue``<br/>  
  ![IDE ThirdPage](https://cdn.discordapp.com/attachments/498622698050813962/695031517067346071/unknown.png "IDE Third Page")
<br/>


5. Sign Into Your JetBrains Account<br/>  
  You should be redirected to this window. Enter in your email and password to sign in.<br/>  
  Once you have entered in your information, click ``Continue`` on the bottom right of the window.<br/>  
  ![IDE SixthPage](https://cdn.discordapp.com/attachments/498622698050813962/695030756728242276/unknown.png "IDE Fourth Page")
<br/>


6. Import Cygwin Into The IDE<br/>  
  CLion should automatically detect your Cygwin and connect to it.<br/>  
  You can tell that you have Cygwin connected if the Debugger section shows _Cygwin GDB_.<br/>  
  If it does not, click the triple dot ``...`` button on the right side of the Debugger section and navigate to the folder where you installed *gdb.exe*. The address to that *.exe* should be exactly as displayed on the image below.<br/>  
  Click on ``Start using CLion`` on the bottom right on the window.<br/>  
  ![IDE 5thPage](https://cdn.discordapp.com/attachments/498622698050813962/695049719889657896/unknown.png "IDE 5th page")
<br/>


7. Welcome to CLion!<br/>  
  After you finish setting up your CLion, you should see this window.<br/>  
  You now have access to CLion and it's features!<br/>  
  ![IDE 6thPage](https://cdn.discordapp.com/attachments/694977588405469265/694995496720269363/unknown.png "IDE 6th page")
<br/>


## Creating Your First C Program!
You have succesfully set up your CLion IDE!

This part of the section will show you how to compile and run the default "Hello, World!" file.

1. Create Your First Program<br/>  
  Click on the ``New Project`` button on the front page, and this window will pop up.<br/>  
  Navigate to the ``C Executable`` section on the left side of the window and change language standard to ``C99``.<br/>  
  Click on the ``Create`` button on the bottom right.<br/>  
  ![HelloWorld](https://cdn.discordapp.com/attachments/498622698050813962/695050703609135114/unknown.png "helloworld 1")
<br/>


2. Tip of the Day<br/>  
  This is what you will see after creating your file C file. <br/>  
  A "Tip of the Day" will show up. If you wish to read about what the IDE has to offer, feel free to read through all of the tips. Otherwise, click ``Close``.<br/>  
  ![HelloWorld2](https://cdn.discordapp.com/attachments/498622698050813962/695051257370509312/unknown.png "helloworld 2")
<br/>


3. Compiling Code<br/>  
  Click on the <img src="https://cdn.discordapp.com/attachments/498622698050813962/695559765367193660/unknown.png" alt="playIcon" width="20"/> icon on the top right of the IDE.<br/>  
  ![HelloWorld3](https://cdn.discordapp.com/attachments/498622698050813962/695052272958439435/unknown.png "helloworld 3")
<br/>


4. Execute and Run the Code <br/>  
  A box should show up on the bottom of the IDE. If it shows: "Hello, World!", then your program works!<br/>  
  ![HelloWorld4](https://cdn.discordapp.com/attachments/498622698050813962/695052779940478986/unknown.png "helloworld 4")
