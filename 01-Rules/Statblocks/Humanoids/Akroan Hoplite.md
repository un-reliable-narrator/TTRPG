---
cssclasses:
  - json5e-monster
tags:
  - src/5e/mot
  - monster/cr/3
  - monster/size/medium
  - monster/type/humanoid
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Akroan Hoplite
---
# [Akroan Hoplite](Akroan%20Hoplite.md)
*Source: Mythic Odysseys of Theros p. 228*  

![](https://5e.tools/img/bestiary/MOT/Hoplite.webp)

Hoplites are highly trained warriors, versed not only in strategy and tactics but in the glorification of the warrior's spirit, the basis of an ethos that forges an unbreakable bond between members of a military unit. In combat, hoplites typically work in groups and use coordinated tactics to win victories.

The three Hoplite Unit Names tables present the sorts of titles used by hoplite contingents hailing from Theros's great poleis. Consider using these names for military forces characters encounter during their adventures or that they were once a part of.

**Akroan Hoplite Unit Names**

| D8 | Name |
|---|---|
| 1 | Spears of Iroas |
| 2 | Iron Fangs |
| 3 | Arrows of Anax |
| 4 | The Unbroken |
| 5 | Anvil of Purphoros |
| 6 | Skewering Squad |
| 7 | Shield of Akros |
| 8 | Cymede's Heart |

**Meletian Hoplite Unit Names**

| D8 | Name |
|---|---|
| 1 | Kraken's Claw |
| 2 | Hands of Justice |
| 3 | Thassa's Spear |
| 4 | Ephara's Shield |
| 5 | Kindred of the Deep |
| 6 | Riders of Heliod |
| 7 | Keepers of Pyrgnos |
| 8 | The Skysworn |

**Setessan Hoplite Unit Names**

| d8 | Name |
|---|---|
| 1 | Nylea's Arrows |
| 2 | The Watchers |
| 3 | Fangs of Ophis |
| 4 | The Swiftswords |
| 5 | Karametra's Wolves |
| 6 | Defenders of the Grove |
| 7 | Bronze Blades |
| 8 | The Jackals |

```statblock
"name": "Akroan Hoplite (MOT)"
"size": "Medium"
"type": "humanoid"
"alignment": "Any alignment"
"ac": !!int "18"
"ac_class": "[breastplate](Breastplate.md), [shield](Shield.md)"
"hp": !!int "52"
"hit_dice": "8d8 + 16"
"modifier": !!int "3"
"stats":
  - !!int "16"
  - !!int "16"
  - !!int "14"
  - !!int "11"
  - !!int "14"
  - !!int "13"
"speed": "30 ft."
"saves":
  - "strength": !!int "5"
  - "dexterity": !!int "5"
"senses": "passive Perception 12"
"languages": "Common"
"cr": "3"
"traits":
  - "desc": "While the hoplite is holding a spear, other creatures provoke an\
      \ opportunity attack from the hoplite when they move within 5 feet of it.\
      \ When the hoplite hits a creature with an opportunity attack using its\
      \ spear, the creature takes an extra 4 (1d8) piercing damage, and the\
      \ creature's speed becomes 0 for the rest of the turn."
    "name": "Hold the Line"
"actions":
  - "desc": "The hoplite makes three melee attacks or two ranged attacks."
    "name": "Multiattack"
  - "desc": "*Melee or Ranged Weapon Attack:* +5 to hit, reach 5 ft., or range\
      \ 20/60 ft., one target. *Hit:* 6 (1d6 + 3) piercing damage, or 7 (1d8 +\
      \ 3) piercing damage if used with two hands to make a melee attack."
    "name": "Spear"
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one creature.\
      \ *Hit:* 5 (1d4 + 3) bludgeoning damage. If the target is a Medium or\
      \ smaller creature, it must succeed on a DC 13 Strength saving throw or\
      \ be knocked [prone](conditions.md#Prone)."
    "name": "Shield Bash"
"source":
  - "MOT"
"image": "bestiary/tokens/MOT/Akroan Hoplite.webp"
```
^statblock
