# Dynamic-Effects-SRD
A compendium pack for SRD items, spells, feats etc configured for use with Dynamic Effects, MQoL, Furnace and About Time
--
### DE is 100% required.

### MQoL and Furnace are needed for auto effect application 
Effects without macro calls do not need Furnace. For MQoL, the setting "Auto apply Active Effects to targets" must be enabled for any "Active Effect" to correctly apply to the target.

### About Time is required for auto effect removal.
Without About Time (or for effects that finish before their full time; concentration broken etc) there is a SpellRemoval macro that will give a popup-selection of what macro-style effects are currently on the target. Select the appropriate one, and click "OK" to remove the macro's effects.

For non-macro effects, there is a macro in the standard DE macro compendium for removal of active effects.

### Item Macro
Due to the imbeded nature of Item Macro macros, you do not need Item Macro to be installed to make use of them. The *DE SRD Spells Contained* compendium contains these style of spells, they are just plug and play. All you need to do is to import the core macros to your directory. To *edit* there macros will require Item Macro however.

## Core Macros
To use any of the macro style effects you **must** import the following macros from the compendium: 
* ActorSetFlag
* ActorUnSetFlag
* ActorGetFlag
* ActorUpdate
* TokenUpdate




**V0.05** Level 1 spells and cantrips finished

**V0.0.6** Most SRD Items finished, excluding more complicated macro items

**V0.0.7** Spell macros cleaned up, spell removal macro added and spell storage method moved to actor.data to save between scenes

**V0.1.0** Most higher level spells without macro effects have been added. Macros now have the option to be stored within the item itself (thanks to the Item Macro functionality)  
