---
layout: default
title: Setting Up CLion
nav_order: 12
---

# Installing CLion
{: .no_toc }

<hr>

CLion is the IDE that Cygwin will be using to compile the C language. We are using CLion due to the amount of useful features for the time limit that it is available for free to the user.

<hr>

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## Downloading the Setup .exe file


### **1.** Go to the CLion website
{: .no_toc }
Redirect to the [JetBrains CLion homepage by clicking here](https://www.jetbrains.com/clion/).
<br/><br/>
Click on the download button displayed on the top right to go to the download page.

![CLion HomePage](https://cdn.discordapp.com/attachments/498622698050813962/695025139766525952/unknown.png "HomePage")

<br/>

### **2.** Download the Setup
{: .no_toc }
Click on the Download button on the middle of the screen. 
<br/><br/>
On the right side of that button, you have an option to download a .exe or a .zip file. For the sake of simplicity and these instructions, you will be using the .exe to install CLion.

![CLion DownloadPage](https://cdn.discordapp.com/attachments/498622698050813962/695026972195028992/unknown.png "DownloadPage")

<br/>

### **3.** Open the Setup
{: .no_toc }
After clicking on the download button, you will be redirected to the page displayed below, and you will start downloading the CLion setup.
<br/><br/>
When the setup is done, run the program by clicking on the downloaded file.

![CLion RunningDotExe](https://cdn.discordapp.com/attachments/498622698050813962/695028299470209064/unknown.png ".exe")

<br/>

## Running the Setup file
### **1.** Run the Setup pt.1
{: .no_toc }
When you open the setup file, this window below will show up. Click ``Next >``

![CLion FirstPage](https://cdn.discordapp.com/attachments/694977588405469265/694991483794751650/unknown.png "First Page")

<br/>

### **2.** Run the Setup pt.2
{: .no_toc }
The next page displays the location of where CLion will be downloaded on your computer. 
<br/><br/>
If you wish to change the destination of where you wish to download the files, click on the Browse button to locate the folder you wish to have it saved to. Otherwise, it is fine to leave it as default.
<br/><br/>
Click ``Next >``

![CLion SecondPage](https://cdn.discordapp.com/attachments/694977588405469265/694991527985938542/unknown.png "Second Page")

<br/>

### **3.** Run the Setup pt.3
{: .no_toc }
The next window will display a number of boxes to be checked.
<br/><br/>
The boxes to be checked are:
- [x] 64-bit launcher _(32-bit, depending on downloaded version)_
- [x] Add launchers dir to the PATH
- [x] Add "Open Folder as Project"
- [x] .c
- [x] .h

After you have checked these boxes, click ``Next >``
 
![CLion ThirdPage](https://cdn.discordapp.com/attachments/694977588405469265/694991864788418600/unknown.png "Third Page")

<br/>

### **4.** Run the Setup pt.4
{: .no_toc }
This next window allows you to choose a start menu folder for the program's shortcuts.
<br/><br/>
You can leave this as default and click ``Next >``

![CLion ForthPage](https://cdn.discordapp.com/attachments/498622698050813962/695551842888712201/unknown.png "Forth Page")

<br/>

### **5.** Run the Setup pt.4
{: .no_toc }
You will need to restart your computer to finish the installation of CLion.
<br/>
<p style='color:red'>WARNING </p>Clicking finish will forcibly restart your computer. If you do not wish to restart yet, click the ``I want to manually reboot later`` option before clicking finish. 

![CLion FifthPage](https://cdn.discordapp.com/attachments/694977588405469265/694992190035722300/unknown.png "Fifth Page")

<br/>

## Run CLion For The First Time
This section of the page will help you set up your CLion IDE.

### **1.** Open the CLion program
{: .no_toc }
You should have the CLion shortcut on your desktop after restarting your computer. Open it and you will see this initial page.
<br/><br/>
As a new user, you will not have any settings to import, so click the "Do not import settings" option and click ``OK``

![IDE FirstPage](https://cdn.discordapp.com/attachments/694977588405469265/694992613002051614/unknown.png "IDE First Page")

<br/>

### **2.** Set up your customization
{: .no_toc }
This window will pop-up afterwards. This is for your personal customization. 
<br/><br/>
If you want a dark-themed IDE, choose ``Darkula``. If you want a light-themed IDE, choose ``Light``. 
<br/><br/>
Afterwards, click on the ``Skip Remaining and Set Defaults`` button on the bottom left side of the window. 

![IDE SecondPage](https://camo.githubusercontent.com/a78232fd2a715e4a36374aeba9d51b1b291b7137/68747470733a2f2f63646e2e646973636f72646170702e636f6d2f6174746163686d656e74732f3439383632323639383035303831333936322f3639353035343736303839333631323038332f756e6b6e6f776e2e706e67 "IDE Second Page")

<br/>

### **3.** Activate Your Free Trial Account pt.1
{: .no_toc }
To activate your free trial account, click on the ``Evaluate for free`` button on the top of the window.

![IDE 22Page](https://cdn.discordapp.com/attachments/498622698050813962/695056162843918336/unknown.png "IDE 22")

<br/>

### **4.** Activate Your Free Trial Account pt.2
{: .no_toc }
Check mark the two boxes displayed on the window and enter your email address.
<br/><br/>
The ``Evaluate`` button should highlight and indicate you to click it. After clicking the button, click ``Continue`` 

![IDE ThirdPage](https://cdn.discordapp.com/attachments/498622698050813962/695031517067346071/unknown.png "IDE Third Page")

<br/>

### **5.** Sign Into Your JetBrains Account
{: .no_toc }
You should be redirected to this window. Enter in your email and password to sign in. 
<br/><br/>
Once you have entered in your information, click ``Continue`` on the bottom right of the window.

![IDE SixthPage](https://cdn.discordapp.com/attachments/498622698050813962/695030756728242276/unknown.png "IDE Fourth Page")

<br/>

### **6.** Import Cygwin Into The IDE
{: .no_toc }
CLion should automatically detect your Cygwin and connect to it.
<br/><br/>
You can tell that you have Cygwin connected if the ``Debugger`` section shows ``Cygwin GDB``.
<br/><br/>
If it does not, click the triple dot ``...`` button on the right side of the Debugger section and navigate to the folder where you installed *gdb.exe*. The address to that *.exe* should be exactly as displayed on the image below.
<br/><br/>
Click on ``Start using CLion`` on the bottom right on the window.

![IDE 5thPage](https://cdn.discordapp.com/attachments/498622698050813962/695049719889657896/unknown.png "IDE 5th page")

<br/>

### **7.** Welcome to CLion!
{: .no_toc }
After you finish setting up your CLion, you should see this window.
<br/><br/>
You now have access to CLion and it's features!

![IDE 6thPage](https://cdn.discordapp.com/attachments/694977588405469265/694995496720269363/unknown.png "IDE 6th page")

<br/>

## Creating Your First C Program!
You have succesfully set up your CLion IDE!

This part of the section will show you how to compile and run the default "Hello, World!" file.

### **1.** Create Your First Program
{: .no_toc }
Click on the ``New Project`` button on the front page, and this window will pop up.
<br/><br/>
Navigate to the ``C Executable`` Section on the left side of the window and change language standard to *C99*.
<br/><br/>
Click on the ``Create`` button on the bottom right.

![HelloWorld](https://cdn.discordapp.com/attachments/498622698050813962/695050703609135114/unknown.png "helloworld 1")

<br/>

### **2.** Execute and Run a Code pt.1
{: .no_toc }
This is what you will see after creating your file C file. 
<br/><br/>
A *Tip of the Day* will show up. If you wish to read about what the IDE has to offer, feel free to read through all of the tips. Otherwise, click ``Close``.

![HelloWorld2](https://cdn.discordapp.com/attachments/498622698050813962/695051257370509312/unknown.png "helloworld 2")

<br/>

### **3.** Execute and Run a Code pt.2
{: .no_toc }
Click on the <img src="https://cdn.discordapp.com/attachments/498622698050813962/695559765367193660/unknown.png" alt="playIcon" width="20"/> icon on the top right of the IDE. 

![HelloWorld3](https://cdn.discordapp.com/attachments/498622698050813962/695052272958439435/unknown.png "helloworld 3")

<br/>

### **4.** Execute and Run the Code pt.3
{: .no_toc }
A box should show up on the bottom of the IDE. If it shows: ```Hello, World!```, then your program works!

![HelloWorld4](https://cdn.discordapp.com/attachments/498622698050813962/695052779940478986/unknown.png "helloworld 4")
