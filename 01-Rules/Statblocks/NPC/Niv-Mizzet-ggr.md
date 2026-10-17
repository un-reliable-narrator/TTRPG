---
cssclasses:
  - json5e-monster
tags:
  - src/5e/ggr
  - monster/cr/26
  - monster/size/gargantuan
  - monster/type/dragon
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Niv-Mizzet
---
# [Niv-Mizzet](Niv-Mizzet-ggr.md)
*Source: Guildmasters' Guide to Ravnica p. 241*  

![](https://5e.tools/img/bestiary/GGR/Niv-Mizzet.webp)

Possessed of arrogance and vanity that matches his vast intellect and tremendous power, Niv-Mizzet is the ancient dragon who founded and continues to control the Izzet League. From his private laboratory at the top of the Izzet guildhall, Niv-Mizzet directs the research and experiments of his countless underlings. He coordinates a tremendous number of apparently unrelated projects, working toward some mysterious end.

There can be little doubt that this ancient dragon is one of the most intelligent beings on Ravnica and one of the world's most powerful spellcasters. He is just as acquisitive as any dragon, but his treasure is scientific and magical knowledge. His ambition is a looming threat in the minds of all the other guildmasters, but confronting him directly is almost unthinkable thanks to the combination of his awesome magical power and the sheer physical threat of a fire-breathing, sword-toothed dragon.

```statblock
"name": "Niv-Mizzet (GGR)"
"size": "Gargantuan"
"type": "dragon"
"alignment": "Chaotic Neutral"
"ac": !!int "22"
"ac_class": "natural armor"
"hp": !!int "370"
"hit_dice": "19d20 + 171"
"modifier": !!int "2"
"stats":
  - !!int "29"
  - !!int "14"
  - !!int "29"
  - !!int "30"
  - !!int "17"
  - !!int "25"
"speed": "40 ft., climb 30 ft., fly 80 ft."
"saves":
  - "constitution": !!int "17"
  - "intelligence": !!int "18"
  - "wisdom": !!int "11"
"skillsaves":
  - "name": "[Arcana](skills.md#Arcana)"
    "desc": "+18"
  - "name": "[Insight](skills.md#Insight)"
    "desc": "+11"
  - "name": "[Perception](skills.md#Perception)"
    "desc": "+11"
"damage_resistances": "cold, psychic, thunder"
"damage_immunities": "fire, lightning"
"condition_immunities": "[charmed](conditions.md#Charmed)"
"senses": "[Blindsight](senses.md#Blindsight) 60 ft.,\
  \ [Darkvision](senses.md#Darkvision) 120 ft., passive Perception 21"
"languages": "Common, Draconic"
"cr": "26"
"traits":
  - "desc": "If Niv-Mizzet fails a saving throw, he can choose to succeed\
      \ instead."
    "name": "Legendary Resistance (3/Day)"
  - "desc": "Niv-Mizzet can maintain concentration on two different spells at\
      \ the same time. In addition, he has advantage on saving throws to\
      \ maintain concentration on spells."
    "name": "Locus of the Firemind"
  - "desc": "Niv-Mizzet has advantage on saving throws against spells and other\
      \ magical effects."
    "name": "Magic Resistance"
  - "desc": "When Niv-Mizzet casts a spell that deals damage, he can change the\
      \ spell's damage to cold, fire, force, lightning, or thunder."
    "name": "Master Chemister"
  - "desc": "Niv-Mizzet is a 20th-level Izzet spellcaster. His spellcasting\
      \ ability is Intelligence (spell save DC 26, +18 to hit with spell\
      \ attacks). He has the following wizard spells prepared:\n\n**Cantrips\
      \ (at will):** [fire bolt](Fire-Bolt.md), [light](Light.md),\
      \ [prestidigitation](Prestidigitation.md), [ray of\
      \ frost](Ray-of-Frost.md), [shocking grasp](Shocking-Grasp.md)\n\n**1st\
      \ level (4 slots):** [detect magic](Detect-Magic.md), [magic\
      \ missile](Magic-Missile.md), [shield](Shield.md),\
      \ [thunderwave](Thunderwave.md), [unseen\
      \ servant](Unseen-Servant.md)\n\n**2nd level (3 slots):**\
      \ [blur](Blur.md), [enlarge/reduce](enlarge-reduce), [flaming\
      \ sphere](Flaming-Sphere.md), [hold person](Hold-Person.md), [scorching\
      \ ray](Scorching-Ray.md)\n\n**3rd level (3 slots):**\
      \ [counterspell](Counterspell.md), [fireball](Fireball.md), [lightning\
      \ bolt](Lightning-Bolt.md), [slow](Slow.md)\n\n**4th level (3 slots):**\
      \ [confusion](Confusion.md), [dimension door](Dimension-Door.md),\
      \ [fabricate](Fabricate.md)\n\n**5th level (2 slots):** [conjure\
      \ elemental](Conjure-Elemental.md), [polymorph](Polymorph.md), [wall of\
      \ fire](Wall-of-Fire.md), [wall of force](Wall-of-Force.md)\n\n**6th\
      \ level (1 slot):** [chain lightning](Chain-Lightning.md),\
      \ [disintegrate](Disintegrate.md), [true seeing](True-Seeing.md)\n\n**7th\
      \ level (1 slot):** [project image](Project-Image.md), [reverse\
      \ gravity](Reverse-Gravity.md), [teleport](Teleport.md)\n\n**8th level (1\
      \ slot):** [control weather](Control-Weather.md), [maze](Maze.md), [power\
      \ word stun](Power-Word-Stun.md)\n\n**9th level (1 slot):** [prismatic\
      \ wall](Prismatic-Wall.md)"
    "name": "Spellcasting"
"actions":
  - "desc": "Niv-Mizzet makes three attacks: one with his bite and two with his\
      \ claws."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +17 to hit, reach 15 ft., one target.\
      \ *Hit:* 18 (2d8 + 9) piercing damage plus 14 (4d6) fire damage."
    "name": "Bite"
  - "desc": "*Melee Weapon Attack:* +17 to hit, reach 10 ft., one target.\
      \ *Hit:* 14 (2d4 + 9) slashing damage."
    "name": "Claw"
  - "desc": "*Melee Weapon Attack:* +17 to hit, reach 20 ft., one target.\
      \ *Hit:* 16 (2d6 + 9) bludgeoning damage."
    "name": "Tail"
  - "desc": "Niv-Mizzet exhales fire in a 90-foot cone. Each creature in that\
      \ area must make a DC 25 Dexterity saving throw, taking 91 (26d6) fire\
      \ damage on a failed save, or half as much damage on a successful one."
    "name": "Fire Breath (Recharge 5-6)"
"legendary_description": "Legendary Action Uses: 3. Immediately after another\
  \ creature's turn, Niv-Mizzet can expend a use to take one of the following\
  \ actions. Niv-Mizzet regains all expended uses at the start of each of its\
  \ turns."
"legendary_actions":
  - "desc": "Niv-Mizzet casts one of his cantrips."
    "name": "Cantrip"
  - "desc": "Niv-Mizzet makes a tail attack."
    "name": "Tail Attack"
  - "desc": "Niv-Mizzet beats his wings. Each creature within 15 feet of him\
      \ must succeed on a DC 25 Dexterity saving throw or take 14 (2d4 + 9)\
      \ bludgeoning damage and be knocked [prone](conditions.md#Prone).\
      \ Niv-Mizzet can then fly up to half his flying speed."
    "name": "Wing Attack (Costs 2 Actions)"
  - "desc": "Niv-Mizzet regains a spell slot of 3rd level or lower."
    "name": "Dracogenius (Costs 3 Actions)"
"source":
  - "GGR"
"image": "bestiary/tokens/GGR/Niv-Mizzet.webp"
```
^statblock
