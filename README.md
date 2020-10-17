![Custom badge](https://img.shields.io/endpoint?url=https%3A%2F%2Fbuild.wabbajack.org%2Flists%2Fstatus%2Fcupid%2Fbadge.json)

![cupid-logo](cupid.png)

**This modlist contains sexual content and you need to be of legal age in your country**.

**Small disclaimer:** You need to read the whole readme. I've tried my best to be as concise as possible. It is crucial that you read this in it's entirety to properly install and play the list.

# Important

**If you are on a 2.0.X update and you want to update to 2.4.0 you must make a new save (if you're on any 1.X.X update you DEFINITELY need to make a new save) stuff *will* break, even if you're not aware of it.**

**If it's not in this readme don't do it. A few tools come with this for people that know what they're doing. There is no reason to launch any tools if you just want the default Cupid experience. Everything works right out of the box.**

### READ THE [FAQ](https://github.com/TheOriginalGeez/Cupid/blob/master/FAQ.md)

# What To Expect

Decent graphics, good performance, a tame but comprehensive SexLab experience and plenty of extra content to explore. Combat is fast and challenging but very fair, you progress and level fast. I no longer provide support for adding anything to the list.

# Requirements

- [Nexus Premium Account](https://forums.nexusmods.com/index.php?/store/category/1-premium-membership/)
- [LoversLab Account](https://www.loverslab.com/)
- [C++ Redist](https://aka.ms/vs/16/release/vc_redist.x64.exe)

You log into Nexus and LoversLab in the login manager located inside Wabbajack at the gear at the top. You can install this without a Nexus Premium Account but you will need to click a couple hundred download buttons.

## Recommended Specs

- CPU: >= Intel Core i5-8400 OR >= AMD Ryzen 5 2600
- GPU: >= GTX 1070 OR >= RX 580
- VRAM: >= 6GBs
- RAM: >= 8GBs

Everything should be installed (preferably) on a SSD or HDD that has at least 150GBs of space available.

### My Specs

- CPU: AMD Ryzen 5 3600
- GPU: RTX 2070 Super
- Game and list installed on a SSD.

# Pre-Installation

## Disable the Overlay

The Steam Overlay causes issues with ENB and should be turned off.

Right click _The Elder Scrolls V: Skyrim Special Edition_ in your Library and click Properties, click the General tab and uncheck _Enable the Steam Overlay while in-game_.

## Change Steams Update Behavior

Skyrim occasionally updates to add Creation Club content. When this happens many mods will break.

To prevent automatic updates from breaking your game reopen the Properties for SSE, click the Updates tab and change _Automatic updates_ to _Only update this game when I launch it_.

Disable the Steam Cloud too (if you'd like) so steam doesn't automatically put saves into your Skyrim after every install.

## Set the Game language to English

English is required for this list. Any other language than English will fail the installation.

Open the Skyrim Properties window, click the Language tab and select _English_ from the dropdown.

## Clean Skyrim

Before installing this list you should uninstall the game through Steam, delete the game folder, delete the _Skyrim Special Edition_ folder inside `Documents/My Games` and reinstall Skyrim.

**Please do this.**

Especially if you have modded your game before and aren't sure what you're doing. Having old modding files in there can and will break your game.

## Start Skyrim

After you have done everything above and got a clean SSE installation ready, start the Launcher and open the _Options_ menu.

1. Click on _Ultra_
2. Set the _Aspect Ratio_ and _Resolution_ to your monitor's native values
3. Set _Antialiasing_ to _Off_
4. Check _Windowed Mode_ and _Borderless_

(Don't worry too much about these values. The values will get overwritten anyway during installation.)

Then, start the game and exit once you're in the main menu.

# Using Wabbajack

## Preparations

Create a _working folder_. This folder **must not** be in a common folder like your Desktop, Downloads or Program Files. It's best to create a Wabbajack folder near the root of your drive like `C:/Wabbajack`.

Grab the latest release of Wabbajack from [the Wabbajack site](https://wabbajack.org) and place `Wabbajack.exe` in the _working folder_.

## Downloading and Installing

Downloading and installing this list can take a while depending on your specs. To get the fastest speeds put the working folder on an SSD.

1. Open Wabbajack.
2. Browse Modlists, check Show NSFW in the top right and download Cupid.
3. Adjust the installation and download paths (EX: D:\Modding\Cupid , D:\Modding\SSEDownloads).
4. Click the start button.
5. Wait for Wabbajack to finish.

## Problems with Wabbajack

There are lots of scenarios where Wabbajack can produce an error. Before asking for support try rerunning Wabbajack to continue from where you last left off.

### Could not download X:

If a has been mod updated and its old files got deleted it is impossible to download them. In this case you will need to wait for me to update my list.

### X is not a whitelisted download:

This can happen when I update the modlist. Check if a new update is available and wait if there is none.

### Wabbajack just closed on me. Is it finished?

No, it has crashed and you will need to try again.

### Wabbajack could not find my game folder:

Wabbajack will not work with a pirated version of the game. If you own the game on Steam, go back to the [Pre-Installation](#pre-installation) step.

# Post-Installation

## Copy Game Folder Files

- Navigate back to your Cupid installation folder.
- Open "Game Folder Files"
- Copy everything inside the Game Folder Files folder.
- Paste it into your Skyrim SE directory.
  * Just to clarify, since there has been some confusion: there is a folder installed by Wabbajack called "Game Folder Files." The contents of this folder are what you need to copy into your Skyrim folder. Not the folder itself, and definitely not everything that Wabbajack installed on your PC. It's just a few .dll files, skse_loader, things like that. It's only about 4 MBs of files.

## Installing the ENB

Download the latest version of the ENB files [here](http://enbdev.com/download_mod_tesskyrimse.htm) and extract the following files to the root folder of your Skyrim:

- `d3d11.dll`
- `d3dcompiler_46e.dll`

**The ENB preset I use comes in the Game Folder Files folder. If you want to use another ENB make sure it's compatible with Skyrim Special Edition and it's for Obsidian Weathers.**

## Rebuilding BodySlide files

NOTE: This is only for people who want to change the shape of the body from Cupid's default one. Skip this unless you understand what this does.

- Open the big dropdown on the right side of MO2 and click edit.
- Select bodyslide and make sure MO2 is pointing to the correct location of BodySlide x64.exe (inside `Cupid\mods\BodySlide and Outfit Studio\CalienteTools\BodySlide`) then hit apply and close the window.
- Run Bodyslide after selecting it in the big dropdown.
- Click the magnifying glass icon in the text box above the save button on the top of Bodyslide.
- Click "Choose Groups..."
- Make sure only the "Clothes" group is checked.
- Select the preset you want to use in the Preset dropdown on the top.
- Check Build Morphs on the bottom left.
- Click "Batch Build..."
- Click "Build"
- Click "Ok"
- Repeat the process but this time making sure only the "Naked Body" group is checked.

# How to launch the game

Open _ModOrganizer.exe_ inside the Cupid installation folder, and select SKSE in the big dropdown on the right and click on the run button to the left of the dropdown. You can also click the shortcut button underneath the run button and click Desktop to add a desktop shortcut to launch the game from. Don't launch the game from Steam, don't launch the game from the Skyrim directory and don't launch from any installation of Mod Organizer 2 *other than the one installed by Wabbajack for CUPID*.

# Updating

If this Modlist receives an update, check the Changelog before doing anything. Always backup your saves or start a new game after updating.

**Wabbajack will delete all files that are not part of the Modlist when updating!**

This means that any additional mods you have installed on top of the Modlist will be deleted. Your downloads folder will not be touched!

Updating is like installing. You only have to make sure that you select the same path and tick the _overwrite existing Modlist_ button.

# There *is* a NSFW Loading Screen Replacer. It does not show on the first loading screen.

[AirplaneRandy's Erotica Replacer](https://www.loverslab.com/files/file/12278-airplanerandys-erotica-replacer-main-menuloading-screenintro-video/) is installed.

If you don't want lewd loading screens disable this mod in MO2.

# Cupid Guide

## Creating your character

Using [RaceMenu](https://www.nexusmods.com/skyrimspecialedition/mods/19080) you can create a character from scratch or use the default presets included as a baseline (one is for a high elf the other is for a nord. Both are for females).

To use presets select the presets tab on the top right, press the load presets button and select the preset you want. You can also save your presets here.

Hold down the right mouse button to rotate your character.

If you want your character to stay still open the console, click on yourself and use the `player.sae idlestaticposeastart` command.

## Disabling the vanilla Depth of Field.

- Press Esc.
- Go to Settings > Display.
- Move the "Depth of Field" slider all the way down to 0.
- Tab out of this menu until you're back in the game.

## In-Game MCM Options

Once you have created your character and want to start playing, you first need to configure the MCM. *Do not exit the Alternate Start Prison Cell* **and wait until no new messages appear in the top left corner!**

Once you're not seeing any more messages, open the Mod Configuration Menu in the ESC menu.

**When inside this menu press TAB to back out of any config screens.** ***If you click on an MCM menu and it does not appear back out of all the menus (wait for any messages to disappear) and try again.***

### AGO

- Settings
  - Arrow Wounds (Player): Disabled
  - Arrow Wounds (NPCs): Disabled
  - Persistent Arrows: Disabled

### CGO

- Settings
  - Unlocked Grip
    - Hotkey: Personal preference. I recommend "G".
  - Dodge Roll
    - Enable iFrames: Enabled
  - Leaning
    - Lean Multiplier (1st Person): 0.50
    - Lean Multiplier (3rd Person): 0.75
  - Camera Noise
    - Camera Noise Mult (1st Person): 0.00

### Immersive HUD

- Activation
  - Compass Activation
    - Key press toggles: Enabled
  - SkyUI Active Effects
    - Link ALL SkyUI Widgets: Enabled

### No Overpenetration

- Enabled: Enabled

### PC Head Tracking

This makes your character look at whatever you last pointed your crosshair at. Sometimes your character will stare at things across the whole room, but it works 80% of the time. If you don't like the sound of this mod, skip this section.

- Head Tracking
  - ON/OFF: Enabled
  - Humanize: Enabled
- Exception Filter
  - Inanimate Actors: Enabled
- Facial Expression
  - ON/OFF: Enabled

### Quick Light

- Type of Light Source: Magic
- Brightness: Bright
- Enable to Long press activation key: Disabled

### Schlongs Of Skyrim

- General Settings
  - Global Settings
    - Min schlong size: 7
    - Max schlong size: 12
    - Schlong size multiplier: 150%
    - SOS potions: Disabled
    
### SexLab

- Install
  - Click INSTALL/UPDATE SEXLAB 1.63 SE DEV BETA 8
    - Tab back out into the game.
    - Wait until it says "SexLab - SexLab v1.63 SE dev beta 8 - Ready!" in the top left.
    - Come back into the SexLab MCM.
    
- Sex Diary
  - Sexual Stats
    - Sexuality: Personal preference, choose your characters sexuality.
- Animation Settings
  - Player Settings
    - Auto Advance Stages: Disabled
    - Automatic Free Camera: Enabled
    - Free Camera Speed: 1
  - Extra Effects
    - Apply Facial Expressions: Enabled
    - Play Ending Orgasm Effects: Enabled
    - Allow Female/Female Cum: Enabled
- Voices & SFX
  - Male Voice Delay: 9 Seconds
- Rebuild & Clean
  - Available Strap-ons
    - Click REMOVE on the Calyps Strapon.

### SexLab Aroused

- Settings
  - General
    - Require naked actors to change arousal.: Disabled.
    - Enable SOS: Enabled

### SexLab Cumshot

- General
  - General settings
    - Cum opacity 0.50
    - Show final drip: Disabled

### SexLab Eager NPCs

- General
  - SLEN Status
    - Click "Enable and set defaults".
    
### SexLab Solutions

- Miscellaneous
  - Integration
    - SLEN integration: Enabled
    
### SL Anim Loader

- General Options
  - SexLab Animation Loader SSE
    - Click "Enable All" then click Accept.
    - Click "Register Animations" and wait until a window pops up then click Accept.

### SLA Monitor Widget

- Widget Looks
  - Widget position
    - Vertical anchor: Center
    
### TDF Aroused Idles

- Settings
  - Threshold Settings
    - Threshold 1: 59
    - Threshold 2: 79
    - Threshold 3: 100
    
### Ultimate Combat

- General
  - Timed Block
    - Effective Time: 0.00S
    - Blur Strength: 0.0
  - Game Balance Settings
    - Speed Bonus: Disabled
  - Others
    - Swing Effect: Disabled
  - Stagger
    - Enemy Poise: Disabled
    - Player Stagger: Disabled
    - NPC's Bow Poise: 0.00
    - Player's Bow Poise: 0.00
  - Locational Damage
    - Headshot Damage Mult: 0.0
    - Headshot Message: Disabled
    - Locational Damage Sound: Disabled
    - Locational Damage Effect: Disabled
- NPC Setting
  - NPC
    - Dodge: Click this until it says "DISABLE".
  - Giant
    - Max HP Scale: 1.0
  - Dwarven Centurion
    - HP Mult: 1.0
  - Dragon Priest
    - HP Mult: 1.0

### Unread Books Glow
- $UBG Book Glow: Click it until it says "$UBG BRIGHT"
- $UBG Plain Books: Disabled

### ZaZ Animation Pack

This is a hardcore BDSM animation pack and framework. Don't enable it if you aren't into it.

- SexLab
  - SexLab Integration
    - SexLab Animations: Click REGISTER and wait until it says REGISTERED.

*You are now done with MCM settings. Continue reading.*

## In-Game Instructions

- Save the game to save your MCM settings.
- Activate the Statue of Mara.
- Scroll down and choose whatever option you would like. (My preference is to choose the Arrived by Boat > Solitude option. You will be prompted to start LOTD once you spawn in.)
- Turn behind you, walk up the steps and sleep in the bed.

Once you're in the game DISABLE the Weapon Speed Fix in the Weapon Speed Fix MCM. Exit back into the game. Then go back and reenable it. **THIS IS VERY IMPORTANT.**

### Setting Up Initial Inventory and Spells

- Open your inventory.
- Click on \[AddItemMenuSE Pack]
- Take all 4 items.
- Reopen your inventory.
- Click on both spell tomes.
- Go to your magic menu.
- Select \[AddItemMenuSE - Search]
- Exit the menu.

Now when you shout (or press Z by default) you can search for any item, armor, clothing etc. in the game.

- Search for "Aether Suite"
- Take the Aether Suite Spell Tome
- Click on the spell tome in your inventory.

You can use this spell to teleport to a HUB with many different modern locations. Useful for screenshots, doesn't have any quests or purpose for gameplay. Same with Goma Pero Land.

You can get to Goma Pero Land by fast traveling to it through the map.

Now go have some fun.

# Uninstalling

You can just remove the MO2 folder. Don't forget to uninstall the files you copied to the game folder as well.

# Contact

Join [my Discord server](https://discord.gg/XTfvnAh) to get the most immediate help. **Please do not DM me, I will not respond**.
