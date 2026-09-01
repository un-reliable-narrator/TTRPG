---
cssclasses:
- json5e-monster
tags:
- src/5e/xmm
- monster/cr/1-4
- monster/environment/forest
- monster/environment/mountain
- monster/environment/underdark
- monster/environment/urban
- monster/size/large
- monster/type/beast
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Swarm of Bats"
---
# [Swarm of Bats](Swarm-of-Bats.md)
*Source: Monster Manual (2024) p. 370. Available in the <span title='Systems Reference Document (5.2)'>SRD</span> and the Free Rules (2024)*  

## Animals

Use these stat blocks to represent the creatures they're named for or other similar creatures. For example, the [Panther](Panther.md) stat block can also represent a mountain lion, while the [Giant Goat](Giant-Goat.md) stat block might represent a buffalo. Any of these stat blocks might also serve as fantastical animals with distinctive names and cosmetic details unique to your D&D adventures.

```statblock
"name": "Swarm of Bats (XMM)"
"size": "Large"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "12"
"hp": !!int "11"
"hit_dice": "2d10"
"modifier": !!int "2"
"stats":
  - !!int "5"
  - !!int "15"
  - !!int "10"
  - !!int "2"
  - !!int "12"
  - !!int "4"
"speed": "5 ft., fly 30 ft."
"damage_resistances": "bludgeoning, piercing, slashing"
"condition_immunities": "[charmed](conditions.md#Charmed), [frightened](conditions.md#Frightened),\
  \ [grappled](conditions.md#Grappled), [paralyzed](conditions.md#Paralyzed),\
  \ [petrified](conditions.md#Petrified), [prone](conditions.md#Prone),\
  \ [restrained](conditions.md#Restrained), [stunned](conditions.md#Stunned)"
"senses": "[Blindsight](senses.md#Blindsight) 60 ft., passive\
  \ Perception 11"
"languages": ""
"cr": "1/4"
"traits":
  - "desc": "The swarm can occupy another creature's space and vice versa, and the\
      \ swarm can move through any opening large enough for a Tiny bat. The swarm\
      \ can't regain [Hit Points](hit-points)\
      \ or gain [Temporary Hit Points](temporary-hit-points)."
    "name": "Swarm"
"actions":
  - "desc": "*Melee Attack Roll:* +4, reach 5 ft. *Hit:* 5 (2d4) Piercing damage,\
      \ or 2 (1d4) Piercing damage if the swarm is [Bloodied](conditions.md#Bloodied)."
    "name": "Bites"
"source":
  - "XMM"
"image": "bestiary/tokens/XMM/Swarm of Bats.webp"
```
^statblock

## Environment

forest, mountain, underdark, urban