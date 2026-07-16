---
cssclasses:
- json5e-monster
tags:
- src/5e/lmop
- monster/cr/1
- monster/size/medium
- monster/type/Humanoids/human
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Evil Mage"
---
# [Evil Mage](Evil-Mage-Lmop.md)
*Source: Lost Mine of Phandelver p. 57*  

Evil mages (such as Iarno Albrek and Hamun Kost) hunger for arcane power and dwell in isolated places, where they can perform terrible magical experiments without interference.

```statblock
"name": "Evil Mage (LMoP)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Lawful Evil"
"ac": !!int "12"
"hp": !!int "22"
"hit_dice": "5d8"
"modifier": !!int "2"
"stats":
  - !!int "9"
  - !!int "14"
  - !!int "11"
  - !!int "17"
  - !!int "12"
  - !!int "11"
"speed": "30 ft."
"saves":
  - "intelligence": !!int "5"
  - "wisdom": !!int "3"
"skillsaves":
  - "name": "[Arcana](Arcana)"
    "desc": "+5"
  - "name": "[History](History)"
    "desc": "+5"
"gear":
  - "[quarterstaff](quarterstaff)"
"senses": "passive Perception 11"
"languages": "Common, Draconic, Dwarvish, Elvish"
"cr": "1"
"traits":
  - "desc": "The mage is a 4th-level spellcaster that uses Intelligence as its spellcasting\
      \ ability (spell save DC 13; +5 to hit with spell attacks). The mage knows\
      \ the following spells from the wizard's spell list:\n\n**Cantrips (at will):**\
      \ [light](light), [mage hand](Mage%20Hand),\
      \ [shocking grasp](shocking-grasp)\n\n**1st level\
      \ (4 slots):** [charm person](charm-person),\
      \ [magic missile](magic-missile)\n\n**2nd level\
      \ (3 slots):** [hold person](hold-person), [misty\
      \ step](misty-step)"
    "name": "Spellcasting"
"actions":
  - "desc": "*Melee Weapon Attack:* +1 to hit, reach 5 ft., one target. *Hit:* 3\
      \ (1d8 - 1) bludgeoning damage."
    "name": "Quarterstaff"
"source":
  - "LMoP"
"image": "bestiary/tokens/LMoP/Evil Mage.webp"
```
^statblock