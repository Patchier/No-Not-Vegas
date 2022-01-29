# My Kind of Courier

October 22nd, 2021 - Full Install: ~54GB.

## OVERVIEW

This ReadMe is designed to help you with installing and beginning your adventures in New Vegas, with a few friends along.

## GOALS

-  Install and make minor configuration to Fallout: New Vegas.

-  Install and get started with My Kind of Courier!

## SPECIFICATIONS

- This list does not have any specific MCM tweaks, but it DOES have an extra step during the installation phase. Be sure to follow ALL instructions.

## First off, you will need:

-   A clean, fresh, and LEGAL GOG or Steam installation of Fallout: New Vegas w/ all DLCs

-   55GB free to install the list itself

## Install Fallout: New Vegas

- This part is self-explanatory. You'll want to go to the installation of the game, and remove all files present in the install folder (For example, steamapps/common/Fallout New Vegas) AND the Documents folder (Documents/My Games/FalloutNV)

### Uninstalling the game

If you have the game installed under `C:\Program Files\`, `C:\Program Files (x86)\`, your Desktop, or your Documents folders, follow these steps to remove it.

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

- While you're here, run the game once, and after the launcher has detected your graphics settings, you may close out of it. We just needed those initial INIs to be created. They will be superceded by the ones in my modlist.

Install My Kind of Courier via Wabbajack: 
----------------------------------------- 

1.  Download My Kind of Courier from my G-Drive (you've probably already done this part): 

2.  After that, you will choose an installation folder (I recommend something like "D:/My Kind of Courier", substituting D: for any drive available.) This CANNOT be where Wabbajack.exe is located, nor your Fallout New Vegas folder.

3.  Downloads will auto-populate for you, but you can change that location if you so choose. 

4.  From there, just click the "play" button and let it do the rest. If you do not have Nexus Premium, you will have to follow along to the manual download prompts.

5. Once the list has finished installing, open the folder you installed it to, and proceed to the "Game Folder Files" folder. 

6. Copy the items inside of the Game Folder Files folder EXCEPT THE NEW VEGAS HEAP REPLACER FOLDER to your Fallout: New Vegas installation location. (NOTE: NOT THE FOLDER ITSELF, JUST WHAT'S IN IT.)

7. Inside the New Vegas Heap Replacer folder within Game Folder Files, run the EXE. Then, copy the d3dx9_38.dll from whichever folder it tells you into your Fallout: New Vegas installation location. Overwrite if asked.

8. Once the files are copied over, run the FalloutNVpatch.exe. This will patch your New Vegas exe to be Large Address Aware, letting you enjoy the list with a severely decreased risk of crashing.

9. IMPORTANT: IF YOU'RE USING GOG, DELETE THE FNV-Lang.esp PLUGIN. 

## Decompress your BSAs
-------------------------

1. In your My Kind of Courier installation folder, there will be folder labelled "Tools". Open it.

2. Open the folder labelled "BSA Decompressor", and double-click on "FNV BSA Decompressor.exe"

3. when the program opens, it should default to your New Vegas installation folder. If it does not, click "Browse", and navigate there, then click "Ok".

4. Run the program. It will take a little while, but trust me, it will be worth it. Afterwords, close out of the program.

## Starting the game

Once you've finished installing the modlist, simply navigate to your installation folder for the modlist, open ModOrganizer.exe, and launch it via the New Vegas option, which should be selected for you. If not, simply choose it from the drop-down and click "run". If the launcher comes up to do graphics settings again, simply set your preferred settings, then exit out of the launcher and launch the game agan.

## MCM Settings

This list includes several mods which utilize hotkey shortcuts. I have no real recommendations regarding these, but I advise you look through the few MCMs there are and set up keybinds however you wish.
