---
cssclasses:
  - json5e-monster
tags:
  - src/5e/veor
  - monster/cr/23
  - monster/size/medium
  - monster/type/humanoid/bard-tiefling
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Windfall
---
# [Windfall](Windfall-veor.md)
*Source: Vecna: Eve of Ruin p. 153*  

![](https://5e.tools/img/bestiary/VEoR/Windfall.webp)

As a dedicated champion of Tiamat, Windfall has been granted phenomenal power by her master. Her skin glitters with patches of multicolored scales, and in combat, her blade sings with all five of the chromatic dragons' elements. Windfall's enchanted tailcoat shimmers with the colors of the Dragon Queen, and she uses this coat to dazzle patrons and enemies alike.

A performer at heart, Windfall is ostentatious and charismatic, making small talk with regular patrons and jovially welcoming new faces to the casino.

```statblock
"name": "Windfall (VEoR)"
"size": "Medium"
"type": "humanoid"
"subtype": "bard, tiefling"
"alignment": "Chaotic Evil"
"ac": !!int "19"
"ac_class": "[studded leather armor](Studded-Leather-Armor.md)"
"hp": !!int "323"
"hit_dice": "34d8 + 170"
"modifier": !!int "7"
"stats":
  - !!int "14"
  - !!int "24"
  - !!int "20"
  - !!int "22"
  - !!int "18"
  - !!int "26"
"speed": "30 ft., fly 30 ft."
"saves":
  - "strength": !!int "9"
  - "dexterity": !!int "14"
  - "wisdom": !!int "11"
  - "charisma": !!int "15"
"skillsaves":
  - "name": "[Arcana](skills.md#Arcana)"
    "desc": "+13"
  - "name": "[Deception](skills.md#Deception)"
    "desc": "+22"
  - "name": "[Insight](skills.md#Insight)"
    "desc": "+18"
  - "name": "[Perception](skills.md#Perception)"
    "desc": "+11"
  - "name": "[Performance](skills.md#Performance)"
    "desc": "+22"
  - "name": "[Persuasion](skills.md#Persuasion)"
    "desc": "+22"
  - "name": "[Sleight Of Hand](skills.md#Sleight%20Of%20Hand)"
    "desc": "+14"
"damage_resistances": "acid, cold, fire, lightning, thunder"
"condition_immunities": "[charmed](conditions.md#Charmed),\
  \ [frightened](conditions.md#Frightened)"
"senses": "[Darkvision](senses.md#Darkvision) 60 ft., passive Perception 21"
"languages": "Common, Draconic, Infernal"
"cr": "23"
"traits":
  - "desc": "A brilliant array of chromatic colors emanates from Windfall,\
      \ causing attack rolls against her to have disadvantage. This trait\
      \ ceases to function while Windfall has the\
      \ [incapacitated](conditions.md#Incapacitated) condition or has a speed\
      \ of 0."
    "name": "Dazzling Visage"
  - "desc": "If Windfall fails a saving throw, she can choose to succeed\
      \ instead."
    "name": "Legendary Resistance (3/Day)"
  - "desc": "Windfall wears an iridescent magic coat that was tailored\
      \ specifically for her and imbued with Tiamat's power. When she dies, the\
      \ coat functions as a [Robe of Scintillating\
      \ Colors](robe-of-Scintillating-Colors.md)."
    "name": "Special Equipment"
"actions":
  - "desc": "Windfall makes two Chromatic Rapier attacks and uses Dragon's Fury\
      \ once."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +14 to hit, reach 5 ft., one target. *Hit:*\
      \ 11 (1d8 + 7) piercing damage plus 21 (6d6) acid, cold, fire, lightning,\
      \ or poison damage (Windfall's choice)."
    "name": "Chromatic Rapier"
  - "desc": "Windfall targets one creature she can see within 60 feet of\
      \ herself and unleashes a burst of magical ire. The target must make a DC\
      \ 23 Wisdom saving throw. On a failed save, the target takes 36 (8d8)\
      \ psychic damage and has the [frightened](conditions.md#Frightened)\
      \ condition until the start of Windfall's next turn. On a successful\
      \ save, the target takes half as much damage only."
    "name": "Dragon's Fury"
  - "desc": "Windfall casts one of the following spells, requiring no material\
      \ components and using Charisma as the spellcasting ability (spell save\
      \ DC 23):\n\n**At will:** [Detect Magic](Detect-Magic.md),\
      \ [Light](Light.md), [Thaumaturgy](Thaumaturgy.md)\n\n**3/day each:**\
      \ [Shatter](Shatter.md), [Unseen Servant](Unseen-Servant.md)\n\n**2/day\
      \ each:** [Hypnotic Pattern](Hypnotic-Pattern.md),\
      \ [Sending](Sending.md)\n\n**1/day:** [Hold Monster](Hold-Monster.md)"
    "name": "Spellcasting"
"bonus_actions":
  - "desc": "Windfall emits an overwhelming array of colors from her coat. Each\
      \ creature within 30 feet of Windfall that can see her must succeed on a\
      \ DC 23 Constitution saving throw or have the\
      \ [stunned](conditions.md#Stunned) condition until the start of\
      \ Windfall's next turn."
    "name": "Stunning Scintillation (Recharge 5-6)"
"legendary_description": "Legendary Action Uses: 3. Immediately after another\
  \ creature's turn, Windfall can expend a use to take one of the following\
  \ actions. Windfall regains all expended uses at the start of each of its\
  \ turns."
"legendary_actions":
  - "desc": "Windfall moves up to her speed without provoking opportunity\
      \ attacks."
    "name": "Deft Dance"
  - "desc": "Windfall flares with multicolored flames and targets a creature\
      \ she can see within 30 feet of herself. The target must make a DC 23\
      \ Dexterity saving throw. On a failed save, the target takes 26 (4d12)\
      \ damage of a type chosen by Windfall: acid, cold, fire, lightning, or\
      \ poison. On a successful save, the target takes half as much damage."
    "name": "Dragon's Flare"
  - "desc": "Windfall uses Spellcasting."
    "name": "Cast a Spell (Costs 2 Actions)"
"source":
  - "VEoR"
"image": "bestiary/tokens/VEoR/Windfall.webp"
```
^statblock
