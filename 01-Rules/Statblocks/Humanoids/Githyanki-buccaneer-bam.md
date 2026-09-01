---
cssclasses:
- json5e-monster
tags:
- src/5e/bam
- monster/cr/3
- monster/size/medium
- monster/type/Humanoids/gith
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Githyanki Buccaneer"
---
# [Githyanki Buccaneer](Githyanki-buccaneer-bam.md)
*Source: Boo's Astral Menagerie p. 27, Light of Xaryxis*  

Githyanki buccaneers ply the Astral Plane for riches, which they haul back to their hidden fortresses in the Deep Astral. Many of them are warriors who lost the will to serve the Lich-Queen Vlaakith; they prefer to live by their own code or revel in their unbridled freedom.

```statblock
"name": "Githyanki Buccaneer (BAM)"
"size": "Medium"
"type": "humanoid"
"subtype": "gith"
"alignment": "Any alignment"
"ac": !!int "16"
"ac_class": "[breastplate](breastplate)"
"hp": !!int "58"
"hit_dice": "9d8 + 18"
"modifier": !!int "2"
"stats":
  - !!int "16"
  - !!int "14"
  - !!int "14"
  - !!int "16"
  - !!int "13"
  - !!int "13"
"speed": "30 ft."
"saves":
  - "constitution": !!int "4"
  - "intelligence": !!int "5"
  - "wisdom": !!int "3"
"skillsaves":
  - "name": "[Athletics](Athletics)"
    "desc": "+5"
  - "name": "[Deception](skills.md#Deception)"
    "desc": "+3"
  - "name": "[Perception](Perception)"
    "desc": "+3"
  - "name": "[Survival](Survival)"
    "desc": "+3"
"gear":
  - "[greatsword](greatsword)"
"senses": "passive Perception 13"
"languages": "Common, Gith"
"cr": "3"
"actions":
  - "desc": "The githyanki makes two Greatsword or Telekinetic Bolt attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one target. *Hit:* 10\
      \ (2d6 + 3) slashing damage plus 3 (1d6) psychic damage."
    "name": "Greatsword"
  - "desc": "*Ranged Spell Attack:* +5 to hit, range 60 ft., one target. *Hit:*\
      \ 13 (3d6 + 3) force damage."
    "name": "Telekinetic Bolt"
  - "desc": "The githyanki casts one of the following spells, requiring no spell components\
      \ and using Intelligence as the spellcasting ability (spell save DC 13):\n\n\
      **At will:** [light](light), [Mage Hand](Mage-Hand)\
      \ (the hand is invisible)\n\n**1/day each:** [plane shift](Plane%20Shift),\
      \ [telekinesis](telekinesis)"
    "name": "Spellcasting (Psionics)"
"bonus_actions":
  - "desc": "The githyanki teleports, along with any equipment it is wearing or carrying,\
      \ up to 30 feet to an unoccupied space it can see."
    "name": "Astral Step (Recharge 4-6)"
"source":
  - "BAM"
  - "LoX"
"image": "bestiary/tokens/BAM/Githyanki Buccaneer.webp"
```
^statblock