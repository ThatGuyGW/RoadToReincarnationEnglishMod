# Road To Reincarnation English Mod

An English Mod for the Cultivation Game "轮回修仙路"

## Installation

Download the latest .7z file from the Releases section

https://github.com/ThatGuyGW/RoadToReincarnationEnglishMod/releases

Extract the archive and drag and drop the entire contents into your game folder.

You'll know the mod is working if the first splash screen has a line of text at the bottom that ends with (ENG Mod Enabled!)

**If you're updating from a version prior to 1.2.0.0, you'll need to delete the "Project1.dll" file from "BepInEx\Plugins"**

On the first run of the game with the mod installed, the game will crash. This is an expected crash due to how the game handles metadata changes at runtime, and it will only happen once. After the initial crash, you can launch the game  without issue.

## Warning regarding Updates

**Playing with the English Mod while using an un-modified metadata file has the potential to cause Save Corruption when switching to a modified Metadata file. If you proceed with your save before a full update is out, you do so at your own risk. We advise you backup your saves manually by copying the files at "AppData\LocalLow烟水寒轮回修仙路\GameDataSave_Steam" to another location.**

## Notes

As this is an initial release, please be aware that it's very likely that upcoming releases or game updates could entirely break your savegame with little to no chance of recovery.

The mod has a large performance cost on game start and new save generation. 
After that, there may be a performance impact, but Cadenza tried to keep it as low as possible. Further optimization is possible if people are enjoying the game. 

When you'll first run the game with the mod, it will take time to start. That's not related to the mod. It's just BepinEx getting ready. It's a first-time only operation.
 
You need to make sure your number-related regional settings are set to CH or US. The game will hang on starting a new game if not. This is not mod-related.

## Troubleshooting

If the mod isn't working for you please look for any of the below log files and raise them as as issue either on the GitHub Issue Page or in the AMA Discord channels for Road to Reincarnation:

In the 轮回修仙路 folder, any .log files with "preloader" in the name.

In the BepInEx folder, any .log files

In your Appdata Folder (Accessible on Windows machines by using the Windows Key + R, typing in "%AppData%" without the ", and then navigating to the "LocalLow" folder. The 烟水寒\轮回修仙路 folder will contain log folders.

## Credits

Thanks to "JeremieCHN" for their code which Cadenza ruthlessly stole to complete the Metadata overwrite functionality 
