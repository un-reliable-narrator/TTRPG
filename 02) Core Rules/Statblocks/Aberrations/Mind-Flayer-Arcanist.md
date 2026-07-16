---
cssclasses:
- json5e-monster
tags:
- src/5e/xmm
- monster/cr/11
- monster/environment/underdark
- monster/size/medium
- monster/type/aberration
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Mind Flayer Arcanist"
---
# [Mind Flayer Arcanist](Mind-Flayer-Arcanist.md)
*Source: Monster Manual (2024) p. 214*  

Mind flayer arcanists enhance their psionic abilities with magic. Other mind flayers view those that undertake such experiments with disgust and fear.

## Mind Flayers

*Brain-Eating Underdark Tyrants*

- **Habitat.** Underdark  
- **Treasure.** [Arcana](random-magic-items-arcana.md)  

Scattered survivors of a world-ruining, multiversal empire, mind flayers lurk in secret conclaves hidden deep within Material Plane worlds. Within their alien sanctuaries, these wicked masterminds—also known as illithids—reshape the Underdark and its inhabitants to serve their unfathomable whims. Mind flayers are feared for their psionic powers, which allow them to stun and control other creatures, and for their horrific method of feeding: using their four slimy tentacles to extract the brains of their victims.

Mind flayers are infamous plotters and manipulators, concocting plans that reach beyond their subterranean realms. Aside from using their psionic powers to control others, mind flayers often experiment with their own bizarre life cycles, implanting other creatures with illithid young to create unnatural servants. Creatures such as grimlocks and intellect devourers result from mind flayers' biological tampering, while other Underdark-dwelling monsters—including kuo-toa, quaggoths, and troglodytes—often serve illithid masters. Githyanki and githzerai have a long adversarial history with mind flayers and bear the scars of illithid manipulation.

### Mind Flayer Colonies

Mind flayers work as lone schemers, in mysterious cabals, or as part of worlds-spanning illithid conspiracies. In groups, mind flayers work toward bizarre agendas organized by an elder brain—a massive, brain-like being with incredible psionic powers. Without such a leader, groups of mind flayers fall to self-destructive squabbling. Roll on or choose a result from the Mind Flayer Machinations table to inspire an illithid conclave's plots.

**Mind Flayer Machinations**

| dice: 1d6 | The Mind Flayer Colony Seeks To... |
|-----------|------------------------------------|
| 1 | Blot out the sun so their Underdark-dwelling servants can invade the surface. |
| 2 | Create a new monstrous fusion between mind flayers and a legendary monster. |
| 3 | Forge a psionic network uniting illithid colonies. |
| 4 | Replace world leaders with intellect devourers. |
| 5 | Restore a vessel to travel through Wildspace. |
| 6 | Sacrifice the mental energy of a planet's populace to take control of a githyanki bastion. |
^mind-flayer-machinations

```statblock
"name": "Mind Flayer Arcanist (XMM)"
"size": "Medium"
"type": "aberration"
"alignment": "Lawful Evil"
"ac": !!int "16"
"hp": !!int "143"
"hit_dice": "26d8 + 26"
"modifier": !!int "6"
"stats":
  - !!int "11"
  - !!int "14"
  - !!int "13"
  - !!int "20"
  - !!int "17"
  - !!int "17"
"speed": "30 ft., fly 30 ft. (hover)"
"saves":
  - "dexterity": !!int "6"
  - "intelligence": !!int "9"
  - "wisdom": !!int "7"
  - "charisma": !!int "7"
"skillsaves":
  - "name": "[Arcana](Arcana)"
    "desc": "+13"
  - "name": "[Insight](skills.md#Insight)"
    "desc": "+7"
  - "name": "[Perception](Perception)"
    "desc": "+7"
  - "name": "[Stealth](Stealth)"
    "desc": "+6"
"damage_immunities": "psychic"
"condition_immunities": "[charmed](conditions.md#Charmed), [frightened](conditions.md#Frightened)"
"gear":
  - "[breastplate](breastplate)"
"senses": "[Darkvision](senses.md#Darkvision) 120 ft., passive\
  \ Perception 17"
"languages": "Deep Speech, Undercommon; telepathy 120 ft."
"cr": "11"
"traits":
  - "desc": "The mind flayer has [Advantage](advantage)\
      \ on saving throws against spells and other magical effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "The mind flayer makes three Arcane Tentacles attacks."
    "name": "Multiattack"
  - "desc": "*Melee  or Ranged Attack Roll:* +9, reach 5 ft. or range 120 ft. *Hit:*\
      \ 27 (4d10 + 5) Psychic damage, and the mind flayer can teleport the target\
      \ up to 30 feet to an unoccupied space the mind flayer can see on a surface\
      \ or liquid large enough to support the target. If this damage reduces the target\
      \ to 0 [Hit Points](hit-points),\
      \ the mind flayer kills it and magically devours its brain."
    "name": "Arcane Tentacles"
  - "desc": "*Intelligence Saving Throw:* DC 17, each creature in a 40-foot [Emanation](emanation-area-of-effect)\
      \ originating from the mind flayer. *Failure:* 41 (8d8 + 5) Psychic damage,\
      \ and the target has the [Stunned](conditions.md#Stunned)\
      \ condition until the end of the mind flayer's next turn. *Success:* Half damage\
      \ only."
    "name": "Mind Burst (Recharge 5-6)"
  - "desc": "The mind flayer casts one of the following spells, requiring no spell\
      \ components and using Intelligence as the spellcasting ability (spell save\
      \ DC 17):\n\n**At will:** [Detect Dagic](Detect%20Magic),\
      \ [Detect Thoughts](detect-thoughts), [Disguise\
      \ Self](disguise-self), [Mage Hand](Mage%20Hand)\
      \ (the hand is Invisible)\n\n**1/day each:** [Clairvoyance](clairvoyance),\
      \ [Dimension Door](dimension-door), [Fireball](fireball)\
      \ (level 5 version), [Lightning Bolt](lightning-bolt)\
      \ (level 5 version), [Plane Shift](Plane%20Shift)\
      \ (self only), [Sending](sending)"
    "name": "Spellcasting"
"reactions":
  - "desc": "The mind flayer casts [Shield](shield)\
      \ in response to that spell's trigger, using the same spellcasting ability as\
      \ Spellcasting.\n"
    "name": "Shield (2/Day)"
"source":
  - "XMM"
"image": "bestiary/tokens/XMM/Mind Flayer Arcanist.webp"
```
^statblock

## Environment

underdark