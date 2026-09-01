---
cssclasses:
- json5e-monster
tags:
- src/5e/xmm
- monster/cr/2
- monster/environment/underwater
- monster/size/large
- monster/type/beast
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Hunter Shark"
---
# [Hunter Shark](Hunter-Shark.md)
*Source: Monster Manual (2024) p. 363. Available in the <span title='Systems Reference Document (5.2)'>SRD</span> and the Free Rules (2024)*  

## Animals

Use these stat blocks to represent the creatures they're named for or other similar creatures. For example, the [Panther](Panther.md) stat block can also represent a mountain lion, while the [Giant Goat](Giant-Goat.md) stat block might represent a buffalo. Any of these stat blocks might also serve as fantastical animals with distinctive names and cosmetic details unique to your D&D adventures.

```statblock
"name": "Hunter Shark (XMM)"
"size": "Large"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "12"
"hp": !!int "45"
"hit_dice": "6d10 + 12"
"modifier": !!int "2"
"stats":
  - !!int "18"
  - !!int "14"
  - !!int "15"
  - !!int "1"
  - !!int "10"
  - !!int "4"
"speed": "5 ft., swim 40 ft."
"skillsaves":
  - "name": "[Perception](Perception)"
    "desc": "+2"
"senses": "[Blindsight](senses.md#Blindsight) 60 ft., passive\
  \ Perception 12"
"languages": ""
"cr": "2"
"traits":
  - "desc": "The shark can breathe only underwater."
    "name": "Water Breathing"
"actions":
  - "desc": "*Melee Attack Roll:* +6 (with [Advantage](advantage)\
      \ if the target doesn't have all its [Hit Points](hit-points)),\
      \ reach 5 ft. *Hit:* 14 (3d6 + 4) Piercing damage."
    "name": "Bite"
"source":
  - "XMM"
"image": "bestiary/tokens/XMM/Hunter Shark.webp"
```
^statblock

## Environment

underwater