---
cssclasses:
- json5e-monster
tags:
- src/5e/xmm
- monster/cr/1
- monster/environment/underwater
- monster/size/medium
- monster/type/beast
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Swarm of Piranhas"
---
# [Swarm of Piranhas](Swarm-of-Piranhas.md)
*Source: Monster Manual (2024) p. 370. Available in the <span title='Systems Reference Document (5.2)'>SRD</span> and the Free Rules (2024)*  

## Animals

Use these stat blocks to represent the creatures they're named for or other similar creatures. For example, the [Panther](Panther.md) stat block can also represent a mountain lion, while the [Giant Goat](Giant-Goat.md) stat block might represent a buffalo. Any of these stat blocks might also serve as fantastical animals with distinctive names and cosmetic details unique to your D&D adventures.

```statblock
"name": "Swarm of Piranhas (XMM)"
"size": "Medium"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "13"
"hp": !!int "28"
"hit_dice": "8d8 - 8"
"modifier": !!int "3"
"stats":
  - !!int "13"
  - !!int "16"
  - !!int "9"
  - !!int "1"
  - !!int "7"
  - !!int "2"
"speed": "5 ft., swim 40 ft."
"damage_resistances": "bludgeoning, piercing, slashing"
"condition_immunities": "[charmed](conditions.md#Charmed), [frightened](conditions.md#Frightened),\
  \ [grappled](conditions.md#Grappled), [paralyzed](conditions.md#Paralyzed),\
  \ [petrified](conditions.md#Petrified), [prone](conditions.md#Prone),\
  \ [restrained](conditions.md#Restrained), [stunned](conditions.md#Stunned)"
"senses": "[Darkvision](senses.md#Darkvision) 60 ft., passive\
  \ Perception 8"
"languages": ""
"cr": "1"
"traits":
  - "desc": "The swarm can occupy another creature's space and vice versa, and the\
      \ swarm can move through any opening large enough for a Tiny piranha. The swarm\
      \ can't regain [Hit Points](hit-points)\
      \ or gain [Temporary Hit Points](temporary-hit-points)."
    "name": "Swarm"
  - "desc": "The swarm can breathe only underwater."
    "name": "Water Breathing"
"actions":
  - "desc": "*Melee Attack Roll:* +5 (with [Advantage](advantage)\
      \ if the target doesn't have all its [Hit Points](hit-points)),\
      \ reach 5 ft. *Hit:* 8 (2d4 + 3) Piercing damage, or 5 (1d4 + 3) Piercing\
      \ damage if the swarm is [Bloodied](conditions.md#Bloodied)."
    "name": "Bites"
"source":
  - "XMM"
"image": "bestiary/tokens/XMM/Swarm of Piranhas.webp"
```
^statblock

## Environment

underwater