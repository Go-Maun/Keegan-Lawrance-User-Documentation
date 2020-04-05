---
layout: default
title: Installing Cygwin
nav_order: 10
---

# Installing Cygwin
{: .no_toc}

To effectively use CLion, you will need to download some components supplied by [Cygwin.](https://www.cygwin.com/)
<br/><br/>
This section will help you download Cygwin to install three specific packages for CLion.

<hr>

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## Installing The Cygwin Setup


First, you will be setting up the directory and download source 
1. Go to [Cygwin's Website](https://cygwin.com/install.html)<br/>  
  Depending on your computer, you will want to either download  
    1. 64-bit version
    2. 32-bit version<br/>  
  <img src="https://cdn.discordapp.com/attachments/498622698050813962/696144246062841937/download.png" alt="note" width="50"/>**NOTE:** If you are not certain of which version is compatible with your computer, it will be safer to download the 32-bit version.<br/>  
  ![Cygwin Download Page](https://cdn.discordapp.com/attachments/498622698050813962/695756069078564934/unknown.png "Download")
<br/><br/>

2. Run the file you downloaded<br/>  
  If you get a security warning, it is safe to ignore it and run the program.<br/>  
  <img src="https://cdn.discordapp.com/attachments/498622698050813962/696144246062841937/download.png" alt="note" width="50"/>**Note:** This was downloaded in a Google Chrome browser. If your browser is different, the file may appear in a different location.
  ![Cygwin Download Link](https://cdn.discordapp.com/attachments/498622698050813962/695036150854713416/unknown.png "Download2")

## Running the Cygwin Setup
1.  Click on ``Next >``<br/>  
  ![Cygwin firstPage](https://cdn.discordapp.com/attachments/694977588405469265/694983080238252053/unknown.png "Setup 1")
  <br/><br/>  
  
2. Select the ``Install from Internet`` download source<br/>  
  Click on ``Next >``<br/>  
  ![Cygwin secondPage](https://cdn.discordapp.com/attachments/498622698050813962/695036893087137902/unknown.png "Setup 2")
  <br/><br/>  
  
3. Keep all selected defaults<br/>  
   Click on ``Next >``<br/>  
  ![Cygwin thirdPage](https://cdn.discordapp.com/attachments/694977588405469265/694983315295305878/unknown.png "Setup 3")
  <br/><br/>  
  
4. Change the ``Local Package Directory`` to _``C:\cygwin64\downloads``_<br/>  
   Click on ``Next >``<br/>  
  ![Cygwin fourthPage](https://cdn.discordapp.com/attachments/694977588405469265/694984033549156403/unknown.png "Setup 4") 
  <br/>  
  <img src="https://cdn.discordapp.com/attachments/498622698050813962/696144246062841937/download.png" alt="note" width="50"/>**NOTE:** If an error message pops up, it is safe to create the new directory by clicking ``Yes``<br/>  
  ![Cygwin fourthPageAddition](https://cdn.discordapp.com/attachments/694977588405469265/694984075378819083/unknown.png "Setup 4.5")
  <br/><br/>  
  
5. Select ``Direct Connection``<br/>  
  Click on ``Next >``<br/>  
  ![Cygwin FifthPage](https://cdn.discordapp.com/attachments/694977588405469265/694984235353768079/unknown.png "Setup 5")
  <br/><br/>  
  
6. Search for the closest [Mirror Site](https://cygwin.com/mirrors.html)<br/>  
  When your preferred download source is found , select it in the scroll window. click on ``Next >``<br/>  
![Cygwin SixthPage](https://cdn.discordapp.com/attachments/694977588405469265/694984840172404806/unknown.png "Setup 6")
<br/><br/>  

## Selecting Packages
These proceeding steps will cover what packages to choose, and how to choose them.
### Selecting _gcc-g++_
1. Change the drop-down ``View`` tab to ``Category``<br/>    
  ![Cygwin Package1](https://cdn.discordapp.com/attachments/694977588405469265/696111097790595113/category.png "Package 1")
  <br/><br/>  

2. Search for _gcc-g++_ in the ``Search`` field<br/>  
  ![Cygwin Package1.5](https://cdn.discordapp.com/attachments/498622698050813962/695042959472590908/unknown.png "Package 1.5")
  <br/><br/>  

3. Expand the ``Devel`` level in the window<br/>  
  ![Cygwin Package2](https://cdn.discordapp.com/attachments/498622698050813962/695039874658467940/unknown.png "Package 2")
  <br/><br/>  

4. Search the ``Devel`` drop-down list<br/>  
  The package name must match _gcc-g++_.<br/>  
  <img src="https://cdn.discordapp.com/attachments/498622698050813962/696144248512446525/warning.png" alt="warning" width="50"/>**Warning:** The package name must exactly match _gcc-g++_, otherwise you will be downloading the wrong package.<br/>  
  Click on the small arrow under the ``New`` collumn.<br/>  
  ![Cygwin Package3](https://cdn.discordapp.com/attachments/498622698050813962/695040472485330984/unknown.png "Package 3")
  <br/><br/>  

5. Select the highest numbered version on the drop-down menu<br/>  
  ![Cygwin Package4](https://cdn.discordapp.com/attachments/498622698050813962/695041017744851014/unknown.png "Package 4")
  <br/><br/>  

6. Check the Src? check box<br/>  
  ![Cygwin Package5](https://cdn.discordapp.com/attachments/498622698050813962/695041637331501126/unknown.png "Package 5")
  <br/><br/>  

### Selecting _gdb_
Follow along with the same steps from [gcc-g++](https://go-maun.github.io/Keegan-Lawrance-User-Documentation/docs/Cygwin-Setup/#selecting-gcc-g), searching instead for _gdb_

![Cygwin gdb](https://cdn.discordapp.com/attachments/498622698050813962/695043794910838894/unknown.png "gdb 1")
<br/><br/>


### Selecting _make_
Follow along with the same steps from [gcc-g++](https://go-maun.github.io/Keegan-Lawrance-User-Documentation/docs/Cygwin-Setup/#selecting-gcc-g), searching instead for _make_

![Cygwin make](https://cdn.discordapp.com/attachments/498622698050813962/695044666927743026/unknown.png "make")
<br/><br/>



## Downloading the Packages
Once you have selected _gcc-g++_, _gdb_, and _make_ you can continue

1. Click on ``Next >``<br/>  
  ![Cygwin package download](https://cdn.discordapp.com/attachments/498622698050813962/695045219090956368/unknown.png "package download")
<br/><br/>  

2. Click on ``Next >``<br/>  
  ![Cygwin package download2](https://cdn.discordapp.com/attachments/694977588405469265/694987045621202995/unknown.png "package download 2")
<br/><br/>  

3. Download the packages<br/>  
  <img src="https://cdn.discordapp.com/attachments/498622698050813962/696144246062841937/download.png" alt="note" width="50"/>**Note:** This process may take some time depending on how close you are to the Mirror Site you selected.<br/>  
  ![Cygwin package download3](https://cdn.discordapp.com/attachments/694977588405469265/694987084036833341/unknown.png "package download 3")
<br/><br/>  

4. Finalize Cygwin installation<br/>  
  Now that the packages have finished downloading, you can choose whether or not to add the Cygwin Terminal to your Desktop and/or Start Menu. Clicking on ``finish`` will complete this process<br/>  
  ![Cygwin package download4](https://cdn.discordapp.com/attachments/694977588405469265/694987469409615952/unknown.png "package download 4")
<br/><br/>  

## Conclusion
You have now sucessfully downloaded Cygwin onto your computer. Your next steps are in [Creating a CLion Account](https://go-maun.github.io/Keegan-Lawrance-User-Documentation/docs/JetBrains-Account-Setup/).
