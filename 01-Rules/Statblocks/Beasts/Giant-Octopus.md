---
cssclasses:
- json5e-monster
tags:
- src/5e/xmm
- monster/cr/1
- monster/environment/underwater
- monster/size/large
- monster/type/beast
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Giant Octopus"
---
# [Giant Octopus](Giant-Octopus.md)
*Source: Monster Manual (2024) p. 358. Available in the <span title='Systems Reference Document (5.2)'>SRD</span> and the Free Rules (2024)*  

## Animals

Use these stat blocks to represent the creatures they're named for or other similar creatures. For example, the [Panther](Panther.md) stat block can also represent a mountain lion, while the [Giant Goat](Giant-Goat.md) stat block might represent a buffalo. Any of these stat blocks might also serve as fantastical animals with distinctive names and cosmetic details unique to your D&D adventures.

```statblock
"name": "Giant Octopus (XMM)"
"size": "Large"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "11"
"hp": !!int "45"
"hit_dice": "7d10 + 7"
"modifier": !!int "1"
"stats":
  - !!int "17"
  - !!int "13"
  - !!int "13"
  - !!int "5"
  - !!int "10"
  - !!int "4"
"speed": "10 ft., swim 60 ft."
"skillsaves":
  - "name": "[Perception](Perception)"
    "desc": "+4"
  - "name": "[Stealth](Stealth)"
    "desc": "+5"
"senses": "[Darkvision](senses.md#Darkvision) 60 ft., passive\
  \ Perception 14"
"languages": ""
"cr": "1"
"traits":
  - "desc": "The octopus can breathe only underwater. It can hold its breath for 1\
      \ hour outside water."
    "name": "Water Breathing"
"actions":
  - "desc": "*Melee Attack Roll:* +5, reach 10 ft. *Hit:* 10 (2d6 + 3) Bludgeoning\
      \ damage. If the target is a Medium or smaller creature, it has the [Grappled](conditions.md#Grappled)\
      \ condition (escape DC 13) from all eight tentacles. While [Grappled](conditions.md#Grappled),\
      \ the target has the [Restrained](conditions.md#Restrained)\
      \ condition."
    "name": "Tentacles"
"reactions":
  - "desc": "Trigger: The octopus takes damage while underwater. _Response:_ The octopus\
      \ releases ink that fills a 10-foot [Cube](cube-area-of-effect)\
      \ centered on itself, and the octopus moves up to its [Swim Speed](swim-speed).\
      \ The [Cube](cube-area-of-effect)\
      \ is [Heavily Obscured](heavily-obscured)\
      \ for 1 minute or until a strong current or similar effect disperses the ink."
    "name": "Ink Cloud (1/Day)"
"source":
  - "XMM"
"image": "bestiary/tokens/XMM/Giant Octopus.webp"
```
^statblock

## Environment

underwater