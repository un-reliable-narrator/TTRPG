---
character_name: ""
class: ""
level: 1
background: ""
race: ""
alignment: ""
xp: 0
inspiration: false
str: 15
dex: 18
con: 10
int: 16
wis: 10
cha: 10
str_mod: 2
dex_mod: 4
con_mod: 0
int_mod: 3
wis_mod: 0
cha_mod: 0
prof_bonus: 2
str_save: false
dex_save: false
con_save: false
int_save: false
wis_save: false
cha_save: false
acrobatics_prof: false
acrobatics_exp: false
animal_handling_prof: false
animal_handling_exp: false
arcana_prof: false
arcana_exp: false
athletics_prof: false
athletics_exp: false
deception_prof: false
deception_exp: false
history_prof: false
history_exp: false
insight_prof: false
insight_exp: false
intimidation_prof: false
intimidation_exp: false
investigation_prof: false
investigation_exp: false
medicine_prof: false
medicine_exp: false
nature_prof: false
nature_exp: false
perception_prof: false
perception_exp: false
perception_bonus: 0
performance_prof: false
performance_exp: false
persuasion_prof: false
persuasion_exp: false
religion_prof: false
religion_exp: false
sleight_of_hand_prof: false
sleight_of_hand_exp: false
stealth_prof: false
stealth_exp: false
survival_prof: false
survival_exp: false
ac_base: 10
ac_dex_cap: 99
ac_misc: 0
initiative_misc: 0
speed: 30
hp_max: 10
hp_current: 10
hp_temp: 0
hit_dice_total: 1d8
hit_dice_current: 1
death_success: 0
death_fail: 0
spell_ability: 0
spell_mod: 3
atk1_name: ""
atk1_ability: 1
atk1_prof: true
atk1_misc: 0
atk1_dmg: ""
atk1_mod: 4
atk2_name: ""
atk2_ability: 0
atk2_prof: false
atk2_misc: 0
atk2_dmg: ""
atk2_mod: 2
atk3_name: ""
atk3_ability: 0
atk3_prof: false
atk3_misc: 0
atk3_dmg: ""
atk3_mod: 2
atk4_name: ""
atk4_ability: 0
atk4_prof: false
atk4_misc: 0
atk4_dmg: ""
atk4_mod: 2
cp: 0
sp: 0
ep: 0
gp: 0
pp: 0
---

> [!info]- Setup (read once, then collapse this)
> This sheet needs the free **Meta Bind** community plugin to make the boxes below interactive and self-calculating. Without it, this file still opens fine but the `INPUT[...]` / `VIEW[...]` tokens render as plain text instead of live widgets.
>
> 1. Settings → Community plugins → turn on community plugins (off by default).
> 2. Browse → search **"Meta Bind"** → Install → Enable.
> 3. Reopen this note in **Reading view** or **Live Preview** (not Source mode) — that's where Meta Bind renders its widgets.
> 4. Every stat that says "auto" below recalculates the instant you change an ability score, level, or a proficiency toggle. Nothing to click or refresh.
>
> **To use this as a template for a new character:** right-click this file → *Make a copy*, rename it, and fill in the copy. (Or use the core *Templates* plugin / community *Templater* plugin to insert it into a fresh note — see the note at the bottom of this file.)

# `INPUT[text:character_name]`

| | | | |
|---|---|---|---|
| **Class** `INPUT[text:class]` | **Level** `INPUT[number:level]` | **Background** `INPUT[text:background]` | **Alignment** `INPUT[text:alignment]` |
| **Race/Species** `INPUT[text:race]` | **XP** `INPUT[number:xp]` | **Inspiration** `INPUT[toggle:inspiration]` | **Proficiency Bonus (auto)** `VIEW[ceil({level}/4)+1][math:prof_bonus]` |

---

## Ability Scores

