---
cssclasses:
- json5e-monster
tags:
- src/5e/mpmm
- monster/cr/7
- monster/size/medium
- monster/type/elemental
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Earth Elemental Myrmidon"
---
# [Earth Elemental Myrmidon](earth-Elemental-myrmidon-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 122*  

## Elemental Myrmidons

Elemental myrmidons are Elementals conjured and bound by magic into ritually created suits of plate armor. In this form, they possess no recollection of their former existence as free Elementals. They exist only to follow the commands of their creators.

```statblock
"name": "Earth Elemental Myrmidon (MPMM)"
"size": "Medium"
"type": "elemental"
"alignment": "Typically  Neutral"
"ac": !!int "18"
"ac_class": "[plate](plate-armor)"
"hp": !!int "127"
"hit_dice": "17d8 + 51"
"modifier": !!int "0"
"stats":
  - !!int "18"
  - !!int "10"
  - !!int "17"
  - !!int "8"
  - !!int "10"
  - !!int "10"
"speed": "30 ft."
"damage_resistances": "bludgeoning, piercing, slashing from nonmagical attacks"
"damage_immunities": "poison"
"condition_immunities": "[paralyzed](conditions.md#Paralyzed),\
  \ [petrified](conditions.md#Petrified), [poisoned](conditions.md#Poisoned),\
  \ [prone](conditions.md#Prone)"
"gear":
  - "[maul](maul)"
"senses": "[Darkvision](senses.md#Darkvision) 60 ft., passive\
  \ Perception 10"
"languages": "Terran, one language of its creator's choice"
"cr": "7"
"actions":
  - "desc": "The myrmidon makes two Maul attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +7 to hit, reach 5 ft., one target. *Hit:* 11\
      \ (2d6 + 4) force damage."
    "name": "Maul"
  - "desc": "The myrmidon makes one Maul attack. On a hit, the target takes an extra\
      \ 22 (4d10) thunder damage, and the target must succeed on a DC 14 Strength\
      \ saving throw or be knocked [prone](conditions.md#Prone)."
    "name": "Thunderous Strike (Recharge 6)"
"source":
  - "MPMM"
"image": "bestiary/tokens/MPMM/Earth Elemental Myrmidon.webp"
```
^statblock