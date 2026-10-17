---
cssclasses:
  - json5e-monster
tags:
  - src/5e/toa
  - monster/cr/4
  - monster/size/medium
  - monster/type/undead
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Withers
---
# [Withers](Withers-toa.md)
*Source: Tomb of Annihilation p. 145*  

![](https://5e.tools/img/bestiary/ToA/Withers.webp)

Before he was turned into an undead creature, Withers was an Omuan engineer named Gorra. Like all of Omu's citizens, Gorra was enslaved and put to work constructing the tomb. When Acererak sacrificed his workers to their own dungeon, Gorra's traps performed the best.

```statblock
"name": "Withers (ToA)"
"size": "Medium"
"type": "undead"
"alignment": "Neutral Evil"
"ac": !!int "14"
"ac_class": "[studded leather](Studded-Leather-Armor.md)"
"hp": !!int "45"
"hit_dice": "6d8 + 18"
"modifier": !!int "2"
"stats":
  - !!int "15"
  - !!int "14"
  - !!int "16"
  - !!int "16"
  - !!int "13"
  - !!int "15"
"speed": "30 ft."
"skillsaves":
  - "name": "[Perception](skills.md#Perception)"
    "desc": "+3"
  - "name": "[Stealth](skills.md#Stealth)"
    "desc": "+4"
"damage_resistances": "necrotic; bludgeoning, piercing, slashing from\
  \ nonmagical attacks that aren't silvered"
"damage_immunities": "poison"
"condition_immunities": "[exhaustion](conditions.md#Exhaustion),\
  \ [poisoned](conditions.md#Poisoned)"
"senses": "[Darkvision](senses.md#Darkvision) 60 ft., passive Perception 13"
"languages": "the languages he knew in life"
"cr": "4"
"traits":
  - "desc": "Withers carries the amulet of the black skull."
    "name": "Special Equipment"
  - "desc": "While in sunlight, Withers has disadvantage on attack rolls, as\
      \ well as on Wisdom (Perception) checks that rely on sight."
    "name": "Sunlight Sensitivity"
  - "desc": "Withers is a 9th-level spellcaster. His spellcasting ability is\
      \ Intelligence (spell save DC 13, +5 to hit with spell attacks). Withers\
      \ has the following wizard spells prepared:\n\n**Cantrips (at will):**\
      \ [acid splash](Acid-Splash.md), [mage hand](Mage-Hand.md), [minor\
      \ illusion](Minor-Illusion.md),\
      \ [prestidigitation](Prestidigitation.md)\n\n**1st level (4 slots):**\
      \ [detect magic](Detect-Magic.md), [expeditious\
      \ retreat](Expeditious-Retreat.md), [feather fall](Feather-Fall.md),\
      \ [thunderwave](Thunderwave.md)\n\n**2nd level (4 slots):**\
      \ [darkness](Darkness.md), [hold person](Hold-Person.md), [rope\
      \ trick](Rope-Trick.md)\n\n**3rd level (3 slots):** [dispel\
      \ magic](Dispel-Magic.md), [lightning bolt](Lightning-Bolt.md)\n\n**4th\
      \ level (3 slots):** [blight](Blight.md), [wall of\
      \ fire](Wall-of-Fire.md)\n\n**5th level (1 slot):**\
      \ [telekinesis](Telekinesis.md)"
    "name": "Spellcasting"
"actions":
  - "desc": "Withers makes two longsword attacks. He can use his Life Drain in\
      \ place of one longsword attack."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one creature.\
      \ *Hit:* 5 (1d6 + 2) necrotic damage. The target must succeed on a DC 13\
      \ Constitution saving throw or its hit point maximum is reduced by an\
      \ amount equal to the damage taken. This reduction lasts until the target\
      \ finishes a long rest. The target dies if this effect reduces its hit\
      \ point maximum to 0.\n\nA humanoid slain by this attack rises 24 hours\
      \ later as a zombie under the Withers's control, unless the humanoid is\
      \ restored to life or its body is destroyed. Withers can have no more\
      \ than twelve zombies under its control at one time."
    "name": "Life Drain"
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target. *Hit:*\
      \ 6 (1d8 + 2) slashing damage, or 7 (1d10 + 2) slashing damage if used\
      \ with two hands."
    "name": "Longsword"
"source":
  - "ToA"
"image": "bestiary/tokens/ToA/Withers.webp"
```
^statblock
