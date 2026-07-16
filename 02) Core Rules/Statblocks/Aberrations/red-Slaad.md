---
cssclasses:
- json5e-monster
tags:
- src/5e/xmm
- monster/cr/5
- monster/environment/limbo
- monster/environment/planar
- monster/size/large
- monster/type/aberration
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Red Slaad"
---
# [Red Slaad](red-Slaad.md)
*Source: Monster Manual (2024) p. 285*  

Red slaadi amass in vast throngs in Limbo. There they wrestle and croak-sing as they endlessly dismantle and rebuild islands of drifting planar matter. When they encounter non-slaadi, red slaadi seek to play with, telepathically converse with, or devour the other creatures. These whims change from moment to moment. Red slaadi instinctively avoid harming those bearing slaadi eggs, which red slaadi implant using their claws, or other slaad curses.

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
"name": "Red Slaad (XMM)"
"size": "Large"
"type": "aberration"
"alignment": "Chaotic Neutral"
"ac": !!int "14"
"hp": !!int "93"
"hit_dice": "11d10 + 33"
"modifier": !!int "1"
"stats":
  - !!int "16"
  - !!int "12"
  - !!int "16"
  - !!int "6"
  - !!int "6"
  - !!int "7"
"speed": "30 ft."
"skillsaves":
  - "name": "[Perception](Perception)"
    "desc": "+1"
"damage_resistances": "acid, cold, fire, lightning, thunder"
"senses": "[Darkvision](senses.md#Darkvision) 60 ft., passive\
  \ Perception 11"
"languages": "Slaad; telepathy 60 ft."
"cr": "5"
"traits":
  - "desc": "The slaad has [Advantage](advantage)\
      \ on saving throws against spells and other magical effects."
    "name": "Magic Resistance"
  - "desc": "The slaad regains 10 [Hit Points](hit-points)\
      \ at the start of each of its turns if it has at least 1 [Hit Point](hit-points)."
    "name": "Regeneration"
"actions":
  - "desc": "The slaad makes three Injecting Claw attacks."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +6, reach 10 ft. *Hit:* 10 (2d6 + 3) Piercing\
      \ damage. If the target is a Humanoid not cursed by a slaad, it is subjected\
      \ to the following effect. *Constitution Saving Throw:* DC 14. *Failure:* The\
      \ target is cursed unawares, and a minuscule slaad egg is implanted in it. Removing\
      \ the curse destroys the egg.\n\nOver 2d4 × 10 days, the egg gestates. In\
      \ the final 24 hours, the cursed target feels unwell; its [Speed](speed)\
      \ is halved, and it has [Disadvantage](disadvantage)\
      \ on [D20 Tests](d20-test). At the\
      \ end of this time, the egg turns into a Slaad Tadpole, which chews out of the\
      \ host and kills it."
    "name": "Injecting Claw"
"source":
  - "XMM"
"image": "bestiary/tokens/XMM/Red Slaad.webp"
```
^statblock

## Environment

planar, limbo