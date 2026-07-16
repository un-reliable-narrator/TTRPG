---
tags:
  - spell
school: Conjuration
spell_level: "2"
---
#### Find Steed

*Level 2 Conjuration (Paladin)*

**Casting Time:** Action
**Range:** 30 feet
**Components:** V, S
**Duration:** Instantaneous

You summon an otherworldly being that appears as a loyal steed in an unoccupied space of your choice within range. This creature uses the **Otherworldly Steed** stat block. If you already have a steed from this spell, the steed is replaced by the new one.

The steed resembles a Large, rideable animal of your choice, such as a horse, a camel, a dire wolf, or an elk. Whenever you cast the spell, choose the steed's creature type — Celestial, Fey, or Fiend which determines certain traits in the stat block.

***Combat.*** The steed is an ally to you and your allies. In combat, it shares your Initiative count, and it functions as a controlled mount while you ride it (as defined in the rules on mounted combat). If you have the Incapacitated condition, the steed takes its turn immediately after yours and acts independently, focusing on protecting you.

***Disappearance of the Steed.*** The steed disappears if it drops to 0 Hit Points or if you die. When it disappears, it leaves behind anything it was wearing or carrying. If you cast this spell again, you decide whether you summon the steed that disappeared or a different one.

***Using a Higher-Level Spell Slot.*** Use the spell slot's level for the spell's level in the stat block.

![[Otherworldly Steed|no-title]]


##### [Otherworldly Steed](Otherworldly-Steed.md)
*Source: Player's Handbook (2024) p. 273*  

```statblock
"name": "Otherworldly Steed (XPHB)"
"size": "Large"
"alignment": "Neutral"
"ac_class": "10 + 1 per spell level"
"modifier": !!int "1"
"stats":
  - !!int "18"
  - !!int "12"
  - !!int "14"
  - !!int "6"
  - !!int "12"
  - !!int "8"
"speed": "60 ft., fly 60 ft. (requires level 4+ spell)"
"senses": "passive Perception 11"
"languages": "telepathy 1 mile (works only with you)"
"traits":
  - "desc": "When you regain Hit Points from a level 1+ spell, the steed regains the\
      \ same number of Hit Points if you're within 5 feet of it."
    "name": "Life Bond"
"actions":
  - "desc": "*Melee Attack Roll:* Bonus equals your spell attack modifier, reach 5\
      \ ft. *Hit:* 1d8 + the spell's level of Radiant (Celestial), Psychic (Fey),\
      \ or Necrotic (Fiend) damage."
    "name": "Otherworldly Slam"
"bonus_actions":
  - "desc": "*Wisdom Saving Throw:* DC equals your spell save DC, one creature within\
      \ 60 feet the steed can see. *Failure:* The target has the [Frightened](conditions.md#Frightened)\
      \ condition until the end of your next turn."
    "name": "Fell Glare (Fiend Only; Recharges after a Long Rest)"
  - "desc": "The steed teleports, along with its rider, to an unoccupied space of\
      \ your choice up to 60 feet away from itself."
    "name": "Fey Step (Fey Only; Recharges after a Long Rest)"
  - "desc": "One creature within 5 feet of the steed regains a number of Hit Points\
      \ equal to 2d8 + the spell's level."
    "name": "Healing Touch (Celestial Only; Recharges after a Long Rest)"
"source":
  - "XPHB"
"image": "bestiary/tokens/XPHB/Otherworldly Steed.webp"
```
^statblock