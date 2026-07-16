---
cssclasses:
- json5e-monster
tags:
- src/5e/xmm
- monster/cr/1-4
- monster/environment/forest
- monster/environment/swamp
- monster/size/medium
- monster/type/beast
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Giant Frog"
---
# [Giant Frog](Giant-frog.md)
*Source: Monster Manual (2024) p. 357. Available in the <span title='Systems Reference Document (5.2)'>SRD</span> and the Free Rules (2024)*  

## Animals

Use these stat blocks to represent the creatures they're named for or other similar creatures. For example, the [Panther](Panther.md) stat block can also represent a mountain lion, while the [Giant Goat](Giant-Goat.md) stat block might represent a buffalo. Any of these stat blocks might also serve as fantastical animals with distinctive names and cosmetic details unique to your D&D adventures.

```statblock
"name": "Giant Frog (XMM)"
"size": "Medium"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "11"
"hp": !!int "18"
"hit_dice": "4d8"
"modifier": !!int "1"
"stats":
  - !!int "12"
  - !!int "13"
  - !!int "11"
  - !!int "2"
  - !!int "10"
  - !!int "3"
"speed": "30 ft., swim 30 ft."
"skillsaves":
  - "name": "[Perception](Perception)"
    "desc": "+2"
  - "name": "[Stealth](Stealth)"
    "desc": "+4"
"senses": "[Darkvision](senses.md#Darkvision) 30 ft., passive\
  \ Perception 12"
"languages": ""
"cr": "1/4"
"traits":
  - "desc": "The frog can breathe air and water."
    "name": "Amphibious"
  - "desc": "The frog's [Long Jump](long-jump)\
      \ is up to 20 feet and its [High Jump](high-jump)\
      \ is up to 10 feet with or without a running start."
    "name": "Standing Leap"
"actions":
  - "desc": "*Melee Attack Roll:* +3, reach 5 ft. *Hit:* 5 (1d6 + 2) Piercing\
      \ damage. If the target is a Medium or smaller creature, it has the [Grappled](conditions.md#Grappled)\
      \ condition (escape DC 11)."
    "name": "Bite"
  - "desc": "The frog swallows a Small or smaller target it is grappling. While swallowed,\
      \ the target isn't [Grappled](conditions.md#Grappled)\
      \ but has the [Blinded](conditions.md#Blinded) and [Restrained](conditions.md#Restrained)\
      \ conditions, and it has [Total Cover](cover)\
      \ against attacks and other effects outside the frog. While swallowing the target,\
      \ the frog can't use Bite, and if the frog dies, the swallowed target is no\
      \ longer [Restrained](conditions.md#Restrained) and can\
      \ escape from the corpse using 5 feet of movement, exiting with the [Prone](conditions.md#Prone)\
      \ condition.\n\nAt the end of the frog's next turn, the swallowed target takes\
      \ 5 (2d4) Acid damage. If that damage doesn't kill it, the frog disgorges\
      \ it, causing it to exit [Prone](conditions.md#Prone)."
    "name": "Swallow"
"source":
  - "XMM"
"image": "bestiary/tokens/XMM/Giant Frog.webp"
```
^statblock

## Environment

forest, swamp