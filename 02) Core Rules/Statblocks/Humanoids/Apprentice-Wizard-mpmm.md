---
cssclasses:
- json5e-monster
tags:
- src/5e/mpmm
- monster/cr/1-4
- monster/environment/urban
- monster/size/medium
- monster/type/humanoid
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Apprentice Wizard"
---
# [Apprentice Wizard](Apprentice-Wizard-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 259*  

Apprentices are novice arcane spellcasters who serve more experienced wizards or attend school. They perform menial work like cooking or cleaning in exchange for education in the ways of magic.

## Wizards

Wizards pursue magical power through the study of arcane texts. Some travel the world searching for esoteric tomes while others train lesser wizards or collaborate with colleagues to create new spells.

```statblock
"name": "Apprentice Wizard (MPMM)"
"size": "Medium"
"type": "humanoid"
"alignment": "Any alignment"
"ac": !!int "10"
"ac_class": "13 with [mage armor](mage-armor)"
"hp": !!int "13"
"hit_dice": "3d8"
"modifier": !!int "0"
"stats":
  - !!int "10"
  - !!int "10"
  - !!int "10"
  - !!int "14"
  - !!int "10"
  - !!int "11"
"speed": "30 ft."
"skillsaves":
  - "name": "[Arcana](Arcana)"
    "desc": "+4"
  - "name": "[History](History)"
    "desc": "+4"
"senses": "passive Perception 10"
"languages": "any one language (usually Common)"
"cr": "1/4"
"actions":
  - "desc": "*Melee  or Ranged Spell Attack:* +4 to hit, reach 5 ft. or range 120\
      \ ft., one target. *Hit:* 7 (1d10 + 2) force damage."
    "name": "Arcane Burst"
  - "desc": "The apprentice casts one of the following spells, using Intelligence\
      \ as the spellcasting ability (spell save DC 12)\n\n**At will:** [mage hand](Mage%20Hand),\
      \ [prestidigitation](prestidigitation)\n\n**1/day\
      \ each:** [burning hands](burning-hands), [disguise\
      \ self](disguise-self), [mage armor](mage-armor)"
    "name": "Spellcasting"
"source":
  - "MPMM"
"image": "bestiary/tokens/MPMM/Apprentice Wizard.webp"
```
^statblock

## Environment

urban