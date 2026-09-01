---
cssclasses:
- json5e-monster
tags:
- src/5e/lox
- monster/cr/5
- monster/size/large
- monster/type/celestial
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Vocath"
---
# [Vocath](vocath-Lox.md)
*Source: Light of Xaryxis p. 42*  

```statblock
"name": "Vocath (LoX)"
"size": "Large"
"type": "celestial"
"alignment": "typically  Lawful Neutral"
"ac": !!int "13"
"ac_class": "[mage armor](mage-armor)"
"hp": !!int "75"
"hit_dice": "10d10 + 20"
"modifier": !!int "0"
"stats":
  - !!int "16"
  - !!int "10"
  - !!int "15"
  - !!int "18"
  - !!int "16"
  - !!int "15"
"speed": "30 ft."
"saves":
  - "intelligence": !!int "7"
  - "wisdom": !!int "6"
  - "charisma": !!int "5"
"skillsaves":
  - "name": "[Insight](skills.md#Insight)"
    "desc": "+9"
  - "name": "[Perception](Perception)"
    "desc": "+6"
  - "name": "[Persuasion](Persuasion)"
    "desc": "+5"
"senses": "passive Perception 16"
"languages": "Common, Giant, telepathy 60 ft. (see also Mercane telepathy)"
"cr": "5"
"traits":
  - "desc": "Vocath can communicate telepathically with any other mercane it knows,\
      \ regardless of the distance between them."
    "name": "Mercane Telepathy"
"actions":
  - "desc": "Vocath makes three Psi-Imbued Blade attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one target. *Hit:* 10\
      \ (2d6 + 3) slashing damage, and if the target is a creature, it must succeed\
      \ on a DC 15 Wisdom saving throw or be [frightened](conditions.md#Frightened)\
      \ of Vocath until the end of the target's next turn."
    "name": "Psi-Imbued Blade"
  - "desc": "Vocath casts one of the following spells, requiring no spell components\
      \ and using Intelligence as the spellcasting ability (spell save DC 15):\n\n\
      **At will:** [Detect Dagic](Detect%20Magic), [light](light)\n\
      \n**1/day each:** [dimension door](dimension-door),\
      \ [invisibility](invisibility), [mage armor](mage-armor)\
      \ (self only)"
    "name": "Spellcasting (Psionics)"
"source":
  - "LoX"
"image": "bestiary/tokens/LoX/Vocath.webp"
```
^statblock