---
cssclasses:
  - json5e-monster
tags:
  - src/5e/cm
  - monster/cr/1/2
  - monster/size/medium
  - monster/type/humanoid/any-race
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Sage
---
# [Sage](Sage-cm.md)
*Source: Candlekeep Mysteries p. 9*  

![](https://5e.tools/img/bestiary/CM/Sage.webp)

Candlekeep's resident lore experts are master sages and sages who dedicate themselves to scholarship above all.

```statblock
"name": "Sage (CM)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": ""
"ac": !!int "10"
"hp": !!int "22"
"hit_dice": "5d8"
"modifier": !!int "0"
"stats":
  - !!int "8"
  - !!int "10"
  - !!int "10"
  - !!int "18"
  - !!int "15"
  - !!int "11"
"speed": "30 ft."
"skillsaves":
  - "name": "[Arcana](skills.md#Arcana)"
    "desc": "+8"
  - "name": "[History](skills.md#History)"
    "desc": "+8"
  - "name": "[Insight](skills.md#Insight)"
    "desc": "+4"
  - "name": "[Investigation](skills.md#Investigation)"
    "desc": "+8"
  - "name": "[Medicine](skills.md#Medicine)"
    "desc": "+6"
  - "name": "[Nature](skills.md#Nature)"
    "desc": "+8"
  - "name": "[Religion](skills.md#Religion)"
    "desc": "+8"
"senses": "passive Perception 12"
"languages": "Common plus any four languages"
"cr": "1/2"
"actions":
  - "desc": "*Melee Spell Attack:* +6 to hit (with advantage if the target is\
      \ wearing armor made of metal), reach 5 ft., one creature. *Hit:* 9 (2d8)\
      \ lightning damage, and the target can't take reactions until the start\
      \ of its next turn."
    "name": "Shocking Grasp (Cantrip)"
  - "desc": "The sage casts one of the following spells, using Intelligence as\
      \ the spellcasting ability (save DC 14, +6 to hit with spell\
      \ attacks):\n\n**At will:** [light](Light.md), [mage hand](Mage-Hand.md),\
      \ [mending](Mending.md), [shocking grasp](Shocking-Grasp.md)\n\n**3/day\
      \ each:** [comprehend languages](Comprehend-Languages.md), [detect\
      \ magic](Detect-Magic.md), [identify](Identify.md),\
      \ [shield](Shield.md)\n\n**1/day each:** [dispel magic](Dispel-Magic.md),\
      \ [levitate](Levitate.md), [locate object](Locate-Object.md), [see\
      \ invisibility](See-Invisibility.md), [sending](Sending.md),\
      \ [tongues](Tongues.md), [unseen servant](Unseen-Servant.md)"
    "name": "Spellcasting"
"reactions":
  - "desc": "When the sage is hit by an attack or targeted by a [magic\
      \ missile](Magic-Missile.md) spell, it calls forth an\
      \ [invisible](conditions.md#Invisible) barrier of magical force that\
      \ protects it. Until the start of its next turn, the sage has a +5 bonus\
      \ to AC, including against the triggering attack, and it takes no damage\
      \ from magic missile."
    "name": "Shield (1st-Level Spell; 3/Day)"
"source":
  - "CM"
"image": "bestiary/tokens/CM/Sage.webp"
```
^statblock
