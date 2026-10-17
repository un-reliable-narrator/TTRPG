---
cssclasses:
  - json5e-monster
tags:
  - src/5e/ggr
  - monster/cr/1/2
  - monster/size/medium
  - monster/type/humanoid/kraul
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Kraul Warrior
---
# [Kraul Warrior](Kraul-Warrior-ggr.md)
*Source: Guildmasters' Guide to Ravnica p. 213*  

![](https://5e.tools/img/bestiary/GGR/Kraul%20Warrior.webp)

## Kraul

The kraul are an ascendant power group within the Golgari Swarm, long content to linger at the margins of the undercity but now increasingly making their buzzing voices heard in the subterranean Golgari guildhall. These six-legged, insectile beings are hard-headed and literal-minded, with little grasp of metaphor or nuance.

```statblock
"name": "Kraul Warrior (GGR)"
"size": "Medium"
"type": "humanoid"
"subtype": "kraul"
"alignment": "Neutral Evil"
"ac": !!int "18"
"ac_class": "natural armor"
"hp": !!int "27"
"hit_dice": "5d8 + 5"
"modifier": !!int "1"
"stats":
  - !!int "15"
  - !!int "12"
  - !!int "13"
  - !!int "10"
  - !!int "11"
  - !!int "8"
"speed": "30 ft., climb 30 ft."
"senses": "[Darkvision](senses.md#Darkvision) 60 ft., passive Perception 10"
"languages": "Kraul, understands Common but can't speak it"
"cr": "1/2"
"traits":
  - "desc": "The kraul is immune to the [charmed](conditions.md#Charmed) and\
      \ [frightened](conditions.md#Frightened) conditions while within 30 feet\
      \ of at least one other kraul."
    "name": "Hive Mind"
  - "desc": "The kraul has advantage on an attack roll against a creature if at\
      \ least one of the kraul's allies is within 5 feet of the creature and\
      \ the ally isn't [incapacitated](conditions.md#Incapacitated)."
    "name": "Pack Tactics"
  - "desc": "The kraul can climb difficult surfaces, including upside down on\
      \ ceilings, without needing to make an ability check."
    "name": "Spider Climb"
"actions":
  - "desc": "*Melee or Ranged Weapon Attack:* +4 to hit, reach 5 ft. or range\
      \ 20/60 ft., one target. *Hit:* 5 (1d6 + 2) piercing damage, or 6 (1d8 +\
      \ 2) piercing damage if used with two hands to make a melee attack."
    "name": "Spear"
"source":
  - "GGR"
"image": "bestiary/tokens/GGR/Kraul Warrior.webp"
```
^statblock

## Winged Kraul Warriors

Some kraul warriors have a flying speed of 40 feet, as a result of possessing gossamer wings. Their wings give them a higher station among the kraul soldiers. Winged kraul warriors serve the guild as scouts and shock troops.
