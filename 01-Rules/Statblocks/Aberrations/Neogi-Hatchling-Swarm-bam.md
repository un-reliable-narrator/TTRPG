---
cssclasses:
  - json5e-monster
tags:
  - src/5e/bam
  - monster/cr/3
  - monster/size/medium
  - monster/type/aberration
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Neogi Hatchling Swarm
---
# [Neogi Hatchling Swarm](Neogi-Hatchling-Swarm-bam.md)
*Source: Boo's Astral Menagerie p. 40*  

![](https://5e.tools/img/bestiary/tokens/BAM/Neogi%20Hatchling%20Swarm.webp)

A neogi lives about a century. When an individual is rendered weak by advanced age, the other neogi in the group overpower it and inject it with a special poison. The toxin transforms the old neogi into a bloated mass of flesh. Younger neogi lay their eggs atop it, and when the hatchlings emerge, they devour the old neogi and one another until only a few of the strongest newborns are left. Sometimes the newborns, united by a singular evil purpose, coalesce into a skittering swarm instead.

Neogi pirates are adult neogi that serve as crew members aboard nightspiders (see the *Astral Adventurer's Guide*) and other neogi-controlled vessels.

Neogi society makes no distinction between individuals, aside from the ability that a given creature has to control others, and they don't comprehend the emotional aspects of existence that humans and similar beings experience. To a neogi, hatred is as foreign a sensation as love, and showing loyalty in the absence of authority is foolishness.

Neogi pirates (and adult neogi in general) mark themselves and those they capture through the use of dyes, transformational magic, and other markings intended to signify rank, achievements, and the identity of the individual's leader. By these signs, neogi can identify each other's place in the hierarchy—and they must defer to those of higher station or risk harsh punishment.

A neogi void hunter is bigger than a typical adult neogi and often fills the role of captain aboard a nightspider (see the *Astral Adventurer's Guide*). The void hunter pledges fealty to one or more stellar entities in exchange for a taste of their immense power. These entities—known by such names as Acamar, Caiphon, Gibbeth, and Hadar—resemble stars and embody the essence of evil.

```statblock
"name": "Neogi Hatchling Swarm (BAM)"
"size": "Medium"
"type": "swarm of Tiny aberrations"
"alignment": "typically Lawful Evil"
"ac": !!int "11"
"hp": !!int "52"
"hit_dice": "8d8 + 16"
"modifier": !!int "1"
"stats":
  - !!int "12"
  - !!int "13"
  - !!int "14"
  - !!int "6"
  - !!int "10"
  - !!int "9"
"speed": "20 ft., climb 20 ft."
"damage_resistances": "bludgeoning, piercing, slashing"
"condition_immunities": "[charmed](conditions.md#Charmed),\
  \ [frightened](conditions.md#Frightened), [grappled](conditions.md#Grappled),\
  \ [paralyzed](conditions.md#Paralyzed), [petrified](conditions.md#Petrified),\
  \ [prone](conditions.md#Prone), [restrained](conditions.md#Restrained),\
  \ [stunned](conditions.md#Stunned)"
"senses": "[Darkvision](senses.md#Darkvision) 60 ft., passive Perception 10"
"languages": ""
"cr": "3"
"traits":
  - "desc": "The swarm can climb difficult surfaces, including upside down on\
      \ ceilings, without needing to make an ability check."
    "name": "Spider Climb"
  - "desc": "The swarm can occupy another creature's space and vice versa, and\
      \ the swarm can move through any opening large enough for a Tiny neogi\
      \ hatchling. The swarm can't regain hit points or gain temporary hit\
      \ points."
    "name": "Swarm"
"actions":
  - "desc": "*Melee Weapon Attack:* +3 to hit, reach 5 ft., one creature.\
      \ *Hit:* 22 (6d6 + 1) poison damage, or 11 (3d6 + 1) poison damage if the\
      \ swarm has half of its hit points or fewer, and the target must succeed\
      \ on a DC 12 Constitution saving throw or become\
      \ [poisoned](conditions.md#Poisoned) for 1 minute. A target can repeat\
      \ the saving throw at the end of each of its turns, ending the effect on\
      \ itself on a success."
    "name": "Swarm of Bites"
"source":
  - "BAM"
"image": "bestiary/tokens/BAM/Neogi Hatchling Swarm.webp"
```
^statblock
