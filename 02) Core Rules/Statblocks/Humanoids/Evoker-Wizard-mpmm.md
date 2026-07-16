---
cssclasses:
- json5e-monster
tags:
- src/5e/mpmm
- monster/cr/9
- monster/environment/urban
- monster/size/medium
- monster/type/humanoid
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Evoker Wizard"
---
# [Evoker Wizard](Evoker-Wizard-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 262*  

Evokers harness arcane energy to destroy. Many armies employ evokers to rain destruction down on enemy forces.

## Wizards

Wizards pursue magical power through the study of arcane texts. Some travel the world searching for esoteric tomes while others train lesser wizards or collaborate with colleagues to create new spells.

```statblock
"name": "Evoker Wizard (MPMM)"
"size": "Medium"
"type": "humanoid"
"alignment": "Any alignment"
"ac": !!int "12"
"ac_class": "15 with [mage armor](mage-armor)"
"hp": !!int "121"
"hit_dice": "22d8 + 22"
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
  - "name": "[Arcana](Arcana)"
    "desc": "+7"
  - "name": "[History](History)"
    "desc": "+7"
"senses": "passive Perception 11"
"languages": "any four languages"
"cr": "9"
"actions":
  - "desc": "The evoker makes three Arcane Burst attacks."
    "name": "Multiattack"
  - "desc": "*Melee  or Ranged Spell Attack:* +7 to hit, reach 5 ft. or range 120\
      \ ft., one target. *Hit:* 25 (4d10 + 3) force damage."
    "name": "Arcane Burst"
  - "desc": "The evoker unleashes a magical explosion of a particular damage type:\
      \ cold, fire, lightning, or thunder. The magic erupts in a 20-foot-radius sphere\
      \ centered on a point within 150 feet of the evoker. Each creature in that area\
      \ must make a DC 15 Dexterity saving throw. The evoker can select up to three\
      \ creatures it can see in the area to ignore the spell, as the evoker sculpts\
      \ the spell's energy around them. On a failed save, a creature takes 40 (9d8)\
      \ damage of the chosen type and is knocked [prone](conditions.md#Prone).\
      \ On a successful save, a creature takes half as much damage and isn't knocked\
      \ [prone](conditions.md#Prone)."
    "name": "Sculpted Explosion (Recharge 4-6)"
  - "desc": "The evoker casts one of the following spells, using Intelligence as the\
      \ spellcasting ability (spell save DC 15):\n\n**At will:** [light](light),\
      \ [mage hand](Mage%20Hand), [message](message),\
      \ [prestidigitation](prestidigitation)\n\n**2/day\
      \ each:** [ice storm](ice-storm), [lightning\
      \ bolt](lightning-bolt), [mage armor](mage-armor)\n\
      \n**1/day each:** [wall of ice](wall-of-ice)"
    "name": "Spellcasting"
"source":
  - "MPMM"
"image": "bestiary/tokens/MPMM/Evoker Wizard.webp"
```
^statblock

## Environment

urban