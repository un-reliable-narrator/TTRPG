---
cssclasses:
  - json5e-monster
tags:
  - src/5e/veor
  - monster/cr/11
  - monster/size/large
  - monster/type/fiend/demon
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Degloth
---
# [Degloth](Degloth-veor.md)
*Source: Vecna: Eve of Ruin p. 218*  

![](https://5e.tools/img/bestiary/VEoR/Degloth.webp)

Degloths are massive, blue, bipedal demons with razor-studded fists. They are commonly used as shock troops on the front lines of wars waged in the Abyss and other Outer Planes. Degloths gravitate toward violence and mayhem without caring about the reasons behind the bloodshed. They enjoy ripping their enemies limb from limb using their razor-studded fists, which are equally adept at slashing foes and crushing the life from them.

```statblock
"name": "Degloth (VEoR)"
"size": "Large"
"type": "fiend"
"subtype": "demon"
"alignment": "typically Chaotic Evil"
"ac": !!int "18"
"ac_class": "natural armor"
"hp": !!int "133"
"hit_dice": "14d10 + 56"
"modifier": !!int "3"
"stats":
  - !!int "23"
  - !!int "17"
  - !!int "18"
  - !!int "6"
  - !!int "11"
  - !!int "9"
"speed": "40 ft., climb 40 ft."
"saves":
  - "strength": !!int "10"
  - "constitution": !!int "8"
"skillsaves":
  - "name": "[Athletics](skills.md#Athletics)"
    "desc": "+10"
  - "name": "[Perception](skills.md#Perception)"
    "desc": "+4"
"damage_resistances": "cold; fire; lightning; bludgeoning, piercing, slashing\
  \ from nonmagical attacks"
"damage_immunities": "poison"
"condition_immunities": "[charmed](conditions.md#Charmed),\
  \ [exhaustion](conditions.md#Exhaustion),\
  \ [frightened](conditions.md#Frightened), [poisoned](conditions.md#Poisoned)"
"senses": "[Darkvision](senses.md#Darkvision) 120 ft., passive Perception 14"
"languages": "Abyssal, telepathy 120 ft."
"cr": "11"
"traits":
  - "desc": "The degloth has advantage on saving throws against spells and\
      \ other magical effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "The degloth makes two Razor Fist attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +10 to hit, reach 10 ft., one target.\
      \ *Hit:* 17 (2d10 + 6) slashing damage, and if the target is a Medium or\
      \ smaller creature, the target has the [grappled](conditions.md#Grappled)\
      \ condition (escape DC 18). Until this grapple ends, the target has the\
      \ [restrained](conditions.md#Restrained) condition, and the degloth can't\
      \ use this fist to grapple another target. The degloth has two fists."
    "name": "Razor Fist"
"bonus_actions":
  - "desc": "The degloth targets one creature currently\
      \ [grappled](conditions.md#Grappled) by it. The target must make a DC 18\
      \ Strength saving throw, taking 15 (2d8 + 6) bludgeoning damage on a\
      \ failed save or half as much damage on a successful one."
    "name": "Crush"
"source":
  - "VEoR"
"image": "bestiary/tokens/VEoR/Degloth.webp"
```
^statblock
