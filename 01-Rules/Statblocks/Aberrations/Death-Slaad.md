---
cssclasses:
- json5e-monster
tags:
- src/5e/xmm
- monster/cr/10
- monster/environment/limbo
- monster/environment/planar
- monster/size/medium
- monster/type/aberration
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Death Slaad"
---
# [Death Slaad](Death-Slaad.md)
*Source: Monster Manual (2024) p. 287*  

Slaad lords create death slaadi by infusing gray slaadi with a portion of their chaotic energy. When groups of slaadi act deliberately, death slaadi are often behind their designs.

## Slaadi

*Chaos-Spawned Hordes of Limbo*

- **Habitat.** Planar (Limbo)  
- **Treasure.** Any  

Unpredictable slaadi devour and multiply across the Ever-Changing Chaos of Limbo. These toad-like, extraplanar beings embody the endless potentiality of their home plane of existence. While slaadi aren't inherently evil, their impulses are wild and often destructive. Many are driven to propagate through supernatural processes. Unfortunately, these processes typically are fatal for other creatures.

Slaadi have no formal society. Rather, strong slaadi dominate weaker ones. Blue and red slaadi rampage across Limbo and spill into other worlds at the direction of green slaadi. More powerful slaadi have connections to the Spawning Stone, a source of chaotic magic from which the first slaadi originated. The Spawning Stone is hidden deep within Limbo, and legends tie its origins to the modron overlord Primus or the ruinous slaad lords, such as Ssendam, the golden amoeboid terror, and Ygorl, the winged skeleton. These slaad lords and others plot to spread slaadi across the multiverse.

> [!note] Slaad Control Gems
> 
> A slaad born from the Spawning Stone has a magical control gem embedded in its head. If a creature claims the gem, the slaad has the [Charmed](Conditions.md#Charmed) condition and obeys the gem's bearer. The slaad ceases to be [Charmed](Conditions.md#Charmed) if it is harmed by the gem's bearer or the bearer's allies or if the gem is returned to the slaad. A [Greater-Restoration](Greater-Restoration.md) spell cast on a slaad destroys the gem, and the slaad ceases to be [Charmed](Conditions.md#Charmed).
> 
> One can obtain a slaad's control gem using a [Wish](Wish.md) or [Imprisonment](Imprisonment.md) spell. If the slaad fails its saving throw against [Imprisonment](Imprisonment.md), the caster gains the gem, and the slaad isn't imprisoned. An [Incapacitated](Conditions.md#Incapacitated) slaad's control gem can be removed by spending 1 minute and succeeding on a DC 20 Wisdom ([Medicine](Medicine.md)) check. Failing this check deals 22 (`dice: 4d10`) Piercing damage to the slaad.
^slaad-control-gems

> [!quote] A quote from Jebeel Sloom  
> 
> Fight a slaad and lose, the story's over. Fight a slaad and win, there's a thousand more standing in line just to prove they're tougher.


```statblock
"name": "Death Slaad (XMM)"
"size": "Medium"
"type": "aberration"
"alignment": "Chaotic Evil"
"ac": !!int "18"
"hp": !!int "178"
"hit_dice": "21d8 + 84"
"modifier": !!int "10"
"stats":
  - !!int "20"
  - !!int "15"
  - !!int "19"
  - !!int "15"
  - !!int "10"
  - !!int "19"
"speed": "40 ft."
"skillsaves":
  - "name": "[Arcana](Arcana)"
    "desc": "+6"
  - "name": "[Perception](Perception)"
    "desc": "+8"
"damage_resistances": "acid, cold, fire, lightning, thunder"
"senses": "[Blindsight](senses.md#Blindsight) 60 ft., [Darkvision](senses.md#Darkvision)\
  \ 60 ft., passive Perception 18"
"languages": "Common, Slaad; telepathy 60 ft."
"cr": "10"
"traits":
  - "desc": "The slaad has [Advantage](advantage)\
      \ on saving throws against spells and other magical effects."
    "name": "Magic Resistance"
  - "desc": "The slaad regains 10 [Hit Points](hit-points)\
      \ at the start of each of its turns if it has at least 1 [Hit Point](hit-points)."
    "name": "Regeneration"
"actions":
  - "desc": "The slaad makes two Chaos Blade attacks."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +9, reach 10 ft. *Hit:* 11 (1d12 + 5) Slashing\
      \ damage plus 10 (3d6) Necrotic damage. Until the start of the slaad's next\
      \ turn, the target has a condition determined by rolling 1d4: on a 1, [Charmed](conditions.md#Charmed);\
      \ on a 2, [Frightened](conditions.md#Frightened); on a\
      \ 3, [poisoned](conditions.md#Poisoned); or on a 4, [Incapacitated](conditions.md#Incapacitated)."
    "name": "Chaos Blade"
  - "desc": "The slaad casts one of the following spells, requiring no Material components\
      \ and using Charisma as the spellcasting ability (spell save DC 16):\n\n**At\
      \ will:** [Detect Dagic](Detect%20Magic), [Detect\
      \ Thoughts](detect-thoughts), [Invisibility](invisibility)\
      \ (self only), [Mage Hand](Mage-Hand), [Major\
      \ Image](major-image)\n\n**1/day each:** [Blight](blight)\
      \ (level 8 version), [Cloudkill](cloudkill) (level\
      \ 6 version), [Fly](fly), [Plane Shift](Plane%20Shift),\
      \ [Tongues](tongues)"
    "name": "Spellcasting"
"bonus_actions":
  - "desc": "The slaad shape-shifts into a Small or Medium Humanoid, or it returns\
      \ to its true form. Other than its size, its game statistics are the same in\
      \ each form. Any equipment it is wearing or carrying isn't transformed."
    "name": "Shape-Shift"
"source":
  - "XMM"
"image": "bestiary/tokens/XMM/Death Slaad.webp"
```
^statblock

## Environment

planar, limbo