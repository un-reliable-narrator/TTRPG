---
cssclasses:
- json5e-monster
tags:
- src/5e/xmm
- monster/cr/10
- monster/environment/any
- monster/size/small-or-medium
- monster/type/humanoid
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Noble Prodigy"
---
# [Noble Prodigy](Noble-Prodigy.md)
*Source: Monster Manual (2024) p. 227*  

Noble prodigies trace their lineage to a legendary hero, a demigod, a dragon, or some other ancestor that grants them magical prowess. Among some nobles, the source of a prodigy's magic might be a family secret.

## Nobles

*Royals and Rich Folk*

- **Habitat.** Any  
- **Treasure.** Individual  

Nobles encompass a variety of people with social influence. They might be rulers, wealthy merchants, callous bureaucrats, or the idle elite.

```statblock
"name": "Noble Prodigy (XMM)"
"size": "Small or Medium"
"type": "humanoid"
"alignment": "Neutral"
"ac": !!int "16"
"hp": !!int "148"
"hit_dice": "27d8 + 27"
"modifier": !!int "7"
"stats":
  - !!int "8"
  - !!int "16"
  - !!int "12"
  - !!int "15"
  - !!int "14"
  - !!int "19"
"speed": "30 ft."
"saves":
  - "dexterity": !!int "7"
  - "constitution": !!int "5"
  - "wisdom": !!int "6"
  - "charisma": !!int "8"
"skillsaves":
  - "name": "[Perception](Perception)"
    "desc": "+6"
  - "name": "[Persuasion](Persuasion)"
    "desc": "+8"
"senses": "passive Perception 16"
"languages": "Common plus two other languages"
"cr": "10"
"actions":
  - "desc": "The noble makes three Beguiling Strike attacks."
    "name": "Multiattack"
  - "desc": "*Melee  or Ranged Attack Roll:* +8, reach 5 ft. or range 60 ft. *Hit:*\
      \ 18 (4d6 + 4) Psychic damage, and the target has the [Charmed](conditions.md#Charmed)\
      \ condition until the start of the noble's next turn."
    "name": "Beguiling Strike"
  - "desc": "The noble casts one of the following spells, requiring no Material components\
      \ and using Charisma as the spellcasting ability (spell save DC 16):\n\n**At\
      \ will:** [Mage Armor](mage-armor) (included\
      \ in AC), [Mage Hand](Mage%20Hand), [Minor Illusion](minor-illusion)\n\
      \n**1/day each:** [Befuddlement](befuddlement),\
      \ [Detect Thoughts](detect-thoughts), [Fly](fly),\
      \ [Scrying](scrying), [Shatter](shatter)\
      \ (level 7 version)"
    "name": "Spellcasting"
"reactions":
  - "desc": "The noble casts [Shield](shield) in response\
      \ to that spell's trigger, using the same spellcasting ability as Spellcasting.\n"
    "name": "Shield (2/Day)"
"source":
  - "XMM"
"image": "bestiary/tokens/XMM/Noble Prodigy.webp"
```
^statblock

## Environment

any