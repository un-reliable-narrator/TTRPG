---
cssclasses:
- json5e-monster
tags:
- src/5e/mpmm
- monster/cr/12
- monster/environment/forest
- monster/environment/mountain
- monster/environment/swamp
- monster/environment/underwater
- monster/size/medium
- monster/type/Humanoids/druid
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Archdruid"
---
# [Archdruid](Archdruid-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 48*  

Archdruids watch over the natural wonders of their domains. They seldom interact with folk away from their druid groves and shrines, unless there is a great threat to the natural order or to a nearby community. An archdruid typically has one or more pupils who are [druids](01-Rules/Statblocks/Humanoids/Druid.md), and the archdruid's lair is usually guarded by loyal Beasts and Fey creatures.

When an archdruid uses their Change Shape action, you may choose the creature they turn into, abiding by the action's restrictions. Or you may roll on the Archdruid Favored Shapes table to determine the form the archdruid adopts.

**Archdruid Favored Shapes**

| dice: d8 | Favored Shape |
|----------|---------------|
| 1 | [Air elemental](Air-Elemental.md) |
| 2 | [Earth elemental](earth-Elemental.md) |
| 3 | [Fire elemental](fire-Elemental.md) |
| 4 | [Giant crocodile](Giant-Crocodile.md) |
| 5 | [Mammoth](Mammoth.md) |
| 6 | [Flail snail](flail-Snail-mpmm.md) |
| 7 | [Triceratops](Triceratops.md) |
| 8 | [Water elemental](water-Elemental.md) |
^archdruid-favored-shapes

```statblock
"name": "Archdruid (MPMM)"
"size": "Medium"
"type": "humanoid"
"subtype": "druid"
"alignment": "Any alignment"
"ac": !!int "14"
"ac_class": "[hide armor](hide-armor)"
"hp": !!int "154"
"hit_dice": "28d8 + 28"
"modifier": !!int "2"
"stats":
  - !!int "14"
  - !!int "14"
  - !!int "12"
  - !!int "12"
  - !!int "20"
  - !!int "11"
"speed": "30 ft."
"saves":
  - "intelligence": !!int "5"
  - "wisdom": !!int "9"
"skillsaves":
  - "name": "[Medicine](skills.md#Medicine)"
    "desc": "+9"
  - "name": "[Nature](Nature)"
    "desc": "+5"
  - "name": "[Perception](Perception)"
    "desc": "+9"
"senses": "passive Perception 19"
"languages": "Druidic plus any two languages"
"cr": "12"
"actions":
  - "desc": "The archdruid makes three Staff or Wildfire attacks. It can replace one\
      \ attack with a use of Spellcasting."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one target. *Hit:* 5\
      \ (1d6 + 2) bludgeoning damage plus 21 (6d6) poison damage."
    "name": "Staff"
  - "desc": "*Ranged Spell Attack:* +9 to hit, range 120 ft., one target. *Hit:*\
      \ 26 (6d6 + 5) fire damage, and the target is [blinded](conditions.md#Blinded)\
      \ until the start of the druid's next turn."
    "name": "Wildfire"
  - "desc": "The archdruid casts one of the following spells, using Wisdom as the\
      \ spellcasting ability (spell save DC 17):\n\n**At will:** [beast sense](beast Sense),\
      \ [entangle](entangle), [speak with animals](speak-with-animals)\n\
      \n**3/day each:** [animal messenger](animal-messenger),\
      \ [dominate beast](dominate-beast), [faerie fire](faerie-fire),\
      \ [tree stride](tree-stride)\n\n**1/day each:**\
      \ [commune with nature](commune-with-nature)\
      \ (as an action), [mass cure wounds](mass-cure-wounds)"
    "name": "Spellcasting"
"bonus_actions":
  - "desc": "The archdruid magically transforms into a Beast or an Elemental with\
      \ a challenge rating of 6 or less and can remain in that form for up to 9 hours.\
      \ The archdruid can choose whether its equipment falls to the ground, melds\
      \ with its new form, or is worn by the new form. The archdruid reverts to its\
      \ true form if it dies or falls [unconscious](conditions.md#Unconscious).\
      \ The archdruid can revert to its true form using a bonus action.\n\nWhile in\
      \ a new form, the archdruid's stat block is replaced by the stat block of that\
      \ form, except the archdruid keeps its current hit points, its hit point maximum,\
      \ this bonus action, its languages and ability to speak, and its Spellcasting\
      \ action.\n\nThe new form's attacks count as magical for the purpose of overcoming\
      \ resistances and immunity to nonmagical attacks."
    "name": "Change Shape (2/Day)"
"source":
  - "MPMM"
"image": "bestiary/tokens/MPMM/Archdruid.webp"
```
^statblock

## Environment

forest, mountain, swamp, underwater