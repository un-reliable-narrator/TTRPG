---
cssclasses:
  - json5e-monster
tags:
  - src/5e/veor
  - monster/cr/9
  - monster/environment/desert
  - monster/environment/urban
  - monster/size/medium
  - monster/type/humanoid
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Jerot Galgin
---
# [Jerot Galgin](Jerot-Galgin-veor.md)
*Source: Vecna: Eve of Ruin p. 28*  

![](https://5e.tools/img/bestiary/tokens/VEoR/Jerot%20Galgin.webp)

```statblock
"name": "Jerot Galgin (VEoR)"
"size": "Medium"
"type": "humanoid"
"alignment": "Neutral Evil"
"ac": !!int "12"
"hp": !!int "110"
"hit_dice": "20d8 + 20"
"modifier": !!int "2"
"stats":
  - !!int "9"
  - !!int "14"
  - !!int "12"
  - !!int "17"
  - !!int "12"
  - !!int "11"
"speed": "30 ft."
"saves":
  - "intelligence": !!int "7"
  - "wisdom": !!int "5"
"skillsaves":
  - "name": "[Arcana](skills.md#Arcana)"
    "desc": "+7"
  - "name": "[History](skills.md#History)"
    "desc": "+7"
"damage_resistances": "necrotic"
"senses": "passive Perception 11"
"languages": "any four languages"
"cr": "9"
"actions":
  - "desc": "Jerot makes three Arcane Burst attacks."
    "name": "Multiattack"
  - "desc": "*Melee or Ranged Spell Attack:* +7 to hit, reach 5 ft. or range\
      \ 120 ft., one target. *Hit:* 25 (4d10 + 3) necrotic damage."
    "name": "Arcane Burst"
  - "desc": "Jerot casts one of the following spells, using Intelligence as the\
      \ spellcasting ability (spell save DC 15):\n\n**At will:** [dancing\
      \ lights](Dancing-Lights.md), [mage hand](Mage-Hand.md),\
      \ [prestidigitation](Prestidigitation.md)\n\n**2/day each:** [bestow\
      \ curse](Bestow-Curse.md), [dimension door](Dimension-Door.md), [mage\
      \ armor](Mage-Armor.md), [web](Web.md)\n\n**1/day each:** [circle of\
      \ death](Circle-of-Death.md)"
    "name": "Spellcasting"
"bonus_actions":
  - "desc": "Jerot magically summons five [skeletons](Skeleton.md) or\
      \ [zombies](Zombie.md). The summoned creatures appear in unoccupied\
      \ spaces within 60 feet of Jerot, whom they obey. They take their turns\
      \ immediately after Jerot. Each lasts for 1 hour, until it or Jerot dies,\
      \ or until Jerot dismisses it as a bonus action."
    "name": "Summon Undead (1/Day)"
"reactions":
  - "desc": "When Jerot kills a creature with necrotic damage, Jerot regains 9\
      \ (2d8) hit points. "
    "name": "Grim Harvest (1/Turn)"
"source":
  - "VEoR"
"image": "bestiary/tokens/VEoR/Jerot Galgin.webp"
```
^statblock

## Environment

desert, urban
