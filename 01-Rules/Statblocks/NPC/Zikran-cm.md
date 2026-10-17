---
cssclasses:
  - json5e-monster
tags:
  - src/5e/cm
  - monster/cr/12
  - monster/environment/urban
  - monster/size/medium
  - monster/type/humanoid/any-race
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Zikran
---
# [Zikran](Zikran-cm.md)
*Source: Candlekeep Mysteries p. 145*  

![](https://5e.tools/img/bestiary/CM/Zikran.webp)

Genasi have strong ties to the Inner Planes and the blood of genies flowing through their veins. Like the marids of the Elemental Plane of Water, Zikran is turbulent and unpredictable.

He carries a handheld magic device that controls the elemental cannon. This device, shown in the accompanying illustration, looks like a metal rod with a tip shaped like a bird's head.

On initiative count 20 (losing initiative ties), Zikran uses his handheld device to fire the cannon at one creature he can see, provided the creature is in the basement or on the staircase. Zikran's target must make a DC 17 Dexterity saving throw, taking 24 (7d6) cold damage on a failed save, or half as much damage on a successful one. The basement furnishings provide half cover, should a creature wish to hide behind them.

The cannon is a Large object with AC 16, 80 hit points, and immunity to poison and psychic damage. It is mounted atop a swivel and bolted to the dais. The cannon draws power from the crystal in the middle of the room. This crystal sparks with elemental power whenever the cannon is about to fire. If the crystal is destroyed, both Zikran's handheld device and the cannon become powerless. The crystal is a Large object with AC 13, 40 hit points, and immunity to poison and psychic damage.

```statblock
"name": "Zikran (CM)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Any alignment"
"ac": !!int "12"
"hp": !!int "144"
"hit_dice": "18d8 + 18"
"modifier": !!int "2"
"stats":
  - !!int "10"
  - !!int "14"
  - !!int "12"
  - !!int "20"
  - !!int "15"
  - !!int "16"
"speed": "30 ft."
"saves":
  - "intelligence": !!int "9"
  - "wisdom": !!int "6"
"skillsaves":
  - "name": "[Arcana](skills.md#Arcana)"
    "desc": "+13"
  - "name": "[History](skills.md#History)"
    "desc": "+13"
"damage_resistances": "damage from spells; nonmagical bludgeoning, piercing,\
  \ slashing (from stoneskin)"
"senses": "passive Perception 12"
"languages": "Aquan, Common, Primordial, Sahuagin, Undercommon"
"cr": "12"
"traits":
  - "desc": "Zikran has advantage on saving throws against spells and other\
      \ magical effects."
    "name": "Magic Resistance"
  - "desc": "Zikran is an 18th-level spellcaster. Its spellcasting ability is\
      \ Intelligence (spell save DC 17, +9 to hit with spell attacks). Zikran\
      \ can cast [disguise self](Disguise-Self.md) and\
      \ [invisibility](Invisibility.md) at will and has the following wizard\
      \ spells prepared:\n\n**At will:** [disguise self](Disguise-Self.md),\
      \ [invisibility](Invisibility.md)\n\n**Cantrips (at will):** [fire\
      \ bolt](Fire-Bolt.md), [light](Light.md), [mage hand](Mage-Hand.md),\
      \ [prestidigitation](Prestidigitation.md), [shocking\
      \ grasp](Shocking-Grasp.md)\n\n**1st level (4 slots):** [detect\
      \ magic](Detect-Magic.md), [identify](Identify.md), [mage\
      \ armor](Mage-Armor.md)*, [magic missile](Magic-Missile.md)\n\n**2nd\
      \ level (3 slots):** [detect thoughts](Detect-Thoughts.md), [mirror\
      \ image](Mirror-Image.md), [misty step](Misty-Step.md)\n\n**3rd level (3\
      \ slots):** [counterspell](Counterspell.md), [fly](Fly.md), [lightning\
      \ bolt](Lightning-Bolt.md)\n\n**4th level (3 slots):**\
      \ [banishment](Banishment.md), [fire shield](Fire-Shield.md),\
      \ [stoneskin](Stoneskin.md)*\n\n**5th level (3 slots):** [cone of\
      \ cold](Cone-of-Cold.md), [scrying](Scrying.md), [wall of\
      \ force](Wall-of-Force.md), [conjure\
      \ elemental](Conjure-Elemental.md)\n\n**6th level (1 slot):** [globe of\
      \ invulnerability](Globe-of-Invulnerability.md)\n\n**7th level (1\
      \ slot):** [teleport](Teleport.md)\n\n**8th level (1 slot):** [mind\
      \ blank](Mind-Blank.md)*\n\n**9th level (1 slot):** [time\
      \ stop](Time-Stop.md)\n\n*Zikran casts these spells on itself before\
      \ combat."
    "name": "Spellcasting"
"actions":
  - "desc": "*Melee or Ranged Weapon Attack:* +6 to hit, reach 5 ft. or range\
      \ 20/60 ft., one target. *Hit:* 4 (1d4 + 2) piercing damage."
    "name": "Dagger"
"source":
  - "CM"
"image": "bestiary/tokens/CM/Zikran.webp"
```
^statblock

## Familiars

Any spellcaster that can cast the [find familiar](Find-Familiar.md) spell (such as an archmage or mage) is likely to have a familiar. The familiar can be one of the creatures described in the spell or some other Tiny monster, such as a [crawling claw](Crawling-Claw.md), [imp](Imp.md), [pseudodragon](Pseudodragon.md), or [quasit](Quasit.md).

## Environment

urban
