---
cssclasses:
  - json5e-monster
tags:
  - src/5e/toa
  - monster/cr/4
  - monster/environment/underdark
  - monster/environment/forest
  - monster/environment/desert
  - monster/size/medium
  - monster/type/monstrosity/shapechanger-yuan-ti
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Fenthaza
---
# [Fenthaza](Fenthaza-toa.md)
*Source: Tomb of Annihilation p. 113*  

![](https://5e.tools/img/bestiary/ToA/Fenthaza.webp)

```statblock
"name": "Fenthaza (ToA)"
"size": "Medium"
"type": "monstrosity"
"subtype": "shapechanger, yuan-ti"
"alignment": "Neutral Evil"
"ac": !!int "14"
"ac_class": "natural armor"
"hp": !!int "71"
"hit_dice": "13d8 + 13"
"modifier": !!int "2"
"stats":
  - !!int "16"
  - !!int "14"
  - !!int "13"
  - !!int "14"
  - !!int "12"
  - !!int "16"
"speed": "30 ft."
"saves":
  - "wisdom": !!int "3"
  - "charisma": !!int "5"
"skillsaves":
  - "name": "[Deception](skills.md#Deception)"
    "desc": "+5"
  - "name": "[Stealth](skills.md#Stealth)"
    "desc": "+4"
"damage_immunities": "poison"
"condition_immunities": "[poisoned](conditions.md#Poisoned)"
"senses": "[Darkvision](senses.md#Darkvision) 120 ft. (penetrates magical\
  \ darkness), passive Perception 11"
"languages": "Abyssal, Common, Draconic"
"cr": "4"
"traits":
  - "desc": "Fenthaza can use its action to polymorph into a Medium snake or\
      \ back into its true form. Its statistics are the same in each form. Any\
      \ equipment it is wearing or carrying isn't transformed. If it dies, it\
      \ stays in its current form."
    "name": "Shapechanger"
  - "desc": "The first time Fenthaza hits with a melee attack on its turn, it\
      \ can deal an extra 16 (3d10) necrotic damage to the target."
    "name": "Death Fangs (2/Day)"
  - "desc": "Fenthaza has advantage on saving throws against spells and other\
      \ magical effects."
    "name": "Magic Resistance"
  - "desc": "Fenthaza's innate spellcasting ability is Charisma (spell save DC\
      \ 13). Fenthaza can innately cast the following spells, requiring no\
      \ material components:\n\n**At will:** [animal\
      \ friendship](Animal-Friendship.md) (snakes only)\n\n**3/day:**\
      \ [suggestion](Suggestion.md)"
    "name": "Innate Spellcasting (Yuan-ti Form Only)"
  - "desc": "Fenthaza is a 6th-level spellcaster. Its spellcasting ability is\
      \ Charisma (spell save DC 13, +5 to hit with spell attacks). It regains\
      \ its expended spell slots when it finishes a short or long rest. It\
      \ knows the following warlock spells:\n\n**Cantrips (at will):** [chill\
      \ touch](Chill-Touch.md), [eldritch blast](Eldritch-Blast.md) (range 300\
      \ ft., +3 bonus to each damage roll), [mage hand](Mage-Hand.md),\
      \ [message](Message.md), [poison spray](Poison-Spray.md),\
      \ [prestidigitation](Prestidigitation.md)\n\n**1st-3rd level (2 slots):**\
      \ [arms of Hadar](Arms-of-Hadar.md), [darkness](Darkness.md),\
      \ [fear](Fear.md), [hex](Hex.md), [hold person](Hold-Person.md), [hunger\
      \ of Hadar](Hunger-of-Hadar.md), [witch bolt](Witch-Bolt.md)"
    "name": "Spellcasting (Yuan-ti Form Only)"
"actions":
  - "desc": "Fenthaza makes one constrict attack and one scimitar attack."
    "name": "Multiattack (Yuan-ti Form Only)"
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 10 ft., one target. *Hit:*\
      \ 10 (2d6 + 3) bludgeoning damage, and the target is\
      \ [grappled](conditions.md#Grappled) (escape DC 14) if it is a Large or\
      \ smaller creature. Until this grapple ends, the target is\
      \ [restrained](conditions.md#Restrained), and Fenthaza can't constrict\
      \ another target."
    "name": "Constrict"
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one target. *Hit:*\
      \ 6 (1d6 + 3) slashing damage."
    "name": "Scimitar (Yuan-ti Form Only)"
  - "desc": "Fenthaza taps into the nightmares of a creature it can see within\
      \ 60 feet of it and creates an illusory, immobile manifestation of the\
      \ creature's deepest fears, visible only to that creature. The target\
      \ must make a DC 13 Intelligence saving throw. On a failed save, the\
      \ target takes 11 (2d10) psychic damage and is\
      \ [frightened](conditions.md#Frightened) of the manifestation, believing\
      \ it to be real. Fenthaza must concentrate to maintain the illusion (as\
      \ if concentrating on a spell), which lasts for up to 1 minute and can't\
      \ be harmed. The target can repeat the saving throw at the end of each of\
      \ its turns, ending the illusion on a success, or taking 11 (2d10)\
      \ psychic damage on a failure."
    "name": "Invoke Nightmare (Recharges after a Short or Long Rest)"
"source":
  - "ToA"
"image": "bestiary/tokens/ToA/Fenthaza.webp"
```
^statblock

## Chameleon Skin

Fenthaza has advantage on Dexterity (Stealth) checks made to hide.

## Shed Skin (1/Day)

Fenthaza can shed its skin as a bonus action to free itself from a grapple, shackles, or other restraints. If Fenthaza spends 1 minute eating its shed skin, it regains hit points equal to half its hit point maximum.

## Environment

underdark, forest, desert