| Ability | Score | Modifier (auto) |
|---|---|---|
| **Strength** | `INPUT[number:str]` | `VIEW[floor(({str}-10)/2)][math:str_mod]` |
| **Dexterity** | `INPUT[number:dex]` | `VIEW[floor(({dex}-10)/2)][math:dex_mod]` |
| **Constitution** | `INPUT[number:con]` | `VIEW[floor(({con}-10)/2)][math:con_mod]` |
| **Intelligence** | `INPUT[number:int]` | `VIEW[floor(({int}-10)/2)][math:int_mod]` |
| **Wisdom** | `INPUT[number:wis]` | `VIEW[floor(({wis}-10)/2)][math:wis_mod]` |
| **Charisma** | `INPUT[number:cha]` | `VIEW[floor(({cha}-10)/2)][math:cha_mod]` |

---

## Saving Throws

| Save | Proficient | Bonus (auto) |
|---|---|---|
| Strength | `INPUT[toggle:str_save]` | `VIEW[{str_mod} + ({str_save} ? {prof_bonus} : 0)]` |
| Dexterity | `INPUT[toggle:dex_save]` | `VIEW[{dex_mod} + ({dex_save} ? {prof_bonus} : 0)]` |
| Constitution | `INPUT[toggle:con_save]` | `VIEW[{con_mod} + ({con_save} ? {prof_bonus} : 0)]` |
| Intelligence | `INPUT[toggle:int_save]` | `VIEW[{int_mod} + ({int_save} ? {prof_bonus} : 0)]` |
| Wisdom | `INPUT[toggle:wis_save]` | `VIEW[{wis_mod} + ({wis_save} ? {prof_bonus} : 0)]` |
| Charisma | `INPUT[toggle:cha_save]` | `VIEW[{cha_mod} + ({cha_save} ? {prof_bonus} : 0)]` |

---

## Skills

`P` = proficient, `E` = expertise (double proficiency). Bonus recalculates automatically.

| Skill (Ability) | P | E | Bonus (auto) |
|---|---|---|---|
| Acrobatics (Dex) | `INPUT[toggle:acrobatics_prof]` | `INPUT[toggle:acrobatics_exp]` | `VIEW[{dex_mod} + (({acrobatics_prof}?1:0)+({acrobatics_exp}?1:0))*{prof_bonus}]` |
| Animal Handling (Wis) | `INPUT[toggle:animal_handling_prof]` | `INPUT[toggle:animal_handling_exp]` | `VIEW[{wis_mod} + (({animal_handling_prof}?1:0)+({animal_handling_exp}?1:0))*{prof_bonus}]` |
| Arcana (Int) | `INPUT[toggle:arcana_prof]` | `INPUT[toggle:arcana_exp]` | `VIEW[{int_mod} + (({arcana_prof}?1:0)+({arcana_exp}?1:0))*{prof_bonus}]` |
| Athletics (Str) | `INPUT[toggle:athletics_prof]` | `INPUT[toggle:athletics_exp]` | `VIEW[{str_mod} + (({athletics_prof}?1:0)+({athletics_exp}?1:0))*{prof_bonus}]` |
| Deception (Cha) | `INPUT[toggle:deception_prof]` | `INPUT[toggle:deception_exp]` | `VIEW[{cha_mod} + (({deception_prof}?1:0)+({deception_exp}?1:0))*{prof_bonus}]` |
| History (Int) | `INPUT[toggle:history_prof]` | `INPUT[toggle:history_exp]` | `VIEW[{int_mod} + (({history_prof}?1:0)+({history_exp}?1:0))*{prof_bonus}]` |
| Insight (Wis) | `INPUT[toggle:insight_prof]` | `INPUT[toggle:insight_exp]` | `VIEW[{wis_mod} + (({insight_prof}?1:0)+({insight_exp}?1:0))*{prof_bonus}]` |
| Intimidation (Cha) | `INPUT[toggle:intimidation_prof]` | `INPUT[toggle:intimidation_exp]` | `VIEW[{cha_mod} + (({intimidation_prof}?1:0)+({intimidation_exp}?1:0))*{prof_bonus}]` |
| Investigation (Int) | `INPUT[toggle:investigation_prof]` | `INPUT[toggle:investigation_exp]` | `VIEW[{int_mod} + (({investigation_prof}?1:0)+({investigation_exp}?1:0))*{prof_bonus}]` |
| Medicine (Wis) | `INPUT[toggle:medicine_prof]` | `INPUT[toggle:medicine_exp]` | `VIEW[{wis_mod} + (({medicine_prof}?1:0)+({medicine_exp}?1:0))*{prof_bonus}]` |
| Nature (Int) | `INPUT[toggle:nature_prof]` | `INPUT[toggle:nature_exp]` | `VIEW[{int_mod} + (({nature_prof}?1:0)+({nature_exp}?1:0))*{prof_bonus}]` |
| Perception (Wis) | `INPUT[toggle:perception_prof]` | `INPUT[toggle:perception_exp]` | `VIEW[{wis_mod} + (({perception_prof}?1:0)+({perception_exp}?1:0))*{prof_bonus}][math:perception_bonus]` |
| Performance (Cha) | `INPUT[toggle:performance_prof]` | `INPUT[toggle:performance_exp]` | `VIEW[{cha_mod} + (({performance_prof}?1:0)+({performance_exp}?1:0))*{prof_bonus}]` |
| Persuasion (Cha) | `INPUT[toggle:persuasion_prof]` | `INPUT[toggle:persuasion_exp]` | `VIEW[{cha_mod} + (({persuasion_prof}?1:0)+({persuasion_exp}?1:0))*{prof_bonus}]` |
| Religion (Int) | `INPUT[toggle:religion_prof]` | `INPUT[toggle:religion_exp]` | `VIEW[{int_mod} + (({religion_prof}?1:0)+({religion_exp}?1:0))*{prof_bonus}]` |
| Sleight of Hand (Dex) | `INPUT[toggle:sleight_of_hand_prof]` | `INPUT[toggle:sleight_of_hand_exp]` | `VIEW[{dex_mod} + (({sleight_of_hand_prof}?1:0)+({sleight_of_hand_exp}?1:0))*{prof_bonus}]` |
| Stealth (Dex) | `INPUT[toggle:stealth_prof]` | `INPUT[toggle:stealth_exp]` | `VIEW[{dex_mod} + (({stealth_prof}?1:0)+({stealth_exp}?1:0))*{prof_bonus}]` |
| Survival (Wis) | `INPUT[toggle:survival_prof]` | `INPUT[toggle:survival_exp]` | `VIEW[{wis_mod} + (({survival_prof}?1:0)+({survival_exp}?1:0))*{prof_bonus}]` |

