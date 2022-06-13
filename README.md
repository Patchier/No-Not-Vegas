# My Kind of Courier

October 22nd, 2021 - Full Install: ~40GB.

**Modlist Download: [My kind of Courier.wabbajack](https://drive.google.com/drive/folders/1lYxE8Zg5wcI5Cn6mYuMdVyhRlWGnH8iU)**

**Modlist Support: [The Animonculory Server](https://discord.gg/DffHKcszfg)**


## OVERVIEW

This ReadMe is designed to help you with installing and beginning your adventures across the US, including Vegas, Reno, and even the Capitol Wasteland.

## GOALS

-  Install and setup My Kind of Courier

-  The overall goal of MKoC is to introduce fans of New Vegas to New Reno and the intrigue surrounding "The Biggest Little City in the World". 

## NOTABLE MODS

Tales of New Reno - An expansive series of mods based around the city of New Reno. A work-in-progress, but an excellent one nonetheless. Expect to see New Reno herself in Episode 3!

Bleedless - A modified version of the excellent BLEED mod, along with its damage scaling optional plugin, means that combat is far less of a slugging match, and more a game of "don't get shot". 

Stewie Tweaks - My own custom take on Stewie Tweaks, forked from Qolore's. Fast travel requires working legs, pickpocketing is improved, and even just entering VATS requires AP. Effort takes energy. Who knew?!

Stash Organizer - In any interior cell, or player-owned exterior cell, press the VATS key on any contained to start what is probably the best sorting mod known to man. I actually recommend reading it yourself so you can see what all it does. Check it out [here](https://eddoursul.win/mods/stash-organizer/).

I have also set JIP to separate headgear DR/DT from body armor DR/DT, and to allow NPCs (including enemies) to get sneak attack criticals. Aim for the head, and keep yours covered!

## SPECIFICATIONS

- Stewie's Tweaks:
M to open the map
J to open the quest journal

- JIP Companions Command & Control:
C to open the companion menu
Mousewheel to scroll through options
Middle mouse button to activate options

- Stash Organizer:
VATS key on an interior container

## First off, you will need:

-   A clean, fresh, and LEGAL GOG or Steam installation of Fallout: New Vegas

-   40GB free to install the list itself

## Install Fallout: New Vegas

- This part is self-explanatory. You'll want to go to the installation of the game, and remove all files present in the install folder (For example, steamapps/common/Fallout New Vegas) AND the Documents folder (Documents/My Games/FalloutNV).

### Uninstalling the game

If you have the games installed under `C:\Program Files\`, `C:\Program Files (x86)\`, your Desktop, or your Documents folders, follow these steps to remove it.

#### Steam

1. Open **Steam** and go to your **Library**.
2. Find **Fallout: New Vegas** in the list.
3. Right-click on it and select **Manage** -> **Uninstall**.
4. Navigate to `Steam\steamapps\common\` and, if present, delete the **Fallout New Vegas** folder.

#### GOG

1. Open **GOG** and go to your **Library**.
2. Find **Fallout: New Vegas** in the list.
3. Right-click on it and select **Manage Installation** -> **Uninstall**.
4. Navigate to where the game was installed (`GOG Galaxy\Games` by default) and, if present, delete the **Fallout New Vegas** folder.

### Making a new Steam Library

If you already have a Steam library set up outside of any default Windows folder, or you have the game on GOG, skip this step.

A new Steam library needs to be set up to install the game on, as the default library is in a default Windows UAC-protected folder (`C:\Program Files (x86)\Steam`).

1. Open **Steam** and select **Steam** -> **Settings** in the top left.
2. In the **Downloads** tab, select **Steam Library Folders**.
3. Select **Add Library Folder** and select a location outside of any default Windows folders.
   * For example, `C:\Games\Steam`.
4. Exit out of the settings when you are finished.

By default, Steam only allows one library per drive, but there is a workaround. If for example you already have the default Steam library at `C:\Program Files (x86)\Steam`, but still want your game on your `C:\` drive, you will need to follow [these instructions](https://github.com/LostDragonist/steam-library-setup-tool/wiki/Usage-Guide) to do so.

- While you're here, run the games once each, and after the launcher has detected your graphics settings, make any special adjustments you need, then you may close out of it. We just needed those initial INIs to be created.

Install My Kind of Courier via Wabbajack: 
----------------------------------------- 

1.  Download My Kind of Courier from my G-Drive (you've probably already done this part, but if not, link is at the top): 

2.  After that, you will choose an installation folder (I recommend something like "D:/My Kind of Courier", substituting D: for any drive available.) This CANNOT be where Wabbajack.exe is located, nor your Fallout New Vegas or Fallout 3 folder.

3.  Downloads will auto-populate for you, but you can change that location if you so choose. 

4.  From there, just click the "play" button and let it do the rest. If you do not have Nexus Premium, you will have to follow along to the manual download prompts.

5. Once the list has finished installing, open the folder you installed it to, and proceed to the "Game Folder Files" folder. 

6. Copy the items inside of the Game Folder Files folder to your Fallout: New Vegas installation location (excluding the NVHR folder). (NOTE: NOT THE FOLDER ITSELF, JUST WHAT'S IN IT.)

7. Inside the New Vegas Heap Replacer folder within the game folder files directory, run the EXE. Then, copy the d3dx9_38.dll from whichever folder it tells you into your Fallout: New Vegas installation location. Overwrite if asked.

8. Once the files are copied over, run the FalloutNVpatch.exe. This will patch your New Vegas exe to be Large Address Aware, letting you enjoy the list with a severely decreased risk of crashing.

9. IMPORTANT: IF YOU'RE USING GOG, DELETE THE FNV-Lang.esp PLUGIN. 

## Starting the game

Once you've finished installing, simply navigate to your installation folder for the modlist and open ModOrganizer.exe. After that, you may launch the game via the New Vegas option, which should be selected for you in the top right corner. If not, simply choose it from the drop-down and click "run". If the launcher comes up to do graphics settings again, simply set your preferred settings, then exit out of the launcher and launch the game agan.
