---
cssclasses:
  - json5e-monster
tags:
  - src/5e/ggr
  - monster/cr/7
  - monster/size/medium
  - monster/type/humanoid/any-race
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Firefist
---
# [Firefist](Firefist-ggr.md)
*Source: Guildmasters' Guide to Ravnica p. 231*  

![](https://5e.tools/img/bestiary/GGR/Firefist.webp)

Boros firefists combine potent magic with peerless fighting ability, inspiring all who serve alongside them. They often act as the point of contact between the Boros Legion and the angelic leaders.

```statblock
"name": "Firefist (GGR)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Lawful Good"
"ac": !!int "18"
"ac_class": "[plate armor](Plate-Armor.md)"
"hp": !!int "117"
"hit_dice": "18d8 + 36"
"modifier": !!int "0"
"stats":
  - !!int "16"
  - !!int "10"
  - !!int "14"
  - !!int "11"
  - !!int "17"
  - !!int "13"
"speed": "30 ft."
"saves":
  - "constitution": !!int "5"
  - "wisdom": !!int "6"
"skillsaves":
  - "name": "[Intimidation](skills.md#Intimidation)"
    "desc": "+4"
  - "name": "[Religion](skills.md#Religion)"
    "desc": "+3"
"senses": "passive Perception 13"
"languages": "any one language (usually Common)"
"cr": "7"
"traits":
  - "desc": "The firefist is a 9th-level Boros spellcaster. Its spellcasting\
      \ ability is Wisdom (spell save DC 14, +6 to hit with spell attacks). It\
      \ has the following cleric spells prepared:\n\n**Cantrips (at will):**\
      \ [fire bolt](Fire-Bolt.md), [light](Light.md), [sacred\
      \ flame](Sacred-Flame.md), [spare the dying](Spare-the-Dying.md)\n\n**1st\
      \ level (4 slots):** [guiding bolt](Guiding-Bolt.md), [healing\
      \ word](Healing-Word.md), [heroism](Heroism.md), [shield of\
      \ faith](Shield-of-Faith.md)\n\n**2nd level (3 slots):** [lesser\
      \ restoration](Lesser-Restoration.md), [scorching\
      \ ray](Scorching-Ray.md)\n\n**3rd level (3 slots):** [blinding\
      \ smite](Blinding Smite.md), [crusader's mantle](Crusader's Mantle.md),\
      \ [revivify](Revivify.md)\n\n**4th level (3 slots):**\
      \ [banishment](Banishment.md), [wall of fire](Wall-of-Fire.md)\n\n**5th\
      \ level (1 slot):** [flame strike](Flame-Strike.md)"
    "name": "Spellcasting"
"actions":
  - "desc": "The firefist makes two greatsword attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one target. *Hit:*\
      \ 10 (2d6 + 3) slashing damage."
    "name": "Greatsword"
"reactions":
  - "desc": "When the firefist or one creature it can see within 30 feet of it\
      \ makes an attack roll, the firefist grants a +10 bonus to that roll."
    "name": "Guided Attack (Recharges after a Short or Long Rest)"
"source":
  - "GGR"
"image": "bestiary/tokens/GGR/Firefist.webp"
```
^statblock
