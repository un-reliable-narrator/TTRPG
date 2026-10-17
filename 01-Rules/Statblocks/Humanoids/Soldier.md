---
cssclasses:
  - json5e-monster
tags:
  - src/5e/ggr
  - monster/cr/1/2
  - monster/size/medium
  - monster/type/humanoid/any-race
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Soldier
---
# [Soldier](Soldier.md)
*Source: Guildmasters' Guide to Ravnica p. 226*  

![](https://5e.tools/img/bestiary/tokens/GGR/Soldier.webp)

Soldiers are found in many of Ravnica's guilds. The soldier stat block represents a typical member of the rank and file, though weaponry and armor can vary.

```statblock
"name": "Soldier (GGR)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Any alignment"
"ac": !!int "18"
"ac_class": "[chain mail](chain-mail.md), [shield](Shield.md)"
"hp": !!int "16"
"hit_dice": "3d8 + 3"
"modifier": !!int "1"
"stats":
  - !!int "13"
  - !!int "12"
  - !!int "12"
  - !!int "10"
  - !!int "11"
  - !!int "11"
"speed": "30 ft."
"skillsaves":
  - "name": "[Perception](skills.md#Perception)"
    "desc": "+2"
  - "name": "[Athletics](skills.md#Athletics)"
    "desc": "+3"
"senses": "passive Perception 12"
"languages": "any one language (usually Common)"
"cr": "1/2"
"traits":
  - "desc": "The soldier has advantage on saving throws against being\
      \ [charmed](conditions.md#Charmed),\
      \ [frightened](conditions.md#Frightened),\
      \ [grappled](conditions.md#Grappled), or\
      \ [restrained](conditions.md#Restrained) while it is within 5 feet of at\
      \ least one ally."
    "name": "Formation Tactics"
"actions":
  - "desc": "The soldier makes two melee attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +3 to hit, reach 5 ft., one target. *Hit:*\
      \ 6 (1d8 + 2) slashing damage, or 7 (1d10 + 2) slashing damage if used\
      \ with two hands."
    "name": "Longsword"
"source":
  - "GGR"
"image": "bestiary/tokens/GGR/Soldier.webp"
```
^statblock
