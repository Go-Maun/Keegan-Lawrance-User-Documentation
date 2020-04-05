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
  Depending on your computer, you will want to either download:
    1. 64-bit version
    2. 32-bit version<br/>  
  <img src="https://cdn.discordapp.com/attachments/498622698050813962/696144246062841937/download.png" alt="note" width="50"/>**NOTE:** If you are unsure which version to download, refer to the [troubleshooting section](https://go-maun.github.io/Keegan-Lawrance-User-Documentation/docs/search/#how-do-i-check-if-im-using-a-64-bit-or-a-32-bit-version-of-windows) to help figure out your operating systems version.<br/>  
  ![Cygwin Download Page](https://cdn.discordapp.com/attachments/619382734984577042/696151746770239518/unknown.png "Download")
<br/>  

2. Run the file you downloaded<br/>  
  If you get a security warning, it is safe to ignore it and run the program.<br/>  
  <img src="https://cdn.discordapp.com/attachments/498622698050813962/696144246062841937/download.png" alt="note" width="50"/>**NOTE:** This was downloaded in a Google Chrome browser. If your browser is different, the file may appear in a different location.<br/>  
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
  <br/>
  
5. Select ``Direct Connection``<br/>  
  Click on ``Next >``<br/>  
  ![Cygwin FifthPage](https://cdn.discordapp.com/attachments/694977588405469265/694984235353768079/unknown.png "Setup 5")
  <br/><br/>  
  
6. Search for the closest [Mirror Site](https://cygwin.com/mirrors.html)<br/> 
  <br/> <img src="https://cdn.discordapp.com/attachments/498622698050813962/696144246062841937/download.png" alt="note" width="50"/>**NOTE:** A Mirror Site is a website that contains the files that you will need to set up Cygwin. You will be using one of these sites as your download source, so choosing a website that is close to your area will help speed up the process. However, it doesn't necessarily matter which Mirror Site you choose.
  <br/><br/>
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
  <img src="https://cdn.discordapp.com/attachments/498622698050813962/696144248512446525/warning.png" alt="warning" width="50"/>**WARNING:** The package name must exactly match _gcc-g++_. This applies to _gdb_ and _make_ in the next steps as well.<br/>  
  ![Cygwin Package3](https://cdn.discordapp.com/attachments/498622698050813962/695040472485330984/unknown.png "Package 3")
  <br/><br/>  

5. Select the highest numbered non-test number version on the drop-down menu<br/>  
  ![Cygwin Package4](https://cdn.discordapp.com/attachments/498622698050813962/695041017744851014/unknown.png "Package 4")
  <br/><br/>  

6. Check the ``Src?`` check box<br/>  
  ![Cygwin Package5](https://cdn.discordapp.com/attachments/498622698050813962/695041637331501126/unknown.png "Package 5")
  <br/><br/>  

### Selecting _gdb_

  <img src="https://cdn.discordapp.com/attachments/498622698050813962/696144246062841937/download.png" alt="note" width="50"/>**NOTE:** It is safe to clear the search for _gcc-g++_ as long as you have the ``Src?`` box checked for it. This applies to _gdb_ and _make_ as well.<br/>  
  
  
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
  <img src="https://cdn.discordapp.com/attachments/498622698050813962/696144246062841937/download.png" alt="note" width="50"/>**NOTE:** This process may take some time depending on how close you are to the mirror site you selected.<br/>  
  ![Cygwin package download3](https://cdn.discordapp.com/attachments/694977588405469265/694987084036833341/unknown.png "package download 3")
<br/><br/>  

4. Finalize Cygwin installation<br/>  
  Now that the packages have finished downloading, you can choose whether or not to add the Cygwin Terminal to your Desktop and/or Start Menu. Clicking on ``Finish`` will complete this process<br/>  
  ![Cygwin package download4](https://cdn.discordapp.com/attachments/694977588405469265/694987469409615952/unknown.png "package download 4")
<br/><br/>  
<hr>
## Conclusion
You have now sucessfully downloaded Cygwin onto your computer. Your next steps are in [Creating a CLion Account](https://go-maun.github.io/Keegan-Lawrance-User-Documentation/docs/JetBrains-Account-Setup/).
