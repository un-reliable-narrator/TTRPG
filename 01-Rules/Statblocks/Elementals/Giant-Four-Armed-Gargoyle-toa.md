---
cssclasses:
  - json5e-monster
tags:
  - src/5e/toa
  - monster/cr/10
  - monster/size/large
  - monster/type/elemental
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Giant Four-Armed Gargoyle
---
# [Giant Four-Armed Gargoyle](Giant-Four-Armed-Gargoyle-toa.md)
*Source: Tomb of Annihilation p. 221*  

![](https://5e.tools/img/bestiary/ToA/Giant%20Four-Armed%20Gargoyle.webp)

Only Acererak knows the secret of creating these creatures. A giant four-armed gargoyle stands 8 to 9 feet tall and weighs roughly five thousand pounds. It is typically employed as a tomb guardian, rending intruders with its fangs and deadly claws. For more information on gargoyles, see the Monster Manual.

```statblock
"name": "Giant Four-Armed Gargoyle (ToA)"
"size": "Large"
"type": "elemental"
"alignment": "Chaotic Evil"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "147"
"hit_dice": "14d10 + 70"
"modifier": !!int "0"
"stats":
  - !!int "19"
  - !!int "11"
  - !!int "20"
  - !!int "6"
  - !!int "11"
  - !!int "9"
"speed": "30 ft., fly 60 ft."
"saves":
  - "wisdom": !!int "4"
"skillsaves":
  - "name": "[Perception](skills.md#Perception)"
    "desc": "+4"
"damage_resistances": "bludgeoning, piercing, slashing from nonmagical attacks\
  \ not made with adamantine weapons"
"damage_immunities": "poison"
"condition_immunities": "[exhaustion](conditions.md#Exhaustion),\
  \ [petrified](conditions.md#Petrified), [poisoned](conditions.md#Poisoned)"
"senses": "[Darkvision](senses.md#Darkvision) 60 ft., passive Perception 14"
"languages": "Terran"
"cr": "10"
"traits":
  - "desc": "While the gargoyle remains motionless, it is indistinguishable\
      \ from an inanimate statue."
    "name": "False Appearance"
"actions":
  - "desc": "The gargoyle makes five attacks: one with its bite and four with\
      \ its claws."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +8 to hit, reach 5 ft., one target. *Hit:*\
      \ 11 (2d6 + 4) piercing damage."
    "name": "Bite"
  - "desc": "*Melee Weapon Attack:* +8 to hit, reach 5 ft., one target. *Hit:*\
      \ 9 (2d4 + 4) slashing damage."
    "name": "Claw"
"source":
  - "ToA"
"image": "bestiary/tokens/ToA/Giant Four-Armed Gargoyle.webp"
```
^statblock
