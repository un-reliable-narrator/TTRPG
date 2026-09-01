---
cssclasses:
- json5e-monster
tags:
- src/5e/xmm
- monster/cr/1-4
- monster/environment/underdark
- monster/size/medium
- monster/type/plant
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Violet Fungus"
---
# [Violet Fungus](violet-fungus.md)
*Source: Monster Manual (2024) p. 126. Available in the <span title='Systems Reference Document (5.2)'>SRD</span> and the Free Rules (2024)*  

Slow but mobile, violet fungi rot any flesh they touch with their lashing tendrils.

## Fungi

*Deadly Spores and Predatory Polyps*

- **Habitat.** Underdark  
- **Treasure.** None  

The dank, sunless Underdark is a fertile breeding ground for weird and dangerous fungi.

```statblock
"name": "Violet Fungus (XMM)"
"size": "Medium"
"type": "plant"
"alignment": "Unaligned"
"ac": !!int "5"
"hp": !!int "18"
"hit_dice": "4d8"
"modifier": !!int "-5"
"stats":
  - !!int "3"
  - !!int "1"
  - !!int "10"
  - !!int "1"
  - !!int "3"
  - !!int "1"
"speed": "5 ft."
"condition_immunities": "[blinded](conditions.md#Blinded), [charmed](conditions.md#Charmed),\
  \ [deafened](conditions.md#Deafened), [frightened](conditions.md#Frightened)"
"senses": "[Blindsight](senses.md#Blindsight) 30 ft., passive\
  \ Perception 6"
"languages": ""
"cr": "1/4"
"actions":
  - "desc": "The fungus makes two Rotting Touch attacks."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +2, reach 10 ft. *Hit:* 4 (1d8) Necrotic damage."
    "name": "Rotting Touch"
"source":
  - "XMM"
"image": "bestiary/tokens/XMM/Violet Fungus.webp"
```
^statblock

## Environment

underdark