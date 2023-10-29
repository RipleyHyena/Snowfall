# Snowfall
Requiem Lite for those that don't have much time to play. Focus is on immersion and roleplaying without tedious micromanagement or silly menuing. Accessibility regarding hardware and controller use are considered. 

### Warnings! 

- Those with epilepsy can and should disable Storm Lightning (Minty SSE), as well as True Storms and its compatibility patch.


![image](placeholder)

Wabbajack Modlist Installer by RipleyHyena

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
      - [Downloading and Installing Snowfall](#downloading-and-installing-Snowfall)
      - [Problems with installation](#problems-with-installation)
  - [Post-Installation](#post-installation)
    - [Post Processing](#post-processing)
  - [Playing the List](#playing-the-list)
    - [Starting up the list](#starting-up-the-list)
    - [In Game MCM Options](#in-game-mcm-options)
  - [Updating Snowfall](#updating-the-modlist)
  - [FAQ](#faq)
   - [Removing the modlist](#removing-the-modlist)
  - [Credits and Thanks](#credits-and-thanks)
  - [Contact](#contact)

## Preamble
Extremely light Requiem for Skyrim AE edition, with all Creation Club Content support.

This work is licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

## System Requirements

4GB VRAM minimum

## Installation

Installing Snowfall is relatively easy and, if you have Nexus Premium, will be a simple waiting game. If you are updating the modlist, you can safely skip to the [updating section](#updating).

### Pre-Installation

Prior to installing Snowfall, please complete the following steps.

1. Install [Visual C++ x64](https://aka.ms/vs/16/release/vc_redist.x64.exe) & [.Net Runtime v5 desktop x64](https://dotnet.microsoft.com/download/dotnet/5.0/runtime).
2. Change Skyrim so it does not [automatically update](https://help.steampowered.com/en/faqs/view/71AB-698D-57EB-178C#disable).
3. Fully uninstall Skyrim by deleting the folder and the Skyrim Special edition folder inside \Documents\My Games\.
4. Reinstall Skyrim into a location that is not Program Files. Somewhere like `C:\Games` is a good location.
5. Start the game once and let it do the graphics check. Do not worry about the settings as it will be replaced during installation.
6. Install the [Creation Kit on steam](https://store.steampowered.com/app/1946180/Skyrim_Special_Edition_Creation_Kit/).
7. Run it once and select `NO` when it asks about unpacking scripts.
8. Close the creation kit and continue with the installation steps.

### Wabbajack Installation

#### Installing Wabbajack

Once you have completed pre-installation, download the [latest version of Wabbajack]((https://github.com/wabbajack-tools/wabbajack/releases)) and place it in a folder such as `C:\Games\Wabbajack`. Do not place it in program files, on your desktop or in your downloads folder. I recommend placing it on an SSD as it will work quicker on there.

#### Downloading and Installing Snowfall

Downloading and installing Snowfall can take a while depending on your internet connection and computer. To install Snowfall, complete the following steps.

1. Open Wabbajack and click on browse modlists.
2. Press the download button on Snowfall and wait for it to download.
3. Set the installation folder to be somewhere like `C:\Games\Snowfall`. **Do not install it to your desktop or downloads folder.**
4. The download location does not need to be on a SSD but it makes installing a bit faster
5. Press the play button to begin.
6. probably read through this readme again.
7. If the installation is successful, jump for joy and move onto [post installation](#post-installation). If the installation is unsuccessful, follow what is below.

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

## Post-Installation

### BethINI

You will need to use BethINI to set your monitors screen resolution, and screenshot location. 

1. Go to where you have installed the list and open the tools folder.
2. Open the BethINI folder and run the program.
3. Set your resolution.
4. Choose whether you want borderless/windowed or Fullscreen.
5. Press save and exit.

### Post Processing
Snowfall does not come with any ENB or Reshade. Community shaders with Light Limit fix and other support mods are used instead.

## Playing the List

### Lights

Hold E or A/X button on gamepad to turn on a nifty lantern. Do the same with nothing targeted to turn it off. 

### Starting up the list
Open the installation folder and double click on the program called `ModOrganizer.exe`. 

Make sure the dropdown box on the right is set to `SKSE` and press the `Run` button.

### In-Game MCM options

- Most have been automated for you, or are player choice.
- Open your Magic Menu when you load in to start Requiem.
	
## Adding mods to Snowfall

If you want some general tips on how to safely mod, visit the [Modding Tutorials](https://github.com/The-Animonculory/Modding-Resources) repository.

### Anniversary Edition

Snowfall supports the latest verison of Skyrim, **and requires** the paid update. Why? Because I paid for backpacks and want them in my list.

## Updating the modlist

Before updating, please check the changelog and back up your saves. You may need to start a new game after certain updates.

Updating is like installing the list. Simply make sure your paths are the same and tick the `overwrite existing modlist` button. **Note**: Any mods you have added will be deleted when updating.

## FAQ

## Removing the Modlist
Simply delete the folder, and you have uninstalled it.

## Credits and Thanks

- _YOU_ for reading this.
- The Animonculory Team.
  
- Phoenix for Legends of the Frost, upon which I forked here, and learned how AE lists are handled. I took too long of a break from Skyrim and Wabbajack, and their list proved invaluable as a jumping off point.

- Halgari and the WJ Team - Wabbajack is awesome and so are you.

## Contact

Whilst I am available primarily on [Aetherius Modding](placeholder), please check the [issues](https://github.com/RipleyHyena/Snowfall/issues) tab on github first if you have any issues. DO NOT DM ME ON DISCORD. DO NOT STALK ME ON GITHUB.

## The Animonculory Team
- Althro - Leader & Head of Development
- Styyx - Senior Management Team & Dev Team
- Chef/Para0x - Senior Management Team & Dev Team
- The Spaniard -Senior Management Team & Documentation
- GuitarBarbarian - Senior Management Team
- Annakins - Dev Team, Testing, Graphics & Documentation
- Astro - Dev Team & Testing
- DestinySlayer - Dev Team & Community Engagement
