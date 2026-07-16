---
cssclasses:
- json5e-monster
tags:
- src/5e/mpmm
- monster/cr/10
- monster/environment/desert
- monster/environment/mountain
- monster/environment/urban
- monster/size/medium
- monster/type/Humanoids/gith
- monster/type/Humanoids/wizard
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Githyanki Gish"
---
# [Githyanki Gish](Githyanki-Gish-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 140*  

Gish blend their magical abilities with swordplay to become dangerous foes in battle. Their specialized capabilities make them well suited for assassination, raiding, and espionage.

## Githyanki

Githyanki descend from an ancient people who were also the progenitors of githzerai (also in this book). These tall, gaunt folk have potent psionic powers and dwell, for the most part, on the Astral Plane. Among the best-known githyanki are the bellicose followers of the Lich Queen Vlaakith. They terrorize the Astral Plane, raiding into other planes to plunder the multiverse of its magic and riches.

```statblock
"name": "Githyanki Gish (MPMM)"
"size": "Medium"
"type": "humanoid"
"subtype": "gith, wizard"
"alignment": "Any alignment"
"ac": !!int "17"
"ac_class": "[half plate](half-plate-armor)"
"hp": !!int "130"
"hit_dice": "20d8 + 40"
"modifier": !!int "2"
"stats":
  - !!int "17"
  - !!int "15"
  - !!int "14"
  - !!int "16"
  - !!int "15"
  - !!int "16"
"speed": "30 ft."
"saves":
  - "constitution": !!int "6"
  - "intelligence": !!int "7"
  - "wisdom": !!int "6"
"skillsaves":
  - "name": "[Insight](skills.md#Insight)"
    "desc": "+6"
  - "name": "[Perception](Perception)"
    "desc": "+6"
  - "name": "[Stealth](Stealth)"
    "desc": "+6"
"gear":
  - "[longsword](longsword)"
"senses": "passive Perception 16"
"languages": "Gith"
"cr": "10"
"actions":
  - "desc": "The githyanki makes three Longsword or Telekinetic Bolt attacks, or it\
      \ makes one of those attacks and uses Spellcasting."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +7 to hit, reach 5 ft., one target. *Hit:* 7\
      \ (1d8 + 3) slashing damage, or 8 (1d10 + 3) slashing damage if used with\
      \ two hands, plus 22 (5d8) psychic damage."
    "name": "Longsword"
  - "desc": "*Ranged Spell Attack:* +7 to hit, range 120 ft., one target. *Hit:*\
      \ 28 (8d6) force damage."
    "name": "Telekinetic Bolt"
  - "desc": "The githyanki casts one of the following spells, requiring no spell components\
      \ and using Intelligence as the spellcasting ability (spell save DC 15):\n\n\
      **At will:** [light](light), [mage hand](Mage%20Hand)\
      \ (the hand is invisible), [message](message)\n\
      \n**3/day each:** [fireball](fireball), [invisibility](invisibility),\
      \ [nondetection](nondetection) (self only)\n\n\
      **1/day each:** [dimension door](dimension-door),\
      \ [plane shift](Plane%20Shift), [telekinesis](telekinesis)"
    "name": "Spellcasting (Psionics)"
"bonus_actions":
  - "desc": "The githyanki teleports, along with any equipment it is wearing or carrying,\
      \ up to 30 feet to an unoccupied space it can see."
    "name": "Astral Step (Recharge 4-6)"
"source":
  - "MPMM"
"image": "bestiary/tokens/MPMM/Githyanki Gish.webp"
```
^statblock

## Environment

desert, mountain, urban