# Character Creation

Ask your GM about the setting, and think about a character, let your imagination go wild.

Pick _Name_, Age, then describe the _Appearance_ (Physique, Skin, Hair, Face, Clothing, Speech, etc),
Chose its _Personality_ (Virtues, Traits, Vices, Flaws, Patron, Deity, Vow, etc)
Finally describe its _Past and Background_.

Then use these to build the **Attributes**, **Stats**, **Features** of your Character.

Later in the game, use it for role-play.

<details markdown="block"><summary>Expand to see <i>Sparrow The Spell Sorcerer</i>'s description</summary>
They call him Sparrow - The Spellsword Sorcerer. He stopped counting summers after his fortieth, though his body never let him forget the passing years. Lanky and weathered like driftwood, carved by battle and time, his skin bears more scars than a map holds secrets. One eye is no longer flesh and blood but a gleaming gemstone. At his side hangs a trusty sword, though rust clings to its edge like barnacles to a hull. His garments reek of filth and age: rancid cloth, cracked leather boots, and a voice so raspy you'd swear it came from the throat of the sea itself. In the lawless corners of the world, such qualities don’t breed suspicion, they earn trust. He is a devoted servant of <i>Çel Ede</i>, god of the wind. In return for his daily prayers, and the occasional sermons, he was granted the magic of the winds at his call. When gold glints on a table, his eye sharpens like a hawk’s. His greed runs as deep as the ocean, vast and bottomless, rivaling even a Kraken’s hunger. It was just half a year past when he lost it all, his ship, his crew. Taken by a monster so terrible that those few who survive its wrath speak no word of it. They do not name it. They do not sail again.
</details>

## Attributes

### Experience `XP`

General experience of the world. This is set by the GM, and used as the currency for **Attributes** and **Stats**. One way of progression is to gain experience during the game.

### Strength `STR`

Physical strength, might, toughness, fortitude, constitution, athletics, muscles, health etc.

It can be depleted, when it hits 0, the Character is [Dead](./conditions.md#dead). Recovering it takes time and resources.

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

### Mana Points `MP`

Ability to manipulate the world beyond normal means. This is the main Currency used in Magic. Recovering it takes time (about 1 mana / hour) or resources. (_For other genres than High Fantasy this can be any genre specific point_)

### `Speed`

Defines the Speed of [Movements](todo), like running, climbing, jumping, swimming, etc.

On a grid the number represents the [Spaces](TODO), its about 1.5m or 5 feet per point.

- Suggestions for the GM and players, but its up to them to decide:
  - Climbing, Swimming is [Slow](./conditions.md#slowed), it is half the **Speed**, unless the character able to do it fast.
  - Vertical Jump distant is equal to the **Speed**, further jumping could require [STR](#strength-str) or [DEX](#dexterity-dex) check depending on the situation, the Character's abilities and role-play.
  - Horizontal Jump distance is low, but it depends on the character.

### `Size`

Defines the Size of the Character. Some examples to help:

0. Tiny - Bug, Mice, Rat, Snake, Dagger
1. Very Small - Average Cat, Dog, Wolf Pup, Pixie, Tower Shield
2. Small - Average Halfling, Kobold, Goblin
3. Normal - Average Human, Elf, Drow
4. Large - Average Horse, Ox, Minotaur, Orc
5. Extra Large - Average Troll, Ogre, Giant Spider
6. Huge - Giant Bear, Juvenile Dragon
7. Massive - Stone Golem, Hill Giant, Giant Mammoth
8. Enormous - Average Adult Dragon, Kraken, Walking Cathedral
9. Titanic - Ancient Dragon, Floating Fortress
10. Gigantic - World Serpent, Living Mountain, Celestial Avatar

### Calculating Attributes and Stats

Each addition to an [Attribute](#attributes) or [Stat](#stats) cost 1, 2, 3, 4, ... [XP](#experience-xp).

- The **Attributes** [STR](#strength-str), [DEX](#dexterity-dex), and [WIL](#will-power-wil) are starting on 10, and can be decreased for +1 [XP](#experience-xp) for each decrement, until 1.
  - To increase an [Attribute](#attributes) from 10 to 15 the cost is `1+2+3+4+5 = 15` [XP](#experience-xp).
  - To decrease an [Attribute](#attributes) from 10 to 5 the player gains `+5` [XP](#experience-xp).
- The **Stats** are starting on 0, and cannot be decreased further.
  - To increase an [Stat](#stats) from 3 to 6 the cost is `4+5+6 = 15` [XP](#experience-xp).

The player can decide to not spent [XP](experience-xp) immediately, it can be allocated later. However they cannot decreased any [Attributes](#attributes) or [Stats](#stats) to gain back [XP](#experience-xp). _(On special occasion the GM can create a situation to "Rebuild" a character, but its entirely up to the GM and the table to decide)_

<details markdown="block"><summary>Table for quick calculation:</summary>

|   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
|...| -3| -2| -1|  0|  1|  2|  3|  4|  5|  6|  7|  8|  9| 10|...|
|...| +3| +2| +1|  0| -1| -3| -6|-10|-15|-21|-28|-36|-45|-55|...|

</details>

<details markdown="block"><summary>For Math Nerds:</summary>

- This is the [Triangual Number Series](https://oeis.org/A000217)
  - `XP_cost = STAT * (STAT+1) / 2`
  - `XP_cost = (ATTR-10) * (ATTR-9) /2`

</details>

<details markdown="block"><summary>Expand to see <i>Sparrow The Spell Sorcerer</i>'s build</summary>

|                          |                       |                       |                        |
|---                       |---                    |---                    |---                     |
| [XP](#experience-xp)     | [STR](#strength-str)  | [DEX](#dexterity-dex) | [WIL](#will-power-wil) |
| 60/0                     | 14/14                 | 15/15                 | 9/9                    |
| [HP](#hit-protection-hp) | [MP](#mana-points-mp) | [SPEED](#speed)       | [SIZE](#size)          |
| 4/4                      | 4/4                   | 4/4                   | 3 Normal               |

</details>

## Features

A list of features of the Character for quick lookup. TODO

## Inventory: Equipment, Items

Items in the character's possession (inventory)

### In hands `H`

Each hand can handle 1 Item. (A short-sword and a shield, a two-handed Great-Axe, etc)

### Within immediate reach `O`

Limited number of items in direct reach. (Potions in a tool-belt, dagger in boots, magically absorbed items, etc)

### Not in direct reach `X`

Limited number of items, not in direct reach. (A book in the backpack, apples in a sack, etc)

### Safekeep `?`

Items left somewhere.

### Money/Wealth `gp`

Character's Wealth or Currency

## Notes

Character's knowledge of the World (NPCs, Points of interests, etc)
