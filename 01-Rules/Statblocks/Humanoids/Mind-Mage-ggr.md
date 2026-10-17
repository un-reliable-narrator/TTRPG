---
cssclasses:
  - json5e-monster
tags:
  - src/5e/ggr
  - monster/cr/5
  - monster/size/medium
  - monster/type/humanoid/any-race
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Mind Mage
---
# [Mind Mage](Mind-Mage-ggr.md)
*Source: Guildmasters' Guide to Ravnica p. 233*  

![](https://5e.tools/img/bestiary/tokens/GGR/Mind%20Mage.webp)

Dimir mind mages are among the most feared spellcasters in Ravnica, thanks in large part to the aura of mystery that shrouds them and their work. Their ability to read and alter memories commands respect from the other members of House Dimir and makes them useful in the full spectrum of the guild's activities. Many mind mages lead cells of their own.

```statblock
"name": "Mind Mage (GGR)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Neutral Evil"
"ac": !!int "12"
"hp": !!int "49"
"hit_dice": "11d8"
"modifier": !!int "2"
"stats":
  - !!int "10"
  - !!int "14"
  - !!int "10"
  - !!int "20"
  - !!int "15"
  - !!int "16"
"speed": "30 ft."
"saves":
  - "intelligence": !!int "8"
  - "wisdom": !!int "5"
"skillsaves":
  - "name": "[Arcana](skills.md#Arcana)"
    "desc": "+8"
  - "name": "[Deception](skills.md#Deception)"
    "desc": "+6"
  - "name": "[Insight](skills.md#Insight)"
    "desc": "+5"
  - "name": "[Persuasion](skills.md#Persuasion)"
    "desc": "+6"
"senses": "passive Perception 12"
"languages": "Common plus any four languages"
"cr": "5"
"traits":
  - "desc": "The mage wears a spies' murmur (see chapter 5)."
    "name": "Special Equipment"
  - "desc": "The mage's spellcasting ability is Intelligence (spell save DC\
      \ 16). It can innately cast the following spells, requiring no\
      \ components:\n\n**At will:** [encode thoughts](encode-thoughts) (see\
      \ chapter 2), [friends](Friends.md)\n\n**3/day each:** [charm\
      \ person](Charm-Person.md), [detect thoughts](Detect-Thoughts.md), [mage\
      \ armor](Mage-Armor.md), [sleep](Sleep.md),\
      \ [suggestion](Suggestion.md)\n\n**1/day each:** [dominate\
      \ person](Dominate-Person.md), [mass suggestion](Mass-Suggestion.md),\
      \ [modify memory](Modify-Memory.md)"
    "name": "Innate Spellcasting (Psionics)"
"actions":
  - "desc": "*Melee or Ranged Weapon Attack:* +5 to hit, reach 5 ft. or range\
      \ 20/60 ft., one target. *Hit:* 4 (1d4 + 2) piercing damage."
    "name": "Dagger"
"source":
  - "GGR"
"image": "bestiary/tokens/GGR/Mind Mage.webp"
```
^statblock
