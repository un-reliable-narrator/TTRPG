---
cssclasses:
- json5e-monster
tags:
- src/5e/lox
- monster/cr/8
- monster/size/medium
- monster/type/celestial
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Hastain"
---
# [Hastain](Hastain-Lox.md)
*Source: Light of Xaryxis p. 25*  

```statblock
"name": "Hastain (LoX)"
"size": "Medium"
"type": "celestial"
"alignment": "typically  Chaotic Evil"
"ac": !!int "19"
"ac_class": "glory"
"hp": !!int "82"
"hit_dice": "15d8 + 15"
"modifier": !!int "2"
"stats":
  - !!int "18"
  - !!int "15"
  - !!int "12"
  - !!int "19"
  - !!int "16"
  - !!int "24"
"speed": "30 ft., swim 30 ft."
"saves":
  - "dexterity": !!int "5"
  - "constitution": !!int "4"
  - "wisdom": !!int "6"
  - "charisma": !!int "10"
"skillsaves":
  - "name": "[Arcana](Arcana)"
    "desc": "+7"
  - "name": "[History](History)"
    "desc": "+7"
  - "name": "[Performance](skills.md#Performance)"
    "desc": "+10"
  - "name": "[Persuasion](Persuasion)"
    "desc": "+10"
"gear":
  - "[trident](trident)"
"senses": "passive Perception 13"
"languages": "Celestial, Common, Deep Speech, Draconic"
"cr": "8"
"traits":
  - "desc": "Hastain's Armor Class includes its Charisma modifier."
    "name": "Glory"
  - "desc": "Hastain can hold its breath for 1 hour."
    "name": "Hold Breath"
  - "desc": "Hastain wears a talarith."
    "name": "Special Equipment"
"actions":
  - "desc": "Hastain makes two Trident attacks."
    "name": "Multiattack"
  - "desc": "*Melee  or Ranged Weapon Attack:* +7 to hit, reach 5 ft. or range 20/60\
      \ ft., one target. *Hit:* 7 (1d6 + 4) piercing damage, or 8 (1d8 + 4) piercing\
      \ damage if used with two hands to make a melee attack, plus 3 (1d6) force\
      \ damage if Hastain is wearing its talarith."
    "name": "Trident"
  - "desc": "*Ranged Spell Attack:* +10 to hit, range 90 ft., one target. *Hit:*\
      \ 22 (5d8) damage of a type chosen by Hastain from the following list: cold,\
      \ fire, lightning, or radiant."
    "name": "Chromatic Bolt"
  - "desc": "Using its talarith, Hastain summons a duplicate of itself. The duplicate\
      \ obeys Hastain's commands and uses Hastain's statistics, except it is an unaligned\
      \ Construct that doesn't have a talarith of its own. The duplicate takes its\
      \ turn immediately after Hastain. It vanishes after 1 hour or when it is reduced\
      \ to 0 hit points."
    "name": "Summon Duplicate (Recharges after a Short or Long Rest)"
  - "desc": "Hastain casts one of the following spells, requiring no spell components\
      \ and using Charisma as the spellcasting ability (spell save DC 18):\n\n**At\
      \ will:** [light](light), [mage hand](Mage%20Hand),\
      \ [prestidigitation](prestidigitation)\n\n**2/day\
      \ each:** [dimension door](dimension-door), [phantasmal\
      \ force](phantasmal-force)\n\n**1/day each:**\
      \ [mass suggestion](mass-suggestion), [sending](sending)"
    "name": "Spellcasting (Psionics)"
"source":
  - "LoX"
"image": "bestiary/tokens/LoX/Hastain.webp"
```
^statblock