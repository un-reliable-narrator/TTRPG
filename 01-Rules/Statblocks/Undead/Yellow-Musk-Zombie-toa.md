---
cssclasses:
  - json5e-monster
tags:
  - src/5e/toa
  - monster/cr/1/4
  - monster/size/medium
  - monster/type/undead
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Yellow Musk Zombie
---
# [Yellow Musk Zombie](Yellow-Musk-Zombie-toa.md)
*Source: Tomb of Annihilation p. 237*  

![](https://5e.tools/img/bestiary/ToA/Yellow%20Musk%20Zombie.webp)

A yellow musk creeper is an unholy vine whose flowers resemble an orchid's. Bright yellow with splashes of purple, these flowers expel a musk that attracts prey. A yellow musk creeper clings to walls, pillars, gravestones, door frames, or statuary in shadowy locations, remaining motionless until it strikes.

```statblock
"name": "Yellow Musk Zombie (ToA)"
"size": "Medium"
"type": "undead"
"alignment": "Unaligned"
"ac": !!int "9"
"hp": !!int "33"
"hit_dice": "6d8 + 6"
"modifier": !!int "-1"
"stats":
  - !!int "13"
  - !!int "9"
  - !!int "12"
  - !!int "1"
  - !!int "6"
  - !!int "3"
"speed": "20 ft."
"condition_immunities": "[charmed](conditions.md#Charmed),\
  \ [exhaustion](conditions.md#Exhaustion)"
"senses": "[Blindsight](senses.md#Blindsight) 30 ft., passive Perception 8"
"languages": ""
"cr": "1/4"
"traits":
  - "desc": "If damage reduces the zombie to 0 hit points, it must make a\
      \ Constitution saving throw with a DC of 5 +the damage taken, unless the\
      \ damage is fire or from a critical hit. On a success, the zombie drops\
      \ to 1 hit point instead."
    "name": "Undead Fortitude"
"actions":
  - "desc": "*Melee Weapon Attack:* +3 to hit, reach 5 ft., one target. *Hit:*\
      \ 5 (1d8 + 1) bludgeoning damage."
    "name": "Slam"
"source":
  - "ToA"
"image": "bestiary/tokens/ToA/Yellow Musk Zombie.webp"
```
^statblock
