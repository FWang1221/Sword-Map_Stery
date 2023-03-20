# Sword-Map_Stery
A file loader "jukebox" for multiple map files utilizing modengine and the fact that maps are hot reloaded really easily. Should work for ER, Sekiro, and DS3 but was designed with only ER in mind.

Just download and unpack.

So this is the mapGen map jukebox addon for mods. Put this in your mod folder so it should be mod/mapGen and then just run the batch file.

The create backups option is kinda unreliable if you didn't undo your changes beforehand because it backs up all contents of mod/map/MapStudio and mod/event directly to the backups folder. So be sure to also backup manually and to a different directory.

In order to add more maps just go to mapGen\SwordMap_stery\SwordMap_stery\bin\Debug\netcoreapp3.1 and add a new folder. Look inside errb or swordmas to see what's up. You make a new event folder, stuff in your map events, and a new map/MapStudio folder and shove in your map files. You can then call the new files to load in-game by typing in the name, like "vanilla" or "errb" (without the quotes, obviously).

To see changes reflected in-game, just go through a loading screen. Note that some things may be borked in the maps due to a) the emevd calling common or common_funcs, which aren't reloaded until you quit to start screen, or b) missing npcparams, speffect params, and so on.

However, this map jukebox should work damn well with most mods with little effort.

Packaged within are the vanilla, Swordmas, and ERRB Stormveil maps and scripts.

Plus it's cool as fuck.

Planned features to come:

Chalice Dungeon mode

Random Gauntlet mode

(both above prolly gonna hafta use SF for that)

Random Map Selection

Code Cleanup and Better Annotations
