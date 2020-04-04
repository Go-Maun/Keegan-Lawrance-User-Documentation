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
### **1.** Go to [Cygwin's Website](https://cygwin.com/install.html)
{: .no_toc }


Depending on your computer, you will want to either download the 64-bit version, or the 32-bit version. 

**NOTE:** If you are not certain of which version is compatible with your computer, it will be safer to download the 32-bit version.

![Cygwin Download Page](https://cdn.discordapp.com/attachments/498622698050813962/695756069078564934/unknown.png "Download")


### **2.** Run _setup-x86.exe_
{: .no_toc }

![Cygwin Download Link](https://cdn.discordapp.com/attachments/498622698050813962/695036150854713416/unknown.png "Download2")



## Running the Cygwin Setup
### **1.** Setup Cygwin pt.1
{: .no_toc }

If you get a security warning, it is safe to ignore it and run the program. Click on ``Next >``

![Cygwin firstPage](https://cdn.discordapp.com/attachments/694977588405469265/694983080238252053/unknown.png "Setup 1")
<br/>

### **2.** Setup Cygwin pt.2
{: .no_toc }

Select the ``Install from Internet`` download source, and click on ``Next >`` 

![Cygwin secondPage](https://cdn.discordapp.com/attachments/498622698050813962/695036893087137902/unknown.png "Setup 2")
<br/>

### **3.** Setup Cygwin pt.3
{: .no_toc }

Keep all selected defaults and click on ``Next >``

![Cygwin thirdPage](https://cdn.discordapp.com/attachments/694977588405469265/694983315295305878/unknown.png "Setup 3")
<br/>

### **4.** Setup Cygwin pt.4
{: .no_toc }

Change the _Local Package Directory_ to ``C:\cygwin64\downloads`` if it is not already set to that as default and click on ``Next >``

![Cygwin fourthPage](https://cdn.discordapp.com/attachments/694977588405469265/694984033549156403/unknown.png "Setup 4")
<br/>

**NOTE:** If an error message pops up, it is safe to create the new directory by clicking ``Yes``

![Cygwin fourthPageAddition](https://cdn.discordapp.com/attachments/694977588405469265/694984075378819083/unknown.png "Setup 4.5")
<br/>

### **5.** Setup Cygwin pt.5
{: .no_toc }

Select ``Direct Connection`` and click on ``Next >``

![Cygwin FifthPage](https://cdn.discordapp.com/attachments/694977588405469265/694984235353768079/unknown.png "Setup 5")
<br/>

### **6.** Setup Cygwin pt.6
{: .no_toc }

Search for the closest [Mirror Site](https://cygwin.com/mirrors.html) and select it in the scroll window. When your preferred download source is found, click on ``Next >``


![Cygwin SixthPage](https://cdn.discordapp.com/attachments/694977588405469265/694984840172404806/unknown.png "Setup 6")
<br/>


## Selecting Packages
These proceeding steps will cover what packages to choose, and how to choose them.
### Selecting ``gcc-g++``
``gcc-g++`` includes a collection of compilers, including C.
## **1.** Selecting ``gcc-g++`` pt.1
{: .no_toc }
Change the drop-down _View_ tab to ``Category`` if it already isn't selected

![Cygwin Package1](https://cdn.discordapp.com/attachments/498622698050813962/695039018433511434/unknown.png "Package 1")
<br/>

## **2.** Selecting ``gcc-g++`` pt.2
{: .no_toc }

In the _Search_ field, search for ``gcc-g++``

![Cygwin Package1.5](https://cdn.discordapp.com/attachments/498622698050813962/695042959472590908/unknown.png "Package 1.5")
<br/>

## **3.** Selecting ``gcc-g++`` pt.3
{: .no_toc }

Expand the _Devel_ level in the window.

![Cygwin Package2](https://cdn.discordapp.com/attachments/498622698050813962/695039874658467940/unknown.png "Package 2")
<br/>


## **4.** Selecting ``gcc-g++`` pt.4
{: .no_toc }

Search the _Devel_ drop-down list for an item that **EXACTLY** matches ``gcc-g++``. Click on the small arrow under the _New_ collumn.

![Cygwin Package3](https://cdn.discordapp.com/attachments/498622698050813962/695040472485330984/unknown.png "Package 3")
<br/>

## **5.** Selecting ``gcc-g++`` pt.5
{: .no_toc }

On the drop-down menu, select the highest numbered version.

![Cygwin Package4](https://cdn.discordapp.com/attachments/498622698050813962/695041017744851014/unknown.png "Package 4")


## **6.** Selecting ``gcc-g++`` pt.6
{: .no_toc }

Check the - [x] Src? check box

![Cygwin Package5](https://cdn.discordapp.com/attachments/498622698050813962/695041637331501126/unknown.png "Package 5")


### Selecting ``gdb``
Follow along with the same steps from [gcc-g++](https://go-maun.github.io/Keegan-Lawrance-User-Documentation/docs/Cygwin-Setup/#selecting-gcc-g), searching instead for ``gdb``

![Cygwin gdb](https://cdn.discordapp.com/attachments/498622698050813962/695043794910838894/unknown.png "gdb 1")
<br/>


### Selecting ``make``
Follow along with the same steps from [gcc-g++](https://go-maun.github.io/Keegan-Lawrance-User-Documentation/docs/Cygwin-Setup/#selecting-gcc-g), searching instead for ``make``

![Cygwin make](https://cdn.discordapp.com/attachments/498622698050813962/695044666927743026/unknown.png "make")
<br/>



## Downloading the Packages
Once you have selected ``gcc-g++``, ``gdb``, and ``make`` you can continue

### **1.** Downloading Packages pt.1
{: .no_toc }

Now that the packages have been selected, click on ``Next >``

![Cygwin package download](https://cdn.discordapp.com/attachments/498622698050813962/695045219090956368/unknown.png "package download")
<br/>


### **2.** Downloading Packages pt.2
{: .no_toc }

These are the packages that will be installed along with ``gcc-g++``, ``gdb``, and ``make``. Click on ``Next >``

![Cygwin package download2](https://cdn.discordapp.com/attachments/694977588405469265/694987045621202995/unknown.png "package download 2")
<br/>

### **3.** Downloading Packages pt.3
{: .no_toc }

The packages will begin to download. 

**Note:** This process may take some time depending on how close you are to the Mirror Site you selected.

![Cygwin package download3](https://cdn.discordapp.com/attachments/694977588405469265/694987084036833341/unknown.png "package download 3")
<br/>


### **4.** Downloading Packages pt.4
{: .no_toc }

Now that the packages have finished downloading, you can choose whether or not to add the Cygwin Terminal to your Desktop and/or Start Menu. Clicking on ``finish`` will complete this process

![Cygwin package download4](https://cdn.discordapp.com/attachments/694977588405469265/694987469409615952/unknown.png "package download 4")
<br/>

You have now sucessfully downloaded Cygwin onto your computer. Your next steps are in [Creating a CLion Account](https://go-maun.github.io/Keegan-Lawrance-User-Documentation/docs/JetBrains-Account-Setup/).
