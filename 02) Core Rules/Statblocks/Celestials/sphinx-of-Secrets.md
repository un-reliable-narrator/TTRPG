---
cssclasses:
- json5e-monster
tags:
- src/5e/xmm
- monster/cr/8
- monster/environment/desert
- monster/environment/planar
- monster/environment/upper
- monster/size/large
- monster/type/celestial
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Sphinx of Secrets"
---
# [Sphinx of Secrets](sphinx-of-Secrets.md)
*Source: Monster Manual (2024) p. 292*  

Sphinxes of secrets are commonly associated with a site of great magic or learning. These immortal beings often outlive such locations, though, and might protect a site's ruins as they continue their own studies. Sphinxes of secrets fiercely guard their dwellings and research.

## Sphinxes

*Collectors and Keepers of Secrets*

- **Habitat.** Desert, Planar (Upper Planes)  
- **Treasure.** [Arcana](random-magic-items-arcana.md)  

Sphinxes protect the secrets of the multiverse. Formed from the spirits of sages and explorers, sphinxes know the power of truth and the importance of preserving it. They share their wisdom only with those who prove themselves wise or overcome tests of worthiness, such as riddles or battles with dangerous beasts. Through their existences, sphinxes might change form as they gain more nuanced understanding of cosmic enigmas.

### Sphinx Lairs

Sphinxes typically dwell in places that hold great knowledge or prophetic magic.

> [!quote]  
> 
> Round she is, yet flat as a board
> 
> Altar of the Lupine Lords
> 
> Jewel on black velvet, pearl in the sea
> 
> Unchanged but e'erchanging eternally

> [!note]
> Answer to the riddle of White Plume Mountain: The Moon.

```statblock
"name": "Sphinx of Secrets (XMM)"
"size": "Large"
"type": "celestial"
"alignment": "Lawful Neutral"
"ac": !!int "16"
"hp": !!int "136"
"hit_dice": "16d10 + 48"
"modifier": !!int "5"
"stats":
  - !!int "18"
  - !!int "15"
  - !!int "16"
  - !!int "18"
  - !!int "18"
  - !!int "18"
"speed": "40 ft., fly 60 ft."
"skillsaves":
  - "name": "[History](History)"
    "desc": "+7"
  - "name": "[Perception](Perception)"
    "desc": "+7"
  - "name": "[Religion](Religion)"
    "desc": "+7"
"damage_resistances": "necrotic, radiant"
"damage_immunities": "psychic"
"condition_immunities": "[charmed](conditions.md#Charmed), [frightened](conditions.md#Frightened)"
"senses": "[Truesight](senses.md#Truesight) 60 ft., passive\
  \ Perception 17"
"languages": "Celestial, Common"
"cr": "8"
"traits":
  - "desc": "No magic can observe the sphinx remotely or detect its thoughts without\
      \ its permission. Wisdom ([Insight](skills.md#Insight))\
      \ checks made to ascertain its intentions or sincerity are made with [Disadvantage](disadvantage)."
    "name": "Inscrutable"
  - "desc": "The sphinx has [Advantage](advantage)\
      \ on saving throws against spells and other magical effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "The sphinx makes three Claw attacks. It can replace one attack with a\
      \ use of [Curse](curses) of the\
      \ Riddle."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +7, reach 5 ft. *Hit:* 13 (2d8 + 4) Slashing\
      \ damage plus 7 (2d6) Radiant damage."
    "name": "Claw"
  - "desc": "*Intelligence Saving Throw:* DC 15, one creature the sphinx can see within\
      \ 60 feet. *Failure:* 21 (6d6) Psychic damage, and the target is cursed with\
      \ a riddle. The cursed target has [Disadvantage](disadvantage)\
      \ on ability checks and attack rolls. In addition, if it takes the Magic action,\
      \ it must succeed on a DC 15 Intelligence saving throw or that action is wasted.\
      \ The cursed target can take a Study action to make a DC 15 Intelligence check,\
      \ solving the riddle and ending the curse on a success. The curse ends early\
      \ if the sphinx curses another target."
    "name": "Curse of the Riddle"
  - "desc": "The sphinx casts one of the following spells, requiring no Material components\
      \ and using Intelligence as the spellcasting ability (spell save DC 15):\n\n\
      **At will:** [Detect Dagic](Detect%20Magic), [Identify](identify),\
      \ [Prestidigitation](prestidigitation)\n\n**1/day\
      \ each:** [Locate Object](locate-object), [Remove\
      \ Curse](remove%20curse)"
    "name": "Spellcasting"
"source":
  - "XMM"
"image": "bestiary/tokens/XMM/Sphinx of Secrets.webp"
```
^statblock

## Environment

desert, planar, upper