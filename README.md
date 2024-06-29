# ELDEN RING HKS repository

Contains various HKS files for ELDEN RING.

HKS (HavokScript) serves as an interface between player/AI inputs and influences the animations and behavior of the respective chr model.

* `c0000.hks`: The interface between player inputs and the player character.
* `c8000.hks`: The HavokScript file for Torrent.
* `c9997.hks`: A HavokScript file applying to all enemies.

The HKS is decompiled using the latest build of [katalash's DSLuaDecompiler](https://github.com/katalash/DSLuaDecompiler), then manually cleaned up and "prettified" for a better end-user experience. Additionally, some small changes are made to better support custom weapon skills.

With input by the community this project may grow in scope.

## Credits

* katalash: DSLuaDecompiler
* Vawser: Main effort of making the decompiled HKS usable in-game
* AshenOne: Early fixes to faulty ExecMagic decompilation
* Kirnifr: Early fixes to faulty Torrent decompilation
* Halvard: Updates for 1.10.1
* Lord Exelot: Rebasing the HKS on the latest raw decompilation, updates for 1.12.1
* ividyon: Better support for custom Ashes of War, general maintenance