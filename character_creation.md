# Character Creation

Ask your GM about the setting, and think about a character, let your imagination go wild.

Pick _Name_, Age, then describe the _Appearance_ (Physique, Size, Body, Skin, Hair, Face, Clothing, Speech, etc),
Chose its _Personality_ (Virtues, Traits, Vices, Flaws, Patron, Deity, Vow, etc)
Finally describe its _Past and Background_.

Then use these to build the **Attributes**, **Stats**, **Features** of your Character.

Later in the game, use it for role-play.

<details markdown="block"><summary>Expand to see <i>Sparrow The Spell Sorcerer</i>'s description</summary>
They call him Sparrow - The Spellsword Sorcerer. He stopped counting summers after his fortieth, though his body never let him forget the passing years. Lanky and weathered like driftwood, carved by battle and time, his skin bears more scars than a map holds secrets. One eye is no longer flesh and blood but a gleaming gemstone. At his side hangs a trusty sword, though rust clings to its edge like barnacles to a hull. His garments reek of filth and age: rancid cloth, cracked leather boots, and a voice so raspy you'd swear it came from the throat of the sea itself. In the lawless corners of the world, such qualities don’t breed suspicion, they earn trust. He is a devoted servant of <i>Çel Ede</i>, god of the wind. In return for his daily prayers, and the occasional sermons, he was granted the magic of the winds at his call. When gold glints on a table, his eye sharpens like a hawk’s. His greed runs as deep as the ocean, vast and bottomless, rivaling even a Kraken’s hunger. It was just half a year past when he lost it all, his ship, his crew. Taken by a monster so terrible that those few who survive its wrath speak no word of it. They do not name it. They do not sail again.
</details>

## Experience `XP`

