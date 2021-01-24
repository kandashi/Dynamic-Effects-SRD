# Dynamic-Effects-SRD
A compendium pack for SRD items, spells, feats etc configured for use with Dynamic Active Effects, MQoL, Furnace and About Time/Times Up
--

### Anything with an X next to the name is currently broken

### DAE is 100% required.

### MQoL and sometimes Furnace are needed for auto effect application 
Effects without macro calls do not need Furnace. For MQoL, the setting "Auto apply Active Effects to targets" must be enabled for any "Active Effect" to correctly apply to the target. Some sort of Auto-Check for hit/save must also be enabled to apply the effects:
![Midi Settings 1](https://github.com/kandashi/Dynamic-Effects-SRD/blob/master/Images/Midi%20Settings.PNG)
![Midi Settings 2](https://github.com/kandashi/Dynamic-Effects-SRD/blob/master/Images/Midi%20Settings%202.PNG)
![Furnace Settings](https://github.com/kandashi/Dynamic-Effects-SRD/blob/master/Images/Furnace%20Settings.PNG)

### About Time or Times Up are required for auto effect removal.
Without About Time or Times Up (or for effects that finish before their full time; navigate to the Active Effects tab of the effected actor and remove the Active Effect manually.

## Core Macros
To use any of the macro style effects you **must** import the following macros from the compendium: 
* ActorSetFlag
* ActorUnSetFlag
* ActorGetFlag
* ActorUpdate
* TokenUpdate
* CUB Condition

## Spells that require macros
- Aid, Alter Self, Banishment, Blindness/Deafness
- Darkvision, Enhance Ability, Enlarge/Reduce, Eyebite
- Fireshield, Haste, Heroes Feast, Heroism
- Invisibility, Greater Invisibility, Levitate, Longstrider
- Magic Weapon, Protection from Energy
- Shillelagh, Slow


## Magic Items module is now included in the compendium packs
- Compendium pack is named SRD Magic Items




**V0.05** Level 1 spells and cantrips finished

**V0.0.6** Most SRD Items finished, excluding more complicated macro items

**V0.0.7** Spell macros cleaned up, spell removal macro added and spell storage method moved to actor.data to save between scenes

**V0.1.0** Most higher level spells without macro effects have been added. Macros now have the option to be stored within the item itself (thanks to the Item Macro functionality)  

**V0.2.0** Updated to DAE and 0.7.5 compatability, removed item macros (you can add/edit them yourself if you really need to) 

**V0.2.1-6** Various fixes and updates

**V3.0.0** Added support for Magic Items

**V3.0.2** 
- Fixed Staff of Power, Broom of Flying, Boots of Speed, Boots of Striding and Springing, Potion of Flying, Aid and Haste, reworked Longstrider, Slow, Spiderclimb and Fly to not reqiuire macros.
- Boots of Levitation moved to Magic Items
- Added Wings of Flying

IF you want to support me my patreon is here https://www.patreon.com/Kandashi

**V3.0.3**
- Fix for various armour priority mis-matches with core DAE

**V4.0.0**
- Updated a lot of spells/items to fall in line with DnD5e 1.2.0, Midi 0.3.35 and DAE 0.2.28
- Added experimental version of Bracers of Archery, Alter Self and Deamon Armor to take use of the item effects from DAE
- Added Dust of Disappearance, Goggles of Night, Horseshoes of Speed, Boots of Elvenkind
- Added Midi versions of Invisibility and Heroes' Feast for timeouts and advanatage on wis saves
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
- added Arcane Sword
