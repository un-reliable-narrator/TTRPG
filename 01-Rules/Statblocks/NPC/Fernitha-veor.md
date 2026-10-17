---
cssclasses:
  - json5e-monster
tags:
  - src/5e/veor
  - monster/cr/12
  - monster/size/medium
  - monster/type/fiend/devil
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Fernitha
---
# [Fernitha](Fernitha-veor.md)
*Source: Vecna: Eve of Ruin p. 53*  

![](https://5e.tools/img/bestiary/tokens/VEoR/Fernitha.webp)

```statblock
"name": "Fernitha (VEoR)"
"size": "Medium"
"type": "fiend"
"subtype": "devil"
"alignment": "Lawful Evil"
"ac": !!int "18"
"ac_class": "[plate armor](Plate-Armor.md)"
"hp": !!int "153"
"hit_dice": "18d8 + 72"
"modifier": !!int "3"
"stats":
  - !!int "18"
  - !!int "16"
  - !!int "18"
  - !!int "14"
  - !!int "14"
  - !!int "18"
"speed": "30 ft., fly 60 ft."
"saves":
  - "dexterity": !!int "7"
  - "constitution": !!int "8"
  - "wisdom": !!int "6"
  - "charisma": !!int "8"
"damage_resistances": "cold; bludgeoning, piercing, slashing from nonmagical\
  \ attacks that aren't silvered"
"damage_immunities": "fire, poison"
"condition_immunities": "[poisoned](conditions.md#Poisoned)"
"senses": "[Truesight](senses.md#Truesight) 120 ft., passive Perception 12"
"languages": "Infernal, telepathy 120 ft."
"cr": "12"
"traits":
  - "desc": "Fernitha's weapon attacks are magical and deal an extra 13 (3d8)\
      \ poison damage on a hit (included in the attacks)."
    "name": "Hellish Weapons"
  - "desc": "Fernitha has advantage on saving throws against spells and other\
      \ magical effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "Fernitha makes three attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +8 to hit, reach 5 ft., one target. *Hit:*\
      \ 8 (1d8 + 4) slashing damage, or 9 (1d10 + 4) slashing damage if used\
      \ with two hands, plus 13 (3d8) poison damage."
    "name": "Longsword"
  - "desc": "*Ranged Weapon Attack:* +7 to hit, range 150/600 ft., one target.\
      \ *Hit:* 7 (1d8 + 3) piercing damage plus 13 (3d8) poison damage, and the\
      \ target must succeed on a DC 14 Constitution saving throw or be\
      \ [poisoned](conditions.md#Poisoned). The poison lasts until it is\
      \ removed by the [lesser restoration](Lesser-Restoration.md) spell or\
      \ similar magic."
    "name": "Longbow"
"reactions":
  - "desc": "Fernitha adds 4 to its AC against one melee attack that would hit\
      \ it. To do so, Fernitha must see the attacker and be wielding a melee\
      \ weapon."
    "name": "Parry"
"source":
  - "VEoR"
"image": "bestiary/tokens/VEoR/Fernitha.webp"
```
^statblock

## Rope of Entanglement

Some erinyes carry a [rope of entanglement](rope-of-entanglement.md) (detailed in the Dungeon Master's Guide). When such an erinyes uses its Multiattack, Fernitha can use the rope in place of two of the attacks.

## Summon Devil (1/Day)

The devil chooses what to summon and attempts a magical summoning.

An erinyes has a 50 percent chance of summoning 3d6 [spined devils](spined-Devil.md), 1d6 [bearded devils](Bearded-Devil.md), or one [erinyes](erinyes.md).

A summoned devil appears in an unoccupied space within 60 feet of its summoner, acts as an ally of its summoner, and can't summon other devils. It remains for 1 minute, until it or its summoner dies, or until its summoner dismisses it as an action.
