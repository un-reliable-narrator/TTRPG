---
cssclasses:
  - json5e-monster
tags:
  - src/5e/toa
  - monster/cr/1
  - monster/environment/underdark
  - monster/environment/grassland
  - monster/environment/forest
  - monster/environment/hill
  - monster/size/small
  - monster/type/humanoid/goblinoid
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Grabstab
---
# [Grabstab](Grabstab-toa.md)
*Source: Tomb of Annihilation p. 89*  

![](https://5e.tools/img/bestiary/ToA/Grabstab.webp)

```statblock
"name": "Grabstab (ToA)"
"size": "Small"
"type": "humanoid"
"subtype": "goblinoid"
"alignment": "Neutral Evil"
"ac": !!int "17"
"ac_class": "[chain shirt](chain-Shirt.md), [shield](Shield.md)"
"hp": !!int "21"
"hit_dice": "6d6"
"modifier": !!int "2"
"stats":
  - !!int "10"
  - !!int "14"
  - !!int "10"
  - !!int "10"
  - !!int "8"
  - !!int "10"
"speed": "30 ft."
"skillsaves":
  - "name": "[Stealth](skills.md#Stealth)"
    "desc": "+6"
"senses": "[Darkvision](senses.md#Darkvision) 60 ft., passive Perception 9"
"languages": "Common, Goblin"
"cr": "1"
"traits":
  - "desc": "Grabstab can take the Disengage or Hide action as a bonus action\
      \ on each of its turns."
    "name": "Nimble Escape"
"actions":
  - "desc": "Grabstab makes two attacks with its scimitar. The second attack\
      \ has disadvantage."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target. *Hit:*\
      \ 5 (1d6 + 2) slashing damage."
    "name": "Scimitar"
  - "desc": "*Melee or Ranged Weapon Attack:* +2 to hit, reach 5 ft. or range\
      \ 30/120 ft., one target. *Hit:* 3 (1d6) piercing damage."
    "name": "Javelin"
"reactions":
  - "desc": "When a creature Grabstab can see targets it with an attack,\
      \ Grabstab chooses another goblin within 5 feet of it. The two goblins\
      \ swap places, and the chosen goblin becomes the target instead."
    "name": "Redirect Attack"
"source":
  - "ToA"
"image": "bestiary/tokens/ToA/Grabstab.webp"
```
^statblock

## Environment

underdark, grassland, forest, hill
