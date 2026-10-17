---
cssclasses:
  - json5e-monster
tags:
  - src/5e/ggr
  - monster/cr/12
  - monster/size/medium
  - monster/type/celestial
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Firemane Angel
---
# [Firemane Angel](Firemane-Angel-ggr.md)
*Source: Guildmasters' Guide to Ravnica p. 190*  

![](https://5e.tools/img/bestiary/GGR/Firemane%20Angel.webp)

## Boros Angels

Angels of the Boros Legion view themselves as the embodiments of what their creator intended. They are fierce warriors devoted to justice and dedicated to protecting the weak against evil and oppression. They are commanders, advisors, strategists, and soldiers. Their presence in battle inspires the mortal soldiers of the legion with righteous zeal.

Most Boros soldiers assume that angels are paragons of goodness, wisdom, and mercy. The reality is that angels aren't immune to the temptations of corruption, and the necessities of political machination can compromise the best of them.

### Warleaders

The wisest, most visionary angels are responsible for forming and implementing the military strategy of the Boros Legion. Since they are immortal, their plans might span centuries, and they have been known to accept decades of losses as a reasonable cost for a more significant victory many years later. These warleaders have the statistics of planetars or solars (as presented in the Monster Manual), but their appearance is similar to other Boros angels.

```statblock
"name": "Firemane Angel (GGR)"
"size": "Medium"
"type": "celestial"
"alignment": "Chaotic Good"
"ac": !!int "18"
"ac_class": "[plate armor](Plate-Armor.md)"
"hp": !!int "135"
"hit_dice": "18d8 + 54"
"modifier": !!int "2"
"stats":
  - !!int "22"
  - !!int "15"
  - !!int "17"
  - !!int "12"
  - !!int "14"
  - !!int "23"
"speed": "40 ft., fly 120 ft."
"saves":
  - "strength": !!int "10"
  - "wisdom": !!int "6"
  - "charisma": !!int "10"
"skillsaves":
  - "name": "[Insight](skills.md#Insight)"
    "desc": "+6"
  - "name": "[Perception](skills.md#Perception)"
    "desc": "+6"
"damage_resistances": "fire; radiant; bludgeoning, piercing, slashing from\
  \ nonmagical attacks"
"condition_immunities": "[charmed](conditions.md#Charmed),\
  \ [exhaustion](conditions.md#Exhaustion),\
  \ [frightened](conditions.md#Frightened)"
"senses": "[Truesight](senses.md#Truesight) 120 ft., passive Perception 16"
"languages": "all"
"cr": "12"
"traits":
  - "desc": "The angel doesn't provoke an opportunity attack when it flies out\
      \ of an enemy's reach."
    "name": "Flyby"
  - "desc": "The angel has advantage on saving throws against spells and other\
      \ magical effects."
    "name": "Magic Resistance"
  - "desc": "If the angel takes 21 damage or less that would reduce it to 0 hit\
      \ points, it is reduced to 1 hit point instead."
    "name": "Relentless (Recharges after a Short or Long Rest)"
  - "desc": "The angel's innate spellcasting ability is Charisma (spell save DC\
      \ 18, +10 to hit with spell attacks). The angel can innately cast the\
      \ following spells, requiring no material components:\n\n**3/day each:**\
      \ [compelled duel](Compelled Duel.md), [guiding bolt](Guiding-Bolt.md)\
      \ (as a 5th-level spell)\n\n**1/day each:** [daylight](Daylight.md),\
      \ [fireball](Fireball.md) (as a 6th-level spell)"
    "name": "Innate Spellcasting"
"actions":
  - "desc": "The angel makes two melee attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +10 to hit, reach 5 ft., one target. *Hit:*\
      \ 10 (1d8 + 6) slashing damage, or 11 (1d10 + 6) slashing damage if used\
      \ with two hands, plus 22 (5d8) fire or radiant damage (angel's choice)."
    "name": "Longsword"
"source":
  - "GGR"
"image": "bestiary/tokens/GGR/Firemane Angel.webp"
```
^statblock
