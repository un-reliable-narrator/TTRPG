---
cssclasses:
  - json5e-monster
tags:
  - src/5e/ggr
  - monster/cr/1
  - monster/size/medium
  - monster/type/humanoid/any-race
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Thought Spy
---
# [Thought Spy](Thought-Spy-ggr.md)
*Source: Guildmasters' Guide to Ravnica p. 233*  

![](https://5e.tools/img/bestiary/tokens/GGR/Thought%20Spy.webp)

Thought spies form the backbone of House Dimir's covert operations. They are trained in stealth and infiltration, tactics that they supplement with rigorously developed mental abilities. To ensure that no secrets slip through Dimir's fingers, they infiltrate rival guilds. In addition to traditional means of gathering intelligence, thought spies use their magic to spy on the thoughts of their targets.

```statblock
"name": "Thought Spy (GGR)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Neutral Evil"
"ac": !!int "13"
"ac_class": "[leather armor](Leather-Armor.md)"
"hp": !!int "27"
"hit_dice": "6d8"
"modifier": !!int "2"
"stats":
  - !!int "11"
  - !!int "14"
  - !!int "10"
  - !!int "16"
  - !!int "13"
  - !!int "14"
"speed": "30 ft."
"skillsaves":
  - "name": "[Deception](skills.md#Deception)"
    "desc": "+6"
  - "name": "[Insight](skills.md#Insight)"
    "desc": "+3"
  - "name": "[Investigation](skills.md#Investigation)"
    "desc": "+5"
  - "name": "[Perception](skills.md#Perception)"
    "desc": "+3"
  - "name": "[Sleight Of Hand](skills.md#Sleight%20Of%20Hand)"
    "desc": "+4"
  - "name": "[Stealth](skills.md#Stealth)"
    "desc": "+4"
"senses": "[Darkvision](senses.md#Darkvision) 30 ft., passive Perception 13"
"languages": "Common plus any one language"
"cr": "1"
"traits":
  - "desc": "On each of its turns, the thought spy can use a bonus action to\
      \ take the Dash, Disengage, or Hide action."
    "name": "Cunning Action"
  - "desc": "The thought spy's innate spellcasting ability is Intelligence\
      \ (spell save DC 13). The thought spy can innately cast the following\
      \ spells, requiring no components:\n\n**At will:** [charm\
      \ person](Charm-Person.md), [disguise self](Disguise-Self.md), [encode\
      \ thoughts](encode-thoughts) (see chapter 2)\n\n**1/day each:**\
      \ [blur](Blur.md), [detect thoughts](Detect-Thoughts.md), [gaseous\
      \ form](Gaseous-Form.md)"
    "name": "Innate Spellcasting (Psionics)"
"actions":
  - "desc": "The thought spy makes two melee attacks, or it makes three ranged\
      \ attacks with its daggers."
    "name": "Multiattack"
  - "desc": "*Melee or Ranged Weapon Attack:* +4 to hit, reach 5 ft. or range\
      \ 20/60 ft., one target. *Hit:* 4 (1d4 + 2) piercing damage."
    "name": "Dagger"
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target. *Hit:*\
      \ 6 (1d8 + 2) piercing damage."
    "name": "Rapier"
"source":
  - "GGR"
"image": "bestiary/tokens/GGR/Thought Spy.webp"
```
^statblock
