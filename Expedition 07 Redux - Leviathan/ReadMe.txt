
¯⁠\⁠_⁠(⁠ツ⁠)⁠_⁠/⁠¯ (⁠⊙⁠_⁠◎⁠)

Expedition 07 Redux - Leviathan
===============================

This file is >> AlsoInProgress << and supervised by Polo & Nada.
It is playable for the most part but perhaps not yet 100% functional.
However, a majority of the rewards will be accessible from your other saves.

We're working on it.
[#NexusEntreprise™ owned by 16/16/16 & (⁠⊙⁠_⁠◎⁠) ]


Lore
-----
Leviathan traps Travellers inside a time loop, and offers a taste of roguelike gameplay. Difficulty is tuned to survival mode settings, and every death means a reset of the loop.

Changes to the SEASON_DATA_CACHE.json file
------
EndTimeUTC value --> 2893423600 (so that it can still be done today)
Added the ability to activate expedition via the Nexus desktop

Notes
------
Some expeditions start with tech in inventory slots. You need to move them.
If you need Polo to show you Atlas stations, he won't do it UNLESS you also ask him to show you black holes. Then you will see both on your galaxy map.
If you start your game in online mode after starting an offline expedition, your game will likely crash when you load it. Just close the game and go offline and everything should be fine.

Warning: This expedition has a milestone to die. If you do the milestone on Permadeath, your expedition and main save will be deleted!

Notice
------
The NMS Orbitals update seems to have broken this expedition. Specifically the "ResetSaveOnDeath" mechanic seems to break your save file. The patch below will remove the "reset save on death" mechanic. If your save is broken, you will need to use a save editor to fix it. Renaming the "ExpeditionContext" key (or deleting the object if you know what you're doing) in the JSON should work. Make a backup of your save first just in case.

Bug ?
---
None recorded to date. Let me know if you have one :p

How do you do it?
------------------
Simply copy/paste a file into a directory ... No modification/influence on saves !!! No intervention on game files ...

a) First of all, set your game software to "Offline".

b) Then, download the file "SEASON_DATA_CACHE.json" from the cache directory of the expedition you wish to redo.

c) Replace the file in your [cache] directory with the one you've just downloaded
-> Steam PC : %APPDATA%\HelloGames\NMS\cache
-> Steam Mac : ~/Library/Application Support/HelloGames/NMS/cache
-> MS Store/GOG : %APPDATA%\HelloGames\NMS\cache

d) Restart "No Man's Sky" in offline mode and start a new game "Expedition".



If you have any problems, please contact us =p
.Leodium & .CwMonkey
