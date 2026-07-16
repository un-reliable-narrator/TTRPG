---
cssclasses:
- json5e-monster
tags:
- src/5e/xmm
- monster/cr/3
- monster/environment/any
- monster/size/medium
- monster/type/undead
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Swarm of Crawling Claws"
---
# [Swarm of Crawling Claws](Swarm-of-Crawling-Claws.md)
*Source: Monster Manual (2024) p. 83. Available in the <span title='Systems Reference Document (5.2)'>SRD</span> and the Free Rules (2024)*  

Swarms of crawling claws are typically animated by depraved necromancers. Occasionally, these grotesque swarms arise from mass graves or after tragedies, refusing to let their murderers escape their grasp.

## Crawling Claws

*Severed Appendages with Malicious Will*

- **Habitat.** Any  
- **Treasure.** None  

Crawling claws are severed hands that move and act of their own murderous accord. These deathless appendages can spring to life from the severed limbs of killers and villains, and sinister magic-users might animate crawling claws as foul servants. Crawling claws appear in a variety of forms, from decaying human hands to the fresh appendages of animals or monsters

> [!quote] A quote from Ansolm Haas  
> 
> Is it possible for any creature, any living being, to be inherently evil? Such an assertion may itself facilitate the committing of evil acts. By defining a person as evil, we give them free rein to behave as they will, absolving them from the wickedness of their words and the evil of their hands.


```statblock
"name": "Swarm of Crawling Claws (XMM)"
"size": "Medium"
"type": "undead"
"alignment": "Neutral Evil"
"ac": !!int "12"
"hp": !!int "49"
"hit_dice": "11d8"
"modifier": !!int "2"
"stats":
  - !!int "14"
  - !!int "14"
  - !!int "11"
  - !!int "5"
  - !!int "10"
  - !!int "4"
"speed": "30 ft., climb 30 ft."
"damage_resistances": "bludgeoning, piercing, slashing"
"damage_immunities": "necrotic, poison"
"condition_immunities": "[charmed](conditions.md#Charmed), [exhaustion](conditions.md#Exhaustion),\
  \ [frightened](conditions.md#Frightened), [grappled](conditions.md#Grappled),\
  \ [incapacitated](conditions.md#Incapacitated), [paralyzed](conditions.md#Paralyzed),\
  \ [petrified](conditions.md#Petrified), [poisoned](conditions.md#Poisoned),\
  \ [prone](conditions.md#Prone), [restrained](conditions.md#Restrained),\
  \ [stunned](conditions.md#Stunned)"
"senses": "[Blindsight](senses.md#Blindsight) 30 ft., passive\
  \ Perception 10"
"languages": "understands Common but can't speak"
"cr": "3"
"traits":
  - "desc": "The swarm can occupy another creature's space and vice versa, and the\
      \ swarm can move through any opening large enough for a Tiny creature. The swarm\
      \ can't regain [Hit Points](hit-points)\
      \ or gain [Temporary Hit Points](temporary-hit-points)."
    "name": "Swarm"
"actions":
  - "desc": "*Melee Attack Roll:* +4, reach 5 ft. *Hit:* 20 (4d8 + 2) Necrotic\
      \ damage, or 11 (2d8 + 2) Necrotic damage if the swarm is [Bloodied](conditions.md#Bloodied).\
      \ If the target is a Medium or smaller creature, it has the [Prone](conditions.md#Prone)\
      \ condition."
    "name": "Swarm of Grasping Hands"
"source":
  - "XMM"
"image": "bestiary/tokens/XMM/Swarm of Crawling Claws.webp"
```
^statblock

## Environment

any