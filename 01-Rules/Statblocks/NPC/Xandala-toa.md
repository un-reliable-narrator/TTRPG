---
cssclasses:
  - json5e-monster
tags:
  - src/5e/toa
  - monster/cr/7
  - monster/size/medium
  - monster/type/humanoid/half-elf
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Xandala
---
# [Xandala](Xandala-toa.md)
*Source: Tomb of Annihilation p. 236*  

![](https://5e.tools/img/bestiary/ToA/Xandala.webp)

The half-elf sorcerer Xandala has come to Chult in search of the Ring of Winter, an artifact in Artus Cimber's possession. Xandala knows that the ring has kept Artus alive for over a century, and she craves its power. If she meets the characters, Xandala pretends to be Artus's daughter and tries to convince them to help her find him. Her plan is to cast [dominate person](Dominate-Person.md) on Artus and force him to give her the ring, then escape using her [fly](Fly.md) spell.

Xandala's magic traces back to a draconic bloodline, and parts of her skin are covered by a thin sheen of protective scales. She has befriended a pseudodragon named Summerwise, who thinks that Xandala's quest for the ring is dangerous but has given up trying to talk the sorcerer out of it. Summerwise can be turned against Xandala by good-aligned characters.

- **Ideal.** "I have the blood of dragons flowing through my veins. I am destined for greatness."  
- **Bond.** "The Ring of Winter will bring me power and immortality."  
- **Flaw.** "I'm surrounded by fools."  

```statblock
"name": "Xandala (ToA)"
"size": "Medium"
"type": "humanoid"
"subtype": "half-elf"
"alignment": "Neutral Evil"
"ac": !!int "13"
"ac_class": "natural armor"
"hp": !!int "71"
"hit_dice": "11d8 + 22"
"modifier": !!int "0"
"stats":
  - !!int "10"
  - !!int "11"
  - !!int "14"
  - !!int "18"
  - !!int "16"
  - !!int "18"
"speed": "30 ft."
"saves":
  - "intelligence": !!int "7"
  - "wisdom": !!int "6"
"skillsaves":
  - "name": "[Arcana](skills.md#Arcana)"
    "desc": "+7"
  - "name": "[Deception](skills.md#Deception)"
    "desc": "+10"
  - "name": "[History](skills.md#History)"
    "desc": "+7"
  - "name": "[Insight](skills.md#Insight)"
    "desc": "+6"
  - "name": "[Survival](skills.md#Survival)"
    "desc": "+6"
"senses": "passive Perception 13"
"languages": "Common, Draconic, Dwarvish, Elvish, Halfling"
"cr": "7"
"traits":
  - "desc": "When she casts a spell that has a casting time of 1 action,\
      \ Xandala changes the casting time to 1 bonus action for that casting."
    "name": "Quickened Spell (3/Day)"
  - "desc": "Xandala is a 9th-level spellcaster. Her spellcasting ability is\
      \ Charisma (spell save DC 15, +7 to hit with spell attacks). Xandala has\
      \ the following sorcerer spells prepared:\n\n**Cantrips (at will):**\
      \ [acid splash](Acid-Splash.md), [fire bolt](Fire-Bolt.md),\
      \ [light](Light.md), [mage hand](Mage-Hand.md), [ray of\
      \ frost](Ray-of-Frost.md)\n\n**1st level (4 slots):** [chromatic\
      \ orb](Chromatic-Orb.md), [feather fall](Feather-Fall.md),\
      \ [shield](Shield.md)\n\n**2nd level (4 slots):**\
      \ [invisibility](Invisibility.md), [misty step](Misty-Step.md)\n\n**3rd\
      \ level (3 slots):** [fireball](Fireball.md), [fly](Fly.md)\n\n**4th\
      \ level (3 slots):** [ice storm](Ice-Storm.md),\
      \ [polymorph](Polymorph.md)\n\n**5th level (1 slot):** [dominate\
      \ person](Dominate-Person.md)"
    "name": "Spellcasting"
"actions":
  - "desc": "*Melee Weapon Attack:* +3 to hit, reach 5 ft., one target. *Hit:*\
      \ 3 (1d6) bludgeoning damage, or 4 (1d8) bludgeoning damage when used\
      \ with two hands."
    "name": "Quarterstaff"
"source":
  - "ToA"
"image": "bestiary/tokens/ToA/Xandala.webp"
```
^statblock
