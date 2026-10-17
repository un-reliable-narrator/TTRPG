---
cssclasses:
  - json5e-monster
tags:
  - src/5e/rhw
  - monster/cr/10
  - monster/size/medium
  - monster/type/humanoid/human
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Madam Eva
---
# [Madam Eva](Madam%20Eva.md)
*Source: Ravenloft: The Horrors Within p. 253*  

![](https://media.dndbeyond.com/compendium-images/rthw/ogMxaVTj4GqgnUqr/22-019.madam-eva.png)

*Duplicitous Diviner*

The mysterious fortune teller Madam Eva shrouds herself in a carefully woven web of lies. Though she appears to be in her seventies, she is much older. She sets herself apart from any group, guarding the secrets of her origins and centuries-spanning agendas.

Madam Eva is a legendary figure known across the Land of the Mists. Few can rival her skill at interpreting omens, reading tarokka cards, or taming spirits during séances. While the fortunes she shares might have double meanings, they're never wrong. She is renowned for revealing when best to enter the Mists to escape a domain or reach an intended destination, leading many travelers to seek her on the shores of the Tser Pool in Barovia to seek her insights. She often hints at knowledge of the Mists' secrets and the tales (and weaknesses) of Darklords, and she's not above revealing them for a price. Madam Eva holds grudges and usually shares her secrets only with those who do her a favor first. Whatever she discovers might soon also be known by Barovia's Darklord, with whom she shares age-old ties.

```statblock
"name": "Madam Eva (RHW)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Chaotic Neutral"
"ac": !!int "15"
"hp": !!int "117"
"hit_dice": "18d8 + 36"
"modifier": !!int "0"
"stats":
  - !!int "8"
  - !!int "11"
  - !!int "14"
  - !!int "17"
  - !!int "20"
  - !!int "18"
"speed": "30 ft."
"saves":
  - "wisdom": !!int "9"
  - "charisma": !!int "8"
"skillsaves":
  - "name": "[Arcana](skills.md#Arcana)"
    "desc": "+7"
  - "name": "[Insight](skills.md#Insight)"
    "desc": "+9"
  - "name": "[Perception](skills.md#Perception)"
    "desc": "+9"
  - "name": "[Religion](skills.md#Religion)"
    "desc": "+7"
"senses": "passive Perception 19"
"languages": "Abyssal, Common, Elvish, Infernal"
"cr": "10"
"traits":
  - "desc": "Madam Eva has Advantage on saving throws against spells and other\
      \ magical effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "Madam Eva makes three attacks, using Cursed Dagger or Radiant\
      \ Flame in any combination."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +9, reach 5 ft. *Hit:* 10 (2d4 + 5) Piercing\
      \ damage plus 21 (6d6) Necrotic damage."
    "name": "Cursed Dagger"
  - "desc": "*Ranged Attack Roll:* +9, range 60 ft. *Hit:* 21 (3d10 + 5)\
      \ Radiant damage, and the target has the [Blinded](conditions.md#Blinded)\
      \ condition until the start of Madam Eva's next turn."
    "name": "Radiant Flame"
  - "desc": "*Wisdom Saving Throw:* DC 17, each creature in a 20-foot-radius\
      \ Sphere centered on a point Madam Eva can see within 120 feet.\
      \ *Failure:* 24 (7d6) Necrotic damage plus 24 (7d6) Psychic damage, and\
      \ the target has the [Frightened](conditions.md#Frightened) condition\
      \ until the start of Madam Eva's next turn. *Success:* Half damage only."
    "name": "Apocalyptic Visions (Recharge 5-6)"
  - "desc": "Madam Eva casts one of the following spells, using Wisdom as the\
      \ spellcasting ability (spell save DC 17):\n\n**At will:**\
      \ [Light](Light.md), [Mending](Mending.md),\
      \ [Thaumaturgy](Thaumaturgy.md)\n\n**2/day each:** [Dispel\
      \ Magic](Dispel-Magic.md), [Remove Curse](Remove-Curse.md)\n\n**1/day\
      \ each:** [Greater Restoration](Greater-Restoration.md), [Raise\
      \ Dead](Raise-Dead.md), [Scrying](Scrying.md), [Spirit\
      \ Guardians](Spirit-Guardians.md) (level 8 version)"
    "name": "Spellcasting"
"bonus_actions":
  - "desc": "Madam Eva casts [Hold Person](Hold-Person.md), using the same\
      \ spellcasting ability as Spellcasting.\n\n**2/day:** [Hold\
      \ Person](Hold-Person.md)"
    "name": "Evil Eye (2/Day)"
"source":
  - "RHW"
"image": "bestiary/tokens/RHW/Madam Eva.webp"
```
^statblock
