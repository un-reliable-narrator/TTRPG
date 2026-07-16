---
cssclasses:
- json5e-monster
tags:
- src/5e/xmm
- monster/cr/4
- monster/environment/underwater
- monster/size/huge
- monster/type/Beasts/dinosaur
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Archelon"
---
# [Archelon](Archelon.md)
*Source: Monster Manual (2024) p. 349. Available in the <span title='Systems Reference Document (5.2)'>SRD</span> and the Free Rules (2024)*  

## Animals

Use these stat blocks to represent the creatures they're named for or other similar creatures. For example, the [Panther](Panther.md) stat block can also represent a mountain lion, while the [Giant Goat](Giant-Goat.md) stat block might represent a buffalo. Any of these stat blocks might also serve as fantastical animals with distinctive names and cosmetic details unique to your D&D adventures.

```statblock
"name": "Archelon (XMM)"
"size": "Huge"
"type": "beast"
"subtype": "dinosaur"
"alignment": "Unaligned"
"ac": !!int "17"
"hp": !!int "90"
"hit_dice": "12d12 + 12"
"modifier": !!int "3"
"stats":
  - !!int "18"
  - !!int "16"
  - !!int "13"
  - !!int "4"
  - !!int "14"
  - !!int "6"
"speed": "20 ft., swim 80 ft."
"skillsaves":
  - "name": "[Stealth](Stealth)"
    "desc": "+5"
"senses": "passive Perception 12"
"languages": ""
"cr": "4"
"traits":
  - "desc": "The archelon can breathe air and water."
    "name": "Amphibious"
"actions":
  - "desc": "The archelon makes two Bite attacks."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +6, reach 5 ft. *Hit:* 14 (3d6 + 4) Piercing\
      \ damage."
    "name": "Bite"
"source":
  - "XMM"
"image": "bestiary/tokens/XMM/Archelon.webp"
```
^statblock

## Environment

underwater