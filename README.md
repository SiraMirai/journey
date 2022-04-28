![](https://raw.githubusercontent.com/SiraMirai/journey/main/images/Journey169v3.webp)

---

<p align="center">
<a href="https://www.nexusmods.com/skyrimspecialedition/mods/65229"?>Nexus Page</a> | <a href="https://github.com/SiraMirai/journey/blob/main/README.md"?>Readme</a> | <a href= "https://github.com/SiraMirai/journey/blob/main/GAMEPLAY.md"?>Gameplay</a> | <a href= "https://github.com/SiraMirai/journey/blob/main/CONFIGURATION.md"?>Configuration</a> | <a href="https://github.com/SiraMirai/journey/blob/main/CHANGELOG.md"?>Changelog</a> | <a href="https://github.com/SiraMirai/journey/blob/main/SUPPORT.md"?>Support</a> | <a href="https://www.wabbajack.org/">Wabbajack</a>
</p>

---

**Download Journey: [Journey.wabbajack](https://github.com/SiraMirai/journey/releases/download/1.0.2/Journey-1.0.2.wabbajack)**

**Modlist Support: [The Animonculory Server](https://discord.gg/DffHKcszfg)**

- [Introduction](#about-journey)
	- [Gameplay](#gameplay)
	- [Discussion and Support](#discussion-and-support)
	- [List Contents](#list-contents)
- [Installation](#installation)
	- [Pre-Installation](#pre-installation)
		- [Installing Microsoft Visual C++](#installing-microsoft-visual-c++-redistributable-x64)
		- [Clean Skyrim](#clean-skyrim)
		- [Start Skyrim](#start-skyrim)
	- [Wabbajack Install](#wabbajack-install)
		- [Initial Setup](#initial-setup)
		- [Download and Installation](#download-and-installation)
		- [Common Wabbajack Issues](#common-wabbajack-issues)
- [Updating](#updating)
- [Finishing Up](#finishing-up)

"You realize that all your life you have been coasting along as if you were in a dream. Suddenly, facing the trials of the last few days, you have come alive."

# About Journey

Journey is a lightweight modlist designed to give an enhanced graphical presentation that keeps the spirit of Skyrim's aesthetic and provide a cohesive lightweight gameplay overhaul with an optional survival component using Survival Mode. Journey's purpose is to provide a base graphical and gameplay overhaul to play an enhanced Skyrim experience with a few carefully selected additional quests, new lands, and optional compainions included. Journey should look beautiful, but run well even on lower end systems.

Journey is designed and made for Skyrim: Special Edition with full support for players with only the free Creation Club content or those who have the full Anniversary Edition content.

### Gameplay

Journey's aims with gameplay modification is to remain unintrusive while enhancing the core mechanics in a way that remains true to the spirit of Skyrim's core design. You can see the full details of what has changed in Journey's gamplay [here](https://github.com/SiraMirai/journey/blob/main/GAMEPLAY.md).

### Discussion and Support

Support for Journey is offered in [The Animonculory Server](https://discord.gg/DffHKcszfg) or in the issues section of the Journey GitHub. If you have any questions, want to discuss gameplay, or if you find any mistakes in documentation, please report it in the Animonculory Server's support channel.

### List Contents

The full contents of Journey can be found [here](https://loadorderlibrary.com/lists/journey-a-vanilla-modlist)

# Installation

Installation is handled by [Wabbajack](https://www.wabbajack.org/#/) for a one-click install of the modlist. For first time users, Journey has one dependency that needs to be pre-installed.

#### Stock Game
Journey makes use of the **Stock Game** feature of MO2 and Wabbajack.

What this means is that it will create a copy of a Skyrim installation within the Journey Installation folder, cleaned with everything required for the modlist to run included. This allows you to run Journey without conflict from files with other Wabbajack lists, Vortex files, or other Skyrim mod installations.

### Pre-Installation

This is only required if you're installing Journey for the first time.

#### Installing Microsoft Visual C++ Redistributable x64

It is very common for this to already be installed as it is required for MO2. It can be downloaded from Microsoft [here](https://docs.microsoft.com/en-us/cpp/windows/latest-supported-vc-redist). Download the x64 version under "Visual Studio 2015, 2017, 2019, and 2022."

#### Clean Skyrim
It is highly recommended that you install Journey from an unmodded Skyrim install through Steam. To do this, uninstall the game through Steam, delete the game folder, and then reinstall it. In addition, you should also clear out files in the `Skyrim Special Edition` folder in `Documents/My Games/` .

#### Start Skyrim
Start the game through the launcher and then exit after you are at the main menu. This ensures settings files needed by the Wabbajack process are created inside the Skyrim directory.

### Wabbajack Install

#### Initial Setup
Download the release and Wabbajack to a _working folder_. This folder **must not** be in a common folder like Desktop, Downloads, or Program Files. It is best practice to create a Wabbajack folder near the root level of your drive like `C:/Wabbajack`. For the best performance during installation, it is recommended to have this working folder on an SSD

Download the latest release of Wabbajack [here](https://www.wabbajack.org/#/) and place `Wabbajack.exe` inside the working folder you created.

#### Download and Installation
The installation process can take some time depending on your system specs. It is recommended to just be patient and let Wabbajack do its thing once it is running.

1. Create a folder for the modlist near the root of your drive (Like the Wabbajack folder) called "Journey". Good example directories include `C:\Journey` or `C:\Games\Journey`.
  
2. Also near the root of a drive, create a "Wabbajack Downloads" folder. This folder may be on a different drive.
  
3. Download the latest version of `Journey.wabbajack` from this page and place it in your Wabbajack working folder.
  
4. In Wabbajack, select "Install From Disk"
  
5. Set target modlist to the `Journey.wabbajack` file.
  
6. Select the folder created in step 1 as your installation folder.
  
7. Select the folder created in step 2 as your downloads folder.
  
8. Click the Start button and wait for Wabbajack to install the modlist.
  

#### Common Wabbajack Issues
Wabbajack has a number of scenarios where it will produce an error. Most often, simply re-running Wabbajack will fix this issue and I recommend attempting that before posting anything. Wabbajack will continue from where it left off and lose no progress.

##### Could not download
There are some files that are known to have issues being downloaded by Wabbajack. You may manually download these mods from their source and place their archives **as is** into the downloads folder.

The other common cause of this error is a mod was updated and its old files were deleted and are now impossible to download. In this situation, simply wait until Journey has been updated.

##### Wabbajack cannot find Skyrim folder
Wabbajack will not work with pirated copies of Skyrim. If you own the game on steam, return to [Pre-Installation](#pre-installation).

# Updating
When Journey releases an update, please check the [changelog](https://github.com/SiraMirai/journey/blob/main/CHANGELOG.md) before updating. **Always** back up your saves or start a new game after updating.

Please note that Wabbajack will **delete all files that are not part of the modlist when it updates**! 

Any additional mods and configurations you have made will be removed. Your saves will be kept, but check the changelog for the update to see if it is compatible with saves from prior versions. Your downloads folder will be left untouched so it is recommended to leave additional mods you have downloaded to reinstall after the update.

Updating follows the same process as installing, simply select the same path and tick the _overwrite existing Modlist_ button.

# Finishing Up
Before playing
- Journey comes with several graphical presets included that you can read about [here](https://github.com/SiraMirai/journey/blob/main/CONFIGURATION.md#graphics-options).
- Make sure you follow the guid for [setting up creation club content](https://github.com/SiraMirai/journey/blob/main/CONFIGURATION.md#anniversary-edition).
- Choose what ENB or ReShade preset you want using [ENB Organizer](https://github.com/SiraMirai/journey/blob/main/CONFIGURATION.md#enb-organizer)
- Journey also comes with several other optionals including alternative profiles and optional companions. You can read about them [here](https://github.com/SiraMirai/journey/blob/main/CONFIGURATION.md#optionals).
