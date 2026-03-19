# How to use Inconnu

### Character Creation and adjustments

1. **Add your character to the bot**

`/character wizard`

After that you get a **link** from the bot and fill in the online sheet.

Everything else beyond this point needs to be done, in server, through the commands listed.

2. **Add specialties**

You will have to add your specialties to your bot and include them into your rolls. They should be added already during the character wizard.&#x20;

If you need to add more, type:

`/specialties add Skill=Specialty`

Example:&#x20;

`/specialties add Brawl=Grapple`

3. **Add discipline levels and powers**

Discipline levels and powers should be added during the character wizard process.

To **add** a new discipline you type: `/disciplines add Discipline=Level`&#x20;

To **update** use: `/disciplines update: discipline=number of dots`

To **add** new powers, use `/powers add: discipline=PowerName`



4. **Add traits/advantages**

You need to add advantages like fame, influence, looks (beautiful, stunning etc.) to Inconnu.

They should be added as traits during the character wizard. Every merit and flaw should be added at their value (example, resources 2 you'd put it at 2).&#x20;

The only exceptions are merits that you roll at a different value. (For example, Beautiful is worth 2 points, but when using the merit it only adds one dot, so you should save it in Inconnu as Beautiful=1).

The command is\
&#x20;`/traits add Advantages=Value`

To **update** traits/advantages use:&#x20;

`/traits update traits Advantage=value`



## Dice rolls

**Wake and Blush of Life**

When the night begins use `/awaken` to wake the character up.&#x20;

You will heal superficial willpower damage as per the book rules.

Use `/bol` to use Blush of Life.

**How to roll**

Since your attributes, skills, disciplines and traits are in the bot you don't need to count dots, you can just write down the skills you are using!

**You always have to use the correct traits and never numbers. This allows you and us to know that your pool is always correct.**

Example: `/roll pool: charisma+persuasion+beautiful` (Attribute+skill+trait)

`/roll pool: strength+brawl+potence` (Attribute+skill+discipline)

`/roll intelligence+academics.research` (attribute+skill.specialty)

If you have negative flaws like **obvious predator,** you can add **`-ObviousPredator`** or even a simple -2 when not using a specific trait.

Example: `/roll pool: manipulation+persuasion-obviouspredator`

If you want to surge your roll add `+surge` to your pool `/roll manipulation+persuasion+surge`&#x20;

You'll get a surge button to rouse the blood which automatically pays the cost and increases the hunger if the rouse check fails.

**Resonances**

When you hunt for Kine you have to roll for resonance.

Use `/resonance` to gain a random temperament and resonance.

If you get a resonance and need to roll for the temperament (bloodhounds for example) use `/temperament`

**Damage & Healing**

To add health and willpower damage to your character use: `/character adjust sup_hp/agg_hp*` or `/character adjust sup_wp/agg_wp`

If you want to **heal superficial health damage** use: `/mend`.

If you want to **heal aggravated health damage** use: `/aggheal`.

**Willpower**

To roll Willpower use `/roll pool: willpower Hunger: 0 diff: the diff you are rolling for`

**Frenzy**

You can perform a frenzy check by using: `/frenzy`
