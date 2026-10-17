---
cssclasses:
  - json5e-monster
tags:
  - src/5e/ggr
  - monster/cr/1/2
  - monster/size/small
  - monster/type/fiend/demon
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Cackler
---
# [Cackler](Cackler-ggr.md)
*Source: Guildmasters' Guide to Ravnica p. 195*  

![](https://5e.tools/img/bestiary/GGR/Cackler.webp)

## Demons

Just as angels are incarnations of the ideals of justice, demons embody depraved impulses: selfishness, cruelty, hatred, greed, and lust for power. Demons are strongly associated with the Cult of Rakdos; in fact, the demons of Ravnica might have been created by Rakdos in the same way that angels were created by the Boros Legion's founder. As a demon lord who has chosen to live in Ravnica, Rakdos claims authority over all the demons of this world-even if some of them, ambitious and headstrong as demons are, rebel against his authority.

Demons are agents of destruction that work their acts of terror in plain sight under the auspices of the Cult of Rakdos. They exhibit their cruelty in dramatic performances that leave the audience members blood-soaked but ecstatic. They incite mob riots that raze entire city blocks. The only thing demons fear is Rakdos himself, who doesn't tolerate rivals and hates to be upstaged.

### Demonic "Devils"

The creatures called "devils" in Ravnica are minor demons akin to [quasits](Quasit.md). While the larger demons embody evil qualities such as blood lust and torment, these lesser demons reflect the whimsical and chaotic side of Rakdos and his cult. Their mischievous antics cause disorder and destruction out of proportion to the demons' small size.

### Diabolic Demons

Many of the demons of Ravnica are monstrous, winged creatures of human-like form. They are best represented by the statistics of the [nalfeshnee](Nalfeshnee.md), the [shadow demon](Shadow-Demon.md), or the [vrock](Vrock.md) in the Monster Manual. Demons associated with the Cult of Rakdos often have fiery attacks that make them similar to barbed devils or horned devils, except that they are demons. (They are chaotic evil, they speak Abyssal and not Infernal, and they lack Devil's Sight.)

```statblock
"name": "Cackler (GGR)"
"size": "Small"
"type": "fiend"
"subtype": "demon"
"alignment": "Chaotic Evil"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "10"
"hit_dice": "3d6"
"modifier": !!int "3"
"stats":
  - !!int "9"
  - !!int "16"
  - !!int "11"
  - !!int "11"
  - !!int "7"
  - !!int "12"
"speed": "30 ft."
"skillsaves":
  - "name": "[Deception](skills.md#Deception)"
    "desc": "+3"
  - "name": "[Perception](skills.md#Perception)"
    "desc": "+0"
  - "name": "[Performance](skills.md#Performance)"
    "desc": "+3"
"damage_resistances": "cold; fire; lightning; bludgeoning, piercing, slashing\
  \ from nonmagical attacks"
"damage_immunities": "poison"
"condition_immunities": "[poisoned](conditions.md#Poisoned)"
"senses": "[Darkvision](senses.md#Darkvision) 120 ft., passive Perception 10"
"languages": "Abyssal, Common"
"cr": "1/2"
"traits":
  - "desc": "When the cackler dies, it releases a dying laugh that scars the\
      \ minds of other nearby creatures. Each creature within 10 feet of the\
      \ cackler must succeed on a DC 11 Wisdom saving throw or take 2 (1d4)\
      \ psychic damage."
    "name": "Last Laugh"
  - "desc": "The cackler can mimic any sounds it has heard, including voices. A\
      \ creature that hears the sounds can tell they are imitations with a\
      \ successful DC 11 Wisdom (Insight) check."
    "name": "Mimicry"
  - "desc": "The cackler's innate spellcasting ability is Charisma (spell save\
      \ DC 11, +3 to hit with spell attacks). The cackler can innately cast the\
      \ following spells, requiring no material components:\n\n**At will:**\
      \ [fire bolt](Fire-Bolt.md)\n\n**1/day:** [Tasha's hideous\
      \ laughter](Tasha's-Hideous-Laughter.md)"
    "name": "Innate Spellcasting"
"actions":
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one target. *Hit:*\
      \ 5 (1d4 + 3) piercing damage."
    "name": "Bite"
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 10 ft., one target. *Hit:*\
      \ 6 (1d6 + 3) slashing damage."
    "name": "Spiked Chain"
"source":
  - "GGR"
"image": "bestiary/tokens/GGR/Cackler.webp"
```
^statblock