**Passive Perception (auto):** `VIEW[10 + {perception_bonus}]`

---

## Combat

| Armor Class (auto) | Initiative (auto) | Speed |
|---|---|---|
| `VIEW[{ac_base} + min({dex_mod},{ac_dex_cap}) + {ac_misc}]` | `VIEW[{dex_mod} + {initiative_misc}]` | `INPUT[number:speed]` ft |

AC inputs — base `INPUT[number:ac_base]` (10 unarmored, or your armor's base AC), Dex cap `INPUT[number:ac_dex_cap]` (99 = no cap, 2 = medium armor, 0 = heavy armor), misc/shield/other `INPUT[number:ac_misc]`.
Initiative misc bonus (feats, etc.): `INPUT[number:initiative_misc]`

| Max HP | Current HP | Temp HP | Hit Dice |
|---|---|---|---|
| `INPUT[number:hp_max]` | `INPUT[number:hp_current]` | `INPUT[number:hp_temp]` | `INPUT[text:hit_dice_total]` (`INPUT[number:hit_dice_current]` left) |

**Death Saves** — Successes: `INPUT[number:death_success]` / 3 Failures: `INPUT[number:death_fail]` / 3

### Attacks / Weapons

Set the ability each weapon uses (STR or DEX — for finesse/ranged weapons), whether you're proficient, and any misc bonus (magic weapon, etc). Attack bonus and the ability modifier for damage recalculate automatically.

| Weapon                  | Ability                                                         | Prof                      | Misc                      | Attack Bonus (auto)                                                 | Ability Mod for Damage (auto)                                    | Damage / Type          |
| ----------------------- | --------------------------------------------------------------- | ------------------------- | ------------------------- | ------------------------------------------------------------------- | ---------------------------------------------------------------- | ---------------------- |
| `INPUT[text:atk1_name]` | `INPUT[inlineSelect(option(0,STR),option(1,DEX)):atk1_ability]` | `INPUT[toggle:atk1_prof]` | `INPUT[number:atk1_misc]` | `VIEW[{atk1_mod} + ({atk1_prof} ? {prof_bonus} : 0) + {atk1_misc}]` | `VIEW[{atk1_ability}==0 ? {str_mod} : {dex_mod}][math:atk1_mod]` | `INPUT[text:atk1_dmg]` |
| `INPUT[text:atk2_name]` | `INPUT[inlineSelect(option(0,STR),option(1,DEX)):atk2_ability]` | `INPUT[toggle:atk2_prof]` | `INPUT[number:atk2_misc]` | `VIEW[{atk2_mod} + ({atk2_prof} ? {prof_bonus} : 0) + {atk2_misc}]` | `VIEW[{atk2_ability}==0 ? {str_mod} : {dex_mod}][math:atk2_mod]` | `INPUT[text:atk2_dmg]` |
| `INPUT[text:atk3_name]` | `INPUT[inlineSelect(option(0,STR),option(1,DEX)):atk3_ability]` | `INPUT[toggle:atk3_prof]` | `INPUT[number:atk3_misc]` | `VIEW[{atk3_mod} + ({atk3_prof} ? {prof_bonus} : 0) + {atk3_misc}]` | `VIEW[{atk3_ability}==0 ? {str_mod} : {dex_mod}][math:atk3_mod]` | `INPUT[text:atk3_dmg]` |
| `INPUT[text:atk4_name]` | `INPUT[inlineSelect(option(0,STR),option(1,DEX)):atk4_ability]` | `INPUT[toggle:atk4_prof]` | `INPUT[number:atk4_misc]` | `VIEW[{atk4_mod} + ({atk4_prof} ? {prof_bonus} : 0) + {atk4_misc}]` | `VIEW[{atk4_ability}==0 ? {str_mod} : {dex_mod}][math:atk4_mod]` | `INPUT[text:atk4_dmg]` |

Add the "Ability Mod for Damage" value to the dice you write in the Damage column (e.g. `1d8` weapon + mod `3` → roll `1d8+3`).

---

## Spellcasting

Spellcasting Ability: `INPUT[inlineSelect(option(0,INT),option(1,WIS),option(2,CHA)):spell_ability]` (0 = INT, 1 = WIS, 2 = CHA)

| Spell Ability Mod (auto) | Spell Save DC (auto) | Spell Attack Bonus (auto) |
|---|---|---|
| `VIEW[{spell_ability}==0 ? {int_mod} : ({spell_ability}==1 ? {wis_mod} : {cha_mod})][math:spell_mod]` | `VIEW[8 + {prof_bonus} + {spell_mod}]` | `VIEW[{prof_bonus} + {spell_mod}]` |

### Spell Slots

| Level | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 |
|---|---|---|---|---|---|---|---|---|---|
| Total | | | | | | | | | |
| Used | | | | | | | | | |

*(Fill in by hand — slot progression differs by class/multiclass; see the free rules for your class's table.)*

### Spells Known / Prepared

-
-
-

---

## Equipment

-
-
-

**Currency:** CP `INPUT[number:cp]` · SP `INPUT[number:sp]` · EP `INPUT[number:ep]` · GP `INPUT[number:gp]` · PP `INPUT[number:pp]`

---

## Features, Traits & Proficiencies

-
-
-

## Personality Traits / Ideals / Bonds / Flaws

-
-
-

---

> [!tip]- Using this file as a template
> **Simplest:** right-click this file in the file explorer → *Make a copy* → rename it to your character's name → fill it in. No extra plugin needed.
>
> **Nicer:** enable the core **Templates** plugin (Settings → Core plugins), point it at the folder containing this file, then `Ctrl/Cmd+P` → *Templates: Insert template* into a new empty note.
>
> **Best (optional):** install the community **Templater** plugin instead of core Templates — it can prompt you for the character name/class at creation time and auto-fill the title, but that's an extra layer on top of what's needed for the calculations themselves.
---
atk1_mod: ""
atk2_mod: ""
atk3_mod: ""
atk4_mod: ""
spell_mod: ""
---
