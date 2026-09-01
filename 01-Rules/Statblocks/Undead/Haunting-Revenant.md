---
cssclasses:
- json5e-monster
tags:
- src/5e/xmm
- monster/cr/10
- monster/environment/forest
- monster/environment/swamp
- monster/environment/urban
- monster/size/gargantuan
- monster/type/undead
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Haunting Revenant"
---
# [Haunting Revenant](Haunting-Revenant.md)
*Source: Monster Manual (2024) p. 260*  

Haunting revenants possess ruins and forsaken places connected with their deaths—such as abandoned buildings, wrecked ships, or junk heaps. These revenants lurk in plain sight, waiting for their foes to near, then trap their victims within their massive bodies. Those inside a revenant might be battered by animate furnishings or more unsettling manifestations of the revenant's hatred.

The places haunting revenants lurk swiftly gain infamous reputations.

## Revenants

*Vengeance from beyond the Grave*

- **Habitat.** Forest, Swamp, Urban  
- **Treasure.** Any  

Wrathful spirits bent on revenge, revenants possess corpses and other materials, using them to seek justice or vent their rage on those who wronged them. Revenants refuse to rest until those they seek to punish are no more. If their bodies are destroyed, revenants claim new forms and continue their ruthless quests.

```statblock
"name": "Haunting Revenant (XMM)"
"size": "Gargantuan"
"type": "undead"
"alignment": "Neutral"
"ac": !!int "20"
"hp": !!int "203"
"hit_dice": "14d20 + 56"
"modifier": !!int "5"
"stats":
  - !!int "20"
  - !!int "12"
  - !!int "18"
  - !!int "16"
  - !!int "18"
  - !!int "20"
"speed": "30 ft."
"saves":
  - "constitution": !!int "8"
  - "wisdom": !!int "8"
"damage_resistances": "necrotic, psychic"
"damage_immunities": "poison"
"condition_immunities": "[charmed](conditions.md#Charmed), [exhaustion](conditions.md#Exhaustion),\
  \ [frightened](conditions.md#Frightened), [grappled](conditions.md#Grappled),\
  \ [paralyzed](conditions.md#Paralyzed), [petrified](conditions.md#Petrified),\
  \ [poisoned](conditions.md#Poisoned), [prone](conditions.md#Prone),\
  \ [restrained](conditions.md#Restrained), [unconscious](conditions.md#Unconscious)"
"senses": "[Truesight](senses.md#Truesight) 60 ft., passive\
  \ Perception 14"
"languages": "Common plus two other languages"
"cr": "10"
"traits":
  - "desc": "*Constitution Saving Throw:* DC 17, any creature that casts a spell while\
      \ inside the revenant's space. *Failure:* The spell fails and is wasted."
    "name": "Haunted Zone"
  - "desc": "If the revenant dies, it revives 24 hours later unless [Dispel Evil and\
      \ Good](dispel%20evil%20and%20good) is cast on its\
      \ remains. If it revives, it animates another Gargantuan object or structure\
      \ elsewhere on the same plane of existence; it now looks different but uses\
      \ the same stat block and returns with all its [Hit Points](hit-points)."
    "name": "Undead Restoration"
"actions":
  - "desc": "The revenant makes two [Object](object)\
      \ Slam attacks and uses Invitation."
    "name": "Multiattack"
  - "desc": "*Melee  or Ranged Attack Roll:* +9 (with [Advantage](advantage)\
      \ if the target is inside the revenant's space), reach 10 ft. or range 30/90\
      \ ft. *Hit:* 27 (5d8 + 5) Bludgeoning damage."
    "name": "Object Slam"
  - "desc": "*Charisma Saving Throw:* DC 17, each creature in a 60-foot [Cone](cone-area-of-effect).\
      \ *Failure:* The target is teleported inside the revenant's space and swallowed.\
      \ A swallowed creature has [Total Cover](cover)\
      \ against attacks and other effects outside the revenant.\n\nWhile the revenant\
      \ has [Hit Points](hit-points),\
      \ a swallowed creature can leave the revenant's space only by using magic that\
      \ enables planar travel, such as the [Plane Shift](Plane%20Shift)\
      \ spell."
    "name": "Invitation"
"source":
  - "XMM"
"image": "bestiary/tokens/XMM/Haunting Revenant.webp"
```
^statblock

## Environment

forest, swamp, urban