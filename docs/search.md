---
layout: default
title: Troubleshooting
nav_order: 17
---

# Troubleshooting
{: .no_toc }
This section will answer possible questions and issues that may pop up during the installation of Cygwin and CLion.

---
## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## How do I check if I'm using a 64-bit or a 32-bit version of Windows?
To find what version of Windows you are using:
1. Press the Windows key on your keyboard
<br/><br/>
2. Search for ``System Information``
<br/>This program should show up when you search it up.
<br/>![SystemInformation](https://cdn.discordapp.com/attachments/498622698050813962/695913254781976598/unknown.png "SystemInformation")
<br/><br/>
3. Open the ``System Information`` program.
<br/><br/>
4. A window similar to the image below should show up. The section you are looking for is displayed in the image below.
<br/>This will tell you which version of Windows you are using.
![SystemType](https://cdn.discordapp.com/attachments/498622698050813962/695873602377220116/Untitled.png "SystemType")
<br/><br/>

## I cannot locate my CLion application!
If your CLion shortcut is not displayed on your Desktop, there are ways to manually create one.
1. Press the Windows key on your keyboard
<br/><br/>
2. Search for ``CLion``. The CLion application should show up as displayed below.
<br/>![CLion](https://cdn.discordapp.com/attachments/498622698050813962/695915851731304448/Untitled.png "CLion")
<br/><br/>
3. Right click the application, and click on ``Open file location``
<br/><br/>
4. A folder will open containing the CLion application that you have downloaded. Right click the application and click on ``Copy``
<br/><br/>
5. Locate the folder that you wish to have your shortcut added to. We recommend saving this copy to your Desktop.
<br/><br/>
6. Once you have accessed the folder, right click on any black space in the folder and click ``Paste``
<br/><br/>

## I do not have access to the free trial to CLion!
Not having access to CLion could mean two things.
1. You have used up your 30-day free trial of CLion
     - In that case, the only solution is to purchase the program from the site itself for $199.00USD a month.
<br/><br/>
2. You have not properly set up and activated your JetBrains account.
     - To solve this, we recommend going over our [Create a CLion account section](https://go-maun.github.io/Keegan-Lawrance-User-Documentation/docs/JetBrains-Account-Setup/) to make sure you didn't forget a step.
     - If this does not solve your issue, we recommend sending JetBrains a support ticket for more help.
<br/><br/>

## My CLion IDE is not detecting Cygwin!
If CLion cannot locate your Cygwin, then it could mean that the installation of gdb, gcc-g++, and make was not successful.
- We suggest reviewing the [Installing Cygwin section](https://go-maun.github.io/Keegan-Lawrance-User-Documentation/docs/Cygwin-Setup/) of the document to make sure you downloaded the correct packages for CLion to work.
- If the issue persists, go back to the [Installing Cygwin section](https://go-maun.github.io/Keegan-Lawrance-User-Documentation/docs/Cygwin-Setup/) to look at the **6th step of Running CLion For The First Time** and manually locate each Cygwin package. They should be the same as the diagram.

## I keep getting a popup saying "Windows Defender might be impacting your build performance." Is it safe to allow the IDE to automatically fix this issue?
The problem should look something like this.
<br/>![WarningAlert](https://cdn.discordapp.com/attachments/498622698050813962/695924569088983101/unknown.png "WarningAlert")
<br/><br/>
It is safe to allow the IDE to fix the issue. Not fixing it should not cause any major complications with the IDE, so it is also fine to leave it alone.
<br/><br/>
If you wish to know more about the reasoning behind this message, [read the support article about it here.](https://cdn.discordapp.com/attachments/498622698050813962/695924569088983101/unknown.png)
