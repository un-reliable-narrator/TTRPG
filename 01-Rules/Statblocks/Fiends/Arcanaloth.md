---
cssclasses:
- json5e-monster
tags:
- src/5e/xmm
- monster/cr/12
- monster/environment/lower
- monster/environment/planar
- monster/size/medium
- monster/type/Fiends/yugoloth
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Arcanaloth"
---
# [Arcanaloth](Arcanaloth.md)
*Source: Monster Manual (2024) p. 19*  

## Arcanaloth

*Yugoloth of Magical Manipulation*

- **Habitat.** Planar (Lower Planes)  
- **Treasure.** [Arcana](random-magic-items-arcana.md)  

While all yugoloths are fiendish manifestations of wickedness and greed, arcanaloths bend their considerable intellects toward hoarding and exploiting secrets. They then deploy these secrets to ensnare countless victims and lesser villains, beguiling foes with false promises and powerful magic.

Arcanaloths possess considerable spellcasting prowess and frequently disguise themselves with magic. While they prefer to let magical servants or other yugoloths do their fighting for them, arcanaloths can defend themselves with arcane might, banishing opponents into the pages of their magic tomes.

```statblock
"name": "Arcanaloth (XMM)"
"size": "Medium"
"type": "fiend"
"subtype": "yugoloth"
"alignment": "Neutral Evil"
"ac": !!int "18"
"hp": !!int "175"
"hit_dice": "27d8 + 54"
"modifier": !!int "5"
"stats":
  - !!int "17"
  - !!int "12"
  - !!int "14"
  - !!int "20"
  - !!int "16"
  - !!int "17"
"speed": "30 ft., fly 30 ft. (hover)"
"saves":
  - "dexterity": !!int "5"
  - "constitution": !!int "6"
  - "intelligence": !!int "9"
  - "wisdom": !!int "7"
"skillsaves":
  - "name": "[Arcana](Arcana)"
    "desc": "+9"
  - "name": "[Deception](skills.md#Deception)"
    "desc": "+7"
  - "name": "[Insight](skills.md#Insight)"
    "desc": "+7"
  - "name": "[Perception](Perception)"
    "desc": "+7"
"damage_resistances": "cold, fire, lightning"
"damage_immunities": "acid, poison"
"condition_immunities": "[charmed](conditions.md#Charmed), [poisoned](conditions.md#Poisoned)"
"senses": "[Truesight](senses.md#Truesight) 120 ft., passive\
  \ Perception 17"
"languages": "all; telepathy 120 ft."
"cr": "12"
"traits":
  - "desc": "If the arcanaloth dies outside Gehenna, its body dissolves into ichor,\
      \ and it gains a new body instantly and revives with all its [Hit Points](hit-points)\
      \ in Gehenna."
    "name": "Fiendish Restoration"
  - "desc": "The arcanaloth has [Advantage](advantage)\
      \ on saving throws against spells and other magical effects."
    "name": "Magic Resistance"
  - "desc": "The arcanaloth has a magic tome. While holding or carrying the tome,\
      \ the arcanaloth can use its Banishing Claw action.\n\nThe tome has AC 17; HP\
      \ 35; and [Immunity](immunity) to\
      \ Necrotic, Poison, and Psychic damage. The tome regains all its [Hit Points](hit-points)\
      \ at the end of every turn, but it turns to dust if reduced to 0 [Hit Points](hit-points)\
      \ or when the arcanaloth dies. If the tome is destroyed, the arcanaloth can\
      \ create a new one when it finishes a [Short](short-rest)\
      \ or [Long Rest](long-rest)."
    "name": "Soul Tome"
"actions":
  - "desc": "The arcanaloth makes three Fiendish Burst attacks. It can replace one\
      \ attack with a Banishing Claw attack."
    "name": "Multiattack"
  - "desc": "*Melee  or Ranged Attack Roll:* +9, reach 5 ft. or range 120 ft. *Hit:*\
      \ 31 (4d12 + 5) Necrotic damage."
    "name": "Fiendish Burst"
  - "desc": "*Melee Attack Roll:* +9, reach 5 ft. *Hit:* 10 (2d4 + 5) Slashing\
      \ damage plus 19 (3d12) Psychic damage. If the target is a creature, it is\
      \ subjected to the following effect. *Charisma Saving Throw:* DC 17. *Failure:*\
      \ The target is trapped in a demiplane inside the Soul Tome. While trapped there,\
      \ the target has the [Incapacitated](conditions.md#Incapacitated)\
      \ condition. At the end of each of its turns, the target repeats the save, escaping\
      \ the tome on a success. When the target escapes, it appears in the space it\
      \ left or, if that space is occupied, the nearest unoccupied space.\n\nIf the\
      \ target fails three of these saves while in the demiplane, it becomes bound\
      \ to the tome and can escape only if the tome is reduced to 0 [Hit Points](hit-points)."
    "name": "Banishing Claw (Requires Soul Tome)"
  - "desc": "The arcanaloth casts one of the following spells, requiring no Material\
      \ components and using Intelligence as the spellcasting ability (spell save\
      \ DC 17):\n\n**At will:** [Alter Self](alter-self),\
      \ [Detect Dagic](Detect%20Magic), [Identify](identify),\
      \ [Mage Hand](Mage-Hand), [Prestidigitation](prestidigitation)\n\
      \n**1/day each:** [Contact Other Plane](contact-other-plane),\
      \ [Detect Thoughts](detect-thoughts), [Dimension\
      \ Door](dimension-door), [Mind Blank](mind%20blank)"
    "name": "Spellcasting"
"bonus_actions":
  - "desc": "The arcanaloth teleports up to 30 feet to an unoccupied space it can\
      \ see."
    "name": "Teleport"
"reactions":
  - "desc": "The arcanaloth casts [Counterspell](counterspell)\
      \ in response to that spell's trigger, using the same spellcasting ability as\
      \ Spellcasting.\n"
    "name": "Counterspell"
"source":
  - "XMM"
"image": "bestiary/tokens/XMM/Arcanaloth.webp"
```
^statblock

## Environment

planar, lower