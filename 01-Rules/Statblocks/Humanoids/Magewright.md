---
cssclasses:
  - json5e-monster
tags:
  - src/5e/erlw
  - monster/cr/0
  - monster/size/medium
  - monster/type/humanoid/any-race
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Magewright
---
# [Magewright](Magewright.md)
*Source: Eberron: Rising from the Last War p. 318*  

![](https://5e.tools/img/bestiary/ERLW/Magewright.webp)

In Khorvaire, magic is part of everyday life. A chef might use [prestidigitation](Prestidigitation.md) to heat and season food, while a blacksmith uses [mending](Mending.md) to perform minor repairs and [guidance](Guidance.md) to help inspire their work. Those who work minor magic into their labors are called magewrights.

Far more limited in magical power than a typical spellcaster, a magewright is dedicated to learning a handful of spells, and magewrights cast their non-cantrip spells as rituals—even spells that can't normally be cast in this way. Most magewright rituals take 10 minutes to perform, but certain complex rituals can take up to 1 hour. However long the ritual takes, it requires extra material components, usually in the form of dragonshards.

## Creating a Magewright

The magewright stat block provides the baseline statistics for a magewright. You then add to that baseline by choosing a specialty from the Magewright Specialties table, or roll for one. The specialty determines additional spells the magewright knows, including ones that can be cast only as rituals. The specialty also gives the magewright more proficiencies.

**Magewright Specialties**

| d8 | Specialty | Spells | Proficiencies |
|---|---|---|---|
| 1 | Artisan | [Guidance](Guidance.md), [mending](Mending.md) | One type of artisan's tools |
| 2 | Entertainer | [Minor illusion](Minor-Illusion.md), [thaumaturgy](Thaumaturgy.md). Ritual only: [disguise self](Disguise-Self.md). | Performance (+3) |
| 3 | Healer | [Resistance](Resistance.md), [spare the dying](Spare-the-Dying.md). Ritual only: [detect poison and disease](Detect-Poison-and-Disease.md), [lesser restoration](Lesser-Restoration.md) (1 hour). | Medicine (+4), [herbalism kit](Herbalism-Kit.md) |
| 4 | Lamplighter | [Light](Light.md). Ritual only: [continual flame](Continual-Flame.md) (1 hour). | Tinker's tools |
| 5 | Locksmith | [Mending](Mending.md). Ritual only: [arcane lock](Arcane-Lock.md) (1 hour), [knock](Knock.md). | Thieves' tools, tinker's tools |
| 6 | Mediator | [Guidance](Guidance.md). Ritual only: [comprehend languages](Comprehend-Languages.md), [zone of truth](Zone-of-Truth.md). | Insight (+4), Persuasion (+3) |
| 7 | Medium | [Minor illusion](Minor-Illusion.md). Ritual only: [speak with dead](Speak-with-Dead.md). | Deception (+3), Religion (+4) |
| 8 | Oracle | [Guidance](Guidance.md). Ritual only: [augury](Augury.md), [divination](Divination.md) (1 hour). | History (+4), Religion (+4) |

```statblock
"name": "Magewright (ERLW)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Any alignment"
"ac": !!int "11"
"hp": !!int "9"
"hit_dice": "2d8"
"modifier": !!int "1"
"stats":
  - !!int "11"
  - !!int "13"
  - !!int "10"
  - !!int "14"
  - !!int "14"
  - !!int "12"
"speed": "30 ft."
"skillsaves":
  - "name": "[Arcana](skills.md#Arcana)"
    "desc": "+4"
"senses": "passive Perception 12"
"languages": "Common plus any two languages"
"cr": "0"
"traits":
  - "desc": "The magewright's spellcasting ability is Intelligence (spell save\
      \ DC 12). To cast one of its rituals, the magewright must provide\
      \ additional material components whose value in gold pieces is 20 times\
      \ the spell's level. These components are consumed when the ritual is\
      \ finished. The magewright knows the following spells:\n\n**At will:**\
      \ [mage hand](Mage-Hand.md), [prestidigitation](Prestidigitation.md)"
    "name": "Spellcasting"
"actions":
  - "desc": "*Melee or Ranged Weapon Attack:* +3 to hit, reach 5 ft. or range\
      \ 20/60 ft., one target. *Hit:* 3 (1d4 + 1) piercing damage."
    "name": "Dagger"
"source":
  - "ERLW"
"image": "bestiary/tokens/ERLW/Magewright.webp"
```
^statblock
