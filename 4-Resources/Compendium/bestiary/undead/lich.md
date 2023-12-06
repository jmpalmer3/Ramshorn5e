---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mm
- monster/cr/21
- monster/size/medium
- monster/type/undead
statblock: inline
aliases: ["Lich"]
---
```statblock
"name": "Lich"
"size": "Medium"
"type": "undead"
"alignment": "Any Evil alignment"
"ac": !!int "17"
"hp": !!int "135"
"hit_dice": "18d8 + 54"
"stats":
- !!int "11"
- !!int "16"
- !!int "16"
- !!int "20"
- !!int "14"
- !!int "16"
"speed": "30 ft."
"saves":
  "Wisdom": !!int "9"
  "Intelligence": !!int "12"
  "Constitution": !!int "10"
"skillsaves":
  "Insight": !!int "9"
  "Perception": !!int "9"
  "History": !!int "12"
  "Arcana": !!int "19"
"damage_resistances": "cold, lightning, necrotic"
"damage_immunities": "poison; bludgeoning, piercing, slashing from nonmagical attacks"
"condition_immunities": "[charmed](4-Resources/Compendium/rules/conditions.md#charmed),\
  \ [exhaustion](4-Resources/Compendium/rules/conditions.md#exhaustion), [frightened](4-Resources/Compendium/rules/conditions.md#frightened),\
  \ [paralyzed](4-Resources/Compendium/rules/conditions.md#paralyzed), [poisoned](4-Resources/Compendium/rules/conditions.md#poisoned)"
"senses": "truesight 120 ft., passive Perception 19"
"languages": "Common plus up to five other languages"
"cr": "21"
"traits":
- "desc": "The lich is an 18th-level spellcaster. Its spellcasting ability is Intelligence\
    \ (spell save DC 20, dice: d20+12 (+12 to hit) with spell attacks). The lich\
    \ has the following wizard spells prepared:\n\nCantrips (at will): [mage hand](4-Resources/Compendium/spells/mage-hand.md),\
    \ [prestidigitation](4-Resources/Compendium/spells/prestidigitation.md), [ray\
    \ of frost](4-Resources/Compendium/spells/ray-of-frost.md)\n\n1st level (4 slots):\
    \ [detect magic](4-Resources/Compendium/spells/detect-magic.md), [magic missile](4-Resources/Compendium/spells/magic-missile.md),\
    \ [shield](4-Resources/Compendium/spells/shield.md), [thunderwave](4-Resources/Compendium/spells/thunderwave.md)\n\
    \n2nd level (3 slots): [detect thoughts](4-Resources/Compendium/spells/detect-thoughts.md),\
    \ [invisibility](4-Resources/Compendium/spells/invisibility.md), [Melf's acid\
    \ arrow](4-Resources/Compendium/spells/melfs-acid-arrow.md), [mirror image](4-Resources/Compendium/spells/mirror-image.md)\n\
    \n3rd level (3 slots): [animate dead](4-Resources/Compendium/spells/animate-dead.md),\
    \ [counterspell](4-Resources/Compendium/spells/counterspell.md), [dispel magic](4-Resources/Compendium/spells/dispel-magic.md),\
    \ [fireball](4-Resources/Compendium/spells/fireball.md)\n\n4th level (3 slots):\
    \ [blight](4-Resources/Compendium/spells/blight.md), [dimension door](4-Resources/Compendium/spells/dimension-door.md)\n\
    \n5th level (3 slots): [cloudkill](4-Resources/Compendium/spells/cloudkill.md),\
    \ [scrying](4-Resources/Compendium/spells/scrying.md)\n\n6th level (1 slots):\
    \ [disintegrate](4-Resources/Compendium/spells/disintegrate.md), [globe of invulnerability](4-Resources/Compendium/spells/globe-of-invulnerability.md)\n\
    \n7th level (1 slots): [finger of death](4-Resources/Compendium/spells/finger-of-death.md),\
    \ [plane shift](4-Resources/Compendium/spells/plane-shift.md)\n\n8th level (1\
    \ slots): [dominate monster](4-Resources/Compendium/spells/dominate-monster.md),\
    \ [power word stun](4-Resources/Compendium/spells/power-word-stun.md)\n\n9th\
    \ level (1 slots): [power word kill](4-Resources/Compendium/spells/power-word-kill.md)"
  "name": "spells"
- "desc": "If the lich fails a saving throw, it can choose to succeed instead."
  "name": "Legendary Resistance (3/Day)"
- "desc": "If it has a phylactery, a destroyed lich gains a new body in dice: 1d10|avg\
    \ (1d10) days, regaining all its hit points and becoming active again. The new\
    \ body appears within 5 feet of the phylactery."
  "name": "Rejuvenation"
- "desc": "The lich has advantage on saving throws against any effect that turns undead."
  "name": "Turn Resistance"
"actions":
- "desc": "Melee Spell Attack: dice: d20+12 (+12 to hit), reach 5 ft., one creature.\
    \ Hit: dice: 3d6|avg (3d6) cold damage. The target must succeed on a DC\
    \ 18 Constitution saving throw or be [paralyzed](4-Resources/Compendium/rules/conditions.md#paralyzed)\
    \ for 1 minute. The target can repeat the saving throw at the end of each of its\
    \ turns, ending the effect on itself on a success."
  "name": "Paralyzing Touch"
"legendary_actions":
- "desc": "The lich casts a cantrip."
  "name": "Cantrip"
- "desc": "The lich uses its Paralyzing Touch."
  "name": "Paralyzing Touch (Costs 2 Actions)"
- "desc": "The lich fixes its gaze on one creature it can see within 10 feet of it.\
    \ The target must succeed on a DC 18 Wisdom saving throw against this magic or\
    \ become [frightened](4-Resources/Compendium/rules/conditions.md#frightened) for\
    \ 1 minute. The [frightened](4-Resources/Compendium/rules/conditions.md#frightened)\
    \ target can repeat the saving throw at the end of each of its turns, ending the\
    \ effect on itself on a success. If a target's saving throw is successful or the\
    \ effect ends for it, the target is immune to the lich's gaze for the next 24\
    \ hours."
  "name": "Frightening Gaze (Costs 2 Actions)"
- "desc": "Each non-undead creature within 20 feet of the lich must make a DC 18 Constitution\
    \ saving throw against this magic, taking dice: 6d6|avg (6d6) necrotic damage\
    \ on a failed save, or half as much damage on a successful one."
  "name": "Disrupt Life (Costs 3 Actions)"
"source":
- "MM"
- "CoS"
- "GoS"
- "IDRotF"
- "TCE"
- "PSI"
- "SatO"
- "ToFW"
- "BMT"
"image": "4-Resources/Compendium/bestiary/undead/token/lich.png"
```
^statblock
# [Lich](4-Resources/Compendium/bestiary/undead/lich.md)
*Source: Monster Manual p. 202, Tasha's Cauldron of Everything. Available in the SRD.*  

