---
cssclasses:
  - json5e-monster
tags:
  - src/5e/rhw
  - monster/cr/15
  - monster/size/medium
  - monster/type/undead/vampire
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Strahd von Zarovich
---
# [Strahd von Zarovich](Strahd%20von%20Zarovich.md)
*Source: Ravenloft: The Horrors Within p. 42*  

![](https://5e.tools/img/bestiary/RHW/Strahd%20von%20Zarovich.webp)

Count Strahd von Zarovich has lost all he ever desired—over and over again. Tormented by the Dark Powers, Strahd is haunted by visions of his lost family and tarnished nobility. The count spends long years brooding in the depths of Castle Ravenloft, but a reincarnation of his obsession appears every generation: Tatyana. Each time Tatyana's reincarnation emerges, Strahd seeks to undo the failures of his past and find a way to win her love. Time and time again, Strahd's heartless, domineering nature causes his bloody history to repeat itself and drives Tatyana beyond his clutches.

A severe, aristocratic figure, the count has the bearing of a former soldier and the impatience of one used to being obeyed. He feels little but occasionally embraces the novelty of toying with amusing strangers or breaking the spirits of his enemies. During his unnaturally long existence, he has learned many occult secrets and mysteries of the Domains of Dread. Strahd's dignified bearing crumbles when someone breaks his laws or denies him what he desires. In such cases, Strahd makes bloody examples of his opponents, drawing out his vengeance into campaigns of terror.

```statblock
"name": "Strahd von Zarovich (RHW)"
"size": "Medium"
"type": "undead"
"subtype": "vampire"
"alignment": "Lawful Evil"
"ac": !!int "16"
"hp": !!int "204"
"hit_dice": "24d8 + 96"
"modifier": !!int "4"
"stats":
  - !!int "18"
  - !!int "18"
  - !!int "18"
  - !!int "20"
  - !!int "15"
  - !!int "18"
"speed": "40 ft., climb 40 ft."
"saves":
  - "dexterity": !!int "9"
  - "wisdom": !!int "7"
  - "charisma": !!int "9"
"skillsaves":
  - "name": "[Arcana](skills.md#Arcana)"
    "desc": "+15"
  - "name": "[Perception](skills.md#Perception)"
    "desc": "+12"
  - "name": "[Religion](skills.md#Religion)"
    "desc": "+10"
  - "name": "[Stealth](skills.md#Stealth)"
    "desc": "+14"
"damage_resistances": "necrotic"
"senses": "[Darkvision](senses.md#Darkvision) 120 ft., passive Perception 22"
"languages": "Abyssal, Common, Draconic, Elvish, Giant, Infernal"
"cr": "15"
"traits":
  - "desc": "If Strahd dies, he revives with all his Hit Points in 1d10 weeks\
      \ somewhere in Barovia."
    "name": "Darklord Restoration"
  - "desc": "If Strahd fails a saving throw, he can choose to succeed instead."
    "name": "Legendary Resistance (3/Day, or 4/Day in Domain)"
  - "desc": "If Strahd drops to 0 Hit Points outside his resting place, he uses\
      \ Shape-Shift to become mist (no action required). If he can't use\
      \ Shape-Shift, he is destroyed. While Strahd has 0 Hit Points in mist\
      \ form, he can't return to his vampire form, and he must reach his\
      \ resting place within 2 hours or be destroyed. Once in his resting\
      \ place, Strahd returns to his vampire form and has the\
      \ [Paralyzed](conditions.md#Paralyzed) condition until he regains any Hit\
      \ Points, and he regains 1 Hit Point after spending 1 hour there."
    "name": "Misty Escape"
  - "desc": "Strahd can climb difficult surfaces, including ceilings, without\
      \ making an ability check."
    "name": "Spider Climb"
  - "desc": "Strahd has these weaknesses:\n\n- **Forbiddance.** Strahd can't\
      \ enter a residence without an invitation from an occupant.  \n-\
      \ **Running Water.** Strahd takes 20 Acid damage if he ends his turn in\
      \ running water.  \n- **Stake to the Heart.** If a weapon that deals\
      \ Piercing damage is driven into Strahd's heart while Strahd has the\
      \ [Incapacitated](conditions.md#Incapacitated) condition in his resting\
      \ place, Strahd has the [Paralyzed](conditions.md#Paralyzed) condition\
      \ until the weapon is removed.  \n- **Sunlight.** Strahd takes 20 Radiant\
      \ damage if he starts his turn in sunlight. While in sunlight, he has\
      \ Disadvantage on attack rolls and ability checks.  "
    "name": "Vampire Weakness"
"actions":
  - "desc": "Strahd makes two Death Strike attacks. He can replace one of these\
      \ attacks with a use of (A) Bite or (B) Spellcasting to cast\
      \ [Fireball](Fireball.md) if available."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +9, reach 5 ft. *Hit:* 8 (1d8 + 4) Slashing\
      \ damage plus 14 (4d6) Necrotic damage. If the target is a Large or\
      \ smaller creature, it has the [Grappled](conditions.md#Grappled)\
      \ condition (escape DC 14) from one of two hands."
    "name": "Death Strike"
  - "desc": "*Constitution Saving Throw:* DC 17, one creature within 5 feet\
      \ that is willing or that has the [Grappled](conditions.md#Grappled),\
      \ [Incapacitated](conditions.md#Incapacitated), or\
      \ [Restrained](conditions.md#Restrained) condition. *Failure:* 7 (1d6 +\
      \ 4) Piercing damage plus 10 (3d6) Necrotic damage. The target's Hit\
      \ Point maximum decreases by an amount equal to the Necrotic damage\
      \ taken, and Strahd regains Hit Points equal to that amount. A Humanoid\
      \ reduced to 0 Hit Points by this damage rises the following night as a\
      \ Vampire Spawn under Strahd's control, unless the Humanoid is restored\
      \ to life or its body is destroyed."
    "name": "Bite (Bat or Vampire Form Only)"
  - "desc": "Strahd casts one of the following spells, using Intelligence as\
      \ the spellcasting ability (spell save DC 18):\n\n**At will:** [Detect\
      \ Thoughts](Detect-Thoughts.md), [Fog Cloud](Fog-Cloud.md), [Mage\
      \ Hand](Mage-Hand.md)\n\n**2/day each:** [Animate Dead](Animate-Dead.md),\
      \ [Fireball](Fireball.md), [Gust of Wind](Gust-of-Wind.md), [Mirror\
      \ Image](Mirror-Image.md), [Nondetection](Nondetection.md)\n\n**1/day\
      \ each:** [Greater Invisibility](Greater-Invisibility.md),\
      \ [Polymorph](Polymorph.md), [Scrying](Scrying.md)"
    "name": "Spellcasting"
"bonus_actions":
  - "desc": "If Strahd isn't in sunlight or running water, he shape-shifts into\
      \ a Tiny bat (Speed 5 ft., Fly Speed 30 ft.), a Medium wolf (Speed 40\
      \ ft.), or a Medium cloud of mist (Speed 5 ft., Fly Speed 20 ft.\
      \ [hover]), or he returns to his vampire form. Anything he is wearing\
      \ transforms with him.\n\nWhile in bat or wolf form, Strahd can't speak.\
      \ His game statistics, other than his size and Speed, are\
      \ unchanged.\n\nWhile in mist form, Strahd can't take any actions, speak,\
      \ or manipulate objects. He is weightless and can enter an enemy's space\
      \ and stop there. If air can pass through a space, Strahd can do so, but\
      \ he can't pass through liquid. Strahd has Resistance to all damage,\
      \ except the damage he takes from sunlight."
    "name": "Shape-Shift"
  - "desc": "Strahd casts [Charm Person](Charm-Person.md), requiring no spell\
      \ components and using the same spellcasting ability as Spellcasting.\
      \ When the spell is cast this way, its duration is 24 hours, and the\
      \ [Charmed](conditions.md#Charmed) target is a willing recipient of\
      \ Strahd's Bite, the damage of which doesn't end the spell. When the\
      \ spell ends, the target is unaware it was\
      \ [Charmed](conditions.md#Charmed) by Strahd.\n\n**At will:** [Charm\
      \ Person](Charm-Person.md)"
    "name": "Charm"
"regional_effects":
  - "desc": "Barovia is altered by Strahd's presence, creating the following\
      \ effects:\n\n- **Closing the Borders.** While in his domain, Strahd can\
      \ close or open the borders to Barovia at will. While the borders are\
      \ closed, noxious fog suffuses the Mists surrounding Barovia. A creature\
      \ that enters the Mists for the first time on a turn or starts its turn\
      \ there must succeed on a DC 20 Constitution saving throw or gain 1\
      \ [Exhaustion](conditions.md#Exhaustion) level. A creature makes this\
      \ save only once per turn.  \n- **Dreadful Darkness.** While in an area\
      \ of Darkness, creatures other than Strahd and creatures of his choice\
      \ have Disadvantage on saving throws to end or avoid the\
      \ [Frightened](conditions.md#Frightened) condition.  \n- **Jealous\
      \ Heart.** When a character receives Heroic Inspiration but already has\
      \ it, that character can't give it to another character in the group. \
      \ \n\nIf Strahd dies, these effects end immediately."
    "name": ""
"legendary_description": "Legendary Action Uses: 3. Immediately after another\
  \ creature's turn, Strahd can expend a use to take one of the following\
  \ actions. Strahd regains all expended uses at the start of each of its turns."
"legendary_actions":
  - "desc": "Strahd moves up to half his Speed, and he makes one Death Strike\
      \ attack."
    "name": "Striding Strike"
  - "desc": "Strahd casts [Command](Command.md) (level 2 version), requiring no\
      \ spell components and using the same spellcasting ability as\
      \ Spellcasting."
    "name": "Count's Command"
"source":
  - "RHW"
"image": "bestiary/tokens/RHW/Strahd von Zarovich.webp"
```
^statblock
