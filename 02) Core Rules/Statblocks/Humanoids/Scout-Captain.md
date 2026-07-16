---
cssclasses:
- json5e-monster
tags:
- src/5e/xmm
- monster/cr/3
- monster/environment/any
- monster/size/small-or-medium
- monster/type/humanoid
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Scout Captain"
---
# [Scout Captain](Scout-Captain.md)
*Source: Monster Manual (2024) p. 270*  

Scout captains are experienced explorers and sharpshooters. They might lead bands of other scouts or disappear into the wilds alone for months at a time.

## Scouts

*Watchers and Wanderers*

- **Habitat.** Any  
- **Treasure.** [Implements](random-magic-items-implements.md), Individual  

Scouts are warriors of the wilderness, trained in hunting and tracking. They might be explorers or trappers, or they could perform more martial roles as archers, bounty hunters, or outriders.

```statblock
"name": "Scout Captain (XMM)"
"size": "Small or Medium"
"type": "humanoid"
"alignment": "Neutral"
"ac": !!int "15"
"hp": !!int "66"
"hit_dice": "12d8 + 12"
"modifier": !!int "5"
"stats":
  - !!int "11"
  - !!int "16"
  - !!int "12"
  - !!int "14"
  - !!int "15"
  - !!int "11"
"speed": "30 ft., climb 30 ft."
"saves":
  - "dexterity": !!int "5"
  - "intelligence": !!int "4"
"skillsaves":
  - "name": "[Perception](Perception)"
    "desc": "+6"
  - "name": "[Stealth](Stealth)"
    "desc": "+7"
  - "name": "[Survival](Survival)"
    "desc": "+6"
"gear":
  - "[longbow](longbow)"
  - "[shortsword](shortsword)"
  - "[studded leather armor](studded-leather-armor)"
"senses": "passive Perception 16"
"languages": "Common plus one other language"
"cr": "3"
"actions":
  - "desc": "The scout makes two attacks, using Shortsword or Longbow in any combination."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +5, reach 5 ft. *Hit:* 6 (1d6 + 3) Piercing\
      \ damage, plus 10 (3d6) Piercing damage if the attack was made with [Advantage](advantage)."
    "name": "Shortsword"
  - "desc": "*Ranged Attack Roll:* +5, range 150/600 ft. *Hit:* 7 (1d8 + 3) Piercing\
      \ damage, plus 10 (3d6) Piercing damage if the attack was made with [Advantage](advantage)."
    "name": "Longbow"
"bonus_actions":
  - "desc": "The scout has [Advantage](advantage)\
      \ on the next attack roll it makes during the current turn."
    "name": "Aim"
"reactions":
  - "desc": "Trigger: The scout is hit by an attack roll. _Response:_ The scout halves\
      \ the damage (round down) it takes from that attack."
    "name": "Uncanny Dodge"
"source":
  - "XMM"
"image": "bestiary/tokens/XMM/Scout Captain.webp"
```
^statblock

## Environment

any