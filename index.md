# **_Hello and welcome to my guide! o >o/'_**

Here you can build a stable foundation to your windows system, many users who may just start up windows and use windows update to keep everything in check can miss out on important resources for stability.
This guide will be focused on Windows 10 OS, it’s possible to follow this guide using similar settings on other versions of windows.

## **_1.Drivers and BIOS_** 
-Myth  BIOS's are difficult and complicated to update.
That maybe true for very old PC setups but today's Motherboards are very user friendly.
Guides to updating your bios can be found in the user manual of your motherboard, if you have lost or thrown away your manual you can get a digital copy from the manufacturer website.
! BIOS updates may reset OC/profile when updating and may need to be re-done; you must NEVER turn off the power to the PC while the BIOS is updating.

**_Identifying your hardware:_**

Press the Win key on your keyboard and type Msinfo and press enter.

Laptops:Under the item name System Model and System Manufacturer the value to the right will be the model and manufacturer of your laptop. (keep this window minimised to be used again)

Desktop:Under the item name BaseBoard Product and BaseBoard Manufacturer will be your model and manufacturer of your motherboard. (keep this window minimised to be used again)


**_The download:_**

Now open your web browser and search for your manufacturer, you can open the Msinfo window as a reminder to the name and model of your system.
Once you are in the manufacturer website navigate to the section that says service, support or downloads.
When you're there you will be greeted with a search bar, here you put in your model number.
Once you find the section with drivers and bios's download the latest driver for the correct windows version.
-There are many drivers to choose from, download the latest of each driver and ignore the duplicate/older drivers.
You can download a digital copy of your user manual in or around this section of the website.

**_The Install:_**

Bios: Follow your user manual and it will guide you through it. 

Motherboard/laptop: Select a driver and install one by one, some drivers may require a restart so please reset your system then continue to the next driver.


Now you have updated the Core drivers to your windows system.
If you have a device connected to your motherboard like sound cards, network cards, usb devices etc.
You can check your up to date with drivers for those devices by finding the manufacturer and model of the device and searching for their website like you did with the motherboard/laptop.

## **_2.Software and OS update_**
Updates are important to system stability and security to ongoing and new games.

**_Windows Update:_**
Press the Win key, type update and press enter.
Click check for updates and let windows update do its thing.
-Earlier versions of Windows 10 had a temperamental updater, close and reopen the updater and spam to check for updates a few times.

**_Windows Defender:_**
Press the Win key, type Defender and press enter.
Click virus and threat protection.
Click check for updates under: virus and threat protection updates.
Now click Check for updates and let it do its thing.

**_Software:_**
Software updates are handled in many ways and they vary between program developers.
Unless there is a section you can click to check for updates simply re-downloading the software and installing it can do the same thing as an update, in some cases the installer of the software will tell you if you have the most current version of that software.

## **_3.Anti-Virus Check-up_**
A common cause for errors is related to a virus infection on your system.
Performing a full system scan is highly recommended.
-For the love of all that is roley poley please only install one antivirus on your system!
Having more than one can do more harm than good.

Press the Win key, type Defender and press enter.
Click virus and threat protection.
Click scan options and choose full scan and click scan now. (a full scan only ever needs to be done if not done in a very long time)
Once done deal with any threats how you see fit.

If you are having trouble with your anti-virus and you believe it to be compromised try this anti-root kit software:
[Malwarebytes Antirootkit](https://www.malwarebytes.com/antirootkit/)
You can choose to purchase 3rd party Antivirus but please do your research into it as the best AV software may change to something else the next year!

## **_4.Command your Firewall_**
Windows firewall is one of the main barriers to your system.
Sometimes it can also block programs that you want to have access to the network, like your games.

**_Allow a program or game through your firewall:_**
Press the Win key and type firewall then press enter.
Click allow and app or feature through windows defender firewall.
Click change settings and scroll through the list, if a game is not on the list that you want Click allow another app...
Click browse and navigate to your game file location, select the launcher .exe file and click open.
Then tick both boxes, do this for any games you wish to add to the list then press ok.

## **_5.Cleaning up_**
Cleaning your PC is ideal to reduce old conflicting files and save you much needed space.

**_Disk clean:_**
Press the Win key and type this PC and press enter. (or Mycomputer for other windows systems)
Right click your C drive and click properties.
Click disk clean-up and look at the list of areas to clean in the center window.
Tick what you want to clean or keep, once done click clean up system files.
Allow it to do its thing and wait for it to finish.

**_Defrag:_** (HDD/Mechanical Drives only!)
Follow the Disk clean guide till you reach the C drive properties.
Then go to the tools tab and click optimise.
Select the drives you wish to defrag/optimise then click the optimise button.
This will take some time so let it run in the background while doing light tasks if your system has the power.
Flushing the DNS:
Hold down the Windows Key and press X.
Click Command Prompt (Admin).
When the command prompt opens,Type ipconfig /registerdns and press Enter.
Type ```ipconfig /release``` and press Enter.
Type ```ipconfig /renew``` and press Enter.
Type ```netsh winsock reset``` and press Enter.
Reboot your computer.

**_Windows Redistributable cleanup:_**
(Only applies to Windows systems that have had a lot of programs installed and uninstalled over a period of time)

First open the programs you very often use all at once.
Then right click the windows icon and click Apps and features.
In the list of programs are a list Redistributable or distro's, un-install each one if they ask you to close a program you know the distro is needed and you can cancel the un-install.
Once done you can close the programs and go to your games.
If a game fails to load, run a repair game or check game file integrity to reinstall distro's the games need.

**_Further cleaning:_**
You can use alternative software to clean your system but it can be risky if you do not know what software to choose.
Ccleaner has been a great organiser with in build registry cleaner, uninstaller, start-up programs and program file cleaner.
[Ccleaner](https://www.ccleaner.com/ccleaner/download)

**_Saving space:_**
To reduce the space your OS is taking you can compress some of the files. (to see how much space you saved take note of how much space you are currently using then check after you have finished the guide.)

Note: Compression will add a small amount of CPU usage so you may reconsider if you own older or low core count CPUs.

Open Command Prompt, right-click the result, and select Run as administrator.
Then type ```Compact.exe /CompactOS:always``` and hit enter.
Once done do the same for ```powercfg /h /type reduced```
Then ```powercfg.exe /h off``` DO NOT use this command for laptops!

And that about wraps it up. o >o
If you take this guide to heart and use parts of the guide to maintain your system it can keep your system at peak health without the need to reinstall windows.

