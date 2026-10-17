---
cssclasses:
  - json5e-monster
tags:
  - src/5e/rhw
  - monster/cr/8
  - monster/environment/any
  - monster/size/huge
  - monster/type/monstrosity
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Unspeakable Horror
---
# [Unspeakable Horror](Unspeakable%20Horror.md)
*Source: Ravenloft: The Horrors Within p. 274*  

![](https://media.dndbeyond.com/compendium-images/rthw/ogMxaVTj4GqgnUqr/22-036.unspeakable-horror.png)

*Terrifying Monster of the Mists*

Unspeakable horrors are anathema to all other life in the multiverse. Their shapes change constantly in ways that defy and disrupt reality. Those who look on these beings instantly understand their absolute and awful wrongness. Such revelations are often the last witnesses have before they're dissolved by discordant, destructive forces.

```statblock
"name": "Unspeakable Horror (RHW)"
"size": "Huge"
"type": "monstrosity"
"alignment": "Chaotic Evil"
"ac": !!int "13"
"hp": !!int "126"
"hit_dice": "12d12 + 48"
"modifier": !!int "1"
"stats":
  - !!int "21"
  - !!int "13"
  - !!int "19"
  - !!int "3"
  - !!int "14"
  - !!int "17"
"speed": "40 ft."
"saves":
  - "constitution": !!int "7"
  - "wisdom": !!int "5"
"damage_resistances": "acid, cold, necrotic, poison"
"condition_immunities": "[frightened](conditions.md#Frightened),\
  \ [grappled](conditions.md#Grappled), [prone](conditions.md#Prone),\
  \ [restrained](conditions.md#Restrained)"
"senses": "[Truesight](senses.md#Truesight) 60 ft., passive Perception 12"
"languages": ""
"cr": "8"
"traits":
  - "desc": "Attack rolls against the horror have Disadvantage. This trait is\
      \ suppressed while the horror has the\
      \ [Incapacitated](conditions.md#Incapacitated) condition."
    "name": "Incomprehensible Form"
  - "desc": "The horror regains 10 Hit Points at the start of each of its turns\
      \ if it has at least 1 Hit Point."
    "name": "Regeneration"
  - "desc": "The horror radiates an aura in a 15-foot Emanation while it\
      \ doesn't have the [Incapacitated](conditions.md#Incapacitated)\
      \ condition. *Wisdom Saving Throw:* DC 15, any enemy that starts its turn\
      \ in the aura. *Failure:* The target has the\
      \ [Frightened](conditions.md#Frightened) condition until the start of its\
      \ next turn. While [Frightened](conditions.md#Frightened) in this way,\
      \ the target has the [Paralyzed](conditions.md#Paralyzed) condition.\
      \ *Success:* The target is immune to this horror's aura for 24 hours."
    "name": "Terrifying Aura"
"actions":
  - "desc": "The horror makes three Phantasmic Assault attacks."
    "name": "Multiattack"
  - "desc": "*Melee or Ranged Attack Roll:* +8, reach 5 ft. or range 60 ft.\
      \ *Hit:* 14 (4d6) Cold, Necrotic, Poison, or Psychic damage (horror's\
      \ choice)."
    "name": "Phantasmic Assault"
"reactions":
  - "desc": "*Trigger:* A creature the horror can see within 120 feet of itself\
      \ takes the Study action or makes a Constitution saving throw to maintain\
      \ Concentration. *Response:**Wisdom Saving Throw:* DC 15, the triggering\
      \ creature. *Failure:* 7 (2d6) Psychic damage, and the target has the\
      \ [Stunned](conditions.md#Stunned) condition until the end of its next\
      \ turn."
    "name": "Warp Mind"
"source":
  - "RHW"
"image": "bestiary/tokens/RHW/Unspeakable Horror.webp"
```
^statblock

## Environment

any
