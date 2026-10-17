---
cssclasses:
  - json5e-monster
tags:
  - src/5e/cm
  - monster/cr/13
  - monster/size/large
  - monster/type/construct
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Canopic Golem
---
# [Canopic Golem](Canopic-Golem-cm.md)
*Source: Candlekeep Mysteries p. 179*  

![](https://5e.tools/img/bestiary/CM/Canopic%20Golem.webp)

A mummy lord's organs, normally stored in sacred canopic jars during mummification, can be magically preserved and transplanted into living humanoids. The transplant recipients come under the control of the mummy lord, either as living supplicants or mindless golems through which the mummy lord can see and speak.

```statblock
"name": "Canopic Golem (CM)"
"size": "Large"
"type": "construct"
"alignment": ""
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "252"
"hit_dice": "24d10 + 120"
"modifier": !!int "0"
"stats":
  - !!int "20"
  - !!int "10"
  - !!int "20"
  - !!int "7"
  - !!int "11"
  - !!int "1"
"speed": "30 ft."
"saves":
  - "intelligence": !!int "3"
  - "wisdom": !!int "5"
  - "charisma": !!int "0"
"damage_immunities": "poison"
"condition_immunities": "[blinded](conditions.md#Blinded),\
  \ [charmed](conditions.md#Charmed), [deafened](conditions.md#Deafened),\
  \ [exhaustion](conditions.md#Exhaustion),\
  \ [frightened](conditions.md#Frightened),\
  \ [paralyzed](conditions.md#Paralyzed), [petrified](conditions.md#Petrified),\
  \ [poisoned](conditions.md#Poisoned)"
"senses": "[Darkvision](senses.md#Darkvision) 120 ft., passive Perception 10"
"languages": ""
"cr": "13"
"traits":
  - "desc": "The golem automatically succeeds on saving throws against spells\
      \ of 7th level or lower, and the attack rolls of such spells always miss\
      \ it."
    "name": "Limited Spell Immunity"
  - "desc": "The golem doesn't require air, food, drink, or sleep."
    "name": "Unusual Nature"
"actions":
  - "desc": "The golem makes two attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +10 to hit, reach 5 ft., one target. *Hit:*\
      \ 27 (4d10 + 5) force damage."
    "name": "Slam"
  - "desc": "*Ranged Weapon Attack:* +10 to hit, range 120 ft., one target.\
      \ *Hit:* 14 (2d8 + 5) force damage."
    "name": "Crystal Dart"
"reactions":
  - "desc": "In response to a spell attack missing the golem, it causes that\
      \ spell to hit another creature within 120 feet of it that it can see."
    "name": "Spell Deflection"
"source":
  - "CM"
"image": "bestiary/tokens/CM/Canopic Golem.webp"
```
^statblock
