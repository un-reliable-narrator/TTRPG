---
cssclasses:
- json5e-monster
tags:
- src/5e/xmm
- monster/cr/5
- monster/environment/lower
- monster/environment/planar
- monster/size/medium
- monster/type/fiend
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Night Hag"
---
# [Night Hag](night Hag.md)
*Source: Monster Manual (2024) p. 225. Available in the <span title='Systems Reference Document (5.2)'>SRD</span> and the Free Rules (2024)*  

## Night Hag

*Hag of Nightmare and Corruption*

- **Habitat.** Planar (Lower Planes)  
- **Treasure.** [Arcana](random-magic-items-arcana.md)  

Night hags seek mortals to torment and turn to evil. By day, night hags use supernatural deceptions to plague their victims, shape-shifting to pose as other creatures and make their targets believe the world has turned against them. By night, these hags reinforce their tortures with terrifying dreams. Once they force their targets to desperate limits, night hags claim their victims' tormented spirits, capturing them in sinister traps called soul bags. The hags then slip between planes of existence to barter stolen souls to vile magic-users and fiendish entities.

Night hags maintain networks of nefarious customers and collect rumors from across the Lower Planes. These hags might part with their secrets in exchange for magic items and other wicked prices.

```statblock
"name": "Night Hag (XMM)"
"size": "Medium"
"type": "fiend"
"alignment": "Neutral Evil"
"ac": !!int "17"
"hp": !!int "112"
"hit_dice": "15d8 + 45"
"modifier": !!int "5"
"stats":
  - !!int "18"
  - !!int "15"
  - !!int "16"
  - !!int "16"
  - !!int "14"
  - !!int "16"
"speed": "30 ft."
"skillsaves":
  - "name": "[Deception](skills.md#Deception)"
    "desc": "+6"
  - "name": "[Insight](skills.md#Insight)"
    "desc": "+5"
  - "name": "[Perception](Perception)"
    "desc": "+5"
  - "name": "[Stealth](Stealth)"
    "desc": "+5"
"damage_resistances": "cold, fire"
"condition_immunities": "[charmed](conditions.md#Charmed)"
"senses": "[Darkvision](senses.md#Darkvision) 120 ft., passive\
  \ Perception 15"
"languages": "Abyssal, Common, Infernal, Primordial"
"cr": "5"
"traits":
  - "desc": "While within 30 feet of at least two hag allies, the hag can cast one\
      \ of the following spells, requiring no Material components, using the spell's\
      \ normal casting time, and using Intelligence as the spellcasting ability (spell\
      \ save DC 14): [Augury](augury), [Find Familiar](find-familiar),\
      \ [Identify](identify), [Locate Object](locate-object),\
      \ [Scrying](scrying), or [Unseen Servant](unseen-servant).\
      \ The hag must finish a [Long Rest](long-rest)\
      \ before using this trait to cast that spell again.\n"
    "name": "Coven Magic"
  - "desc": "The hag has [Advantage](advantage)\
      \ on saving throws against spells and other magical effects."
    "name": "Magic Resistance"
  - "desc": "The hag has a soul bag. While holding or carrying the bag, the hag can\
      \ use its Nightmare Haunting action.\n\nThe bag has AC 15, HP 20, and [Resistance](resistance)\
      \ to all damage. The bag turns to dust if reduced to 0 [Hit Points](hit-points).\
      \ If the bag is destroyed, any souls the bag is holding are released. The hag\
      \ can create a new bag after 7 days."
    "name": "Soul Bag"
"actions":
  - "desc": "The hag makes two Claw attacks."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +7, reach 5 ft. *Hit:* 13 (2d8 + 4) Slashing\
      \ damage."
    "name": "Claw"
  - "desc": "The hag casts one of the following spells, requiring no Material components\
      \ and using Intelligence as the spellcasting ability (spell save DC 14):\n\n\
      **At will:** [Detect Dagic](Detect-Magic), [Etherealness](etherealness),\
      \ [Magic Missile](magic-missile) (level 4 version)\n\
      \n**2/day each:** [Phantasmal Killer](phantasmal-killer),\
      \ [Plane Shift](Plane-Shift) (self only)"
    "name": "Spellcasting"
  - "desc": "While on the Ethereal Plane, the hag casts [Dream](dream),\
      \ using the same spellcasting ability as Spellcasting. Only the hag can serve\
      \ as the spell's messenger, and the target must be a creature the hag can see\
      \ on the Material Plane. The spell fails and is wasted if the target is under\
      \ the effect of the [Protection from Evil and Good](protection-from-evil-and-good)\
      \ spell or within a [Magic Circle](magic-circle)\
      \ spell.\n\nIf the target takes damage from the [Dream](dream)\
      \ spell, the target's [Hit Point](hit-points)\
      \ maximum decreases by an amount equal to that damage. If the spell kills the\
      \ target, its soul is trapped in the hag's soul bag, and the target can't be\
      \ raised from the dead until its soul is released.\n"
    "name": "Nightmare Haunting (1/Day; Requires Soul Bag)"
"bonus_actions":
  - "desc": "The hag shape-shifts into a Small or Medium Humanoid, or it returns to\
      \ its true form. Other than its size, its game statistics are the same in each\
      \ form. Any equipment it is wearing or carrying isn't transformed."
    "name": "Shape-Shift"
"source":
  - "XMM"
"image": "bestiary/tokens/XMM/Night Hag.webp"
```
^statblock

## Environment

planar, lower