---
cssclasses:
  - json5e-monster
tags:
  - src/5e/veor
  - monster/cr/13
  - monster/environment/urban
  - monster/size/medium
  - monster/type/undead/shapechanger
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Sangora
---
# [Sangora](Sangora-veor.md)
*Source: Vecna: Eve of Ruin p. 31*  

![](https://5e.tools/img/bestiary/tokens/VEoR/Sangora.webp)

```statblock
"name": "Sangora (VEoR)"
"size": "Medium"
"type": "undead"
"subtype": "shapechanger"
"alignment": "Lawful Evil"
"ac": !!int "16"
"ac_class": "natural armor"
"hp": !!int "144"
"hit_dice": "17d8 + 68"
"modifier": !!int "4"
"stats":
  - !!int "18"
  - !!int "18"
  - !!int "18"
  - !!int "17"
  - !!int "15"
  - !!int "18"
"speed": "30 ft."
"saves":
  - "dexterity": !!int "9"
  - "wisdom": !!int "7"
  - "charisma": !!int "9"
"skillsaves":
  - "name": "[Perception](skills.md#Perception)"
    "desc": "+7"
  - "name": "[Stealth](skills.md#Stealth)"
    "desc": "+9"
"damage_resistances": "necrotic; bludgeoning, piercing, slashing from\
  \ nonmagical attacks"
"senses": "[Darkvision](senses.md#Darkvision) 120 ft., passive Perception 17"
"languages": "the languages it knew in life"
"cr": "13"
"traits":
  - "desc": "If Sangora isn't in sunlight or running water, it can use its\
      \ action to polymorph into a Tiny bat or a Medium cloud of mist, or back\
      \ into its true form.\n\nWhile in bat form, Sangora can't speak, its\
      \ walking speed is 5 feet, and it has a flying speed of 30 feet. Its\
      \ statistics, other than its size and speed, are unchanged. Anything it\
      \ is wearing transforms with it, but nothing it is carrying does. It\
      \ reverts to its true form if it dies.\n\nWhile in mist form, Sangora\
      \ can't take any actions, speak, or manipulate objects. It is weightless,\
      \ has a flying speed of 20 feet, can hover, and can enter a hostile\
      \ creature's space and stop there. In addition, if air can pass through a\
      \ space, the mist can do so without squeezing, and it can't pass through\
      \ water. It has advantage on Strength, Dexterity, and Constitution saving\
      \ throws, and it is immune to all nonmagical damage, except the damage it\
      \ takes from sunlight."
    "name": "Shapechanger"
  - "desc": "If Sangora fails a saving throw, it can choose to succeed instead."
    "name": "Legendary Resistance (3/Day)"
  - "desc": "When it drops to 0 hit points outside its resting place, Sangora\
      \ transforms into a cloud of mist (as in the Shapechanger trait) instead\
      \ of falling [unconscious](conditions.md#Unconscious), provided that it\
      \ isn't in sunlight or running water. If it can't transform, it is\
      \ destroyed.\n\nWhile it has 0 hit points in mist form, it can't revert\
      \ to its vampire form, and it must reach its resting place within 2 hours\
      \ or be destroyed. Once in its resting place, it reverts to its vampire\
      \ form. It is then [paralyzed](conditions.md#Paralyzed) until it regains\
      \ at least 1 hit point. After spending 1 hour in its resting place with 0\
      \ hit points, it regains 1 hit point."
    "name": "Misty Escape"
  - "desc": "Sangora regains 20 hit points at the start of its turn if it has\
      \ at least 1 hit point and isn't in sunlight or running water. If Sangora\
      \ takes radiant damage or damage from holy water, this trait doesn't\
      \ function at the start of Sangora's next turn."
    "name": "Regeneration"
  - "desc": "Sangora can climb difficult surfaces, including upside down on\
      \ ceilings, without needing to make an ability check."
    "name": "Spider Climb"
  - "desc": "Sangora has the following flaws:\n\n- **Forbiddance.** Sangora\
      \ can't enter a residence without an invitation from one of the\
      \ occupants.  \n- **Harmed by Running Water.** Sangora takes 20 acid\
      \ damage if it ends its turn in running water.  \n- **Stake to the\
      \ Heart.** If a piercing weapon made of wood is driven into Sangora's\
      \ heart while Sangora is [incapacitated](conditions.md#Incapacitated) in\
      \ its resting place, Sangora is [paralyzed](conditions.md#Paralyzed)\
      \ until the stake is removed.  \n- **Sunlight Hypersensitivity.** Sangora\
      \ takes 20 radiant damage when it starts its turn in sunlight. While in\
      \ sunlight, it has disadvantage on attack rolls and ability checks.  "
    "name": "Vampire Weaknesses"
"actions":
  - "desc": "Sangora makes two attacks, only one of which can be a bite attack."
    "name": "Multiattack (Vampire Form Only)"
  - "desc": "*Melee Weapon Attack:* +9 to hit, reach 5 ft., one creature.\
      \ *Hit:* 8 (1d8 + 4) bludgeoning damage. Instead of dealing damage,\
      \ Sangora can grapple the target (escape DC 18)."
    "name": "Unarmed Strike (Vampire Form Only)"
  - "desc": "*Melee Weapon Attack:* +9 to hit, reach 5 ft., one willing\
      \ creature, or a creature that is [grappled](conditions.md#Grappled) by\
      \ Sangora, [incapacitated](conditions.md#Incapacitated), or\
      \ [restrained](conditions.md#Restrained). *Hit:* 7 (1d6 + 4) piercing\
      \ damage plus 10 (3d6) necrotic damage. The target's hit point maximum is\
      \ reduced by an amount equal to the necrotic damage taken, and Sangora\
      \ regains hit points equal to that amount. The reduction lasts until the\
      \ target finishes a long rest. The target dies if this effect reduces its\
      \ hit point maximum to 0. A humanoid slain in this way and then buried in\
      \ the ground rises the following night as a [vampire\
      \ spawn](Vampire-Spawn.md) under Sangora's control."
    "name": "Bite (Bat or Vampire Form Only)"
  - "desc": "Sangora targets one humanoid it can see within 30 feet of it. If\
      \ the target can see Sangora, the target must succeed on a DC 17 Wisdom\
      \ saving throw against this magic or be [charmed](conditions.md#Charmed)\
      \ by Sangora. The [charmed](conditions.md#Charmed) target regards Sangora\
      \ as a trusted friend to be heeded and protected. Although the target\
      \ isn't under Sangora's control, it takes Sangora's requests or actions\
      \ in the most favorable way it can, and it is a willing target for\
      \ Sangora's bite attack.\n\nEach time Sangora or Sangora's companions do\
      \ anything harmful to the target, it can repeat the saving throw, ending\
      \ the effect on itself on a success. Otherwise, the effect lasts 24 hours\
      \ or until Sangora is destroyed, is on a different plane of existence\
      \ than the target, or takes a bonus action to end the effect."
    "name": "Charm"
  - "desc": "Sangora magically calls 2d4 swarms of [bats](Swarm-of-Bats.md) or\
      \ [rats](Swarm-of-Rats.md), provided that the sun isn't up. While\
      \ outdoors, Sangora can call 3d6 [wolves](wolf.md) instead. The called\
      \ creatures arrive in 1d4 rounds, acting as allies of Sangora and obeying\
      \ its spoken commands. The beasts remain for 1 hour, until Sangora dies,\
      \ or until Sangora dismisses them as a bonus action."
    "name": "Children of the Night (1/Day)"
"regional_effects":
  - "desc": "The region surrounding a vampire's lair is warped by the\
      \ creature's unnatural presence, creating any of the following\
      \ effects:\n\n- There's a noticeable increase in the populations of bats,\
      \ rats, and wolves in the region.  \n- Plants within 500 feet of the lair\
      \ wither, and their stems and branches become twisted and thorny.  \n-\
      \ Shadows cast within 500 feet of the lair seem abnormally gaunt and\
      \ sometimes move as though alive.  \n- A creeping fog clings to the\
      \ ground within 500 feet of the vampire's lair. The fog occasionally\
      \ takes eerie forms, such as grasping claws and writhing serpents. \
      \ \n\nIf the vampire is destroyed, these effects end after 2d6 days."
    "name": ""
"legendary_description": "Legendary Action Uses: 3. Immediately after another\
  \ creature's turn, Sangora can expend a use to take one of the following\
  \ actions. Sangora regains all expended uses at the start of each of its\
  \ turns."
"legendary_actions":
  - "desc": "Sangora moves up to its speed without provoking opportunity\
      \ attacks."
    "name": "Move"
  - "desc": "Sangora makes one unarmed strike."
    "name": "Unarmed Strike"
  - "desc": "Sangora makes one bite attack."
    "name": "Bite (Costs 2 Actions)"
"source":
  - "VEoR"
"image": "bestiary/tokens/VEoR/Sangora.webp"
```
^statblock

## Environment

urban
