---
cssclasses:
  - json5e-monster
tags:
  - src/5e/ggr
  - monster/cr/14
  - monster/size/medium
  - monster/type/undead
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Devkarin Lich
---
# [Devkarin Lich](Devkarin-Lich-ggr.md)
*Source: Guildmasters' Guide to Ravnica p. 198*  

![](https://5e.tools/img/bestiary/GGR/Devkarin%20Lich.webp)

Powerful spellcasters of the Devkarin elves, steeped in Golgari magic, can transcend death to become liches. For them, life and death don't merely chase each other in an inevitable cycle; the two can intersect, and at that nexus the liches find immense power, which commands the awe, envy, and fear of other Golgari.

Unlike the shambling zombies they command, liches retain their memories, their personalities, and especially their ambition. They also retain the grace and stature of living elves, but their bodies are in a constant state of slow decay. Various forms of fungus grow in and over the rotting flesh to hold the body together.

## Undead Nature

The lich doesn't require air, food, drink, or sleep.

```statblock
"name": "Devkarin Lich (GGR)"
"size": "Medium"
"type": "undead"
"alignment": "Neutral Evil"
"ac": !!int "14"
"ac_class": "natural armor"
"hp": !!int "97"
"hit_dice": "15d8 + 30"
"modifier": !!int "3"
"stats":
  - !!int "11"
  - !!int "16"
  - !!int "14"
  - !!int "19"
  - !!int "16"
  - !!int "15"
"speed": "30 ft."
"saves":
  - "constitution": !!int "7"
  - "intelligence": !!int "9"
  - "wisdom": !!int "8"
"skillsaves":
  - "name": "[Arcana](skills.md#Arcana)"
    "desc": "+14"
  - "name": "[Insight](skills.md#Insight)"
    "desc": "+8"
  - "name": "[Perception](skills.md#Perception)"
    "desc": "+8"
"damage_resistances": "necrotic; bludgeoning, piercing, slashing from\
  \ nonmagical attacks"
"damage_immunities": "poison"
"condition_immunities": "[charmed](conditions.md#Charmed),\
  \ [exhaustion](conditions.md#Exhaustion),\
  \ [frightened](conditions.md#Frightened),\
  \ [paralyzed](conditions.md#Paralyzed), [poisoned](conditions.md#Poisoned)"
"senses": "[Truesight](senses.md#Truesight) 120 ft., passive Perception 18"
"languages": "Common, Elvish, Kraul"
"cr": "14"
"traits":
  - "desc": "If the lich fails a saving throw, it can choose to succeed instead."
    "name": "Legendary Resistance (3/Day)"
  - "desc": "The lich regains 10 hit points at the start of its turn. If the\
      \ lich takes fire or radiant damage, this trait doesn't function at the\
      \ start of the lich's next turn. The lich dies only if it starts its turn\
      \ with 0 hit points and doesn't regenerate."
    "name": "Regeneration"
  - "desc": "The lich has advantage on saving throws against any effect that\
      \ turns undead."
    "name": "Turn Resistance"
  - "desc": "If damage reduces the lich to 0 hit points, it must make a\
      \ Constitution saving throw with a DC of 5 + the damage taken, unless the\
      \ damage is radiant or from a critical hit. On a success, the lich drops\
      \ to 1 hit point instead."
    "name": "Undead Fortitude"
  - "desc": "The lich is a 14th-level Golgari spellcaster. Its spellcasting\
      \ ability is Intelligence (spell save DC 17, +9 to hit with spell\
      \ attacks). The lich has the following wizard spells\
      \ prepared:\n\n**Cantrips (at will):** [acid splash](Acid-Splash.md),\
      \ [chill touch](Chill-Touch.md), [mage hand](Mage-Hand.md), [poison\
      \ spray](Poison-Spray.md),\
      \ [prestidigitation](Prestidigitation.md)\n\n**1st level (4 slots):**\
      \ [chromatic orb](Chromatic-Orb.md), [magic missile](Magic-Missile.md),\
      \ [ray of sickness](Ray-of-Sickness.md)\n\n**2nd level (3 slots):**\
      \ [Melf's acid arrow](melf-s-acid-arrow), [ray of\
      \ enfeeblement](Ray-of-Enfeeblement.md), [spider climb](Spider-Climb.md),\
      \ [web](Web.md)\n\n**3rd level (3 slots):** [animate\
      \ dead](Animate-Dead.md), [bestow curse](Bestow-Curse.md),\
      \ [fear](Fear.md), [vampiric touch](Vampiric-Touch.md)\n\n**4th level (3\
      \ slots):** [blight](Blight.md), [Evard's black\
      \ tentacles](Evard's-Black-Tentacles.md)\n\n**5th level (2 slots):**\
      \ [cloudkill](Cloudkill.md), [insect plague](Insect-Plague.md)\n\n**6th\
      \ level (1 slot):** [circle of death](Circle-of-Death.md), [create\
      \ undead](Create-Undead.md)\n\n**7th level (1 slot):** [finger of\
      \ death](Finger-of-Death.md)"
    "name": "Spellcasting"
"actions":
  - "desc": "*Melee Spell Attack:* +9 to hit, reach 5 ft., one creature. *Hit:*\
      \ 14 (4d6) poison damage, and the target must succeed on a DC 17\
      \ Constitution saving throw or be [poisoned](conditions.md#Poisoned) for\
      \ 1 minute. The [poisoned](conditions.md#Poisoned) target can repeat the\
      \ saving throw at the end of each of its turns, ending the effect on\
      \ itself on a success."
    "name": "Noxious Touch"
"legendary_description": "Legendary Action Uses: 3. Immediately after another\
  \ creature's turn, the devkarin lich can expend a use to take one of the\
  \ following actions. The devkarin lich regains all expended uses at the start\
  \ of each of its turns."
"legendary_actions":
  - "desc": "The lich casts one of its cantrips."
    "name": "Cantrip"
  - "desc": "The lich uses Noxious Touch."
    "name": "Noxious Touch (Costs 2 Actions)"
  - "desc": "Each creature within 30 feet of the lich must make a DC 17\
      \ Constitution saving throw, taking 21 (6d6) necrotic damage on a failed\
      \ save, or half as much damage on a successful one."
    "name": "Disrupt Life (Costs 3 Actions)"
"source":
  - "GGR"
"image": "bestiary/tokens/GGR/Devkarin Lich.webp"
```
^statblock
