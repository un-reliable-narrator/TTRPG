---
cssclasses:
  - json5e-monster
tags:
  - src/5e/bam
  - monster/cr/3
  - monster/size/medium
  - monster/type/ooze
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Plasmoid Warrior
---
# [Plasmoid Warrior](Plasmoid-Warrior-bam.md)
*Source: Boo's Astral Menagerie p. 43*  

![](https://5e.tools/img/bestiary/BAM/Plasmoid%20Warrior.webp)

These battle-hardened plasmoids can toughen their outer surfaces, giving themselves protection comparable to light armor.

```statblock
"name": "Plasmoid Warrior (BAM)"
"size": "Medium"
"type": "ooze"
"alignment": "Any alignment"
"ac": !!int "16"
"ac_class": "natural armor, [shield](Shield.md)"
"hp": !!int "71"
"hit_dice": "11d8 + 22"
"modifier": !!int "2"
"stats":
  - !!int "16"
  - !!int "14"
  - !!int "14"
  - !!int "10"
  - !!int "11"
  - !!int "10"
"speed": "30 ft."
"skillsaves":
  - "name": "[Athletics](skills.md#Athletics)"
    "desc": "+5"
  - "name": "[Stealth](skills.md#Stealth)"
    "desc": "+4"
"damage_resistances": "acid, poison"
"senses": "[Darkvision](senses.md#Darkvision) 60 ft., passive Perception 14"
"languages": "Common"
"cr": "3"
"traits":
  - "desc": "The plasmoid can squeeze through a space as narrow as 1 inch wide,\
      \ provided it is wearing and carrying nothing. It has advantage on\
      \ ability checks it makes to initiate or escape a grapple."
    "name": "Amorphous"
  - "desc": "The plasmoid can hold its breath for 1 hour."
    "name": "Hold Breath"
"actions":
  - "desc": "The plasmoid makes three Pseudopod attacks. It can replace one of\
      \ those attacks with a Spear or Pistol attack."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one target. *Hit:*\
      \ 6 (1d6 + 3) bludgeoning damage."
    "name": "Pseudopod"
  - "desc": "*Melee or Ranged Weapon Attack:* +5 to hit, reach 5 ft. or range\
      \ 20/60 ft., one target. *Hit:* 6 (1d6 + 3) piercing damage, or 7 (1d8 +\
      \ 3) piercing damage when used with two hands to make a melee attack."
    "name": "Spear"
  - "desc": "*Ranged Weapon Attack:* +4 to hit, range 30/90 ft., one target.\
      \ *Hit:* 7 (1d10 + 2) piercing damage."
    "name": "Pistol"
"source":
  - "BAM"
"image": "bestiary/tokens/BAM/Plasmoid Warrior.webp"
```
^statblock
