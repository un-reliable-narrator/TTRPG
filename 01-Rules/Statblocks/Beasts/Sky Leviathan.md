---
cssclasses:
  - json5e-monster
tags:
  - src/5e/psk
  - monster/cr/10
  - monster/size/gargantuan
  - monster/type/beast
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Sky Leviathan
---
# [Sky Leviathan](Sky%20Leviathan.md)
*Source: Plane Shift: Kaladesh p. 28*  

![](https://5e.tools/img/bestiary/PSK/Sky%20Leviathan.webp)

The aethersphere is home to its own ecosystem. Tiny organisms float in the aether currents, deriving all their energy from it and serving as food for larger creatures. Leviathans (similar in form to enormous eels) and flying whales filter these organisms out of the air as they swim through the aethersphere. The whales, as a rule, are not hostile by nature, though they can cause devastating sparks or destructive storms as they move through the aether flows. But leviathans are perpetually hungry, and feed on drakes and airships just as readily as they do on smaller creatures. Along with dragons, leviathans are the primary reason that aether-mining airships carry enormous harpoons.

A sky leviathan is similar to a [purple worm](Purple-Worm.md) in its propensity to swallow prey whole, but it lacks the worm's poison stinger and is therefore significantly less dangerous. Use the statistics presented here.

Sky whales are generally docile filter-feeders that avoid confrontations with airships and flying predators whenever possible. Use the statistics for a [giant crocodile](Giant-Crocodile.md), but replace its bite attack with a flipper attack that is identical to its tail attack. A sky whale has a flying speed of 50 feet and can hover.

```statblock
"name": "Sky Leviathan (PSK)"
"size": "Gargantuan"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "14"
"ac_class": "natural armor"
"hp": !!int "247"
"hit_dice": "15d20 + 90"
"modifier": !!int "-2"
"stats":
  - !!int "28"
  - !!int "7"
  - !!int "22"
  - !!int "1"
  - !!int "8"
  - !!int "4"
"speed": "0 ft., fly 50 ft. (hover)"
"saves":
  - "constitution": !!int "10"
  - "wisdom": !!int "3"
"senses": "passive Perception 9"
"languages": ""
"cr": "10"
"actions":
  - "desc": "*Melee Weapon Attack:* +9 to hit, reach 10 ft., one target. *Hit:*\
      \ 22 (3d8 + 9) piercing damage. If the target is a Large or smaller\
      \ creature, it must succeed on a DC 18 Dexterity saving throw or be\
      \ swallowed by the leviathan. A swallowed creature is\
      \ [blinded](conditions.md#Blinded) and\
      \ [restrained](conditions.md#Restrained), it has total cover against\
      \ attacks and other effects outside the leviathan, and it takes 21 (6d6)\
      \ acid damage at the start of each of the leviathan's turns.\n\nIf the\
      \ leviathan takes 30 damage or more on a single turn from a creature\
      \ inside it, the leviathan must succeed on a DC 21 Constitution saving\
      \ throw at the end of that turn or regurgitate all swallowed creatures,\
      \ which fall [prone](conditions.md#Prone) in a space within 10 feet of\
      \ the leviathan. If the leviathan dies, a swallowed creature is no longer\
      \ [restrained](conditions.md#Restrained) by it and can escape from the\
      \ corpse by using 20 feet of movement, exiting\
      \ [prone](conditions.md#Prone)."
    "name": "Bite"
"source":
  - "PSK"
"image": "bestiary/tokens/PSK/Sky Leviathan.webp"
```
^statblock
