---
cssclasses:
  - json5e-monster
tags:
  - src/5e/dmg
  - monster/cr/
  - monster/size/medium
  - monster/type/undead
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Avatar of Death
---
# [Avatar of Death](avatar-of-death.md)
*Source: Dungeon Master's Guide (2024) p. 252*  

```statblock
"name": "Avatar of Death (XDMG)"
"size": "Medium"
"type": "undead"
"alignment": "Neutral Evil"
"ac": !!int "20"
"modifier": !!int "3"
"stats":
  - !!int "16"
  - !!int "16"
  - !!int "16"
  - !!int "16"
  - !!int "16"
  - !!int "16"
"speed": "60 ft., fly 60 ft. (hover)"
"damage_immunities": "necrotic, poison"
"condition_immunities": "[charmed](conditions.md#Charmed), [exhaustion](conditions.md#Exhaustion),\
  \ [frightened](conditions.md#Frightened), [paralyzed](conditions.md#Paralyzed),\
  \ [petrified](conditions.md#Petrified), [poisoned](conditions.md#Poisoned),\
  \ [unconscious](conditions.md#Unconscious)"
"senses": "[Truesight](senses.md#Truesight) 60 ft., passive\
  \ Perception 13"
"languages": "all languages known to its summoner"
"traits":
  - "desc": "The avatar can move through other creatures and objects as if they were\
      \ Difficult Terrain. It takes 5 (1d10) Force damage if it ends its turn inside\
      \ an object."
    "name": "Incorporeal Movement"
"actions":
  - "desc": "The avatar makes a number of Reaping Scythe attacks equal to half the\
      \ summoner's Proficiency Bonus (rounded up)."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* Automatic hit, reach 5 ft. *Hit:* 7 (1d8 + 3)\
      \ Slashing damage plus 4 (1d8) Necrotic damage."
    "name": "Reaping Scythe"
"source":
  - "XDMG"
"image": "bestiary/tokens/XDMG/Avatar of Death.webp"
```
^statblock