# Complex Doom Evolved
![LOGO](https://i.ibb.co/fXbqYR6/MDOOMHD.png)

# STATUS: 🏁WORK IN PROGRESS

### ⚠️WARNING!⚠️ This is a fork, not the original mod I built. The original (Complex Doom v27b2), authored by Deadalus, can be found [here](https://forum.zdoom.org/viewtopic.php?t=58535).
### ⚠️WARNING!⚠️The fork is still in development, so it may behave erratically at times. Keep this in mind.

## Download (**⚠️UNSTABLE⚠️**):
- [Complex Doom Evolved v0.1](https://github.com/Doom-Mapping-Modding-Lair-DRON12261/MOD-Complex-Doom-Evolved/releases/download/v0.1/Complex_Doom_Evolved_v0.1.pk3)
- [Russian Language patch v0.1 for Zandronum](https://github.com/Doom-Mapping-Modding-Lair-DRON12261/MOD-Complex-Doom-Evolved/releases/download/v0.1/CDE_v0.1_RUS_Patch_for_Zandronum.pk3)

To run the patch, load it after the main mod and type in the console `language ru`.

## What this fork does:
- [x] Added cvar Pistol Start Bonus(cd_pistolstartbonus) - at the start in pistol start mode, the player will also have 100 green armor, 3 ammo satchels and a certain number (set by cvar below) weapon upgrade boxes.
- [x] Added cvar Pistol Start Bonus Upgrade Boxes Count(cd_pistolstartwubcount) - number of weapon upgrade boxes spawning in pistol start bonus mode.
- [x] The system of weapon upgrade boxes has been reworked - now you can choose one of three modes through cvar Weapon Upgrades Style(cd_weaponupgradesstyle):

  - `Old` - A random upgrade just falls out of the box;
  - `Checking the player's weapons` - Only the weapons that the player has are dropped from the box;
  - `Portable upgrades` - A random upgrade just drops out of the box, but now it is a portable active inventory item.
  
- [x] Also, now all gameplay cvars are saved in the config (I'm tired of re-plugging them after each restart).
- [x] Removed replacement for commander kin.
- [x] Full refactoring of the project.
- [x] Russian localization (including zandronum).
- [x] Changed the working of quick mines, grenades, and kicks - now they work with Any weapon, without the need to write a separate code for each weapon for quick action.
- [x] Because of the innovation above, the unique animations for throwing a mine/grenade or kick under each weapon are gone (at least until I figure out how to implement them in conjunction with that standalone QuickAction system).
- [x] Now the grenade flies exactly in the crosshairs.
- [x] Mines no longer explode on each other.
- [x] Mines no longer bounce off of actors.
- [x] Mines now track their target much more steadily.
- [x] An upgrade for mines appeared: Stunning mines.
- [x] The animation of the first revolver pickup can now be skipped.
- [x] The shotgun upgrade animation can now be skipped.
- [x] The upgrade animation for the Assault Shotgun can now be skipped.
- [x] Now portable weapon upgrades are not picked up if the player already has that upgrade installed on the weapon.
- [x] Reworked hotkeys and brought to an adequate state (their number was reduced from 7 to 3):
	- Alternate fire of weapon enhancements is now on `RMB`;
	- Railgun sight is now on the `RMB`;
	- `Quick Grenade Throw` and `Quick Melee` for normal player and terminator now on the same key;
	- Reload now on the `R` key (guns without alternate fire mode also on the `RMB`).
- [x] Rebalancing the revolver.
- [x] Added the ability to configure in detail the spawn types of mobs. You can disable the type of monster to prevent his spawn in the future on the map. If, for example, all of the mobs, replacing a single vanilla will be disabled, then in place of a vanilla monster just nobody will spawn, with softlock on maps on the type MAP07, E1M8, E2M8, E3M8, etc. will not happen.
- [x] Changed the color palette of the menu.
- [x] Fixed bug with incomplete reloading of the gun with an empty clip.
- [x] The grenade and mine on slot 1 as separate weapons have been brought to appropriate condition.
- [x] Added 4 new box types, more powerful loot from which falls with a rarer chance:
	- `Weapon Box` (Orange);
	- `Item Box` (Green);
	- `PowerUPs Box` (Blue);
	- `Perks Box` (White).
- [x] The boxes are now illuminated.
- [x] Now all bullets fly at the level of the crosshair, not below. Now there will be no situations where you can't shoot from a high window or balcony.

## What else is planned in the future:
- Bring refactoring to an end.
- Nerf some high-ranked mobs, like `Demon Tech Fiend` and `Abaddon` all sorts. At least reduce HP, because in many traps with them gameplay turns into a quicksave spam.
- Add an even more detailed pistol start configuration.
- Maybe make more changes regarding weapon upgrades, or add new ones.
- Fix the Deathmatch mode.
- Fix spawners of mobs and other things in Deathmatch mode.
- And maybe something else...

# Screenshots:
![Screen1](https://i.ibb.co/w672fzC/Screenshot-Doom-20230326-142853.png)
![Screen2](https://i.ibb.co/j3C5Nr9/Screenshot-Doom-20230326-142942.png)
