---
cssclasses:
- json5e-monster
tags:
- src/5e/xmm
- monster/cr/2
- monster/environment/forest
- monster/size/tiny
- monster/type/dragon
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Faerie Dragon Adult"
---
# [Faerie Dragon Adult](faerie-Dragon-Adult.md)
*Source: Monster Manual (2024) p. 117*  

The pranks of faerie dragon adults tend to lead others to people in need or wrongs to be righted.

## Faerie Dragons

*Whimsical Draconic Tricksters*

- **Habitat.** Forest  
- **Treasure.** [Implements](random-magic-items-implements.md)  

Faerie dragons are cat Size pranksters with draconic features, butterfly-like wings, and scales of warm hues as youths and cool hues as adults.

```statblock
"name": "Faerie Dragon Adult (XMM)"
"size": "Tiny"
"type": "dragon"
"alignment": "Chaotic Good"
"ac": !!int "15"
"hp": !!int "35"
"hit_dice": "10d4 + 10"
"modifier": !!int "5"
"stats":
  - !!int "3"
  - !!int "20"
  - !!int "13"
  - !!int "14"
  - !!int "12"
  - !!int "16"
"speed": "10 ft., fly 60 ft."
"skillsaves":
  - "name": "[Arcana](Arcana)"
    "desc": "+4"
  - "name": "[Perception](Perception)"
    "desc": "+3"
  - "name": "[Stealth](Stealth)"
    "desc": "+7"
"senses": "[Darkvision](senses.md#Darkvision) 60 ft., passive\
  \ Perception 13"
"languages": "Draconic, Sylvan; telepathy 60 ft. (faerie dragons only)"
"cr": "2"
"traits":
  - "desc": "The dragon has [Advantage](advantage)\
      \ on saving throws against spells and other magical effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "*Melee Attack Roll:* +7, reach 5 ft. *Hit:* 7 (1d4 + 5) Piercing\
      \ damage plus 3 (1d6) Psychic damage."
    "name": "Bite"
  - "desc": "*Wisdom Saving Throw:* DC 13, each creature in a 15-foot [Cone](cone-area-of-effect).\
      \ *Failure:* The target has the [Incapacitated](conditions.md#Incapacitated)\
      \ condition and repeats the save at the end of each of its turns, ending the\
      \ effect on itself on a success. After 1 minute, it succeeds automatically.\
      \ While [Incapacitated](conditions.md#Incapacitated),\
      \ the target uses all its movement on each of its turns to move in a random\
      \ direction."
    "name": "Euphoria Breath (Recharge 5-6)"
  - "desc": "The dragon casts one of the following spells, requiring no Material components\
      \ and using Charisma as the spellcasting ability (spell save DC 13):\n\n**At\
      \ will:** [Dancing Lights](dancing-lights), [Mage\
      \ Hand](Mage%20Hand), [Minor Illusion](minor-illusion)\n\
      \n**1/day each:** [Hallucinatory Terrain](hallucinatory-terrain),\
      \ [Polymorph](polymorph)"
    "name": "Spellcasting"
"bonus_actions":
  - "desc": "The dragon casts [Greater Invisibility](greater-invisibility)\
      \ on itself, requiring no spell components and using the same spellcasting ability\
      \ as Spellcasting.\n"
    "name": "Superior Invisibility"
"source":
  - "XMM"
"image": "bestiary/tokens/XMM/Faerie Dragon Adult.webp"
```
^statblock

## Environment

forest