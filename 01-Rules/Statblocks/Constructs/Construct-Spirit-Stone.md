---
cssclasses:
- json5e-monster
tags:
- src/5e/xphb
- monster/cr/
- monster/size/medium
- monster/type/construct
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Construct Spirit (Stone)"
---
# [Construct Spirit (Stone)](construct Spirit Stone)
*Source: Player's Handbook (2024) p. 324*  

```statblock
"name": "Construct Spirit (Stone) (XPHB)"
"size": "Medium"
"type": "construct"
"alignment": "Neutral"
"ac_class": "13 + the spell's level"
"modifier": !!int "0"
"stats":
  - !!int "18"
  - !!int "10"
  - !!int "18"
  - !!int "14"
  - !!int "11"
  - !!int "5"
"speed": "30 ft."
"damage_resistances": "poison"
"condition_immunities": "[charmed](conditions.md#Charmed), [exhaustion](conditions.md#Exhaustion),\
  \ [frightened](conditions.md#Frightened), [paralyzed](conditions.md#Paralyzed),\
  \ [poisoned](conditions.md#Poisoned)"
"senses": "[Darkvision](senses.md#Darkvision) 60 ft., passive\
  \ Perception 10"
"languages": "Understands the languages you know"
"traits":
  - "desc": "When a creature starts its turn within 10 feet of the spirit, the spirit\
      \ can target it with magical energy if the spirit can see it. *Wisdom Saving\
      \ Throw:* DC equals your spell save DC, the target. *Failure:* Until the start\
      \ of its next turn, the target can't make [Opportunity Attacks](actions.md#Opportunity%20Attack),\
      \ and its Speed is halved."
    "name": "Stony Lethargy"
"actions":
  - "desc": "The spirit makes a number of Slam attacks equal to half this spell's\
      \ level (round down)."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* Bonus equals your spell attack modifier, reach 5\
      \ ft. *Hit:* 1d8 + 4 + the spell's level Bludgeoning damage."
    "name": "Slam"
"source":
  - "XPHB"
```
^statblock