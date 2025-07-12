# Conditions

TODO:

- Explain this list
- Expand this list
- Reduce this list

## Absorbed

## Animated

## Aura

## Baned

## Barrier

## Battle Field Opportunist

## Battle Trance

## Blessed

## Blind sighted

## Blinded

## Bolstered

## Charging

## Charmed

## Compelled Honesty

## Concealed

## Confused

## Connecting Senses

## Covered in

## Damage Over Time `Dot`

- Description: A sustained effect that damages the affected target over time. The nature of the effect depends on the tag, such as fire, poison, or psychic assault.
- Possible causes: Burning, Bleeding, Freezing, Toxic, Necrotic, Acidic, Psychic, etc
- Stackable: Yes
- Effect: The target damaged by 1 for each DoT condition at the start of its turn.
- Duration: Depending on the cause, a bucket of water, antidote/healing, stopping the caster, etc
- Suggested cost: Low
- Examples:
  - Creature:
    - **Burining Hand**: The Fire Imp attacks with his claws, on hit it deals damage, and ignites the target on fire.
      - 1 AP
      - (DEX) 1d4 vs (STR or DEX)
        - [Slashing Damage](#damaged)
        - Until the flames are exhausted:
          - [Burning Dot](#damage-over-time-dot)
          - [Confused](#confused)
    - **Freezing chant**: The target engulfed in a cold magic which chills it from inside out.
      - 1 AP + 1 MP
      - (WIL) 1d10 vs (WIL)
      - Conditions on the target until the spell is [Sustained](#sustaining):
        - [Freezing Dot]
        - [Slowed](#slowed)
  - Environment:
    - An acid pool stacking [Corrosive Dot](#damage-over-time-dot) condition each round a creature stands in it. It ends as soon as the creature leaves.
    - Booby trap: 1d6 [Piercing Damage](#damaged), and 2 stack [Bleeding Dot](#damage-over-time-dot) until its bandaged or healed.
  - Object:
    - Whoever sees this object will suffer [Dot Psychic](#damage-over-time-dot) and [Fatigued](#fatigued) 1d6 minutes. It does not stack.

## Damaged

- Description: Target failed to avoid or block the damage and suffers it.
- Damage types:
  - Physical: Bludgeoning, Piercing, Slashing, Sonic, etc
  - Elemental: Fire, Cold, Electric, Toxic, Corrosive, etc
  - Mind: Psychic
  - Magical: Radiant, Umbral, etc
  - True: True
- Effect: Initiator's [Object Dice](TODO) damage is reduced from the [HP](./character_creation.md#hit-protection-hp)
- Duration: Instant
- Suggested cost: Low
- Examples:
  - Creature:
    - **Sharp Fangs**: Biting the target by its sharp fangs.
      - 1 AP
      - (STR or DEX) 1d6 vs (STR or DEX)
        - [Piercing Damage](#damaged)
  - Object:
    - **Great Axe**: A well maintained two handed Battle Axe, with blade and a pick side.
      - 1 AP
      - (STR) 1d8 vs (STR or DEX)
        - [Slashing Damage](#damaged) or [Piercing Damage](#damaged)
    - **Crossbow**: A well oiled heavy crossbow
      - 1 AP to shoot 2 AP to reload
      - (DEX) 2d4 vs (STR or DEX)
        - [Piercing Damage](#damaged)

## Darkness

## Dead

## Deafened

## Defending

## Defensive

## Demoralized

## Detected

## Disarmed

## Distracted

## Dominated

## Drowning

## Falling

## Fatigued

## Fear

## Feather Falling

## Flanked

## Flight

## Forced Move

## Full Covered

## Genesis

## Half Covered

## Hastened

## Healed

## Illusion Affected

## Immobile

- Description: Effected movement is restricted.
- Effect: Effected cannot move or do things that requires movement, depending on how well restrained.
- Duration: Depending on the cause.
- Suggested cost: Low, Medium
- Examples:
  - Creature:
    - **Entailing web**: Spits a sticky web which entangles the whole creature.
      - 1 AP 1 MP
      - (WIL) 2d6 vs (DEX)
        - Until target freed by washing off with acid or burning off with fire
          - [Immobile: Whole body](#immobile)
    - **Grappling**: Grabbing with both or one hand, depending on the size of the target, it restrict its movement.
      - 1 AP
      - (STR) (1d6 or 1d4) vs (DEX or STR)
        - Until target free himself and the grapling is [Sustained](#sustaining)
          - [Immobile: Whole body](#immobile)
  - Environment:
    - A deep quagmire captured the legs of the unsuspecting creature, its [Immobile: Legs](#immobile) until it gets out.

## In Line of Sight

## Incapacitated

## Insubstantial

## Intimidated

## Invisible

## Knocked Down

## Lightened

## Marked

## Mastery in

## Memory Altered

## Mind Reading

## Moving

## Nullified

## Precognition

## Provoked

## Regeneration

## Resistant to

## Restoration

## Retro Cognition

## Scrying

## Silenced

## Slowed

## Stupefied

## Summoned

## Surprised

## Sustaining

- Description: Effected is currently sustaining a condition to keep it ongoing
- Effect: To keep sustaining, the Effected should use [Sustain Action](#sustaining)
- Cost: 1 AP for each sustained action
- Stacking: Depending on the sustained actions. _(Eg: Sustaining more spells is possible, grabbing 2 Tiny creatures with each hand is possible)_
- Examples:
  - Creature:
    - **Living Wines**: The target creature is entangled in living wines, its unable to move.
      - 1 AP + 1 MP
      - (WIL) 1d10 vs (STR or DEX)
        - Until the spell is [Sustained](#sustaining) or the Living Wine attacked with slashing, tearing or fire damage.
          [Immobile: Legs and Arms](#immobile)

## Swimming

## Taunted

## Telepathically Connected

## Teleport

## Transformed

## True sighted

## Understand Language

## Vulnerability to

---

## TODO: Remove

---

- Extra Dimensional Space: Bob can open a small pocket dimension in front of him and palace a small object to later retrieval (Absorb Object / Store One | Cost to store: 1 AP + 1 MP; Cost to Recall: 1 AP)
- Gluttony: Gulp the chubby humanoid frog, can eat about 3-4 small items, and store them inside his special organ. To retrieve the items he barfs out all at once in front of him. (Absorb Object / Store 3 | Cost to store: 1 AP | Cost to recall: 1 AP)
- Bag of the Void: If the Bag supplied mana daily (1 MP) it can store any number of items, without affecting its mass. However it spits out random objects when the user tries to access it. Roll the number of items stored rounded up to the nearest dice, its spits out the rolled item, or if it is rolled over GM describes the strange thing it. Forget to feed mana it eats the items one by one each day randomly. (Absorb Object / Store Multiple Object | Cost 1 MP / day)
- Bag of Greedy Eyes: It can store any number of gold, gemstones or valuables, without affecting its mass. To open up, it needs to see a greater treasure than stored in it. (Absorb Object / Store Multiple Object | Cost: Situational)

## Alternate Form

- Tags: #Transform, #Druid, #Personality, #WildBestForm
- Class: Alteration
- Stacks: Yes
- Target: Self

You alter your form with magic. Or have a different personality depending on the situation. Or you are a Warewolf. Or Druid with Wild Beast form.

Pre-create another [Character Sheet](./character_creation.md) for each Alternate form, and you can transform into that, depending on your character.

Each [Attribute](./character_creation.md#attributes) and [Stat](./character_creation.md#stats) loss and gain affecting all forms equally.

**Power levels:**

- PW 1: Personality change
  - Change into another Persona, with similar attributes and stats
- PW 3: Lesser form
  - Turn into a critter with low [XP](./character_creation.md#experience-xp)
  - Cost: Time
  - Duration: [Concentration](TODO)
- PW 4: Normal form
  - Change into a creature with same [XP](./character_creation.md#experience-xp)
  - Cost: Time and MP
  - Duration: [Concentration](TODO)
- PW 5+: Greater form +XP
  - Change into a creature with +[XP](./character_creation.md#experience-xp)
  - Cost: Time and MP
  - Duration: [Concentration](TODO)

<details markdown="block"><summary>Expand to see Examples</summary>

### Ruki and Robin

A prophesy was given that the twins Ruki and Robin will do something grand in the future, but during pregnancy, Robin died, and his spirit merged with Ruki's. Now both live in the same body, and switching personality each time they eat or drink something sweet. Ruki is brave and has assertive personality, Robin can control their body better.

- Stats are the same, but [WIL](./character_creation.md#will-power-wil) and [DEX](./character_creation.md#dexterity-dex) is swapped.
- Features:
  - Common: ...
  - Only Ruki: ...
  - Only Robin: ...

### Mardu the Druid

Mardu born in the nature, in a small community where every whim of the Mother <i>Dali</i> affected their life. They were shamans and druids, and Mardu learned to turn into animals he hunted for years of his early life.

- Features Mardu can turn into:
  - Common Mouse (Alternate Form / Lesser Form)
    - STR 1 | DEX 1 | WIL 1 | HP 1 | MP 0 | SPEED 3 | SIZE 0 Tiny
    - Features: (TODO)
      - Just a critter: Blends in easily where a mouse can. Hidden 1d10 vs (WIL)
  - Horned Rabbit (Alternate Form / Lesser Form)
    - STR 1 | DEX 17 | WIL 1 | HP 1 | MP 0 | SPEED 6 | SIZE 1 Very Small
    - Features: (TODO)
      - Running solves everything: Runs fast and can dodge almost anything. Dodge and Move (1d4)
      - Charging Horns: Using momentum Horns can pierce the enemy. Charging 1d4 Piercing dmg (STR or DEX)
      - Charming delicacy: Most of the living like to eat its flesh, or capture it to turn into a Rich girl's pet. Taunt 1d4 vs (WILL)
  - Black Lynx (Alernate Form / Normal Form)
    - XP 60/0 | STR 9 | DEX 17 | WIL 9 | HP 4 | MP 0 | SPEED 6 | SIZE 2 Small
    - Features: (TODO)
      - Prowl: Stealthy and Agile. Hidden 1d8 vs (WIL)
      - Bites: 1d6 piercing damage vs (STR or DEX)
      - Claws: 1d6 piercing damage vs (STR or DEX)
      - Grabbing prey: Can grapple with claws and teeth vs (STR or DEX)

### Lilian and the Pixie

When Liliana was little a charming Pixie lured here into the dark forest. Annoyed by the fragile body of the little girl the he cast a permanent spell on Lilian so they can play together. Every time she harmed, she turns into pixie. A big search and rescue group formed and found her abandoned by the him. They were unable to break the spell, but the effect is duration is reduced to 6 minutes, and she gained affinity to Pixie magic.

- Features:
  - Pixie: Lilian will turn into a pixie each time she is harmed once per day for 6 minutes (Alternate Form / Greater Form +10XP)
    - XP 70/1 | STR 10 | DEX 11 | WIL 17 | HP 2 | MP 6 | SPEED 5 | SIZE 1 Very Small
    - Feautres: (TODO)
      - Pixie Magic: ...

</details>

----