Liches are the remains of great wizards who embrace undeath as a means of preserving themselves. They further their own power at any cost, having no interest in the affairs of the living except where those affairs interfere with their own. Scheming and insane, they hunger for long-forgotten knowledge and the most terrible secrets. Because the shadow of death doesn't hang over them, they can conceive plans that take years, decades, or centuries to come to fruition.

A lich is a gaunt and skeletal humanoid with withered flesh stretched tight across its bones. Its eyes succumbed to decay long ago, but points of light burn in its empty sockets. It is often garbed in the moldering remains of fine clothing and jewelry worn and dulled by the passage of time.

## Secrets of Undeath

No wizard takes up the path to lichdom on a whim, and the process of becoming a lich is a well-guarded secret. Wizards that seek lichdom must make bargains with fiends, evil gods, or other foul entities. Many turn to Orcus, Demon Prince of Undeath, whose power has created countless liches. However, those that control the power of lichdom always demand fealty and service for their knowledge.

A lich is created by an arcane ritual that traps the wizard's soul within a phylactery. Doing so binds the soul to the mortal world, preventing it from traveling to the Outer Planes after death. A phylactery is traditionally an amulet in the shape of a small box, but it can take the form of any item possessing an interior space into which arcane sigils of naming, binding, immortality, and dark magic are scribed in silver.

With its phylactery prepared, the future lich drinks a potion of transformation-a vile concoction of poison mixed with the blood of a sentient creature whose soul is sacrificed to the phylactery. The wizard falls dead, then rises as a lich as its soul is drawn into the phylactery, where it forever remains.

## Soul Sacrifices

A lich must periodically feed souls to its phylactery to sustain the magic preserving its body and consciousness. It does this using the [imprisonment](4-Resources/Compendium/spells/imprisonment.md) spell. Instead of choosing one of the normal options of the spell, the lich uses the spell to magically trap the target's body and soul inside its phylactery. The phylactery must be on the same plane as the lich for the spell to work. A lich's phylactery can hold only one creature at a time, and a [dispel magic](4-Resources/Compendium/spells/dispel-magic.md) cast as a 9th-level spell upon the phylactery releases any creature imprisoned within it. A creature imprisoned in the phylactery for 24 hours is consumed and destroyed utterly, whereupon nothing short of divine intervention can restore it to life.

A lich that fails or forgets to maintain its body with sacrificed souls begins to physically fall apart, and might eventually become a demilich.

## Death and Restoration

When a lich's body is broken by accident or assault, the will and mind of the lich drains from it, leaving only a lifeless corpse behind. Within days, a new body reforms next to the lich's phylactery, coalescing out of glowing smoke that issues from the device. Because the destruction of its phylactery means the possibility of eternal death, a lich usually keeps its phylactery in a hidden, well-guarded location.

Destroying a lich's phylactery is no easy task and often requires a special ritual, item, or weapon. Every phylactery is unique, and discovering the key to its destruction can be a quest in and of itself.

## Lonely Existence

From time to time, a lich might be stirred from its single-minded pursuit of power to take an interest in the world around it, most often when some great event reminds it of the life it once led. It otherwise lives in isolation, engaging only with those creatures whose service helps secure its lair.

Few liches call themselves by their former names, instead adopting monikers such as the Black Hand or the Forgotten King.

## Magic Collectors

Liches collect spells and magic items. In addition to its spell repertoire, a lich has ready access to potions, scrolls, libraries of spellbooks, one or more wands, and perhaps a staff or two. It has no qualms about putting these treasures to use whenever its lair comes under attack.

## Undead Nature

A lich doesn't require air, food, drink, or sleep.

## A Lich's Lair

A lich often haunts the abode it favored in life, such as a lonely tower, a haunted ruin, or an academy of black magic. Alternatively, some liches construct secret tombs filled with powerful guardians and traps. Everything about a lich's lair reflects its keen mind and wicked cunning, including the magic and mundane traps that secure it. Undead, constructs, and bound demons lurk in shadowy recesses, emerging to destroy those who dare to disturb the lich's work.

A lich encountered in its lair has a challenge rating of 22 (41,000 XP).