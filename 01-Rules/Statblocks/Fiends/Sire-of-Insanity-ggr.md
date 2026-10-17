---
cssclasses:
  - json5e-monster
tags:
  - src/5e/ggr
  - monster/cr/12
  - monster/size/huge
  - monster/type/fiend/demon
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Sire of Insanity
---
# [Sire of Insanity](Sire-of-Insanity-ggr.md)
*Source: Guildmasters' Guide to Ravnica p. 197*  

![](https://5e.tools/img/bestiary/GGR/Sire%20of%20Insanity.webp)

## Demons

Just as angels are incarnations of the ideals of justice, demons embody depraved impulses: selfishness, cruelty, hatred, greed, and lust for power. Demons are strongly associated with the Cult of Rakdos; in fact, the demons of Ravnica might have been created by Rakdos in the same way that angels were created by the Boros Legion's founder. As a demon lord who has chosen to live in Ravnica, Rakdos claims authority over all the demons of this world-even if some of them, ambitious and headstrong as demons are, rebel against his authority.

Demons are agents of destruction that work their acts of terror in plain sight under the auspices of the Cult of Rakdos. They exhibit their cruelty in dramatic performances that leave the audience members blood-soaked but ecstatic. They incite mob riots that raze entire city blocks. The only thing demons fear is Rakdos himself, who doesn't tolerate rivals and hates to be upstaged.

### Demonic "Devils"

The creatures called "devils" in Ravnica are minor demons akin to [quasits](Quasit.md). While the larger demons embody evil qualities such as blood lust and torment, these lesser demons reflect the whimsical and chaotic side of Rakdos and his cult. Their mischievous antics cause disorder and destruction out of proportion to the demons' small size.

### Diabolic Demons

Many of the demons of Ravnica are monstrous, winged creatures of human-like form. They are best represented by the statistics of the [nalfeshnee](Nalfeshnee.md), the [shadow demon](Shadow-Demon.md), or the [vrock](Vrock.md) in the Monster Manual. Demons associated with the Cult of Rakdos often have fiery attacks that make them similar to barbed devils or horned devils, except that they are demons. (They are chaotic evil, they speak Abyssal and not Infernal, and they lack Devil's Sight.)

```statblock
"name": "Sire of Insanity (GGR)"
"size": "Huge"
"type": "fiend"
"subtype": "demon"
"alignment": "Chaotic Evil"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "157"
"hit_dice": "15d12 + 60"
"modifier": !!int "-2"
"stats":
  - !!int "23"
  - !!int "6"
  - !!int "19"
  - !!int "14"
  - !!int "19"
  - !!int "22"
"speed": "40 ft."
"saves":
  - "constitution": !!int "8"
  - "intelligence": !!int "6"
  - "wisdom": !!int "8"
  - "charisma": !!int "10"
"skillsaves":
  - "name": "[Deception](skills.md#Deception)"
    "desc": "+10"
  - "name": "[Intimidation](skills.md#Intimidation)"
    "desc": "+10"
"damage_resistances": "cold; fire; lightning; bludgeoning, piercing, slashing\
  \ from nonmagical attacks"
"damage_immunities": "poison"
"condition_immunities": "[poisoned](conditions.md#Poisoned)"
"senses": "[Truesight](senses.md#Truesight) 120 ft., passive Perception 14"
"languages": "Abyssal, Common, telepathy 120 ft."
"cr": "12"
"traits":
  - "desc": "Any creature that starts its turn within 30 feet of the sire must\
      \ make a DC 18 Wisdom saving throw. On a successful save, the creature is\
      \ immune to this aura for the next 24 hours. On a failed save, the\
      \ creature has disadvantage for 1 minute on Wisdom and Charisma checks\
      \ and on Wisdom and Charisma saves. At the start of each of its turns,\
      \ the sire can suppress this aura until the start of its next turn."
    "name": "Aura of Mind Erosion"
  - "desc": "The sire has advantage on saving throws against spells and other\
      \ magical effects."
    "name": "Magic Resistance"
  - "desc": "The sire's innate spellcasting ability is Charisma (spell save DC\
      \ 18, +10 to hit with spell attacks). The sire can innately cast the\
      \ following spells, requiring no material components:\n\n**At will:**\
      \ [clairvoyance](Clairvoyance.md), [crown of\
      \ madness](Crown-of-Madness.md), [major image](Major-Image.md),\
      \ [suggestion](Suggestion.md)\n\n**1/day each:**\
      \ [confusion](Confusion.md), [mass suggestion](Mass-Suggestion.md)"
    "name": "Innate Spellcasting"
"actions":
  - "desc": "The sire makes two attacks: one with its bite and one with its\
      \ claws."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +10 to hit, reach 5 ft., one creature.\
      \ *Hit:* 25 (3d12 + 6) piercing damage plus 16 (3d10) psychic damage."
    "name": "Bite"
  - "desc": "*Melee Weapon Attack:* +10 to hit, reach 10 ft., one target.\
      \ *Hit:* 10 (1d8 + 6) slashing damage plus 9 (2d8) psychic damage."
    "name": "Claws"
"source":
  - "GGR"
"image": "bestiary/tokens/GGR/Sire of Insanity.webp"
```
^statblock
