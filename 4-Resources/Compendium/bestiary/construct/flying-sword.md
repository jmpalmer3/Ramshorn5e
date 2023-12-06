---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mm
- monster/cr/1-4
- monster/size/small
- monster/type/construct
statblock: inline
aliases: ["Flying Sword"]
---
```statblock
"name": "Flying Sword"
"size": "Small"
"type": "construct"
"alignment": "Unaligned"
"ac": !!int "17"
"hp": !!int "17"
"hit_dice": "5d6"
"stats":
- !!int "12"
- !!int "15"
- !!int "11"
- !!int "1"
- !!int "5"
- !!int "1"
"speed": "0 ft., fly 50 ft. (hover)"
"saves":
  "Dexterity": !!int "4"
"damage_immunities": "poison, psychic"
"condition_immunities": "[blinded](4-Resources/Compendium/rules/conditions.md#blinded),\
  \ [charmed](4-Resources/Compendium/rules/conditions.md#charmed), [deafened](4-Resources/Compendium/rules/conditions.md#deafened),\
  \ [frightened](4-Resources/Compendium/rules/conditions.md#frightened), [paralyzed](4-Resources/Compendium/rules/conditions.md#paralyzed),\
  \ [petrified](4-Resources/Compendium/rules/conditions.md#petrified), [poisoned](4-Resources/Compendium/rules/conditions.md#poisoned)"
"senses": "blindsight 60 ft. (blind beyond this radius), passive Perception 7"
"languages": ""
"cr": "1/4"
"traits":
- "desc": "The sword is [incapacitated](4-Resources/Compendium/rules/conditions.md#incapacitated)\
    \ while in the area of an [antimagic field](4-Resources/Compendium/spells/antimagic-field.md).\
    \ If targeted by [dispel magic](4-Resources/Compendium/spells/dispel-magic.md),\
    \ the sword must succeed on a Constitution saving throw against the caster's spell\
    \ save DC or fall [unconscious](4-Resources/Compendium/rules/conditions.md#unconscious)\
    \ for 1 minute."
  "name": "Antimagic Susceptibility"
- "desc": "While the sword remains motionless and isn't flying, it is indistinguishable\
    \ from a normal sword."
  "name": "False Appearance"
"actions":
- "desc": "Melee Weapon Attack: dice: d20+3 (+3 to hit), reach 5 ft., one target.\
    \ Hit: dice: 1d8 + 1|avg (1d8 + 1) slashing damage."
  "name": "Longsword"
"source":
- "MM"
- "CoS"
- "PotA"
- "SKT"
- "TftYP"
- "ToA"
- "WDH"
- "WDMM"
- "GoS"
- "BGDIA"
- "EGW"
- "IDRotF"
- "TCE"
- "CM"
- "KftGV"
- "BMT"
"image": "4-Resources/Compendium/bestiary/construct/token/flying-sword.png"
```
^statblock
# [Flying Sword](4-Resources/Compendium/bestiary/construct/flying-sword.md)
*Source: Monster Manual p. 20, Tasha's Cauldron of Everything. Available in the SRD and the Basic Rules.*  

A flying sword dances through the air, fighting with the confidence of a warrior that can't be injured. Swords are the most common weapons animated with magic. Axes, clubs, daggers, maces, spears, and even self-loading crossbows are also known to exist in animated object form.

> [!quote]- A quote from Levity Quickstitch, halfling rogue  
> 
> Lyin' next to the chest were the bones of Cap'n Scornblade himself, still clutchin' his rusty sword. Imagine my surprise when the blade flew from his bony grasp! Still go the scar.

## Animated Objects

Animated objects are crafted with potent magic to follow the commands of their creators. When not commanded, they follow the last order they received to the best of their ability, and can act independently to fulfill simple instructions. Some animated objects (including many of those created in the Feywild) might converse fluently or adopt a persona, but most are simple automatons.

### Constructed Nature

An animated object doesn't require air, food, drink, or sleep. The magic that animates an object is dispelled when the construct drops to 0 hit points. An animated object reduced to 0 hit points becomes inanimate and is too damaged to be of much use or value to anyone.