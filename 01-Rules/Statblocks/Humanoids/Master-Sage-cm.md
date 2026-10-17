---
cssclasses:
  - json5e-monster
tags:
  - src/5e/cm
  - monster/cr/5
  - monster/size/medium
  - monster/type/humanoid/any-race
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Master Sage
---
# [Master Sage](Master-Sage-cm.md)
*Source: Candlekeep Mysteries p. 9*  

![](https://5e.tools/img/bestiary/CM/Master%20Sage.webp)

Candlekeep's resident lore experts are master sages and sages who dedicate themselves to scholarship above all.

```statblock
"name": "Master Sage (CM)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": ""
"ac": !!int "10"
"hp": !!int "54"
"hit_dice": "12d8"
"modifier": !!int "0"
"stats":
  - !!int "8"
  - !!int "10"
  - !!int "10"
  - !!int "20"
  - !!int "18"
  - !!int "11"
"speed": "30 ft."
"skillsaves":
  - "name": "[Arcana](skills.md#Arcana)"
    "desc": "+11"
  - "name": "[History](skills.md#History)"
    "desc": "+11"
  - "name": "[Insight](skills.md#Insight)"
    "desc": "+7"
  - "name": "[Investigation](skills.md#Investigation)"
    "desc": "+11"
  - "name": "[Medicine](skills.md#Medicine)"
    "desc": "+10"
  - "name": "[Nature](skills.md#Nature)"
    "desc": "+11"
  - "name": "[Religion](skills.md#Religion)"
    "desc": "+11"
"senses": "passive Perception 14"
"languages": "Common plus any five languages"
"cr": "5"
"actions":
  - "desc": "*Melee Spell Attack:* +8 to hit (with advantage if the target is\
      \ wearing armor made of metal), reach 5 ft., one creature. *Hit:* 13\
      \ (3d8) lightning damage, and the target can't take reactions until the\
      \ start of its next turn."
    "name": "Shocking Grasp (Cantrip)"
  - "desc": "The sage creates an eruption of magical lightning centered on a\
      \ point it can see within 150 feet of it. Each creature in a\
      \ 20-foot-radius sphere centered on that point must make a DC 16\
      \ Dexterity saving throw, taking 28 (8d6) lightning damage on a failed\
      \ save, or half as much damage on a successful one."
    "name": "Lightning Eruption (3/Day)"
  - "desc": "The sage casts one of the following spells, using Intelligence as\
      \ the spellcasting ability (save DC 16, +8 to hit with spell\
      \ attacks):\n\n**At will:** [light](Light.md), [mage hand](Mage-Hand.md),\
      \ [mending](Mending.md), [prestidigitation](Prestidigitation.md),\
      \ [Shocking Grasp](Shocking-Grasp.md)\n\n**3/day each:** [comprehend\
      \ languages](Comprehend-Languages.md), [detect magic](Detect-Magic.md),\
      \ [dispel magic](Dispel-Magic.md), [identify](Identify.md),\
      \ [levitate](Levitate.md), [locate object](Locate-Object.md),\
      \ [Shield](Shield.md), [Tenser's Floating\
      \ Disk](Tenser's-Floating-Disk.md), [unseen\
      \ servant](Unseen-Servant.md)\n\n**1/day each:**\
      \ [banishment](Banishment.md), [contact other\
      \ plane](Contact-Other-Plane.md), [Drawmij's instant\
      \ summons](drawmij-s-instant-summons), [legend lore](Legend-Lore.md),\
      \ [locate creature](Locate-Creature.md), [planar\
      \ binding](Planar-Binding.md), [polymorph](Polymorph.md), [protection\
      \ from evil and good](Protection-from-Evil-and-Good.md),\
      \ [scrying](Scrying.md), [sending](Sending.md), [true\
      \ seeing](True-Seeing.md)"
    "name": "Spellcasting"
"reactions":
  - "desc": "When the sage is hit by an attack or targeted by a [magic\
      \ missile](Magic-Missile.md) spell, it calls forth an\
      \ [invisible](conditions.md#Invisible) barrier of magical force that\
      \ protects it. Until the start of its next turn, the sage has a +5 bonus\
      \ to AC, including against the triggering attack, and it takes no damage\
      \ from magic missile."
    "name": "Shield (1st-Level Spell; 3/Day)"
"source":
  - "CM"
"image": "bestiary/tokens/CM/Master Sage.webp"
```
^statblock
