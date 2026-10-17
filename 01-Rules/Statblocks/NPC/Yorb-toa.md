---
cssclasses:
  - json5e-monster
tags:
  - src/5e/toa
  - monster/cr/2
  - monster/environment/forest
  - monster/size/small
  - monster/type/humanoid/grung
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Yorb
---
# [Yorb](Yorb-toa.md)
*Source: Tomb of Annihilation p. 108*  

![](https://5e.tools/img/bestiary/ToA/Yorb.webp)

```statblock
"name": "Yorb (ToA)"
"size": "Small"
"type": "humanoid"
"subtype": "grung"
"alignment": "Lawful Evil"
"ac": !!int "13"
"hp": !!int "49"
"hit_dice": "9d6 + 18"
"modifier": !!int "3"
"stats":
  - !!int "7"
  - !!int "16"
  - !!int "15"
  - !!int "10"
  - !!int "11"
  - !!int "12"
"speed": "25 ft., climb 25 ft."
"saves":
  - "dexterity": !!int "5"
"skillsaves":
  - "name": "[Athletics](skills.md#Athletics)"
    "desc": "+2"
  - "name": "[Perception](skills.md#Perception)"
    "desc": "+2"
  - "name": "[Stealth](skills.md#Stealth)"
    "desc": "+5"
  - "name": "[Survival](skills.md#Survival)"
    "desc": "+2"
"damage_immunities": "poison"
"condition_immunities": "[poisoned](conditions.md#Poisoned)"
"senses": "passive Perception 12"
"languages": "Grung"
"cr": "2"
"traits":
  - "desc": "Yorb can breathe air and water."
    "name": "Amphibious"
  - "desc": "Any creature that grapples Yorb or otherwise comes into direct\
      \ contact with Yorb's skin must succeed on a DC 12 Constitution saving\
      \ throw or become [poisoned](conditions.md#Poisoned) for 1 minute. A\
      \ [poisoned](conditions.md#Poisoned) creature no longer in direct contact\
      \ with Yorb can repeat the saving throw at the end of each of its turns,\
      \ ending the effect on itself on a success."
    "name": "Poisonous Skin"
  - "desc": "Yorb's long jump is up to 25 feet and its high jump is up to 15\
      \ feet, with or without a running start."
    "name": "Standing Leap"
"actions":
  - "desc": "*Melee or Ranged Weapon Attack:* +5 to hit, reach 5 ft. or range\
      \ 20/60 ft., one target. *Hit:* 5 (1d4 + 3) piercing damage, and the\
      \ target must succeed on a DC 12 Constitution saving throw or take 5\
      \ (2d4) poison damage."
    "name": "Dagger"
  - "desc": "*Ranged Weapon Attack:* +5 to hit, range 80/320 ft., one target.\
      \ *Hit:* 6 (1d6 + 3) piercing damage, and the target must succeed on a DC\
      \ 12 Constitution saving throw or take 5 (2d4) poison damage."
    "name": "Shortbow"
  - "desc": "Yorb makes a chirring noise to which grungs are immune. Each\
      \ humanoid or beast that is within 15 feet of Yorb and able to hear it\
      \ must succeed on a DC 12 Wisdom saving throw or be\
      \ [stunned](conditions.md#Stunned) until the end of Yorb's next turn."
    "name": "Mesmerizing Chirr (Recharge 6)"
"source":
  - "ToA"
"image": "bestiary/tokens/ToA/Yorb.webp"
```
^statblock

## Grung Poison

Grung poison loses its potency 1 minute after being removed from a grung. A similar breakdown occurs if Yorb dies. A creature [poisoned](conditions.md#Poisoned) by a grung can suffer an additional effect that varies depending on Yorb's skin color. This effect lasts until the creature is no longer [poisoned](conditions.md#Poisoned) by Yorb.

### Green

The [poisoned](conditions.md#Poisoned) creature can't move except to climb or make standing jumps. If the creature is flying, it can't take any actions or reactions unless it lands.

### Blue

The [poisoned](conditions.md#Poisoned) creature must shout loudly or otherwise make a loud noise at the start and end of its turn.

### Purple

The [poisoned](conditions.md#Poisoned) creature feels a desperate need to soak itself in liquid or mud. It can't take actions or move except to do so or to reach a body of liquid or mud.

### Red

The [poisoned](conditions.md#Poisoned) creature must use its action to eat if food is within reach.

### Orange

The [poisoned](conditions.md#Poisoned) creature is [frightened](conditions.md#Frightened) of its allies.

### Gold

The [poisoned](conditions.md#Poisoned) creature is [charmed](conditions.md#Charmed) and can speak Grung.

## Environment

forest
