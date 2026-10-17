---
cssclasses:
  - json5e-monster
tags:
  - src/5e/rhw
  - monster/cr/4
  - monster/environment/planar-shadowfell
  - monster/environment/underdark
  - monster/environment/urban
  - monster/size/medium
  - monster/type/undead
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Strahd Skeleton
---
# [Strahd Skeleton](Strahd%20Skeleton.md)
*Source: Ravenloft: The Horrors Within p. 269*  

![](https://5e.tools/img/bestiary/RHW/Strahd%20Skeleton.webp)

*Skeletal Soldier of the First Vampire*

Vampires sometimes turn mortal servants unworthy of the gift of vampirism into skeletal soldiers. Known as Strahd skeletons—in recognition of the lord of Barovia who first created them—these silent, capable undead soldiers wield vampiric blades. Strahd skeletons that whet their blades in blood often carry their weapons back to their vampire lords. Tales disagree on whether vampires can feed from these bloody blades or merely revel in the sacrifice.

```statblock
"name": "Strahd Skeleton (RHW)"
"size": "Medium"
"type": "undead"
"alignment": "Lawful Evil"
"ac": !!int "16"
"hp": !!int "65"
"hit_dice": "10d8 + 20"
"modifier": !!int "1"
"stats":
  - !!int "17"
  - !!int "13"
  - !!int "15"
  - !!int "12"
  - !!int "15"
  - !!int "16"
"speed": "30 ft."
"saves":
  - "strength": !!int "5"
"damage_vulnerabilities": "bludgeoning"
"damage_immunities": "poison"
"condition_immunities": "[exhaustion](conditions.md#Exhaustion),\
  \ [frightened](conditions.md#Frightened), [poisoned](conditions.md#Poisoned)"
"senses": "[Darkvision](senses.md#Darkvision) 60 ft., passive Perception 12"
"languages": "understands Common but can't speak"
"cr": "4"
"traits":
  - "desc": "If damage reduces the skeleton to 0 Hit Points, it makes a\
      \ Constitution saving throw (DC 5 plus the damage taken) unless the\
      \ damage is Radiant or from a Critical Hit. On a successful save, the\
      \ skeleton drops to 1 Hit Point instead."
    "name": "Undead Fortitude"
"actions":
  - "desc": "The skeleton makes two Vampiric Longsword attacks. It can replace\
      \ one attack with a use of Shield Bash."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +5, reach 5 ft. *Hit:* 7 (1d8 + 3) Slashing\
      \ damage plus 7 (2d6) Necrotic damage. The target's Hit Point maximum\
      \ decreases by an amount equal to the Necrotic damage taken."
    "name": "Vampiric Longsword"
  - "desc": "*Strength Saving Throw:* DC 13, one creature within 5 feet that\
      \ the skeleton can see. *Failure:* 10 (2d6 + 3) Bludgeoning damage. If\
      \ the target is a Medium or smaller creature, it has the\
      \ [Prone](conditions.md#Prone) condition."
    "name": "Shield Bash"
"source":
  - "RHW"
"image": "bestiary/tokens/RHW/Strahd Skeleton.webp"
```
^statblock

## Environment

planar, shadowfell, underdark, urban

## Original Thoughts
**Strahd's Royal Guard.** At first glance, Strahd Skeletons may fill a similar thematic niche as the [[Wight]]s serving as former guards of Castle Ravenloft. Crucially, however, they do not speak. Also, in spite of a higher CR, they are arguably weaker in many respects. As such, they are more suited as enforcers and personal guards. 

**Skeletal Rider.** May appear mounted on a [[Warhorse-Skeleton|Warhorse Skeleton]] and benefit from the [[Mounted Combatant]] feat. (While mounted, has advantage attacking unmounted medium or smaller creatures, can force attacks targeting the warhorse to hit it instead, warhorse benefits from pseudo-Evasion while mounted.) While mounted, shield bash is re-flavored as charge or the horse kicking. If the rider is unmounted, incapacitated or destroyed, the warhorse may fight on.
