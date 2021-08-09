![](https://img.shields.io/badge/Foundry-v0.8.8-informational)
[Latest Release Download Count](https://img.shields.io/github/downloads/Kandashi/Dynamic-Effects-SRD/latest/module.zip)
[Forge Installs](https://img.shields.io/badge/dynamic/json?label=Forge%20Installs&query=package.installs&suffix=%25&url=https%3A%2F%2Fforge-vtt.com%2Fapi%2Fbazaar%2Fpackage%2FDynamic-Effects-SRD&colorB=4aa94a)

# Dynamic-Effects-SRD
A compendium pack for SRD items, feats etc configured for use with Dynamic Active Effects.

The partner module to this, the <a href="https://github.com/kandashi/midi-srd/" target="_blank">Midi-SRD</a> has all of these items and all the SRD spells configured for use with Midi QOL

--


## Magic Items module is now included in the compendium packs
- Compendium pack is named SRD Magic Items


**V0.05** Level 1 spells and cantrips finished

**V0.0.6** Most SRD Items finished, excluding more complicated macro items

**V0.0.7** Spell macros cleaned up, spell removal macro added and spell storage method moved to actor.data to save between scenes

**V0.1.0** Most higher level spells without macro effects have been added. Macros now have the option to be stored within the item itself (thanks to the Item Macro functionality)  

**V0.2.0** Updated to DAE and 0.7.5 compatibility, removed item macros (you can add/edit them yourself if you really need to) 

**V0.2.1-6** Various fixes and updates

**V3.0.0** Added support for Magic Items

**V3.0.2** 
- Fixed Staff of Power, Broom of Flying, Boots of Speed, Boots of Striding and Springing, Potion of Flying, Aid and Haste, reworked Longstrider, Slow, Spiderclimb and Fly to not require macros.
- Boots of Levitation moved to Magic Items
- Added Wings of Flying

IF you want to support me my patreon is here https://www.patreon.com/Kandashi

**V3.0.3**
- Fix for various armour priority mis-matches with core DAE

**V4.0.0**
- Updated a lot of spells/items to fall in line with DnD5e 1.2.0, Midi 0.3.35 and DAE 0.2.28
- Added experimental version of Bracers of Archery, Alter Self and Deamon Armor to take use of the item effects from DAE
- Added Dust of Disappearance, Goggles of Night, Horseshoes of Speed, Boots of Elvenkind
- Added Midi versions of Invisibility and Heroes' Feast for timeouts and advantage on wis saves
- Updated Blindness/Deafness to not require a macro
- Added specific damage types for Divine Favour
- Added Contagion, Divine Word (requires About Time), Faerie Fire, Feeblemind, True Strike spells, all require Midi some need CUB (Contagion and Divine Word)
- Added "summon" spells: Flame Blade, Moonbeam these create items in the actors inventory to avoid "repeat casting"
- Added Ray of Enfeeblement, Regenerate (requires About Time) spells, True Strike
- Changed Rage name to fix with replacements/importers
- Reworked Unarmored Defense to be a singe name with 2 different effects, delete as required

**V4.0.3**
- Fixed Unarmoured Defense (Monk)
- Fixed Heroes' Feast macro (thanks to Lyra)

**V4.1.0**
- [BREAKING] All DAE SRD macro spells now almost require Times Up for correct removal, it will not prevent use, but lots of the spells require its functionality now
- [BREAKING] All DAE SRD spells now use Item Macros. This **does not** require you to install that module. The spells will now run without importing any macros at all
- Added Arcane Sword, Beacon of Hope, Call Lightning, Confusion, Faerie Fire, Flesh to Stone, Grease, Misty Step, Irresistible Dance and Warding Bond
- Fixed Moonbeam and Cloak of Displacement

**V4.1.08**
- Fixed Slippers of Climbing, Wings of Flying, Spider Climb, Invisibility spells and cleaned up spare versions
- Added Web
- Added Bug Reporter compatibility https://github.com/League-of-Foundry-Developers/bug-reporter

**V4.1.13**
-Fixed Spiritual Weapon, Magic Weapon. 
- Added Potion of Heroism


**V5.0.00**
-0.8.6 updates
-Sickening Radiance spell removed, use Active Auras for this instead
- small bug fixes, invisibility now whispers to the user and GM instead of announcing publicly

**V6**
- All Midi items/spells etc have been moved to the MIDI SRD
