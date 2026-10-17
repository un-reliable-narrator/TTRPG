---
cssclasses:
  - json5e-monster
tags:
  - src/5e/pota
  - monster/cr/2
  - monster/size/medium
  - monster/type/humanoid/human
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Black Earth Guard
---
# [Black Earth Guard](Black%20Earth%20Guard.md)
*Source: Princes of the Apocalypse p. 195*  

![](https://5e.tools/img/bestiary/PotA/Black%20Earth%20Guard.webp)

Black Earth guards are the warriors of the earth cult. They are brutal, heavily armored thugs devoted to Ogrémoch. That devotion has granted them an uncanny ability to hold their ground against the buffeting assaults. It has also earned them the right to wear special plate armor of elemental stone, which breaks down when the guard is slain.

These guards are fanatically loyal to the Black Earth priests and the leaders of the cult. They fight to the death if commanded to do so by their superiors. Those with more potential become burrowsharks.

```statblock
"name": "Black Earth Guard (PotA)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Neutral Evil"
"ac": !!int "18"
"ac_class": "[plate armor](Plate-Armor.md)"
"hp": !!int "39"
"hit_dice": "6d8 + 12"
"modifier": !!int "0"
"stats":
  - !!int "17"
  - !!int "11"
  - !!int "14"
  - !!int "10"
  - !!int "10"
  - !!int "9"
"speed": "30 ft."
"skillsaves":
  - "name": "[Intimidation](skills.md#Intimidation)"
    "desc": "+1"
  - "name": "[Perception](skills.md#Perception)"
    "desc": "+2"
"senses": "passive Perception 12"
"languages": "Common"
"cr": "2"
"actions":
  - "desc": "The guard makes two melee attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one target. *Hit:*\
      \ 7 (1d8 + 3) piercing damage."
    "name": "Morningstar"
"reactions":
  - "desc": "When the guard is subjected to an effect that would move it, knock\
      \ it [prone](conditions.md#Prone), or both, it can use its reaction to be\
      \ neither moved nor knocked [prone](conditions.md#Prone)."
    "name": "Unyielding"
"source":
  - "PotA"
"image": "bestiary/tokens/PotA/Black Earth Guard.webp"
```
^statblock
