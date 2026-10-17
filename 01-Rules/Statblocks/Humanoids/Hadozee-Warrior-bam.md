---
cssclasses:
  - json5e-monster
tags:
  - src/5e/bam
  - monster/cr/1/2
  - monster/size/medium
  - monster/type/humanoid
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Hadozee Warrior
---
# [Hadozee Warrior](Hadozee-Warrior-bam.md)
*Source: Boo's Astral Menagerie p. 29*  

![](https://5e.tools/img/bestiary/BAM/Hadozee%20Warrior.webp)

Hadozee warriors make their living as mercenaries, sometimes in the company of pirates. Squads of warriors often adopt colorful names, such as the Soaring Hadozees, the Jammin' Wingbats, and the Night Howlers.

```statblock
"name": "Hadozee Warrior (BAM)"
"size": "Medium"
"type": "humanoid"
"alignment": "Any alignment"
"ac": !!int "16"
"ac_class": "[breastplate](Breastplate.md)"
"hp": !!int "16"
"hit_dice": "3d8 + 3"
"modifier": !!int "3"
"stats":
  - !!int "11"
  - !!int "16"
  - !!int "13"
  - !!int "10"
  - !!int "13"
  - !!int "12"
"speed": "30 ft., climb 30 ft."
"saves":
  - "dexterity": !!int "5"
  - "constitution": !!int "3"
"skillsaves":
  - "name": "[Perception](skills.md#Perception)"
    "desc": "+3"
  - "name": "[Stealth](skills.md#Stealth)"
    "desc": "+5"
  - "name": "[Survival](skills.md#Survival)"
    "desc": "+5"
"senses": "passive Perception 13"
"languages": "Common, Hadozee"
"cr": "1/2"
"traits":
  - "desc": "If it isn't [incapacitated](conditions.md#Incapacitated) or\
      \ wearing heavy armor, the hadozee can extend its skin membranes to move\
      \ up to 5 feet horizontally for every 1 foot it descends in the air."
    "name": "Glide"
"actions":
  - "desc": "The hadozee makes two Shortsword attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one target. *Hit:*\
      \ 6 (1d6 + 3) piercing damage."
    "name": "Shortsword"
  - "desc": "*Ranged Weapon Attack:* +5 to hit, range 80/320 ft., one target.\
      \ *Hit:* 12 (2d8 + 3) piercing damage."
    "name": "Light Crossbow"
"reactions":
  - "desc": "When it would take damage from a fall, the hadozee extends its\
      \ skin membranes to reduce the fall's damage to 0, provided it isn't\
      \ wearing heavy armor."
    "name": "Safe Descent"
  - "desc": "The hadozee halves the damage that it takes from an attack that\
      \ hits it, provided it can see the attacker."
    "name": "Uncanny Dodge"
"source":
  - "BAM"
"image": "bestiary/tokens/BAM/Hadozee Warrior.webp"
```
^statblock
