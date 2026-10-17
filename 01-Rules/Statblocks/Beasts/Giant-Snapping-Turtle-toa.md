---
cssclasses:
  - json5e-monster
tags:
  - src/5e/toa
  - monster/cr/3
  - monster/size/large
  - monster/type/beast
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Giant Snapping Turtle
---
# [Giant Snapping Turtle](Giant-Snapping-Turtle-toa.md)
*Source: Tomb of Annihilation p. 222*  

![](https://5e.tools/img/bestiary/tokens/ToA/Giant%20Snapping%20Turtle.webp)

Giant snapping turtles can grow to be 12 feet in diameter. Although they appear slow and ponderous, they are capable of startling bursts of speed and will aggressively attack smaller creatures that approach them. One snap of a giant turtle's jaws can cut a human in half, and these creatures aren't fussy about what they eat.

```statblock
"name": "Giant Snapping Turtle (ToA)"
"size": "Large"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "17"
"ac_class": "natural armor; 12 while prone"
"hp": !!int "75"
"hit_dice": "10d10 + 20"
"modifier": !!int "0"
"stats":
  - !!int "19"
  - !!int "10"
  - !!int "14"
  - !!int "2"
  - !!int "12"
  - !!int "5"
"speed": "30 ft., swim 40 ft."
"senses": "[Darkvision](senses.md#Darkvision) 60 ft., passive Perception 11"
"languages": ""
"cr": "3"
"traits":
  - "desc": "The turtle can breathe air and water."
    "name": "Amphibious"
  - "desc": "Whenever an effect knocks the turtle [prone](conditions.md#Prone),\
      \ it can make a DC 10 Constitution saving throw to avoid being knocked\
      \ [prone](conditions.md#Prone). A [prone](conditions.md#Prone) turtle is\
      \ upside down. To stand up, it must succeed on a DC 10 Dexterity check on\
      \ its turn and then use all its movement for that turn."
    "name": "Stable"
"actions":
  - "desc": "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one target. *Hit:*\
      \ 18 (4d6 + 4) slashing damage."
    "name": "Bite"
"source":
  - "ToA"
"image": "bestiary/tokens/ToA/Giant Snapping Turtle.webp"
```
^statblock
