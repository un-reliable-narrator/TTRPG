---
cssclasses:
- json5e-monster
tags:
- src/5e/xmm
- monster/cr/1
- monster/environment/forest
- monster/environment/grassland
- monster/size/large
- monster/type/beast
statblock: inline
statblock-link: "#^statblock"
---
# [Tiger](Tiger.md)
*Source: Monster Manual (2024) p. 371, Player's Handbook (2024) p. 358. Available in the <span title='Systems Reference Document (5.2)'>SRD</span> and the Free Rules (2024)*  

## Animals

Use these stat blocks to represent the creatures they're named for or other similar creatures. For example, the [Panther](Panther.md) stat block can also represent a mountain lion, while the [Giant Goat](Giant-Goat.md) stat block might represent a buffalo. Any of these stat blocks might also serve as fantastical animals with distinctive names and cosmetic details unique to your D&D adventures.

```statblock
"name": "Tiger (XMM)"
"size": "Large"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "13"
"hp": !!int "30"
"hit_dice": "4d10 + 8"
"modifier": !!int "3"
"stats":
  - !!int "17"
  - !!int "16"
  - !!int "14"
  - !!int "3"
  - !!int "12"
  - !!int "8"
"speed": "40 ft."
"skillsaves":
  - "name": "[Perception](Perception)"
    "desc": "+3"
  - "name": "[Stealth](Stealth)"
    "desc": "+7"
"senses": "[Darkvision](senses.md#Darkvision) 60 ft., passive\
  \ Perception 13"
"languages": ""
"cr": "1"
"actions":
  - "desc": "*Melee Attack Roll:* +5, reach 5 ft. *Hit:* 10 (2d6 + 3) Slashing\
      \ damage. If the target is a Large or smaller creature, it has the [Prone](conditions.md#Prone)\
      \ condition."
    "name": "Rend"
"bonus_actions":
  - "desc": "The tiger takes the Disengage or Hide action."
    "name": "Nimble Escape"
"source":
  - "XMM"
  - "XPHB"
"image": "bestiary/tokens/XMM/Tiger.webp"
```
^statblock

## Environment

forest, grassland