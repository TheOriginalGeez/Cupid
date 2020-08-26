# Cupid

![Custom badge](https://img.shields.io/endpoint?url=https%3A%2F%2Fbuild.wabbajack.org%2Flists%2Fstatus%2Fcupid%2Fbadge.json)

![cupid-logo](cupid.png)

**This modlist contains sexual content and you need to be of legal age in your country**.

## What To Expect

Decent graphics, good performance, a tame but comprehensive SexLab experience and plenty of extra content to explore. Combat is challenging and fast paced, you progress fast  This list is built around installing and replacing: outfits, armor, pose animations, and SexLab animations. I will only provide support for installing outfits, poses, and additional SexLab animations.

## Requirements

- [Nexus Premium Account](https://forums.nexusmods.com/index.php?/store/category/1-premium-membership/)
- [LoversLab Account](https://www.loverslab.com/)
- [C++ Redist](https://aka.ms/vs/16/release/vc_redist.x64.exe)

You log into Nexus and LoversLab in the login manager located inside Wabbajack at the gear at the top. You can install this without a Nexus Premium Account but you will need to download everything manually.

### System Specs

- CPU: >= Intel Core i7-7700k OR >= AMD Ryzen 5 3600
- GPU: >= RTX 2060 OR >= RX 5700
- VRAM: >= 6GBs
- RAM: >= 8GBs

Everything should be installed on an SSD or HDD that has at least 150GBs of space available.

#### My Specs

- CPU: AMD Ryzen 5 3600
- GPU: RTX 2070 Super
- Game and list installed on a HDD.

## Installation

### Pre-Installation

#### Steam Settings

##### Disable the Overlay

The Steam Overlay causes issues with ENB and should be turned off.

Right click _The Elder Scrolls V: Skyrim Special Edition_ in your Library and click Properties, click the General tab and uncheck _Enable the Steam Overlay while in-game_.

##### Change Steams Update Behavior

Skyrim occasionally updates to add Creation Club content. When this happens many mods will break.

To prevent automatic updates from breaking your game reopen the Properties for SSE, click the Updates tab and change _Automatic updates_ to _Only update this game when I launch it_.

Disable the Steam Cloud too so steam doesn't automatically put saves into your Skyrim after every install.

##### Set the Game language to English

English is required for this list. Any other language than English will fail the installation.

Open the Skyrim Properties window, click the Language tab and select _English_ from the dropdown.

#### Clean Skyrim

Before installing this list you should uninstall the game through Steam, delete the game folder, delete the _Skyrim Special Edition_ folder inside `Documents/My Games` and reinstall Skyrim.

#### Start Skyrim

After you have done everything above and got a clean SSE installation ready, start the Launcher and open the _Options_ menu.

1) Click on _Ultra_
2) Set the _Aspect Ratio_ and _Resolution_ to your monitor's native values
3) Set _Antialiasing_ to _Off_
4) Check _Windowed Mode_ and _Borderless_

Then, start the game and exit once you're in the main menu.

### Using Wabbajack

#### Preparations

Create a _working folder_. This folder **must not** be in a common folder like your Desktop, Downloads or Program Files. It's best to create a Wabbajack folder near the root of your drive like `C:/Wabbajack`.

Grab the latest release of Wabbajack from [GitHub](https://github.com/wabbajack-tools/wabbajack/releases) and place `Wabbajack.exe` in the _working folder_.

#### Downloading and Installing

Downloading and installing this list can take a while depending on your specs. To get the fastest speeds put the working folder on an SSD.

1) Open Wabbajack.
2) Browse Modlists, check Show NSFW in the top right, and download Cupid.
3) Adjust the installation and download paths (EX: D:\Modding\Cupid , D:\Modding\SSEDownloads).
4) Click the start button.
5) Wait for Wabbajack to finish.

#### Problems with Wabbajack

