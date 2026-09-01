---
cssclasses:
- json5e-monster
tags:
- src/5e/xmm
- monster/cr/1
- monster/environment/forest
- monster/environment/hill
- monster/size/large
- monster/type/beast
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Dire Wolf"
---
# [Dire Wolf](Dire-Wolf.md)
*Source: Monster Manual (2024) p. 352, Player's Handbook (2024) p. 348. Available in the <span title='Systems Reference Document (5.2)'>SRD</span> and the Free Rules (2024)*  

## Animals

Use these stat blocks to represent the creatures they're named for or other similar creatures. For example, the [Panther](Panther.md) stat block can also represent a mountain lion, while the [Giant Goat](Giant-Goat.md) stat block might represent a buffalo. Any of these stat blocks might also serve as fantastical animals with distinctive names and cosmetic details unique to your D&D adventures.

```statblock
"name": "Dire Wolf (XMM)"
"size": "Large"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "14"
"hp": !!int "22"
"hit_dice": "3d10 + 6"
"modifier": !!int "2"
"stats":
  - !!int "17"
  - !!int "15"
  - !!int "15"
  - !!int "3"
  - !!int "12"
  - !!int "7"
"speed": "50 ft."
"skillsaves":
  - "name": "[Perception](Perception)"
    "desc": "+5"
  - "name": "[Stealth](Stealth)"
    "desc": "+4"
"senses": "[Darkvision](senses.md#Darkvision) 60 ft., passive\
  \ Perception 15"
"languages": ""
"cr": "1"
"traits":
  - "desc": "The wolf has [Advantage](advantage)\
      \ on an attack roll against a creature if at least one of the wolf's allies\
      \ is within 5 feet of the creature and the ally doesn't have the [Incapacitated](conditions.md#Incapacitated)\
      \ condition."
    "name": "Pack Tactics"
"actions":
  - "desc": "*Melee Attack Roll:* +5, reach 5 ft. *Hit:* 8 (1d10 + 3) Piercing\
      \ damage. If the target is a Large or smaller creature, it has the [Prone](conditions.md#Prone)\
      \ condition."
    "name": "Bite"
"source":
  - "XMM"
  - "XPHB"
"image": "bestiary/tokens/XMM/Dire Wolf.webp"
```
^statblock

## Environment

forest, hill