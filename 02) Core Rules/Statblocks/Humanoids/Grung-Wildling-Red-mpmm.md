---
cssclasses:
- json5e-monster
tags:
- src/5e/mpmm
- monster/cr/1
- monster/environment/forest
- monster/size/small
- monster/type/humanoid
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Grung Wildling (Red)"
---
# [Grung Wildling (Red)](Grung-Wildling-Red-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 150*  

```statblock
"name": "Grung Wildling (Red) (MPMM)"
"size": "Small"
"type": "humanoid"
"alignment": "Any alignment"
"ac": !!int "16"
"ac_class": "natural armor"
"hp": !!int "27"
"hit_dice": "5d6 + 10"
"modifier": !!int "3"
"stats":
  - !!int "7"
  - !!int "16"
  - !!int "15"
  - !!int "10"
  - !!int "15"
  - !!int "11"
"speed": "25 ft., climb 25 ft."
"saves":
  - "dexterity": !!int "5"
"skillsaves":
  - "name": "[Athletics](Athletics)"
    "desc": "+2"
  - "name": "[Perception](Perception)"
    "desc": "+4"
  - "name": "[Stealth](Stealth)"
    "desc": "+5"
  - "name": "[Survival](Survival)"
    "desc": "+4"
"damage_immunities": "poison"
"condition_immunities": "[poisoned](conditions.md#Poisoned)"
"gear":
  - "[dagger](dagger)"
  - "[shortbow](shortbow)"
"senses": "passive Perception 14"
"languages": "Grung"
"cr": "1"
"traits":
  - "desc": "The grung can breathe air and water."
    "name": "Amphibious"
  - "desc": "A creature [poisoned](conditions.md#Poisoned) by\
      \ a grung suffers an additional effect that depends on the grung's color. This\
      \ effect lasts until the creature is no longer [poisoned](conditions.md#Poisoned)\
      \ by the grung. The [poisoned](conditions.md#Poisoned)\
      \ creature must use its action to eat if food is within reach."
    "name": "Poisonous Skin"
  - "desc": "The grung's long jump is up to 25 feet and its high jump is up to 15\
      \ feet, with or without a running start."
    "name": "Standing Leap"
  - "desc": "If the grung isn't immersed in water for at least 1 hour during a day,\
      \ it suffers 1 level of [exhaustion](conditions.md#Exhaustion)\
      \ at the end of that day. The grung can recover from this [exhaustion](conditions.md#Exhaustion)\
      \ only through magic or by immersing itself in water for at least 1 hour."
    "name": "Water Dependency"
"actions":
  - "desc": "*Melee  or Ranged Weapon Attack:* +5 to hit, reach 5 ft. or range 20/60\
      \ ft., one target. *Hit:* 5 (1d4 + 3) piercing damage plus 5 (2d4) poison\
      \ damage."
    "name": "Dagger"
  - "desc": "*Ranged Weapon Attack:* +5 to hit, range 80/320 ft., one target. *Hit:*\
      \ 6 (1d6 + 3) piercing damage plus 5 (2d4) poison damage."
    "name": "Shortbow"
  - "desc": "The grung casts one of the following spells, using Wisdom as the spellcasting\
      \ ability (spell save DC 12):\n\n**At will:** [druidcraft](druidcraft)\n\
      \n**3/day each:** [cure wounds](cure-wounds),\
      \ [spike growth](spike-growth)\n\n**2/day:**\
      \ [plant growth](plant-growth)"
    "name": "Spellcasting"
"source":
  - "MPMM"
```
^statblock

## Environment

forest