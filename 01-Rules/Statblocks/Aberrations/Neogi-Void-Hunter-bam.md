---
cssclasses:
  - json5e-monster
tags:
  - src/5e/bam
  - monster/cr/4
  - monster/size/medium
  - monster/type/aberration/warlock
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Neogi Void Hunter
---
# [Neogi Void Hunter](Neogi-Void-Hunter-bam.md)
*Source: Boo's Astral Menagerie p. 41*  

![](https://5e.tools/img/bestiary/tokens/BAM/Neogi%20Void%20Hunter.webp)

A neogi void hunter is bigger than a typical adult neogi and often fills the role of captain aboard a nightspider (see the *Astral Adventurer's Guide*). The void hunter pledges fealty to one or more stellar entities in exchange for a taste of their immense power. These entities—known by such names as Acamar, Caiphon, Gibbeth, and Hadar—resemble stars and embody the essence of evil.

```statblock
"name": "Neogi Void Hunter (BAM)"
"size": "Medium"
"type": "aberration"
"subtype": "warlock"
"alignment": "typically Lawful Evil"
"ac": !!int "14"
"ac_class": "natural armor"
"hp": !!int "58"
"hit_dice": "9d8 + 18"
"modifier": !!int "3"
"stats":
  - !!int "6"
  - !!int "16"
  - !!int "14"
  - !!int "16"
  - !!int "12"
  - !!int "18"
"speed": "30 ft., climb 30 ft."
"saves":
  - "wisdom": !!int "3"
  - "charisma": !!int "6"
"skillsaves":
  - "name": "[Arcana](skills.md#Arcana)"
    "desc": "+5"
  - "name": "[Deception](skills.md#Deception)"
    "desc": "+6"
  - "name": "[Intimidation](skills.md#Intimidation)"
    "desc": "+6"
  - "name": "[Perception](skills.md#Perception)"
    "desc": "+3"
  - "name": "[Persuasion](skills.md#Persuasion)"
    "desc": "+6"
"senses": "[Darkvision](senses.md#Darkvision) 120 ft., passive Perception 13"
"languages": "Common, Deep Speech, telepathy 30 ft., Undercommon"
"cr": "4"
"traits":
  - "desc": "Magical darkness doesn't impede the neogi's darkvision."
    "name": "Devil's Sight"
  - "desc": "The neogi has advantage on saving throws against being\
      \ [charmed](conditions.md#Charmed) or\
      \ [frightened](conditions.md#Frightened), and magic can't put the neogi\
      \ to sleep."
    "name": "Mental Fortitude"
  - "desc": "The neogi can climb difficult surfaces, including upside down on\
      \ ceilings, without needing to make an ability check."
    "name": "Spider Climb"
"actions":
  - "desc": "The neogi makes one Bite attack and two Claw attacks, or it makes\
      \ two Eldritch Bolt attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one target. *Hit:*\
      \ 7 (1d8 + 3) piercing damage plus 14 (4d6) poison damage, and the target\
      \ must succeed on a DC 12 Constitution saving throw or become\
      \ [poisoned](conditions.md#Poisoned) for 1 minute. A target can repeat\
      \ the saving throw at the end of each of its turns, ending the effect on\
      \ itself on a success."
    "name": "Bite"
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one target. *Hit:*\
      \ 7 (1d8 + 3) piercing damage."
    "name": "Claw"
  - "desc": "*Ranged Spell Attack:* +6 to hit, range 120 ft., one creature.\
      \ *Hit:* 20 (3d10 + 4) force damage."
    "name": "Eldritch Bolt"
  - "desc": "The neogi casts one of the following spells, using Charisma as the\
      \ spellcasting ability:\n\n**1/day each:** [dimension\
      \ door](Dimension-Door.md), [invisibility](Invisibility.md)"
    "name": "Spellcasting"
"bonus_actions":
  - "desc": "The neogi targets one creature it can see within 30 feet of\
      \ itself. The target must succeed on a DC 14 Wisdom saving throw or be\
      \ magically [charmed](conditions.md#Charmed) by the neogi for 1 day, or\
      \ until the neogi dies or is more than 1 mile from the target. The\
      \ [charmed](conditions.md#Charmed) target obeys the neogi's commands and\
      \ can't take reactions, and the neogi and the target can communicate\
      \ telepathically with each other at a distance of up to 1 mile. Whenever\
      \ the [charmed](conditions.md#Charmed) target takes damage, it can repeat\
      \ the saving throw, ending the effect on itself on a success."
    "name": "Enslave (Recharges after a Short or Long Rest)"
"source":
  - "BAM"
"image": "bestiary/tokens/BAM/Neogi Void Hunter.webp"
```
^statblock
