---
cssclasses:
- json5e-monster
tags:
- src/5e/mpmm
- monster/cr/20
- monster/environment/underdark
- monster/size/medium
- monster/type/Humanoids/cleric
- monster/type/Humanoids/elf
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Drow Matron Mother"
---
# [Drow Matron Mother](Drow-matron-mother-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 104*  

Among drow followers of Lolth, each noble house is led by a matron mother, an influential priestess of Lolth charged with carrying out the god's will while also advancing the interests of the family. Matron mothers embody the scheming and treachery associated with the Queen of Spiders. Each stands at the center of a vast conspiratorial web, with demons, spiders, and conscripted soldiers positioned between them and their enemies. Although matron mothers command great power, that power depends on maintaining the Spider Queen's favor, and the goddess sometimes capriciously takes back what she has given. The stat block here represents a matron mother at the height of her power.

A matron mother is almost never encountered alone. She is typically accompanied by a [drow favored consort](Drow-favored-Consort-mpmm.md) and a [drow house captain](Drow-house-Captain-mpmm.md), each of whom appears in this book. Other Underdark creatures might also be in the priestess's presence, providing protection or advice.

## Mothers of Rebellion

Some matron mothers renounce Lolth and join the war against their former goddess. Such drow could be of any alignment, and they lose the following abilities in the stat block: Lolth's Fickle Favor, Summon Servant, and Compel Demon. Even without these abilities, drow matron mothers are formidable opponents, and several of them hold positions of great influence in the Underdark armies arrayed against the followers of Lolth.

## A Matron Mother's Lair

The palace of a drow matron mother is her home and fortress. Sigils throughout the building allow the matron mother to use the following lair actions while within it.

Any temple of Lolth also functions as a matron mother's lair while she is inside it, unless she has renounced Lolth or another matron mother is present. When two or more matron mothers gather within a temple of their goddess, none of them can use it as their lair.

