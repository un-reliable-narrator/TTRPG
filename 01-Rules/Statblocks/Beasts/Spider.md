---
cssclasses:
- json5e-monster
tags:
- src/5e/xmm
- monster/cr/0
- monster/environment/desert
- monster/environment/forest
- monster/environment/swamp
- monster/environment/underdark
- monster/environment/urban
- monster/size/tiny
- monster/type/beast
statblock: inline
statblock-link: "#^statblock"
---
# [Spider](Spider.md)
*Source: Monster Manual (2024) p. 369, Player's Handbook (2024) p. 357. Available in the <span title='Systems Reference Document (5.2)'>SRD</span> and the Free Rules (2024)*  

## Animals

Use these stat blocks to represent the creatures they're named for or other similar creatures. For example, the [Panther](Panther.md) stat block can also represent a mountain lion, while the [Giant Goat](Giant-Goat.md) stat block might represent a buffalo. Any of these stat blocks might also serve as fantastical animals with distinctive names and cosmetic details unique to your D&D adventures.

```statblock
"name": "Spider (XMM)"
"size": "Tiny"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "12"
"hp": !!int "1"
"hit_dice": "1d4 - 1"
"modifier": !!int "2"
"stats":
  - !!int "2"
  - !!int "14"
  - !!int "8"
  - !!int "1"
  - !!int "10"
  - !!int "2"
"speed": "20 ft., climb 20 ft."
"skillsaves":
  - "name": "[Stealth](Stealth)"
    "desc": "+4"
"senses": "[Darkvision](senses.md#Darkvision) 30 ft., passive\
  \ Perception 10"
"languages": ""
"cr": "0"
"traits":
  - "desc": "The spider can climb difficult surfaces, including along ceilings, without\
      \ needing to make an ability check."
    "name": "Spider Climb"
  - "desc": "The spider ignores movement restrictions caused by webs, and the spider\
      \ knows the location of any other creature in contact with the same web."
    "name": "Web Walker"
"actions":
  - "desc": "*Melee Attack Roll:* +4, reach 5 ft. *Hit:* 1 Piercing damage plus\
      \ 2 (1d4) Poison damage."
    "name": "Bite"
"source":
  - "XMM"
  - "XPHB"
"image": "bestiary/tokens/XMM/Spider.webp"
```
^statblock

## Environment

desert, forest, swamp, underdark, urban