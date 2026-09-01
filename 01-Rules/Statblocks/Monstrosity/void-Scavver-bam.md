---
cssclasses:
- json5e-monster
tags:
- src/5e/bam
- monster/cr/11
- monster/size/huge
- monster/type/monstrosity
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Void Scavver"
---
# [Void Scavver](void-Scavver-bam.md)
*Source: Boo's Astral Menagerie p. 49, Light of Xaryxis*  

Void scavvers are 20 feet long. Each one is a solitary menace with a pitch-black hide. While most other scavvers are content to feed on kitchen scraps, a void scavver goes after the cook.

A void scavver can emit an invisible ray from its eye that causes its target to feel fear even more intense than what it might normally experience given the creature's size and nature.

```statblock
"name": "Void Scavver (BAM)"
"size": "Huge"
"type": "monstrosity"
"alignment": "Unaligned"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "157"
"hit_dice": "15d12 + 60"
"modifier": !!int "3"
"stats":
  - !!int "22"
  - !!int "16"
  - !!int "19"
  - !!int "4"
  - !!int "13"
  - !!int "5"
"speed": "0 ft., fly 40 ft."
"skillsaves":
  - "name": "[Perception](Perception)"
    "desc": "+5"
  - "name": "[Stealth](Stealth)"
    "desc": "+11"
"senses": "[Darkvision](senses.md#Darkvision) 120 ft., passive\
  \ Perception 15"
"languages": ""
"cr": "11"
"traits":
  - "desc": "The scavver doesn't require air."
    "name": "Unusual Nature"
"actions":
  - "desc": "*Melee Weapon Attack:* +10 to hit, reach 10 ft., one target. *Hit:*\
      \ 45 (6d12 + 6) piercing damage. If the target is a Large or smaller creature,\
      \ it must succeed on a DC 16 Dexterity saving throw or be swallowed by the scavver.\
      \ The scavver can have one creature swallowed at a time.\n\nA swallowed creature\
      \ is [blinded](conditions.md#Blinded) and [restrained](conditions.md#Restrained),\
      \ has total cover against attacks and other effects outside the scavver, and\
      \ takes 11 (2d10) acid damage at the start of each of the scavver's turns\
      \ from the digestive juices in the scavver's gullet.\n\nIf the scavver takes\
      \ 25 damage or more on a single turn from a creature inside it, the scavver\
      \ must succeed on a DC 20 Constitution saving throw at the end of that turn\
      \ or regurgitate the swallowed creature, which falls [prone](conditions.md#Prone)\
      \ in a space within 10 feet of the scavver. If the scavver dies, a swallowed\
      \ creature is no longer [restrained](conditions.md#Restrained)\
      \ by it and can escape from the corpse by using 10 feet of movement, exiting\
      \ [prone](conditions.md#Prone)."
    "name": "Swallowing Bite"
"bonus_actions":
  - "desc": "The scavver's eye emits an [invisible](conditions.md#Invisible),\
      \ magical ray that targets one creature the scavver can see within 60 feet of\
      \ itself. The target must succeed on a DC 16 Wisdom saving throw or be [frightened](conditions.md#Frightened)\
      \ of the scavver until the start of the scavver's next turn."
    "name": "Ray of Fear (Recharge 4-6)"
"source":
  - "BAM"
  - "LoX"
"image": "bestiary/tokens/BAM/Void Scavver.webp"
```
^statblock