```statblock
"name": "Drow Matron Mother (MPMM)"
"size": "Medium"
"type": "humanoid"
"subtype": "cleric, elf"
"alignment": "Typically  Neutral Evil"
"ac": !!int "17"
"ac_class": "[half plate](half-plate-armor)"
"hp": !!int "247"
"hit_dice": "33d8 + 99"
"modifier": !!int "4"
"stats":
  - !!int "12"
  - !!int "18"
  - !!int "16"
  - !!int "17"
  - !!int "21"
  - !!int "22"
"speed": "30 ft."
"saves":
  - "constitution": !!int "9"
  - "wisdom": !!int "11"
  - "charisma": !!int "12"
"skillsaves":
  - "name": "[Insight](skills.md#Insight)"
    "desc": "+11"
  - "name": "[Perception](Perception)"
    "desc": "+11"
  - "name": "[Religion](Religion)"
    "desc": "+9"
  - "name": "[Stealth](Stealth)"
    "desc": "+10"
"condition_immunities": "[charmed](conditions.md#Charmed), [frightened](conditions.md#Frightened),\
  \ [poisoned](conditions.md#Poisoned)"
"senses": "[Darkvision](senses.md#Darkvision) 120 ft., passive\
  \ Perception 21"
"languages": "Elvish, Undercommon"
"cr": "20"
"traits":
  - "desc": "The drow has advantage on saving throws against being [charmed](conditions.md#Charmed),\
      \ and magic can't put the drow to sleep."
    "name": "Fey Ancestry"
  - "desc": "The drow wields a [tentacle rod](tentacle-rod.md)."
    "name": "Special Equipment"
  - "desc": "While in sunlight, the drow has disadvantage on attack rolls, as well\
      \ as on Wisdom ([Perception](Perception)) checks\
      \ that rely on sight."
    "name": "Sunlight Sensitivity"
"actions":
  - "desc": "The drow makes two Demon Staff attacks or one Demon Staff attack and\
      \ three Tentacle Rod attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +10 to hit, reach 5 ft., one target. *Hit:*\
      \ 7 (1d6 + 4) bludgeoning damage, or 8 (1d8 + 4) bludgeoning damage if used\
      \ with two hands, plus 14 (4d6) psychic damage. The target must succeed on\
      \ a DC 19 Wisdom saving throw or become [frightened](conditions.md#Frightened)\
      \ of the drow for 1 minute. The [frightened](conditions.md#Frightened)\
      \ target can repeat the saving throw at the end of each of its turns, ending\
      \ the effect on itself on a success."
    "name": "Demon Staff"
  - "desc": "*Melee Weapon Attack:* +9 to hit, reach 15 ft., one creature. *Hit:*\
      \ 3 (1d6) bludgeoning damage. If the target is hit three times by the [rod](tentacle-rod.md)\
      \ on one turn, the target must succeed on a DC 15 Constitution saving throw\
      \ or suffer the following effects for 1 minute: the target's speed is halved,\
      \ it has disadvantage on Dexterity saving throws, and it can't use reactions.\
      \ Moreover, on each of its turns, it can take either an action or a bonus action,\
      \ but not both. At the end of each of its turns, it can repeat the saving throw,\
      \ ending the effect on itself on a success."
    "name": "Tentacle Rod"
  - "desc": "A 10-foot-radius, 40-foot High column of divine fire sprouts in an area\
      \ up to 120 feet away from the drow. Each creature in the column must make a\
      \ DC 20 Dexterity saving throw, taking 14 (4d6) fire damage and 14 (4d6)\
      \ radiant damage on a failed save, or half as much damage on a successful one."
    "name": "Divine Flame (2/Day)"
  - "desc": "The drow casts one of the following spells, requiring no material components\
      \ and using Charisma as the spellcasting ability (spell save DC 20):\n\n**At\
      \ will:** [command](command), [dancing lights](dancing-lights),\
      \ [Detect Dagic](Detect%20Magic), [thaumaturgy](thaumaturgy)\n\
      \n**2/day each:** [banishment](banishment), [blade\
      \ barrier](blade-barrier), [cure wounds](cure-wounds),\
      \ [hold person](hold-person), [plane shift](Plane%20Shift),\
      \ [silence](silence)\n\n**1/day each:** [clairvoyance](clairvoyance),\
      \ [darkness](darkness), [detect thoughts](detect-thoughts),\
      \ [dispel magic](dispel-magic), [faerie fire](faerie-fire),\
      \ [gate](gate), [levitate](levitate)\
      \ (self only), [suggestion](suggestion)"
    "name": "Spellcasting"
"bonus_actions":
  - "desc": "The drow bestows the Spider Queen's blessing on one ally she can see\
      \ within 30 feet of her. The ally takes 7 (2d6) psychic damage but has advantage\
      \ on the next attack roll it makes before the end of its next turn."
    "name": "Lolth's Fickle Favor"
  - "desc": "The drow magically summons a [glabrezu](glabrezu.md)\
      \ or a [yochlol](yochlol.md). The summoned\
      \ creature appears in an unoccupied space within 60 feet of its summoner, acts\
      \ as an ally of its summoner, and can't summon other demons. It remains for\
      \ 10 minutes, until it or its summoner dies, or until its summoner dismisses\
      \ it as an action."
    "name": "Summon Servant (1/Day)"
"lair_actions":
  - "desc": "On initiative count 20 (losing initiative ties), the drow can take one\
      \ of the following lair actions when in her lair; she can't take the same lair\
      \ action two rounds in a row:\n\n- **Perceive Interlopers.** The drow projects\
      \ her mind throughout her lair, marking any potential threats against her or\
      \ her retinue. Until initiative count 20 of the next round, hostile creatures\
      \ within the lair can't become hidden from her and gain no benefit from the\
      \ [invisible](conditions.md#Invisible) condition against\
      \ her.  \n- **Spectral Web.** A glistening spectral spider web erupts from a\
      \ point the drow can see within 120 feet of her. Each creature within 60 feet\
      \ of that point must succeed a DC 19 Dexterity saving throw or be [restrained](conditions.md#Restrained)\
      \ for 1 minute. A creature can repeat the saving throw at the end of each of\
      \ its turns, ending the effect on itself on a success.  \n- **Telekinetic Throw.**\
      \ The drow targets one creature she can see within 60 feet of her and attempts\
      \ to expel it from her presence. The target must succeed on a DC 19 Strength\
      \ saving throw or be flung 2d6 × 10 feet through the air. A creature smashed\
      \ into a solid object takes 1d6 bludgeoning damage for every 10 feet moved.\
      \ If released in midair, the creature takes falling damage as normal.  "
    "name": ""
"legendary_description": "Legendary Action Uses: 3. Immediately after another creature's\
  \ turn, the drow matron mother can expend a use to take one of the following actions.\
  \ The drow matron mother regains all expended uses at the start of each of its turns."
"legendary_actions":
  - "desc": "An allied demon within 30 feet of the drow uses its reaction to make\
      \ one attack against a target of the drow's choice that she can see."
    "name": "Compel Demon"
  - "desc": "The drow makes one Demon Staff attack."
    "name": "Demon Staff"
  - "desc": "The drow uses Spellcasting."
    "name": "Cast a Spell (Costs 2 Actions)"
"source":
  - "MPMM"
"image": "bestiary/tokens/MPMM/Drow Matron Mother.webp"
```
^statblock

## Environment

underdark