---
cssclasses:
  - json5e-monster
tags:
  - src/5e/cm
  - monster/cr/3
  - monster/environment/forest
  - monster/environment/swamp
  - monster/environment/hill
  - monster/size/medium
  - monster/type/fey
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Hag of the Fetid Gaze
---
# [Hag of the Fetid Gaze](Hag-of-the-Fetid-Gaze-cm.md)
*Source: Candlekeep Mysteries p. 76*  

![](https://5e.tools/img/bestiary/CM/Hag%20of%20the%20Fetid%20Gaze.webp)

Three green hags named Dread Morgan, Vile Sazha, and Auntie Greenbones were once rivals who dwelled in an area of the Feywild coterminous with the High Forest. A decade ago, during a time when the boundaries between the planes thinned, the hags became aware of the magic spring controlled by Sylvarie—and decided to control and corrupt it for their own purposes. The covetous hags each knew part of a ritual for crafting magic paintings that could bind mortal creatures with a terrible curse. After agreeing to share their knowledge and work together, they formed a coven dedicated to claiming Sylvarie's temple and making it a base for their nefarious plans.

The hags use their powers of illusion to pose as three elf sisters named Morganna, Azirssa, and Greensong. They are typically found in the bathhouse by day and in their tower lair at night. Each hag carries a master key that opens all the doors in the bathhouse and the tower.

```statblock
"name": "Hag of the Fetid Gaze (CM)"
"size": "Medium"
"type": "fey"
"alignment": "Neutral Evil"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "82"
"hit_dice": "11d8 + 33"
"modifier": !!int "1"
"stats":
  - !!int "18"
  - !!int "12"
  - !!int "16"
  - !!int "13"
  - !!int "14"
  - !!int "14"
"speed": "30 ft."
"skillsaves":
  - "name": "[Arcana](skills.md#Arcana)"
    "desc": "+3"
  - "name": "[Deception](skills.md#Deception)"
    "desc": "+4"
  - "name": "[Perception](skills.md#Perception)"
    "desc": "+4"
  - "name": "[Stealth](skills.md#Stealth)"
    "desc": "+3"
"senses": "[Darkvision](senses.md#Darkvision) 60 ft., passive Perception 14"
"languages": "Common, Draconic, Sylvan"
"cr": "3"
"traits":
  - "desc": "The hag can breathe air and water."
    "name": "Amphibious"
  - "desc": "The hag can mimic animal sounds and humanoid voices. A creature\
      \ that hears the sounds can tell they are imitations with a successful DC\
      \ 14 Wisdom (Insight) check."
    "name": "Mimicry"
  - "desc": "The hag's innate spellcasting ability is Charisma (spell save DC\
      \ 12). She can innately cast the following spells, requiring no material\
      \ components:\n\n**At will:** [dancing lights](Dancing-Lights.md), [minor\
      \ illusion](Minor-Illusion.md), [vicious mockery](Vicious Mockery.md)"
    "name": "Innate Spellcasting"
  - "desc": "While all three members of a hag coven are within 30 feet of one\
      \ another, they can each cast the following spells from the wizard's\
      \ spell list but must share the spell slots among themselves:\n\n**1st\
      \ level (4 slots):** [charm person](Charm-Person.md), [witch\
      \ bolt](Witch-Bolt.md)\n\n**2nd level (3 slots):** [alter\
      \ self](Alter-Self.md), [suggestion](Suggestion.md)\n\n**3rd level (3\
      \ slots):** [dispel magic](Dispel-Magic.md), [glyph of\
      \ warding](Glyph-of-Warding.md), [slow](Slow.md)\n\n**4th level (3\
      \ slots):** [blight](Blight.md), [polymorph](Polymorph.md)\n\n**5th level\
      \ (2 slots):** [dominate person](Dominate-Person.md),\
      \ [seeming](Seeming.md)\n\n**6th level (1 slot):** [Otto's irresistible\
      \ dance](otto-s-irresistible-dance)\n\nFor casting these spells, each hag\
      \ is a 12th-level spellcaster that uses Intelligence as her spellcasting\
      \ ability. The spell save DC is 12 + the hag's Intelligence modifier, and\
      \ the spell attack bonus is 4 + the hag's Intelligence modifier."
    "name": "Shared Spellcasting (Coven Only)"
"actions":
  - "desc": "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one target. *Hit:*\
      \ 13 (2d8 + 4) slashing damage."
    "name": "Claws"
  - "desc": "The hag covers herself and anything she is wearing or carrying\
      \ with a magical illusion that makes her look like another creature of\
      \ her general size and humanoid shape. The illusion ends if the hag takes\
      \ a bonus action to end it or if she dies.\n\nThe changes wrought by this\
      \ effect fail to hold up to physical inspection. For example, the hag\
      \ could appear to have smooth skin, but someone touching her would feel\
      \ her rough flesh. Otherwise, a creature must take an action to visually\
      \ inspect the illusion and succeed on a DC 20 Intelligence\
      \ (Investigation) check to discern that the hag is disguised."
    "name": "Illusory Appearance"
  - "desc": "The hag magically turns [invisible](conditions.md#Invisible) until\
      \ she attacks or casts a spell, or until her concentration ends (as if\
      \ concentrating on a spell). While [invisible](conditions.md#Invisible),\
      \ she leaves no physical evidence of her passage, so she can be tracked\
      \ only by magic. Any equipment she wears or carries is\
      \ [invisible](conditions.md#Invisible) with her."
    "name": "Invisible Passage"
"source":
  - "CM"
"image": "bestiary/tokens/CM/Hag of the Fetid Gaze.webp"
```
^statblock

## Hag Covens

When hags must work together, they form covens, in spite of their selfish natures. A coven is made up of hags of any type, all of whom are equals within the group. However, each of the hags continues to desire more personal power.

A coven consists of three hags so that any arguments between two hags can be settled by the third. If more than three hags ever come together, as might happen if two covens come into conflict, the result is usually chaos.

While all three members of a hag coven are within 30 feet of one another, they can each cast the following spells from the wizard's spell list but must share the spell slots among themselves:

**1st level (4 slots):** [identify](Identify.md), [ray of sickness](Ray-of-Sickness.md)

**2nd level (3 slots):** [hold person](Hold-Person.md), [locate object](Locate-Object.md)

**3rd level (3 slots):** [bestow curse](Bestow-Curse.md), [counterspell](Counterspell.md), [lightning bolt](Lightning-Bolt.md)

**4th level (3 slots):** [phantasmal killer](Phantasmal-Killer.md), [polymorph](Polymorph.md)

**5th level (2 slots):** [contact other plane](Contact-Other-Plane.md), [scrying](Scrying.md)

**6th level (1 slot):** [eyebite](Eyebite.md)

For casting these spells, each hag is a 12th-level spellcaster that uses Intelligence as her spellcasting ability. The spell save DC is 12 + the hag's Intelligence modifier, and the spell attack bonus is 4 + the hag's Intelligence modifier.

### Hag Eye

A hag coven can craft a magic item called a hag eye, which is made from a real eye coated in varnish and often fitted to a pendant or other wearable item. The hag eye is usually entrusted to a minion for safekeeping and transport. A hag in the coven can take an action to see what the hag eye sees if the hag eye is on the same plane of existence. A hag eye has AC 10, 1 hit point, and darkvision with a radius of 60 feet. If it is destroyed, each coven member takes 3d10 psychic damage and is [blinded](conditions.md#Blinded) for 24 hours.

A hag coven can have only one hag eye at a time, and creating a new one requires all three members of the coven to perform a ritual. The ritual takes 1 hour, and the hags can't perform it while [blinded](conditions.md#Blinded). During the ritual, if the hags take any action other than performing the ritual, they must start over.

## Environment

forest, swamp, hill
