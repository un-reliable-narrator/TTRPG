**Blurb.** There's lots of MtG content for DnD, both official and not-so official. They're compatible universes. But let's take it a step further, in the most asinine way.
Imagine this: I have a bunch of magic cards lying around, and I'm improvising a "deck of many creatures"-situation mid-game. My players draw an [Aegis Angel](https://i.ebayimg.com/images/g/1a0AAOSwcVdlXjSE/s-l1200.png). Great Card! I could probably whip up a decent boon based on the card effect. But. I'm a sucker for summons and statblocks. So.
Do I want them to summon it? YES. But how? Maybe there's an existing Aegis Angel homebrew statblock. Probably not, though. It's not [Ulamog](https://5e.tools/bestiary/ulamog-psz.html). Obviously, a generic Angel statblock. Hopefully it's not an Angel deck they're drawing from. And hopefully, they don't draw a weird card. 
But why even use magic cards, if all that matters is their card art or creature type?

Here's what no one's been asking for: A "guide" for (roughly) turning any magic creature into a statblock. Not a statblock, maybe, but at least some numbers.

## The Minimalist Method
Take the numbers that matter.
Toughness converts directly to HP. Wait, no. 

| CR / Mana Value | Hit Points |
| --------------- | ---------- |
| 1               | ~10        |
| 2               | ~40        |
| 3               | ~60        |
| 4               | ~80        |
| 5               | ~100       |
| 6               | ~120       |
| 7               | ~140       |

| Mana Value | Toughness |
| ---------- | --------- |
| 1          | 1-3       |
| 2          | 1-4       |
| 3          | 1-5       |
| 4          | 2-6       |


## The Granular Method
###### Attributes and Numbers
**Mana Value = CR.** This is the junction that determines the rest of our journey. We learn the XP and general power level. Maybe more importantly, we could infer their PB from here. Potential 
Issues: Quite a few.
- Mana Value =/= (Card) Power. Some cards can reduce their cost, and thus have low stats. 
- Low Ceiling. Aside from cost-reduction mechanics and Emrakul, magic creatures usually cap out at ~6 mana. Probably fine.

**Power = Attack Modifier.** By "attack modifier", I mean the attribute they use for their "basic" attacks. Strength or Dex, unless they're magic. Add this to their *To Hit* bonus (WITH their PB) and damage (not spells.) Also use for Spell Save DC, probably.
Issues: 
- DnD attributes cap out at +10 (30). [Daemogoth Titan](https://scryfall.com/card/stx/174/daemogoth-titan) has 11 power at 4 mana. I guess that makes it a 32 Str creature at CR4? Stronger than a Tarrasque? So that's interesting.
- How to handle multi-attack? Number of strikes equal to half the PB? Or half the power? Rounded down?
Additionally, damage dice on the attack are determined by weapon (if present) or creature size.

**Toughness.** Determines HP? Con?

**Hit Dice.** Have their type of die determined by approximated creature size.

### Example - Phyrexian Plaguelord
Phyrexian Plaguelord {3}{B}{B}
Creature — Phyrexian Carrier
{T}, Sacrifice this creature: Target creature gets -4/-4 until end of turn.
Sacrifice a creature: Target creature gets -1/-1 until end of turn.
“Even after death, a wealth of serviceable biomass remains.”  
—Phyrexian progress notes
4/4

##### **Phyrexian Plaguelord**
*Medium Humanoid (Phyrexian), Lawful Evil*
**AC** 16 (Scale)
**HP** 85 (10d8+40)
**Speed** 30 ft.

| STR | DEX | CON | WIS | INT | CHA |
| --- | --- | --- | --- | --- | --- |
| +4  | +2  | +4  | +1  | +1  | +4  |
**CR** 5

###### **Actions**
***Multiattack.*** The Plaguelord makes two Greataxe attacks.
***Greataxe.*** *Melee Attack Roll:* +8, reach 5 ft. *Hit:* 11 (1d12+4) slashing damage.
***Plague Carrier.*** *Constitution Saving Throw:* DC 15, one creature the Plaguelord can see within 60 ft. *Failure:* The target takes 36 (8d8) necrotic damage and is poisoned. *Success:* Half Damage. *Failure or Success:* The Plaguelord dies.
###### **Reactions**
***Serviceable Biomass.*** *Trigger:* An Ally the Plaguelord can see within 30 ft. dies. *Response:* Target creature the Plaguelord can see within 30 ft. of the dead ally: *Constitution Saving Throw:* DC 15. *Failure:* 2d8 necrotic damage, poisoned. *Success:* Half damage.

###### Keywords
*Keywords feel convertible to traits, but a lot would just affect the statblock "invisibly"...*
***First Strike.*** Advantage on Initiative. Advantage vs. creatures lower in initiative order?
***Lifelink.*** Heal 1HD on a successful hit.
***Vigilance.*** Advantage on opportunity attacks.
***Deathtouch.*** Save or die? 
***Haste.*** Free surprise round? Action Surge on first turn?
***Flying.*** Has fly speed.
***Double Strike.*** Multi-Attack.

***Infect.*** Attacks poison their target. (If target is already poisoned, it must save or die?)
***Wither.*** Attacks reduce target's max hp.

