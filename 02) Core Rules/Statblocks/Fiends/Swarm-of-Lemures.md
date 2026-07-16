---
cssclasses:
- json5e-monster
tags:
- src/5e/xmm
- monster/cr/3
- monster/environment/nine-hells
- monster/environment/planar
- monster/size/large
- monster/type/Fiends/devil
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Swarm of Lemures"
---
# [Swarm of Lemures](Swarm-of-Lemures.md)
*Source: Monster Manual (2024) p. 194*  

When devils drive hosts of lemures into close proximity or when lemures compress into a single mass, a swarm forms and adopts a unified mind.

## Lemures

*Devils of Agony and Despair*

- **Habitat.** Planar (Nine Hells)  
- **Treasure.** None  

The least of all devils, lemures arise from wicked souls, their mortal memories scoured away. Only vague limbs and anguished features jut from these slurries of infernal proto-matter.

```statblock
"name": "Swarm of Lemures (XMM)"
"size": "Large"
"type": "fiend"
"subtype": "devil"
"alignment": "Lawful Evil"
"ac": !!int "12"
"hp": !!int "45"
"hit_dice": "6d10 + 12"
"modifier": !!int "-2"
"stats":
  - !!int "14"
  - !!int "7"
  - !!int "14"
  - !!int "1"
  - !!int "12"
  - !!int "3"
"speed": "40 ft."
"damage_resistances": "bludgeoning, cold, piercing, slashing"
"damage_immunities": "fire, poison"
"condition_immunities": "[charmed](conditions.md#Charmed), [frightened](conditions.md#Frightened),\
  \ [grappled](conditions.md#Grappled), [paralyzed](conditions.md#Paralyzed),\
  \ [petrified](conditions.md#Petrified), [poisoned](conditions.md#Poisoned),\
  \ [prone](conditions.md#Prone), [restrained](conditions.md#Restrained),\
  \ [stunned](conditions.md#Stunned)"
"senses": "[Darkvision](senses.md#Darkvision) 120 ft. (unimpeded\
  \ by magical [Darkness](darkness)),\
  \ passive Perception 11"
"languages": "understands Infernal but can't speak"
"cr": "3"
"traits":
  - "desc": "If the swarm dies in the Nine Hells, it revives with all its [Hit Points](hit-points)\
      \ in 1d10 days unless it is killed by a creature under the effects of a [Bless](bless)\
      \ spell or its remains are sprinkled with Holy Water."
    "name": "Hellish Restoration"
  - "desc": "The swarm can occupy another creature's space and vice versa, and the\
      \ swarm can move through an opening large enough for a Medium creature. The\
      \ swarm can't regain [Hit Points](hit-points)\
      \ or gain [Temporary Hit Points](temporary-hit-points)."
    "name": "Swarm"
"actions":
  - "desc": "The swarm makes two Vile Slime attacks."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +4, reach 5 ft. *Hit:* 11 (2d8 + 2) Poison damage,\
      \ or 9 (2d6 + 2) Poison damage if the swarm is [Bloodied](conditions.md#Bloodied)."
    "name": "Vile Slime"
"source":
  - "XMM"
"image": "bestiary/tokens/XMM/Swarm of Lemures.webp"
```
^statblock

## Environment

planar, nine hells