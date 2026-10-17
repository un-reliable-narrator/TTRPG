---
cssclasses:
  - json5e-monster
tags:
  - src/5e/toa
  - monster/cr/8
  - monster/environment/mountain
  - monster/environment/arctic
  - monster/size/huge
  - monster/type/giant
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Drufi
---
# [Drufi](Drufi-toa.md)
*Source: Tomb of Annihilation p. 64*  

![](https://5e.tools/img/bestiary/tokens/ToA/Drufi.webp)

```statblock
"name": "Drufi (ToA)"
"size": "Huge"
"type": "giant"
"alignment": "Neutral Evil"
"ac": !!int "15"
"ac_class": "patchwork armor"
"hp": !!int "138"
"hit_dice": "12d12 + 60"
"modifier": !!int "-1"
"stats":
  - !!int "23"
  - !!int "9"
  - !!int "21"
  - !!int "9"
  - !!int "10"
  - !!int "12"
"speed": "40 ft."
"saves":
  - "constitution": !!int "8"
  - "wisdom": !!int "3"
  - "charisma": !!int "4"
"skillsaves":
  - "name": "[Athletics](skills.md#Athletics)"
    "desc": "+9"
  - "name": "[Perception](skills.md#Perception)"
    "desc": "+3"
"damage_immunities": "cold"
"senses": "passive Perception 13"
"languages": "Giant"
"cr": "8"
"actions":
  - "desc": "Drufi makes two greataxe attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +9 to hit, reach 10 ft., one target. *Hit:*\
      \ 25 (3d12 + 6) slashing damage."
    "name": "Greataxe"
  - "desc": "*Ranged Weapon Attack:* +9 to hit, range 60/240 ft., one target.\
      \ *Hit:* 28 (4d10 + 6) bludgeoning damage."
    "name": "Rock"
"source":
  - "ToA"
"image": "bestiary/tokens/ToA/Drufi.webp"
```
^statblock

## New Giant Options

Some adult frost giants are skilled hunters who construct and hurl nets weighted down with fragments of metal or bone. This ability is represented by the following action option.

### Weighted Net

*Ranged Weapon Attack:* +5 to hit, ranged 20/60 ft., one Small, Medium, or Large creature. *Hit:* The target is [restrained](conditions.md#Restrained) until it escapes the net. Any creature can use its action to make a DC 17 Strength check to free itself or another creature in the net, ending the effect on a success. Dealing 15 slashing damage to the net (AC 12) destroys the net and frees the target.

## Environment

mountain, arctic
