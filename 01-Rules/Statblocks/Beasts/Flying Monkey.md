---
cssclasses:
  - json5e-monster
tags:
  - src/5e/toa
  - monster/cr/0
  - monster/size/small
  - monster/type/beast
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Flying Monkey
---
# [Flying Monkey](Flying%20Monkey.md)
*Source: Tomb of Annihilation p. 220*  

![](https://5e.tools/img/bestiary/ToA/Flying%20Monkey.webp)

Flying monkeys are slightly more clever and curious than common monkeys, and they can be domesticated and taught to obey simple commands. They come in many colors and varieties, with feathered wings that have a span of about 5 feet. With the DM's permission, the [find familiar](Find-Familiar.md) spell can summon a flying monkey.

```statblock
"name": "Flying Monkey (ToA)"
"size": "Small"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "12"
"hp": !!int "3"
"hit_dice": "1d6"
"modifier": !!int "2"
"stats":
  - !!int "8"
  - !!int "14"
  - !!int "11"
  - !!int "5"
  - !!int "12"
  - !!int "6"
"speed": "30 ft., climb 20 ft., fly 30 ft."
"senses": "passive Perception 11"
"languages": ""
"cr": "0"
"traits":
  - "desc": "The flying monkey has advantage on an attack roll against a\
      \ creature if at least one of the monkey's allies is within 5 feet of the\
      \ creature and the ally isn't\
      \ [incapacitated](conditions.md#Incapacitated)."
    "name": "Pack Tactics"
  - "desc": "With the DM's permission, the [find familiar](Find-Familiar.md)\
      \ spell can summon a flying monkey."
    "name": "Familiar"
"actions":
  - "desc": "*Melee Weapon Attack:* +1 to hit, reach 5 ft., one target *Hit:* 1\
      \ (1d4 - 1) piercing damage."
    "name": "Bite"
"source":
  - "ToA"
"image": "bestiary/tokens/ToA/Flying Monkey.webp"
```
^statblock
