---
cssclasses:
- json5e-monster
tags:
- src/5e/mpmm
- monster/cr/7
- monster/environment/arctic
- monster/environment/desert
- monster/environment/underdark
- monster/environment/urban
- monster/size/medium
- monster/type/humanoid
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Warlock of the Fiend"
---
# [Warlock of the Fiend](Warlock%20of%20the%20Fiend%20-%20mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 255*  

Warlocks of the Fiend gain their powers through magical pacts forged with archfiends of the Lower Planes. These warlocks often keep [imps](Imp.md) or [quasits](Quasit.md) as companions, and they tend toward philosophical extremes: consorting with fiendish cults or dedicating their lives to destroying such cults.

## Warlocks

Warlocks gain arcane might through magical pacts with mysterious entities. While some use their abilities to serve the sources of their power, others use them to undermine or even destroy these entities.

```statblock
"name": "Warlock of the Fiend (MPMM)"
"size": "Medium"
"type": "humanoid"
"alignment": "Any alignment"
"ac": !!int "13"
"ac_class": "16 with [mage armor](mage-armor)"
"hp": !!int "78"
"hit_dice": "12d8 + 24"
"modifier": !!int "3"
"stats":
  - !!int "10"
  - !!int "16"
  - !!int "15"
  - !!int "12"
  - !!int "12"
  - !!int "18"
"speed": "30 ft."
"saves":
  - "wisdom": !!int "4"
  - "charisma": !!int "7"
"skillsaves":
  - "name": "[Arcana](Arcana)"
    "desc": "+4"
  - "name": "[Deception](skills.md#Deception)"
    "desc": "+7"
  - "name": "[Persuasion](Persuasion)"
    "desc": "+7"
  - "name": "[Religion](Religion)"
    "desc": "+4"
"gear":
  - "[scimitar](scimitar)"
"senses": "[Darkvision](senses.md#Darkvision) 60 ft., passive\
  \ Perception 11"
"languages": "any two languages (usually Abyssal or Infernal)"
"cr": "7"
"traits":
  - "desc": "When the warlock makes an ability check or saving throw, it can add a\
      \ d10 to the roll. It can do this after the roll is made but before any of\
      \ the roll's effects occur."
    "name": "Dark One's Own Luck (Recharges after a Short or Long Rest)"
"actions":
  - "desc": "The warlock makes three Scimitar attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one target. *Hit:* 6\
      \ (1d6 + 3) slashing damage plus 14 (4d6) fire damage."
    "name": "Scimitar"
  - "desc": "Green flame explodes in a 10-foot-radius sphere centered on a point within\
      \ 120 feet of the warlock. Each creature in that area must make a DC 15 Dexterity\
      \ saving throw, taking 16 (3d10) fire damage and 11 (2d10) necrotic damage\
      \ on a failed save, or half as much damage on a successful one."
    "name": "Hellfire"
  - "desc": "The warlock casts one of the following spells, using Charisma as the\
      \ spellcasting ability (spell save DC 15): \n\n**At will:** [alter self](alter-self),\
      \ [mage armor](mage-armor) (self only), [mage\
      \ hand](Mage%20Hand), [minor illusion](minor-illusion),\
      \ [prestidigitation](prestidigitation)\n\n**1/day\
      \ each:** [banishment](banishment), [plane shift](Plane%20Shift),\
      \ [suggestion](suggestion)"
    "name": "Spellcasting"
"reactions":
  - "desc": "In response to being damaged by a visible creature within 60 feet of\
      \ it, the warlock forces that creature to make a DC 15 Constitution saving throw,\
      \ taking 22 (4d10) necrotic damage on a failed save, or half as much damage\
      \ on a successful one."
    "name": "Fiendish Rebuke (3/Day)"
"source":
  - "MPMM"
"image": "bestiary/tokens/MPMM/Warlock of the Fiend.webp"
```
^statblock

## Environment

arctic, desert, underdark, urban