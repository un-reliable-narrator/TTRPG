---
cssclasses:
- json5e-monster
tags:
- src/5e/xmm
- monster/cr/1-4
- monster/environment/forest
- monster/environment/grassland
- monster/environment/hill
- monster/size/medium
- monster/type/beast
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Boar"
---
# [Boar](Boar.md)
*Source: Monster Manual (2024) p. 350, Player's Handbook (2024) p. 347. Available in the <span title='Systems Reference Document (5.2)'>SRD</span> and the Free Rules (2024)*  

## Animals

Use these stat blocks to represent the creatures they're named for or other similar creatures. For example, the [Panther](Panther.md) stat block can also represent a mountain lion, while the [Giant Goat](Giant-Goat.md) stat block might represent a buffalo. Any of these stat blocks might also serve as fantastical animals with distinctive names and cosmetic details unique to your D&D adventures.

```statblock
"name": "Boar (XMM)"
"size": "Medium"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "11"
"hp": !!int "13"
"hit_dice": "2d8 + 4"
"modifier": !!int "0"
"stats":
  - !!int "13"
  - !!int "11"
  - !!int "14"
  - !!int "2"
  - !!int "9"
  - !!int "5"
"speed": "40 ft."
"senses": "passive Perception 9"
"languages": ""
"cr": "1/4"
"traits":
  - "desc": "While [Bloodied](conditions.md#Bloodied), the boar\
      \ has [Advantage](advantage) on\
      \ attack rolls."
    "name": "Bloodied Fury"
"actions":
  - "desc": "*Melee Attack Roll:* +3, reach 5 ft. *Hit:* 4 (1d6 + 1) Piercing\
      \ damage. If the target is a Medium or smaller creature and the boar moved 20+\
      \ feet straight toward it immediately before the hit, the target takes an extra\
      \ 3 (1d6) Piercing damage and has the [Prone](conditions.md#Prone)\
      \ condition."
    "name": "Gore"
"source":
  - "XMM"
  - "XPHB"
"image": "bestiary/tokens/XMM/Boar.webp"
```
^statblock

## Environment

forest, grassland, hill