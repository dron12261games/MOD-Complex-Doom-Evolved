# Complex Doom Evolved

# STATUS: 🏁WORK IN PROGRESS

### ⚠️WARNING!⚠️ This is a fork, not the original mod I built. The original (Complex Doom v27b2), authored by Deadalus, can be found [here](https://forum.zdoom.org/viewtopic.php?t=58535).
### ⚠️WARNING!⚠️The fork is still in development, so it may behave erratically at times. Keep this in mind.

## Download:
- [Complex Doom Evolved v1](https://github.com/Doom-Mapping-Modding-Lair-DRON12261/MOD-Complex-Doom-Evolved/releases/download/v1/Complex_Doom_Evolved_v1.pk3)
- [Russian Language patch for Zandronum](https://github.com/Doom-Mapping-Modding-Lair-DRON12261/MOD-Complex-Doom-Evolved/releases/download/v1/CDE_v1_RUS_Patch_for_Zandronum.pk3)

To run the patch, load it after the main mod and type in the console `language ru`.

## What this fork does:
- [x] Added cvar Pistol Start Bonus(cd_pistolstartbonus) - at the start in pistol start mode, the player will also have 100 green armor, 3 ammo satchels and a certain number (set by cvar below) weapon upgrade boxes.
- [x] Added cvar Pistol Start Bonus Upgrade Boxes Count(cd_pistolstartwubcount) - number of weapon upgrade boxes spawning in pistol start bonus mode.
- [x] The system of weapon upgrade boxes has been reworked - now you can choose one of three modes through cvar Weapon Upgrades Style(cd_weaponupgradesstyle):

  - `Old` - A random upgrade just falls out of the box;
  - `Checking the player's weapons` - Only the weapons that the player has are dropped from the box.
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

## What else is planned in the future:
- Bring refactoring to an end.
- Nerf some high-ranked mobs, like `Demon Tech Fiend` and `Abaddon` all sorts. At least reduce HP, because in many traps with them gameplay turns into a quicksave spam.
- Add an even more detailed pistol start configuration.
- Maybe make more changes regarding weapon upgrades, or add new ones.
- Nerf magnum, or rather make it a little more voracious, because it is a weapon with which half the game you can easily run (at least make a nerve magnum optional in the settings).
- Fix the Deathmatch mode.
- Fix spawners of mobs and other things in Deathmatch mode.
- And maybe something else...
