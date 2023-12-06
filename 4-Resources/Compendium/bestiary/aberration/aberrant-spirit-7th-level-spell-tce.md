---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tce
- monster/cr/
- monster/size/medium
- monster/type/aberration
statblock: inline
aliases: ["Aberrant Spirit (7th-level Spell)"]
---
```statblock
"name": "Aberrant Spirit (7th-level Spell) (TCE)"
"size": "Medium"
"type": "aberration"
"alignment": "Unaligned"
"ac": !!int "18"
"hp": !!int "70"
"stats":
- !!int "16"
- !!int "10"
- !!int "15"
- !!int "16"
- !!int "10"
- !!int "6"
"speed": "30 ft., fly 30 ft. (beholderkin only; hover)"
"damage_immunities": "psychic"
"senses": "darkvision 60 ft., passive Perception 10"
"languages": "Deep Speech, understands the languages you speak"
"traits":
- "desc": "The aberration regains 5 hit points at the start of its turn if it has\
    \ at least 1 hit point."
  "name": "Regeneration (Slaad Only)"
- "desc": "At the start of each of the aberration's turns, each creature within 5\
    \ feet of the aberration must succeed on a Wisdom saving throw against your spell\
    \ save DC or take dice: 2d6|avg (2d6) psychic damage, provided that the aberration\
    \ isn't [incapacitated](4-Resources/Compendium/rules/conditions.md#incapacitated)."
  "name": "Whispering Aura (Star Spawn Only)"
"actions":
- "desc": "The aberration makes a number of attacks equal to half this spell's level\
    \ (rounded down)."
  "name": "Multiattack"
- "desc": "Ranged Spell Attack: the summoner's spell attack modifier to hit, range\
    \ 150 ft., one creature. Hit: 1d8 + 3 + summonSpellLevel psychic damage."
  "name": "Eye Ray (Beholderkin Only)"
- "desc": "Melee Weapon Attack: the summoner's spell attack modifier to hit, reach\
    \ 5 ft., one target. Hit: 1d10 + 3 + summonSpellLevel slashing damage. If\
    \ the target is a creature, it can't regain hit points until the start of the\
    \ aberration's next turn."
  "name": "Claws (Slaad Only)"
- "desc": "Melee Spell Attack: the summoner's spell attack modifier to hit, reach\
    \ 5 ft., one creature. Hit: 1d8 + 3 + summonSpellLevel psychic damage."
  "name": "Psychic Slam (Star Spawn Only)"
"source":
- "TCE"
"image": "4-Resources/Compendium/bestiary/aberration/token/aberrant-spirit.png"
```
^statblock
# [Aberrant Spirit (7th-level Spell)](4-Resources/Compendium/bestiary/aberration/aberrant-spirit-7th-level-spell-tce.md)
*Source: Tasha's Cauldron of Everything p. 109*