General experience of the world. This is set by the GM, and used as the currency for [Attributes](#attributes) and [Stats](#stats). One way of progression is to gain experience during the game.

The base 'Level 1' adventurer should be around **50 XP**.

## Attributes

### Strength `STR`

Physical strength, might, toughness, fortitude, constitution, athletics, muscles, health etc.

It can be depleted, when it hits 0, the Character is on the [Death's Door](TODO). Recovering it takes time and resources.

### Dexterity `DEX`

Agility, poise, acrobatics, sneakiness, muscle memory, slight of hand, maneuverability, quickness etc.

It can be depleted, when it hits 0, the Character is [Immobile](./conditions.md#immobile), unable to move any muscle. Recovering it takes time and resources.

### Will Power `WIL`

Mental force, knowledge, persuasion, interrogation, charm, intimidation, provocation, manipulation, etc.

It can be depleted, when it hits 0, the Character is [Incapacitated](./conditions.md#incapacitated) out of their mind and unable to use their senses or communicate in any way. Recovering it takes time and resources.

## Stats

### Hit Protection `HP`

Ability to ignore pain, and avoid fatal harm.

When the character damaged in combat this stat depletes. However it is not lost for very long, resting a bit, drinking water and eating will restores all **HP**. If it is reduced under 0, the rest of the damage will the deplete the main [Attributes](#attributes) depending on the type of the [Defence](TODO) used.

### `Speed`

Defines the Speed of [Movements](todo), like running, climbing, jumping, swimming, etc.

On a grid the number represents the [Spaces](TODO), its about 1.5m or 5 feet per point.

An average Creature's **Speed** is usually around 4.

- Suggestions for the GM and players, but its up to them to decide:
  - Climbing, Swimming is [Slow](./conditions.md#slowed), it is half the **Speed**, unless the character able to do it fast.
  - Vertical Jump distant is equal to the **Speed**, further jumping could require [STR](#strength-str) or [DEX](#dexterity-dex) check depending on the situation, the Character's abilities and role-play.
  - Horizontal Jump distance is low, but it depends on the character.

### Special `SP`

Ability to manipulate the world beyond normal means. For Magic, this is the main Currency, think of it like this is the Mana. For a Brute it can represents it's inner Beast Power, for a Technician it can represents its ability to invent, for a Cleric it can represents its Faith Points, etc.

Recovering it takes time (about 1 **SP** / hour) or resources like mana potions. Or It can be restored by any means the Character background could validate (GM should agree)

It's Premium, [Features](#features) using it greatly improve success rate and/or gave special bonuses for the character.

## Calculating Attributes and Stats

Each addition to an [Attribute](#attributes) or [Stat](#stats) cost 1, 2, 3, 4, ... [XP](#experience-xp).

- To increase an [Attribute](#attributes) or [Stat](#stats)
  - from 0 to 5 the cost is `1+2+3+4+5 = 15` [XP](#experience-xp)
  - from 3 to 6 the cost is `4+5+6 = 15` [XP](#experience-xp)
  - from 14 to 15 the cost is `15` [XP](#experience-xp)

The player can decide to not spend the [XP](experience-xp) immediately, it can be saved and allocated later any time. However they cannot decreased any [Attributes](#attributes) or [Stats](#stats) to gain back [XP](#experience-xp). Except if they have some kind of special mean to do so, presented by the GM or the Character has a means to do it. (GM should agree)

<details markdown="block"><summary>Table for quick calculation:</summary>

|   |   |   |   |    |    |    |    |    |    |    |    |    |    |     |     |     |     |     |     |     |     |
|---|---|---|---|----|----|----|----|----|----|----|----|----|----|-----|-----|-----|-----|-----|-----|-----|-----|
| 0 | 1 | 2 | 3 |  4 |  5 |  6 |  7 |  8 |  9 | 10 | 11 | 12 | 13 |  14 |  15 |  16 |  17 |  18 |  19 |  20 | ... |
| 0 | 1 | 3 | 6 | 10 | 15 | 21 | 28 | 36 | 45 | 55 | 66 | 78 | 91 | 105 | 120 | 136 | 153 | 171 | 190 | 210 | ... |

</details>

<details markdown="block"><summary>For Math Nerds:</summary>

- This is the [Triangual Number Series](https://oeis.org/A000217)
- The formula: `XP_cost = ATTRorSTAT * (ATTRorSTAT+1) / 2`

</details>

<details markdown="block"><summary>Expand to see <i>Sparrow The Spell Sorcerer</i>'s build</summary>

> [XP](#experience-xp) 50/0                                 e

|                          |                       |                        |
|---                       |---                    |---                     |
| [STR](#strength-str)     | [DEX](#dexterity-dex) | [WIL](#will-power-wil) |
| 4/4                      | 5/5                   | 3/3                    |
| [HP](#hit-protection-hp) | [SPEED](#speed)       | [SP](#special-sp)      |
| 3/3                      | 4/4                   | 2/2                    |

</details>

## Features

A list of features of the Character can do, and passive conditions, for quick lookup. When a Character takes an [Actions](./core_rules.md#taking-an-action) it can use these features.

This list should contain the Extra Features/Actions that is the Character speciality. Normal Actions/Features are not necessary to include here. Example: Attacking with fist: NOP, Casting a Spell: YEP, Using Martial art manuver: Yep, Kicking the enemy: NOP, etc

### Creating a Feature

Based on the [Background](#character-creation) of the Character list create features, like offensive/defensive/utility actions and passives.

- **Name of the Offensive Feature**: Description of the feature
  - ([Attributes](#attributes) which can used with the feature) -> (Target's [Attributes](#attributes) which can be used for defence)
    - The conditions it inflicts, with the duration and description
- **Passive/Defensive/Utility Feature**: Description of the feature, with the conditions it inflicts
  - Description of the conditions

<details markdown="block"><summary>Expand to see <i>Sparrow The Spell Sorcerer</i>'s features</summary>

- **Seasoned in crime**: When dealing with Shady Characters, Sparrow gains 1 Advantage on Social Interaction rolls. (Influence, Insight, Intimidation, etc). He has 1 Disadvantage when dealing with Honest Character's with Good Aliment.

</details>

## Inventory: Equipment, Items

Items in the character's possession (inventory). When the Character takes an [Actions](./core_rules.md#taking-an-action) they usually use an Object, and that determines the [Object Dice](/core_rules.md#object-dice)

### In hands `◯`

Each hand can handle 1 Item. (A short-sword and a shield, a two-handed Great-Axe, etc)

### Within immediate reach `⦿`

Limited number of items in direct reach. (Potions in a tool-belt, dagger in boots, magically absorbed items, etc)

### Not in direct reach `⧇`

Limited number of items, not in direct reach. (A book in the backpack, apples in a sack, etc)

### Safekeep `?`

Items left somewhere.

### Money/Wealth `¤`

Character's Wealth or Currency

## Notes

Character's knowledge of the World (NPCs, Points of interests, etc)
