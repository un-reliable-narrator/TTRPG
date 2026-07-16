---
cssclasses:
- json5e-monster
tags:
- src/5e/xmm
- monster/cr/13
- monster/environment/lower
- monster/environment/planar
- monster/size/medium
- monster/type/Fiends/yugoloth
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Ultroloth"
---
# [Ultroloth](ultroloth.md)
*Source: Monster Manual (2024) p. 311*  

## Ultroloth

*Yugoloth of Conspiracy and Control*

- **Habitat.** Planar (Lower Planes)  
- **Treasure.** [Armaments](random-magic-items-armaments.md)  

With uncanny patience and fiendish cunning, ultroloths manipulate mortals and their fellow yugoloths alike, seeking to hoard power and spread suffering. These sinister masterminds often work with other yugoloths, but they might compel nearly any creature into their service. If coercion doesn't work, ultroloths use their eerie eyes and innate magic to hypnotize or charm targets.

Ultroloths strive to achieve planes-spanning plots. Roll on or choose a result from the Ultroloth Conspiracies table to inspire such villainy.

**Ultroloth Conspiracies**

| dice: 1d6 | The Ultroloth Schemes To... |
|-----------|-----------------------------|
| 1 | Convince cultists their god has forsaken them. |
| 2 | Destabilize a nation and rule the chaos. |
| 3 | Incite a calamity and hold a world hostage. |
| 4 | Provoke hostilities between immortal armies and sell magic weapons to both sides. |
| 5 | Steal an invention and slay all who know of it. |
| 6 | Unleash fiendish hordes on a foe's homeland. |
^ultroloth-conspiracies

```statblock
"name": "Ultroloth (XMM)"
"size": "Medium"
"type": "fiend"
"subtype": "yugoloth"
"alignment": "Neutral Evil"
"ac": !!int "19"
"hp": !!int "221"
"hit_dice": "26d8 + 104"
"modifier": !!int "8"
"stats":
  - !!int "19"
  - !!int "16"
  - !!int "18"
  - !!int "19"
  - !!int "15"
  - !!int "18"
"speed": "30 ft., fly 60 ft. (hover)"
"skillsaves":
  - "name": "[Deception](skills.md#Deception)"
    "desc": "+9"
  - "name": "[Perception](Perception)"
    "desc": "+7"
  - "name": "[Stealth](Stealth)"
    "desc": "+8"
"damage_resistances": "cold, fire, lightning"
"damage_immunities": "acid, poison"
"condition_immunities": "[charmed](conditions.md#Charmed), [frightened](conditions.md#Frightened),\
  \ [poisoned](conditions.md#Poisoned)"
"senses": "[Truesight](senses.md#Truesight) 120 ft., passive\
  \ Perception 17"
"languages": "Abyssal, Infernal; telepathy 120 ft."
"cr": "13"
"traits":
  - "desc": "If the ultroloth dies outside Gehenna, its body dissolves into ichor,\
      \ and it gains a new body instantly, reviving with all its [Hit Points](hit-points)\
      \ somewhere in Gehenna."
    "name": "Fiendish Restoration"
  - "desc": "The ultroloth has [Advantage](advantage)\
      \ on saving throws against spells and other magical effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "The ultroloth uses Hypnotic Gaze and makes two Mercurial Whip attacks."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +9, reach 15 ft. *Hit:* 25 (6d6 + 4) Force damage,\
      \ and the ultroloth can teleport the target up to 10 feet to an unoccupied space\
      \ the ultroloth can see that isn't in the air."
    "name": "Mercurial Whip"
  - "desc": "*Wisdom Saving Throw:* DC 17, each creature in a 30-foot [Cone](cone-area-of-effect).\
      \ *Failure:* 10 (3d6) Psychic damage, and the target has the [Stunned](conditions.md#Stunned)\
      \ condition until the start of the ultroloth's next turn. *Success:* The target\
      \ is immune to this ultroloth's Hypnotic Gaze for 24 hours."
    "name": "Hypnotic Gaze"
  - "desc": "The ultroloth casts one of the following spells, requiring no Material\
      \ components and using Intelligence as the spellcasting ability (spell save\
      \ DC 17):\n\n**At will:** [Alter Self](alter-self),\
      \ [Clairvoyance](clairvoyance), [Detect Dagic](Detect%20Magic)\n\
      \n**1/day each:** [Dimension Door](dimension-door),\
      \ [Fireball](fireball) (level 5 version), [Wall\
      \ of Fire](wall-of-fire)"
    "name": "Spellcasting"
"bonus_actions":
  - "desc": "The ultroloth casts [Dispel Magic](dispel-magic),\
      \ [Invisibility](invisibility) (self only), [Misty\
      \ Step](misty-step), or [Suggestion](suggestion),\
      \ requiring no Material components and using the same spellcasting ability as\
      \ Spellcasting.\n"
    "name": "Fiendish Guile (Recharge 4-6)"
"source":
  - "XMM"
"image": "bestiary/tokens/XMM/Ultroloth.webp"
```
^statblock

## Environment

planar, lower