---
cssclasses:
  - json5e-monster
tags:
  - src/5e/toa
  - monster/cr/2
  - monster/size/medium
  - monster/type/plant
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Yellow Musk Creeper
---
# [Yellow Musk Creeper](Yellow-Musk-Creeper-toa.md)
*Source: Tomb of Annihilation p. 237*  

![](https://5e.tools/img/bestiary/ToA/Yellow%20Musk%20Creeper.webp)

A yellow musk creeper is an unholy vine whose flowers resemble an orchid's. Bright yellow with splashes of purple, these flowers expel a musk that attracts prey. A yellow musk creeper clings to walls, pillars, gravestones, door frames, or statuary in shadowy locations, remaining motionless until it strikes.

```statblock
"name": "Yellow Musk Creeper (ToA)"
"size": "Medium"
"type": "plant"
"alignment": "Unaligned"
"ac": !!int "6"
"hp": !!int "60"
"hit_dice": "11d8 + 11"
"modifier": !!int "-4"
"stats":
  - !!int "12"
  - !!int "3"
  - !!int "12"
  - !!int "1"
  - !!int "10"
  - !!int "3"
"speed": "5 ft., climb 5 ft."
"condition_immunities": "[blinded](conditions.md#Blinded),\
  \ [deafened](conditions.md#Deafened), [exhaustion](conditions.md#Exhaustion),\
  \ [prone](conditions.md#Prone)"
"senses": "[Blindsight](senses.md#Blindsight) 30 ft., passive Perception 10"
"languages": ""
"cr": "2"
"traits":
  - "desc": "While the creeper remains motionless, it is indistinguishable from\
      \ an ordinary flowering vine."
    "name": "False Appearance"
  - "desc": "The creeper regains 10 hit points at the start of its turn. If the\
      \ creeper takes fire, necrotic, or radiant damage, this trait doesn't\
      \ function at the start of its next turn. The creeper dies only if it\
      \ starts its turn with 0 hit points and doesn't regenerate."
    "name": "Regeneration"
"actions":
  - "desc": "*Melee Weapon Attack:* +3 to hit, reach 5 ft., one creature.\
      \ *Hit:* 13 (3d8) psychic damage. If the target is a humanoid that drops\
      \ to 0 hit points as a result of this damage, it dies and is implanted\
      \ with a yellow musk creeper bulb. Unless the bulb is destroyed, the\
      \ corpse animates as a yellow musk zombie after being dead for 24 hours.\
      \ The bulb is destroyed if the creature is raised from the dead before it\
      \ can transform into a yellow musk zombie, or if the corpse is targeted\
      \ by a [remove curse](Remove-Curse.md) spell or similar magic before it\
      \ animates."
    "name": "Touch"
  - "desc": "The creeper's flowers release a strong musk that targets all\
      \ humanoids within 30 feet of it. Each target must succeed on a DC 11\
      \ Wisdom saving throw or be [charmed](conditions.md#Charmed) by the\
      \ creeper for 1 minute. A creature [charmed](conditions.md#Charmed) in\
      \ this way does nothing on its turn except move as close as it can to the\
      \ creeper. A creature [charmed](conditions.md#Charmed) by the creeper can\
      \ repeat the saving throw at the end of each of its turns, ending the\
      \ effect on itself on a success."
    "name": "Yellow Musk (3/Day)"
"source":
  - "ToA"
"image": "bestiary/tokens/ToA/Yellow Musk Creeper.webp"
```
^statblock
