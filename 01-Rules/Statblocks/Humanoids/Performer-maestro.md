---
cssclasses:
  - json5e-monster
tags:
  - src/5e/xmm
  - monster/cr/6
  - monster/environment/any
  - monster/size/small-or-medium
  - monster/type/humanoid
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Performer Maestro
---
# [Performer Maestro](Performer-Maestro.md)
*Source: Monster Manual (2024) p. 237*  

> [!multi-column]
>> ![|200](https://www.dndbeyond.com/avatars/thumbnails/47139/144/1000/1000/638741964502968946.png)
>
>> Maestros are headlining performers who enjoy considerable renown. They might be theaters' marquee actors, astonishing daredevils, or jesters experienced at entertaining fickle royals. Some share their techniques with apprentices, while others jealously guard their secrets.

## Performers

*Artists and Entertainers*

- **Habitat.** Any  
- **Treasure.** [Implements](random-magic-items-implements.md), Individual  

From royal courts to village squares, skilled entertainers hone their talents and delight audiences. Some travel far, sharing tales and demonstrating mysterious arts. Others serve in the courts and theaters of great nations, cultivating celebrity and navigating the whims of patrons. Many hone professional secrets and magical flourishes, striving to make their performances truly unforgettable.

Use the following list of entertainers and roles to inspire the performers in your adventures:
> [!multi-column]
>
>> 1. Acrobat
>> 2. Actor
>> 3. Aerialist
>> 4. Animal trainer
>> 5. Athlete
>> 6. Burlesque artist
>> 7. Busker
>> 8. Circus performer
>> 9. Comedian
>> 10. Contortionist
>> 11. Dancer
>> 12. Daredevil
>> 13. Jester
>> 14. Juggler
>> 15. Magician
>
>> 16. Mentalist
>> 17. Mime
>> 18. Minstrel
>> 19. Mourner
>> 20. Oral Historian
>> 21. Poet
>> 22. Puppeteer
>> 23. Ritualist
>> 24. Stage Fighter
>> 25. Storyteller
>> 26. Throat Singer
>> 27. Town Crier
>> 28. Trick Rider
>> 29. Vocalist
>> 30. Wrestler


> [!quote] A quote from Tindal, Carnival Barker  
> 
> *Welcome, one! Welcome, all! Welcome to the short, and welcome to the tall! Welcome angels, welcome fiends, welcome to all from walks between! Welcome to the Carnival!*


```statblock
"name": "Performer Maestro (XMM)"
"size": "Small or Medium"
"type": "humanoid"
"alignment": "Neutral"
"ac": !!int "18"
"hp": !!int "110"
"hit_dice": "17d8 + 34"
"modifier": !!int "7"
"stats":
  - !!int "12"
  - !!int "18"
  - !!int "14"
  - !!int "13"
  - !!int "14"
  - !!int "19"
"speed": "30 ft."
"saves":
  - "dexterity": !!int "7"
  - "charisma": !!int "7"
"skillsaves":
  - "name": "[Acrobatics](Acrobatics)"
    "desc": "+10"
  - "name": "[Athletics](Athletics)"
    "desc": "+4"
  - "name": "[Perception](Perception)"
    "desc": "+5"
  - "name": "[Performance](skills.md#Performance)"
    "desc": "+10"
  - "name": "[Stealth](Stealth)"
    "desc": "+7"
"gear":
  - "[rapier](rapier)"
"senses": "passive Perception 15"
"languages": "Common plus one other language"
"cr": "6"
"actions":
  - "desc": "The performer makes three Rapier attacks."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +7, reach 5 ft. *Hit:* 8 (1d8 + 4) Piercing\
      \ damage plus 7 (2d6) Psychic damage."
    "name": "Rapier"
  - "desc": "*Wisdom Saving Throw:* DC 15, each creature in a 20-foot-radius [Sphere](sphere-area-of-effect)\
      \ centered on a point within 120 feet. *Failure:* 20 (3d10 + 4) Psychic damage,\
      \ and the target has the [Charmed](conditions.md#Charmed)\
      \ condition until the end of the performer's next turn. *Success:* Half damage\
      \ only."
    "name": "Beguiling Song"
  - "desc": "The performer casts one of the following spells, requiring no Material\
      \ components and using Charisma as the spellcasting ability (spell save DC 15):\n\
      \n**At will:** [Minor Illusion](minor-illusion),\
      \ [Prestidigitation](prestidigitation)\n\n**1/day:**\
      \ [Tasha's Hideous Laughter](tasha's-hideous-laughter)\
      \ (level 3 version)"
    "name": "Spellcasting"
"source":
  - "XMM"
"image": "bestiary/tokens/XMM/Performer Maestro.webp"
```
^statblock

## Environment

any