---
cssclasses:
  - json5e-monster
tags:
  - src/5e/ggr
  - monster/cr/2
  - monster/size/medium
  - monster/type/humanoid/any-race
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Counterflux Blastseeker
---
# [Counterflux Blastseeker](Counterflux-Blastseeker-ggr.md)
*Source: Guildmasters' Guide to Ravnica p. 242*  

![](https://5e.tools/img/bestiary/GGR/Counterflux%20Blastseeker.webp)

While chemisters focus on inventing new tools, weapons, and other devices for the guild to use, the role of a blastseeker is to put those devices to work. Despite the name, not all such devices produce explosions, but all the most interesting ones (from the Izzet perspective) do.

```statblock
"name": "Counterflux Blastseeker (GGR)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Chaotic Neutral"
"ac": !!int "13"
"hp": !!int "39"
"hit_dice": "6d8 + 12"
"modifier": !!int "3"
"stats":
  - !!int "13"
  - !!int "16"
  - !!int "15"
  - !!int "18"
  - !!int "11"
  - !!int "14"
"speed": "30 ft."
"saves":
  - "constitution": !!int "4"
  - "wisdom": !!int "2"
"skillsaves":
  - "name": "[Arcana](skills.md#Arcana)"
    "desc": "+6"
  - "name": "[Perception](skills.md#Perception)"
    "desc": "+2"
"senses": "passive Perception 12"
"languages": "Common plus any one language"
"cr": "2"
"traits":
  - "desc": "The blastseeker can create an additional effect immediately after\
      \ casting a spell. Roll a d6 to determine the effect:\n\n- **1–3.** The\
      \ blastseeker creates a 15-foot-radius\
      \ [invisible](conditions.md#Invisible) sphere centered on itself that\
      \ lasts until the end of its next turn. Creatures in the sphere have\
      \ disadvantage on saving throws against spells and other magical effects.\
      \  \n- **4–6.** The blastseeker creates a 15-foot-radius\
      \ [invisible](conditions.md#Invisible) sphere centered on itself that\
      \ lasts until the end of its next turn. Creatures in the sphere have\
      \ advantage on saving throws against spells and other magical effects.  "
    "name": "Counterflux Overcast (Recharge 5-6)"
  - "desc": "The blastseeker's innate spellcasting ability is Intelligence\
      \ (spell save DC 14, +6 to hit with spell attacks). The blastseeker can\
      \ innately cast the following spells, requiring no components other than\
      \ its Izzet gear, which doesn't function for others:\n\n**3/day each:**\
      \ [enlarge/reduce](enlarge-reduce), [mage armor](Mage-Armor.md) (self\
      \ only), [scorching ray](Scorching-Ray.md)\n\n**1/day each:**\
      \ [counterspell](Counterspell.md), [dispel magic](Dispel-Magic.md),\
      \ [protection from energy](Protection-from-Energy.md)"
    "name": "Innate Spellcasting"
"actions":
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one target. *Hit:*\
      \ 7 (1d8 + 3) piercing damage."
    "name": "Rapier"
"source":
  - "GGR"
"image": "bestiary/tokens/GGR/Counterflux Blastseeker.webp"
```
^statblock
