# How to use Inconnu
### Character Creation and adjustments

1) **__Add your character to the bot__**

``/character create 
name:You character's name 
template:Vampire
health:character's health 
willpower:character's willpower 
humanity:character's humanity``

After that you get a **DM** from the bot and fill in the __attributes & skills and convictions__

2) **__Add specialties__**

You can add your specialties to your bot and include them into your rolls. To add them you type:

``/specialties add Specialties Skill=Specialty ``

Example: [Screenshot showing /specialties add Specialties Skill=Specialty]

3) **__Add discipline levels__**

To **add** your discipline levels you type: ``/disciplines add Discipline=Level``

To **update** use:`` /disciplines update: discipline=number of dots``

Example: [Screenshot showing discipline update]

4) **__Add traits/advantages__**

You can add advantages like fame, influence, looks (beautiful, stunning etc.) to Inconnu.

Please type ``/traits add Advantages=Number of dice``

To **update** traits/advantages use: ``/traits update traits Advantage=Number of dice``

Beware: Stunning adds 2 dice! Use Stunning=2

Example: [Screenshot showing traits update]

## Dice rolls

**__Wake and Blush of Life__**

When the night begins use ``/awaken`` to wake the character up. You will gain used WP back.

Use ``/bol`` to use Blush of Life.



**__How to roll__**

Since your attributes, skills, disciplines and traits are in the bot you don't need to count dots, you can just write down the skills you are using!

Example: ``/roll pool: charisma+persuasion+beautiful``
(Attribute+skill+trait)

``/roll pool: strength+brawl+potence``
(Attribute+skill+discipline)

``/roll intelligence+academics.research``
(attribute+skill.specialty)

If you have advantages like **obvious predator** add **-2** to your pool.

Example: ``/roll pool: manipulation+persuasion-2``

If you want to surge your roll add ``+surge`` to your pool
``/roll manipulation+persuasion+surge``
You'll get a surge bottom to rouse the blood for this roll.



**__Resonances__**

When you hunt for Kine you have to roll for resonance.

Use ``/resonance`` to gain a random temperament and resonance.

If you get a resonance and need to roll for the temperament (bloodhounds for example) use
``/temperament``



**__Damage & Healing__**

To add health and willpower damage to your character use: 
``/character adjust sup_hp/agg_hp*``
or 
``/character adjust sup_wp/agg_wp``

If you want to **heal superficial health damage** use: ``/mend``.

If you want to **heal aggravated health damage** use: ``/aggheal``.



**__Willpower__**

To roll Willpower use
``/roll pool: willpower Hunger: 0 diff: the diff you are rolling for``



**__Frenzy__**

You can perform a frenzy check  by using:
``/frenzy``
