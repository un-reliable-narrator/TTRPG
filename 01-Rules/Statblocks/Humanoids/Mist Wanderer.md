---
cssclasses:
  - json5e-monster
tags:
  - src/5e/rhw
  - monster/cr/3
  - monster/environment/any
  - monster/size/small
  - monster/size/medium
  - monster/type/humanoid
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Mist Wanderer
---
# [Mist Wanderer](Mist%20Wanderer.md)
*Source: Ravenloft: The Horrors Within p. 256*  

![](https://media.dndbeyond.com/compendium-images/rthw/ogMxaVTj4GqgnUqr/22-022.mist-wanderer.png)

*Traveler Between Domains*

Those who travel between the Domains of Dread develop traditions that hasten their travel and protect them from evil. Vistani, along with those who research their ways or the secrets of the Mists, are the most adept of such domain explorers.

```statblock
"name": "Mist Wanderer (RHW)"
"size": "Small or Medium"
"type": "humanoid"
"alignment": "Neutral"
"ac": !!int "13"
"hp": !!int "52"
"hit_dice": "8d8 + 16"
"modifier": !!int "2"
"stats":
  - !!int "10"
  - !!int "14"
  - !!int "14"
  - !!int "12"
  - !!int "16"
  - !!int "13"
"speed": "30 ft."
"skillsaves":
  - "name": "[Arcana](skills.md#Arcana)"
    "desc": "+3"
  - "name": "[Insight](skills.md#Insight)"
    "desc": "+5"
  - "name": "[Medicine](skills.md#Medicine)"
    "desc": "+5"
"senses": "passive Perception 13"
"languages": "Common plus one other language"
"cr": "3"
"traits":
  - "desc": "*Charisma Saving Throw:* DC 13, each creature in a 5-foot\
      \ Emanation originating from the wanderer when it dies. *Failure:* The\
      \ target is cursed. While cursed, the target has the\
      \ [Blinded](conditions.md#Blinded) and [Deafened](conditions.md#Deafened)\
      \ conditions."
    "name": "Death Curse"
  - "desc": "The wanderer can travel safely through the Mists to reach a\
      \ specific domain it knows by name. The wanderer still can't bypass\
      \ domain borders closed by a Darklord's will."
    "name": "Mist Walker"
"actions":
  - "desc": "The wanderer makes two Radiant Burst attacks. It can replace one\
      \ attack with a use of Spellcasting to cast [Mind Spike](Mind-Spike.md)\
      \ if available."
    "name": "Multiattack"
  - "desc": "*Melee or Ranged Attack Roll:* +5, reach 5 ft. or range 60 ft.\
      \ *Hit:* 14 (2d10 + 3) Radiant damage."
    "name": "Radiant Burst"
  - "desc": "The wanderer casts one of the following spells, using Wisdom as\
      \ the spellcasting ability (spell save DC 13):\n\n**At will:**\
      \ [Light](Light.md), [Mage Hand](Mage-Hand.md)\n\n**1/day each:**\
      \ [Augury](Augury.md), [Detect Magic](Detect-Magic.md), [Mind\
      \ Spike](Mind-Spike.md)"
    "name": "Spellcasting"
"bonus_actions":
  - "desc": "The wanderer casts [Hold Person](Hold-Person.md), using the same\
      \ spellcasting ability as Spellcasting.\n\n**1/day:** [Hold\
      \ Person](Hold-Person.md)"
    "name": "Evil Eye (1/Day)"
"source":
  - "RHW"
"image": "bestiary/tokens/RHW/Mist Wanderer.webp"
```
^statblock

## Environment

any
