Better Strife v0.2

Developed by Nash Muhandes

COMPATIBILITY
-------------

IWADs supported: Strife: Quest for the Sigil (1.2 - 1.31) and Strife: Veteran Edition.

Compatible with single player, and with Strife Coop Patch Project (https://forum.zdoom.org/viewtopic.php?f=43&t=71580)

May or may not be compatible with other Strife gameplay mods. I haven't played all of them, sorry. Try it for yourself and see.

FULL LIST OF CHANGES
--------------------

- Show level exit markers on the automap, and optionally on the 3D viewport (bring up the Objectives popup to show them; or optionally always show them (set it in the Options menu)).
- Show quest markers. Implementation is currently a little janky and will be improved in future. Like the exit markers, these can be shown either only on the automap, only when the Objectives popup is open, or always.
- Applies sprite billboarding for actors that, in my opinion, would benefit from it due to their visual profile: explosions and effects sprites, gibs and metal junk, alarm sprites, ceiling turrets, stalkers, sentinels, the alien spectres, item pickups.
- Merchants' max health lowered to the same amount as the peasants. The main reason for this change is so that merchants won't be shown to have a ridiculous amount of health when the game is played with an HP Bar mod. Plus it'd make sense for the merchants to have low health, given how weak they apparently are. They are still unkillable, however.
- For similar reasons to the above, the Oracle's max health has been bumped up to give the impression that it is a powerful being. Will still die in 1 hit, as per the game's original design.
- When jumping on the spot, the player will now "squat" after falling back to the ground. Mimics original Strife behavior.
- Changed the sound of the water fountain to something more pleasant-sounding (can be seen/heard just outside the entrance to the Programmer's Keep in MAP07). Used a sound from FreeSound.org (see credits file).
- Toggleable head-mounted flashlight, based on what is visible on StrifeGuy's player sprite. Either select the icon in the inventory bar and activate it, or bind a key in the Options menu (default is F on the keyboard). The inventory icon is added as a convenience to players who play with gamepads and don't have enough extra buttons to bind a key to it. Note: the spotlight only renders correctly in hardware rendering; in software rendering, it will appear as a normal radial light source. This is because GZDoom only renders spotlights correctly in hardware rendering.
- Quick Health hotkey, bindable in the Options menu (default is H on the keyboard). An attempt at bringing back the "Heal" key from the original game (it is shown in the help screen, after all)... although my implementation may be a bit different. In Better Strife, pressing H will attempt to use all available health items you have (except the surgery kit), until your health is maxed out.
- Gibs, glass and metal junk no longer disappear.
- Improved animated flowing river textures. Textures made by me, from scratch.
- Temporary fix for "prison pass duplicate" bug. GZDoom bug; has been reported: https://forum.zdoom.org/viewtopic.php?f=2&t=71863
- [Strife: Veteran Edition] Degnin ores will now move on the conveyor belts.

MAP-SPECIFIC CHANGES
--------------------

- Fix "leave Administration early" dead end" (https://doomwiki.org/wiki/Strife_dead_ends#Leave_Administration_early)
- Fixed incorrect teleporter floor texture offsets in the Borderlands (teleporter to the new Front Base), and also in the Abandoned Front Base.
- Fixed missing textures on the platform just before the entrance to The Programmer's Keep (lines 2778, 2779, 2780 and 2781).
- Fix Zombie conveyor belt buildup in MAP24.
- Fix missing textures in MAP16: Bishop's Tower (lines 2827 and 2660).

