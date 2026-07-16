---
cssclasses:
- json5e-monster
tags:
- src/5e/bam
- monster/cr/1-8
- monster/size/medium
- monster/type/humanoid
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Hadozee Shipmate"
---
# [Hadozee Shipmate](Hadozee-Shipmate-bam.md)
*Source: Boo's Astral Menagerie p. 29, Light of Xaryxis*  

Hadozee shipmates make up much of the crew aboard some spelljamming ships.

```statblock
"name": "Hadozee Shipmate (BAM)"
"size": "Medium"
"type": "humanoid"
"alignment": "Any alignment"
"ac": !!int "12"
"hp": !!int "9"
"hit_dice": "2d8"
"modifier": !!int "2"
"stats":
  - !!int "11"
  - !!int "14"
  - !!int "11"
  - !!int "10"
  - !!int "14"
  - !!int "12"
"speed": "30 ft., climb 30 ft."
"saves":
  - "dexterity": !!int "4"
  - "constitution": !!int "2"
"skillsaves":
  - "name": "[Perception](Perception)"
    "desc": "+4"
  - "name": "[Survival](Survival)"
    "desc": "+6"
"gear":
  - "[dagger](dagger)"
"senses": "passive Perception 14"
"languages": "Common, Hadozee"
"cr": "1/8"
"traits":
  - "desc": "If it isn't [incapacitated](conditions.md#Incapacitated)\
      \ or wearing heavy armor, the hadozee can extend its skin membranes to move\
      \ up to 5 feet horizontally for every 1 foot it descends in the air."
    "name": "Glide"
"actions":
  - "desc": "*Melee  or Ranged Weapon Attack:* +4 to hit, reach 5 ft. or range 20/60\
      \ ft., one target. *Hit:* 4 (1d4 + 2) piercing damage."
    "name": "Dagger"
"reactions":
  - "desc": "When it would take damage from a fall, the hadozee extends its skin membranes\
      \ to reduce the fall's damage to 0, provided it isn't wearing heavy armor."
    "name": "Safe Descent"
"source":
  - "BAM"
  - "LoX"
"image": "bestiary/tokens/BAM/Hadozee Shipmate.webp"
```
^statblock