There are lots of scenarios where Wabbajack can produce an error. Before asking for support try rerunning Wabbajack to continue from where you last left off.

**Could not download X**:

If a has been mod updated and its old files got deleted it is impossible to download them. In this case you will need to wait for me to update my list.

**X is not a whitelisted download**:

This can happen when I update the modlist. Check if a new update is available and wait if there is none.

**Wabbajack could not find my game folder**:

Wabbajack will not work with a pirated version of the game. If you own the game on Steam, go back to the [Pre-Installation](#pre-installation) step.

### Post-Installation

#### Copy Game Folder Files

Copy all of the files from the `MO2/Game Folder Files` directory to your game folder.

#### Installing the ENB

Download the latest version of the ENB files [here](http://enbdev.com/download_mod_tesskyrimse.htm) and extract the following files to the root folder of your Skyrim:

- `d3d11.dll`
- `d3dcompiler_46e.dll` 

#### Build BodySlide files

By default everything is fit to the Shiva body preset. 

NOTE: You DO NOT need to do this unless you have downloaded and installed additional outfits.

To build new bodyslides do the following:
- Open the big dropdown on the right side of MO2 and click edit.
- Select bodyslide and make sure MO2 is pointing to the correct location of BodySlide x64.exe (inside `Cupid\mods\BodySlide and Outfit Studio\CalienteTools\BodySlide`) then hit apply and close the window.
- Open Bodyslide through the icon on the top.
- Select the outfit to build on the very top.
- Select the preset to use just beneath that.
- Check Build Morphs on the bottom left.
- Click Build.

#### Nemesis

NOTE: You DO NOT need to do this unless you have downloaded and installed additional animations.

To build Nemesis for new animations do the following:
- Make sure _360 Movement Behavior SE_ is checked.
- Click Update Engine.
- Click Launch Nemesis Behavior Engine.

#### How to launch the game

Open _ModOrganizer.exe_ inside the Cupid installation folder, and select SKSE in the big dropdown on the right and click on the run button to the left of the dropdown. You can also click the shortcut button underneath the run button and click Desktop to add a desktop shortcut to launch the game from. Don't launch the game from Steam, don't launch the game from the Skyrim directory and don't launch from any installation of Mod Organizer 2 *other than the one installed by Wabbajack for CUPID*.

## Updating

If this Modlist receives an update, check the Changelog before doing anything. Always backup your saves or start a new game after updating.

**Wabbajack will delete all files that are not part of the Modlist when updating!**

This means that any additional mods you have installed on top of the Modlist will be deleted. Your downloads folder will not be touched!

Updating is like installing. You only have to make sure that you select the same path and tick the _overwrite existing Modlist_ button.

## Important Mods you should know about

This section contains information about the important mods in this list.

### Loading Screen Replacer

[AirplaneRandy's Erotica Replacer](https://www.loverslab.com/files/file/12278-airplanerandys-erotica-replacer-main-menuloading-screenintro-video/) is installed.

If you don't want lewd loading screens disable this mod in MO2.

### SexLab - Frameworks

[SexLab Framework](https://www.loverslab.com/topic/91861-sexlab-framework-se-163-beta-8-november-22nd-2019/) is the core of all installed LL mods. Do note that this is a **beta build**. [SLAL](https://www.loverslab.com/files/file/5328-sexlab-animation-loader-sse/) or _SexLab Animation Loader_ is included as well.

There is currently no creature support. This will change in the future.

### SexLab - Animations

- Milky SLAL
- Ayasato SLAL
- Leito SLAL

Default SexLab animations were removed and should be disabled after following the MCM set up. This was to add room for people to add their own SexLab animations and Poses. (Also I wasn't a fan of any of the default animations.)

### SexLab - Others

The following mods have a more _supportive_ role and do not fit any of the other categories.

- WetFunctionRedux (adds sweaty and wet effects to the body and increases in intensity under certain conditions)
- GenderBenderSE (easy futa support)

### Character Mods

I went with [CBBE 3BBB Advanced](https://www.nexusmods.com/skyrimspecialedition/mods/30174/).

[XMPSSE](https://www.nexusmods.com/skyrimspecialedition/mods/1988), [CBPC](https://www.nexusmods.com/skyrimspecialedition/mods/21224) and [HDT-SMP](https://www.nexusmods.com/skyrimspecialedition/mods/30872) are installed. For textures I used Bijin skin with Fair Skin Complexion's goosebump specular map and SSS textures.

[Schlongs of Skyrim](https://www.loverslab.com/files/file/5355-schlongs-of-skyrim-se/) and [Tempered Skins for Males](https://www.nexusmods.com/skyrimspecialedition/mods/7902) were used for the guys.

For futa I used [SOS Futanari Addon](https://www.loverslab.com/files/file/11344-sos-addon-futanari-cbbe-sse/)

### NPC Retextures

#### NPC Retextures (Major)

- Kalilies NPCs
- Pandorable's NPCs
- Bijin All in One

#### NPC Retextures (Minor)

- Fresh Faces SSE covers the rest of the faces.

### Followers

My favorite [Daedric Bitchs](https://www.nexusmods.com/skyrimspecialedition/mods/30549) are included.

### UI

For loading screens I went with [AirplaneRandy's Erotica Replacer](https://www.loverslab.com/files/file/12278-airplanerandys-erotica-replacer-main-menuloading-screenintro-video/)

[moreHUD](https://www.nexusmods.com/skyrimspecialedition/mods/12688) by [ahzaab](https://www.nexusmods.com/skyrimspecialedition/users/368196) and [SkyHUD](https://www.nexusmods.com/skyrimspecialedition/mods/463/) default preset.

### Outfit Mods

- BDO Arethel + Heled
- Osare Underwear
- Undies
- BDOR kibelius
- Astaroth Suit
- Mini Skirts Collection

For the vanilla clothes and armor I'm using BD's 3BBB Armor and Clothes replacer.

### Poses

If you created a sexy character or just wanna have some fun screenshotting stuff, you might want to use some pose mods. I put in [Poser Hotkeys Plus SSE](https://www.nexusmods.com/skyrimspecialedition/mods/17743) for the framework.

- GomaPeroPoses SE
- GSPoses
- Halos Poser

Halos Poser is disabled due to the animation limit. You can swap Goma or GSPoses for Halo and rebuild Nemesis to use it.

## Content For Screenshots

### New Places

I added a few modern looking places to the game incase anyone wanted to take screenshots or use SexLab there.

- GomaPeroLand SE
- Bathing Beauties Luxury Suite
- Aether Suite SE

## Creating your Character

Using [RaceMenu](https://www.nexusmods.com/skyrimspecialedition/mods/19080) you can create a character from scratch or use the default preset included as a baseline.

If you don't like the idle animation open the console, click on the player and use the `player.sae idlestaticposeastart` command.

## In-Game MCM Options

Once you're in-game, have created your character and want to start playing, you first need to configure the MCM. **Wait until no new messages appear in the top left corner!**

If you get no more messages, save the game and open the Mod Configuration Menu in the ESC menu.

When inside this menu press TAB to back out of any config screens.

### AGO

Set these to your personal preferences. (If you don't know what to change just disable persistent arrows.)

### Immersive Hud

In the _Activation_ tab under the _Compass Activation_ section enable _Key press toggles_.

In the same _Activation_ tab under the _SkyUI Active Effects_ section enable _Link ALL SkyUI Active Effects_.

In the _Options_ tab enable _Hide shout meter with compass_.

### Mass Match Maker SE

In the _Config_ tab set the _Solo Rate_ to 0%.

In the same _Config_ tab uncheck the following:

- Mass Matchmaker Area
- Mass Matchmaker Mass
- Mass Matchmaker Gangbang Self
- Mass Matchmaker Gangbang Target

### Schlongs of Skyrim

In the _General Settings_ tab under the _Global Settings_ section do the following:

- Set Min schlong size to 7.
- Set Max schlong size to 12.
- Set Schlong Size Multiplier to 125%.
- Disable Spells.
- Disable SOS Potions.

In the _Futanari CBBE_ tab set the _NPC schlong type probability_ to 0%.

### SexLab Installation

- Click INSTALL/UPDATE on the top right.
- Exit the menu back into the game and wait until the "SexLab v1.63 SE dev beta 8 - Ready!" message appears on the top left of your screen.
- Reopen the Mod Configuration Menu.

#### SexLab

In the _Animation Settings_ tab under the _Player Settings_ section do the following:

- Disable Auto Advance Stages. (This will make it so you manually advance the SexLab animation your character is involved by pressing space. If you want the game to automatically do this don't disable this option.)
- Enable Automatic Free Camera.
- Set the Free Camera Speed to 2.

In the same _Animations Settings_ tab under the _Extra Effects_ section do the following:

- Enable Apply Facial Expressions.
- Enable Play Ending Orgasm Effects.
- Enable Allow Female/Female Cum
- Set Cum Effect Time to 300 Seconds. (or whatever value you'd like)
- Set NPCs Use Beds to Sometimes.

In the same _Animations Settings_ tab under the _Animation Handling_ section do the following:

- Disable Restrict Aggressive Animations.
- Change Females Use Strap-ons to your preference. (If you keep Strap-ons enabled disable the Calyps Strap-on in the rebuild and clean section of the SexLab MCM.)

In the _Voices & SFX_ tab do the following:

- Set Voice Volume to 50%.
- Set Male Voice Delay to 9s.

In the same _Voices & SFX_ tab under the _Toggle Voices_ _**DISABLE**_ the following:

- Classic (Female)
- Young (Female)
- Quiet (Female)
- Stimulated (Female)
- Excitable (Female)

### SLAL

In the _General Options_ tab do the following:

- Click Enable ALL.
- Click Register Animations.
- Wait until a popup appears that says "Registered X new animations"
- Hit Accept to close the popup.

### Gender Bender

In the _General_ section do the following:

- Enable Mod Active.
- Back out of the MCM all the way to in-game.
- Wait until it's finished activating. (10 seconds)
- Go back into the Gender Bender MCM menu.
- Set Gender Quick Change to Mouse 3.

### Poser Hotkeys Plus

In the _Hotkeys_ tab set Show Pose to Mouse 4.

### Ultimate Combat and TK Dodge

These mods are both completely up to preference. I recommend turning off Swing Effect in Ultimate Combat at the least and then setting the health ratios to whatever you want. A bigger timed block window can be nice and if you want extra damage on headshots increase the slider. Or just disable all the features of both mods if you'd like, up to you. A good dodge keybind is Mouse 5.

### ABMM

In the _Settings_ tab set _Minimum NPC Arousal_ to 60%.
in the _Settings_ tab set _Minimum Player Arousal_ to 0%.
In the _More_ tab disable _Horny Idle_.

### No Overpenetration

Tick _Enabled_.

### PC Head Tracking

This is all up to you, if unsure just ignore.

### Quick Light

Set _Type of Light Source_ to _No Special Effect_.
Set _Brightness_ to _Bright_.
Disable _Enable to Long Press Activation Key_.

### SexLab Aroused

In the _Settings_ tab in the _Arousal_ section set _Cell Scan Frequency Seconds_ to 30.
In the _Settings_ tab in the _General_ section disable _Require naked actors to change arousal_.

### SLA Monitor Widget

In the _Widget Looks_ tab in the _Widget Position_ section set _Vertical Offset_ to 60pts.

### SexLab Eager NPCs

In the _General_ tab in the _SLEN Status_ section enable _Mod Enabled_.
In the same tab in the _SLEN Dialogues_ section enable _Charm Dialogue_.
In the same tab in the _Virtual Sexlife_ section set _NPCs have a sexlife_ to All NPCs.

### SexLab Cumshot

In the _General_ tab in the _General Settings_ section set Cum Opacity to 0.50.
In the same tab in the same section disable Show final drip.

## In-Game Instructions

- Save the game to save your MCM settings.
- Activate the Statue of Mara.
- Scroll down and hit "I am the owner of the Luxury Suite."
- Turn behind you, walk up the steps and sleep in the bed.

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

You can use this spell to teleport to a HUB with many different modern locations.

You can get to Goma Pero Land by fast traveling to it through the map.

Now go have some fun.

## Adding more Mods

### Textures

Textures are by far the easiest mods to install. Simply install the mod and check what other mods (if any) change the same textures in MO2. The only textures that could be problematic are landscape/environment textures like new mountain textures.

#### Skin Textures

You can easily replace the skin textures with no issues. I recommend leaving Fair Skin Complexion enabled in MO2 to keep the better teeth, SSS, and specular textures.

If you want, take a look at [this](https://www.loverslab.com/topic/137830-easy-way-to-make-seamless-sos-textures/) post on how to make seamless SOS textures for the Futa schlong.

### Meshes

Similar to [Textures](#textures) just slap them into MO2. Just be careful that those new meshes are for outfits as those should be compatible with the character body of this setup (see [Character Mods](#character-mods)).

### Animations

New animations can be easily added depending on the category. You have to differentiate between [SLAL Animations](#slal-animations) and [Normal Animations](#normal-animations). The former being animations for Sexlab and the latter being animations like [Pretty Sit Idles](https://www.nexusmods.com/skyrimspecialedition/mods/10399).

#### SLAL Animations

[SLAL](https://www.loverslab.com/files/file/5328-sexlab-animation-loader-sse/) or _Sexlab Animation Loader_ requires special animations. You should only install additional Sexlab animations if they are made for SLAL.

Simply install them and re-run Nemesis.

#### Normal Animations

Simply install the new animations and re-run FNIS. You might want to consider adding [Project New Reign - Nemesis PCEA](https://www.nexusmods.com/skyrimspecialedition/mods/31667) if you want those new animations to be player exclusive.

### Pose Mods

You can disable GSPoses, and or GomaPeroPoses to enable Halos Poser.

Just re-run Nemesis when you decide what combo to run with.

### Outfits

Another category of mods you can easily add to this setup. You only have to make sure that the outfits fit the character body (see [Character Mods](#character-mods)). It's also a good idea to find BodySlide files for that outfit so you can customize it.

Simply install any outfits through MO2 and build them with morphs to the preset you want inside BodySlide.

### ENB

The weather mod used in this Modlist is [Obsidian Weathers and Seasons](https://www.nexusmods.com/skyrimspecialedition/mods/12125) and the lighting mod is [Enhanced Lights and FX](https://www.nexusmods.com/skyrimspecialedition/mods/2424). If you want to swap out the ENB, make sure that it is compatible with Obsidian Weathers and looks decent with ELFX.

Other ENBs that work with Obsidian Weathers:

- [Rudy ENB](https://www.nexusmods.com/skyrimspecialedition/mods/4796)
- [NVT](https://www.nexusmods.com/skyrimspecialedition/mods/11203)
- [Apex](https://www.nexusmods.com/skyrimspecialedition/mods/18042)

## Uninstalling

You can just remove the MO2 folder. Don't forget to uninstall the files you copied to the game folder as well as your ENB and Silent Horizons if you're no longer using them.

## Contact

You can always reach me on the [Wabbajack Discord](https://discord.gg/wabbajack). **DO NOT DM ME ON DISCORD. I WILL NOT PROVIDE SUPPORT FOR YOU IN DMS AND I WILL BLOCK YOU IF NECESSARY**.
