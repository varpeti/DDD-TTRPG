# Core Rules

## Advantage and Disadvantage

**Advantage** and **Disadvantage** is expressed by their quantity. If you have one or multiple **Advantage** and one or multiple **Disadvantage**, take their difference.

- **Rolling with X Advantage**: You can chose X dice when you roll, you can chose the same die multiple times. For each chosen die roll an extra die, and take the highest result.
- **Rolling with X Disadvantage**: You can chose X dice when you roll, you can chose the same die multiple times. For each chosen die roll an extra die, and take the lowest result.

<details markdown="block"><summary>Example</summary>

Bob has 5 Advantage on his next attack against the Giant Spider with his Twin Dagger. He has 1 Disadvantage. Ha has a penalty die -1d4 for this roll as well. He calculates that he has 3 Advantage, and he chooses the [Base Die](#base-die) twice, the [Object Die (Twin dagger 2d4)](#object-dice) and the penalty dice. He rolls:

- Base die:    Adv(d20, d20):    8, 14    -> 14
- Twin dagger: Adv(2d4, 1d4):    1,  2, 4 ->  2, 4
- Penalty die: Adv(-1d4, -1d4): -2, -3    -> -2
- Result: 14 + 6 - 2 = 18

</details>

## Rolling Dice

If an action can [Succeed or Fail](#success-and-failure). The GM ask you to roll a [Base Die](#base-die) and the [Object Dice](#object-dice) and add the [Attribute](character_creation.md#attributes) modifier. Tell the result. If the [Base Die](#base-die) is 1 or 20, announce it [Natural 1 or 20](#natural-1-or-20).

## Natural 1 or 20

The Action you take is exceptional, the GM should describe what extra things happen. It is not automatic [Success or Fail](#success-and-failure), instead it goes over or below the expected outcome.

## Success and Failure

Success is when the expected outcome happens. Failure when the expected outcome happens but with an unexpected turn, or the expected outcome does not happen, but something else is. It should never block the progression. Players should never try to roll for the same ting over and over again.

## Base Die

Base die is 1d20, it can be affected by [Advantage or Disadvantage](#advantage-and-disadvantage).

## Object Dice

Object dice is [rolled](#rolling-dice) alongside the [Base Die (d20)](#base-die), it is added to the roll to affect the success and usually used to for the [Damage](./conditions.md#damaged). It can be affected by [Advantage or Disadvantage](TODO)

| Dice Roll | Min | Max | Average | Distribution Shape | Suggested use                     |
|-----------|-----|-----|---------|--------------------|-----------------------------------|
| 0d        | 0   | 0   | 0       | 0                  | Basic defense                     |
| 1d4       | 1   | 4   | 2.5     | Uniform            | One naked hand                    |
| 1d6       | 1   | 6   | 3.5     | Uniform            | Two naked hand, One handed weapon |
| 1d8       | 1   | 8   | 4.5     | Uniform            | Two handed weapon                 |
| 2d4       | 2   | 8   | 5.0     | Bell curve         | 2 AP Spent                        |
| 1d10      | 1   | 10  | 5.5     | Uniform            |                                   |
| 2d6       | 2   | 12  | 7.0     | Bell curve         | 1 Mana Spent, 3 AP Spent          |
| 3d4       | 3   | 12  | 7.5     | Bell curve         | 4 AP Spent                        |
| 2d8       | 2   | 16  | 9.0     | Bell curve         | 2 Mana Spent                      |
| 4d4       | 4   | 16  | 10.0    | Bell curve         |                                   |
| 3d6       | 3   | 18  | 10.5    | Bell curve         | 3 Mana Spent                      |
| 2d10      | 2   | 20  | 11.0    | Bell curve         |                                   |
| 3d8       | 3   | 24  | 13.5    | Bell curve         | 4 Mana Spent                      |
| 4d6       | 4   | 24  | 14.0    | Bell curve         |                                   |
| 3d10      | 3   | 30  | 16.5    | Bell curve         |                                   |
| 4d8       | 4   | 32  | 18.0    | Bell curve         |                                   |
| 4d10      | 4   | 40  | 22.0    | Bell curve         |                                   |
