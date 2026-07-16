---
cssclasses:
- json5e-monster
tags:
- src/5e/xmm
- monster/cr/1
- monster/environment/desert
- monster/environment/grassland
- monster/environment/hill
- monster/size/large
- monster/type/monstrosity
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Giant Vulture"
---
# [Giant Vulture](Giant-vulture.md)
*Source: Monster Manual (2024) p. 361. Available in the <span title='Systems Reference Document (5.2)'>SRD</span> and the Free Rules (2024)*  

## Animals

Use these stat blocks to represent the creatures they're named for or other similar creatures. For example, the [Panther](Panther.md) stat block can also represent a mountain lion, while the [Giant Goat](Giant-Goat.md) stat block might represent a buffalo. Any of these stat blocks might also serve as fantastical animals with distinctive names and cosmetic details unique to your D&D adventures.

```statblock
"name": "Giant Vulture (XMM)"
"size": "Large"
"type": "monstrosity"
"alignment": "Neutral Evil"
"ac": !!int "10"
"hp": !!int "25"
"hit_dice": "3d10 + 9"
"modifier": !!int "0"
"stats":
  - !!int "15"
  - !!int "10"
  - !!int "16"
  - !!int "6"
  - !!int "12"
  - !!int "7"
"speed": "10 ft., fly 60 ft."
"skillsaves":
  - "name": "[Perception](Perception)"
    "desc": "+3"
"damage_resistances": "necrotic"
"senses": "[Darkvision](senses.md#Darkvision) 60 ft., passive\
  \ Perception 13"
"languages": "understands Common but can't speak"
"cr": "1"
"traits":
  - "desc": "The vulture has [Advantage](advantage)\
      \ on an attack roll against a creature if at least one of the vulture's allies\
      \ is within 5 feet of the creature and the ally doesn't have the [Incapacitated](conditions.md#Incapacitated)\
      \ condition."
    "name": "Pack Tactics"
"actions":
  - "desc": "*Melee Attack Roll:* +4, reach 5 ft. *Hit:* 9 (2d6 + 2) Piercing\
      \ damage, and the target has the [poisoned](conditions.md#Poisoned)\
      \ condition until the end of its next turn."
    "name": "Gouge"
"source":
  - "XMM"
"image": "bestiary/tokens/XMM/Giant Vulture.webp"
```
^statblock

## Environment

desert, grassland, hill