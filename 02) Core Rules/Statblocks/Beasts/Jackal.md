---
cssclasses:
- json5e-monster
tags:
- src/5e/xmm
- monster/cr/0
- monster/environment/desert
- monster/environment/grassland
- monster/size/small
- monster/type/beast
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Jackal"
---
# [Jackal](Jackal.md)
*Source: Monster Manual (2024) p. 364. Available in the <span title='Systems Reference Document (5.2)'>SRD</span> and the Free Rules (2024)*  

## Animals

Use these stat blocks to represent the creatures they're named for or other similar creatures. For example, the [Panther](Panther.md) stat block can also represent a mountain lion, while the [Giant Goat](Giant-Goat.md) stat block might represent a buffalo. Any of these stat blocks might also serve as fantastical animals with distinctive names and cosmetic details unique to your D&D adventures.

```statblock
"name": "Jackal (XMM)"
"size": "Small"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "12"
"hp": !!int "3"
"hit_dice": "1d6"
"modifier": !!int "2"
"stats":
  - !!int "8"
  - !!int "15"
  - !!int "11"
  - !!int "3"
  - !!int "12"
  - !!int "6"
"speed": "40 ft."
"skillsaves":
  - "name": "[Perception](Perception)"
    "desc": "+5"
  - "name": "[Stealth](Stealth)"
    "desc": "+4"
"senses": "[Darkvision](senses.md#Darkvision) 90 ft., passive\
  \ Perception 15"
"languages": ""
"cr": "0"
"actions":
  - "desc": "*Melee Attack Roll:* +1, reach 5 ft. *Hit:* 1 (1d4 - 1) Piercing\
      \ damage."
    "name": "Bite"
"source":
  - "XMM"
"image": "bestiary/tokens/XMM/Jackal.webp"
```
^statblock

## Environment

desert, grassland