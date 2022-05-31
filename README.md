# Stock-Game-for-mod-making
Quick installer to set up the Creation Kit

[![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg

## Contents
  - [Preamble](#preamble)
  - [System Requirements](#system-requirements)
  - [Installation](#installation)
    - [Pre-Installation](#pre-installation)
    - [Wabbajack Installation](#wabbajack-installation)
      - [Installing Wabbajack](#installing-wabbajack)
      - [Downloading and Installing the setup](#downloading-and-installing-the-setup)
      - [Problems with installation](#problems-with-installation)


### This installer is meant as an easy way to install the CK to make mods

## Preamble

> A one click (not entirely but as close as it gets) solution to set up the Creation Kit for modding and scripting purposes. You need to install your external scripting tools on your own as there are many to choose from and not everyone likes the same methods.

# <ins>**This installer requires the latest Skyrim SE version wrongfully called AE.**</ins>

This work is licensed under a
[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

## System Requirements

Space required: 
- Approx 14.9GB (Downloads included)
 
Size without downloads: 
- Approx 14.7GB

## Installation

Installing will only take a few minutes and is fairly simple

### Pre-Installation

Prior to installing Ruvaak, please complete the following steps.

1. Install [Visual C++ x64](https://aka.ms/vs/16/release/vc_redist.x64.exe) & [.Net Runtime v5 desktop x64](https://dotnet.microsoft.com/download/dotnet/5.0/runtime).
2. Change Skyrim so it does not [automatically update](https://help.steampowered.com/en/faqs/view/71AB-698D-57EB-178C#disable).
3. Fully uninstall Skyrim by deleting the folder and the Skyrim Special edition folder inside /Documents/My Games/.
4. Reinstall Skyrim into a location that is not Program files. Somewhere like C:\Games is a good location.
5. Start the game once and let it do the graphics check. Do not worry about the settings as it will be replaced during installation.
6. Install the Creation Kit **from Steam** and put it into the same folder as Skyrim SE
7. You also need to start the game to the main menu in order to download all the creations


### Wabbajack Installation

#### Installing Wabbajack

Once you have completed pre-installation, download the [latest version of Wabbajack]((https://github.com/wabbajack-tools/wabbajack/releases)) and place it in a folder such as `C:\Games\Wabbajack`. Do not place it in program files, on your desktop or in your downloads folder. I recommend placing it on an SSD as it will work quicker on there.

#### Downloading and Installing the setup

Downloading and installing will only take a few minutes and works as follows:

1. Get the latest version of the installer [here](https://github.com/chri3i/Stock-Game-for-mod-making/releases/download/v1.0/Stockgame.for.Mod.Making.wabbajack)
2. Open Wabbajack and click on ``install from disc``
3. Set the installation folder to be somewhere like C:\Games\Modmaking. **Do not install it to your desktop, downloads folder or Skyrim's game folder.**
4. The download location does not need to be on a SSD but it makes installing a bit faster
5. Press the play button to begin.
6. Wait while Wabbajack does its thing. It won't take long
7. If the installation is successful, you're done and this readme ends. All that is left, is starting up the MO2 instance in the install folder and make your mods.


##### Problems with installation

It is possible that you may encounter an error with Wabbajack when installing. Some common issues are listed below.

- Could not download x:
	- Big files can fail to download due to connection issues. You can either run wabbajack again or download the file manually. If you decide to manually download it, make sure to place it in the same place as the other downloads.

- x is not a whitelisted download:

	 - This will happen when I update the modlist. Please check if there is a new update or wait until you see a release ping.

- Wabbajack could not find my game folder:

	- Either buy the game or go back to the [Pre-Installation](#pre-installation) step.

- Antivirus reports a virus:
	- Windows 10/11 may automatically quarantine a key file which is needed for Mod Organizer. You can fix this by [adding an exclusion for Mod Organizer in windows defender](https://www.thewindowsclub.com/exclude-a-folder-from-windows-security-scan).


# Requirements:

1) Legal copy of the latest Skyrim version (1.6.353)
2) Creation Kit from **Steam** installed into the same folder as Skyrim SE

# Credits:

Annakins for her great [tutorial](https://github.com/annakins/Skyrim) which this installer is based on
