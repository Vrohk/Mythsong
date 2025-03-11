---
summary: 
thumbnail: 
links: 
aliases: 
tags:
  - "#new"
created: <% tp.date.now("YYYY-MM-DD HH:mm") %>
heritages: 
ancestry: 
background:
---
<%*
  let title = tp.file.title
  if (title.startsWith("Untitled")) {
    title = await tp.system.prompt("Title");
    await tp.file.rename(`${title}`);}%>
# [[<%* tR += `${title}` %>]]
Given Name
Alias
Summary - Ancestry, Heritage/Homeland, Background, Profession/Organization

## My vibe is...
Voice
Introduction
Appearance?
## What I'm about is...
Personality?
## What I need is...
Backstory?
## But I can't get it because...
Motivation/Quests
# Statblock
Attributes, Combat Stats
## Abilities
Behaviors, Features, and Abilities
## Skills
Skills, Languages...
# Items
Equipment, wares, loot, etc.
# Appearance / Personality
???
# Full Character Creation
## Ancestry
- 
## Heritage
- 
## Homeland
- 
## Background
- 
## Attributes
The 6 Primary Stats that make up a Creature's Body and Mind.
- 'Standard Array' - 15 (+2), 14 (+2), 13 (+1), 12 (+1), 10 (+0), 8 (-1)

|     | Mod | Total | Name         | Description                                                                             |
| --- | --- | ----- | ------------ | --------------------------------------------------------------------------------------- |
| CON |     |       | Constitution | Your body's durability, hardiness, and capacity to withstand hindering effects          |
| STR |     |       | Strength     | Your body's power and capability to lift, climb, swim, etc.                             |
| DEX |     |       | Dexterity    | Your body's flexibility and capability to move precisely and quickly                    |
| CHA |     |       | Charisma     | Your mind's presence, how others understand and are charmed you                         |
| INT |     |       | Intellect    | Your mind's capacity for reason, problem solving, and calculation.                      |
| WIS |     |       | Wisdom       | Your mind's flexibility, ability to learn from experience, intuit, feel, and empathize. |
## Appearance
How others perceive you and how you express yourself to others.
### Physical
How does your Strength, Dexterity, and Constitution manifest physically? What's your size and shape? What do your eyes, hair, and face look like? What are your other physical features (mane, tail, horns, antlers, etc.)?
- Height - 
- Eyes - 
- Face - 
- Hair - 
- Skin - 
- Age - 
- Features - 
### Expression
How do you express yourself? What do you want others to know about you from your appearance alone? What clothes do you wear casually, while adventuring, or professionally? How do you wear your hair if you have it? Do you wear jewelry, have piercings, tattoos, or glasses?
- 
## Personality
How you express your Intellect, Wisdom, and Charisma.
- Talents? / Flaws - Something people would like about you / how that thing could be considered bad
- Hobbies - What do you do with your spare time and money?
- Likes
- Dislikes
- Shames
- Prides
- Quirks - Something strange yet endearing about you
## Goals and Motivation
What do you want and Why?

### Obstacles
What's preventing you from getting it?

## Backstory
Who were you before becoming an Adventurer?
- 
### Childhood
How were you raised?
- 
### Coming of Age
When did you consider yourself an Adult? How did it change you?
- 
### Adulthood
What lead you to your Adventure?
- 
#### Successes
What were some victories along the way?
- 
#### Struggles
What do still have problems with?
- 
#### Lifestyle
How do you live, and what sort of luxuries can you not live without?
- 
## Social
Who did you know in your life before your Adventure?
- 
### Family
Who did you grow up around? How/did you adopt their values?
- 
### Friends
Who did you choose to spend your time with?
- 
### Colleagues or Mentors
Did you know anyone professionally?
- 
### Rivals or Enemies
Who would be your old competition or who has wronged you/been wronged by you?
- 
## Skills
What did you spend most of your time doing?
- Choose 2+INT (Min 0)

|                 | Total | Base | Mod |     | Source |     |
| --------------- | ----- | ---- | --- | --- | ------ | --- |
| Athletics       |       |      |     | Str |        |     |
| Acrobatics      |       |      |     | Dex |        |     |
| Sleight of Hand |       |      |     | Dex |        |     |
| Stealth         |       |      |     | Dex |        |     |
| Deception       |       |      |     | Cha |        |     |
| Intimidation    |       |      |     | Cha |        |     |
| Performance     |       |      |     | Cha |        |     |
| Persuasion      |       |      |     | Cha |        |     |
| Animal Handling |       |      |     | Cha |        |     |
| Arcana          |       |      |     | Int |        |     |
| History         |       |      |     | Int |        |     |
| Society         |       |      |     | Int |        |     |
| Medicine        |       |      |     | Int |        |     |
| Engineering     |       |      |     | Int |        |     |
| Investigation   |       |      |     | Int |        |     |
| Nature          |       |      |     | Wis |        |     |
| Religion        |       |      |     | Wis |        |     |
| Survival        |       |      |     | Wis |        |     |
| Perception      |       |      |     | Wis |        |     |
| Insight         |       |      |     | Wis |        |     |
| Lore:           |       |      |     | Int |        |     |
| Crafting:       |       |      |     | Int |        |     |
### Languages
What Languages do you understand?
- Common, your Heritage's Native Language, and choose INT (Min 0) additional.
## Feats
What Abilities have you Learned from your Ancestry, Heritage, Background, or Skills?
- 
## Training
Did you receive any formal training? If not, what did you naturally learn?

## Specialization
How do your gifts manifest?

### [[Awakening]]
The moment you suddenly were aware of your Magical Gift. 
- How and when did this happen?
- Who knows about your Awakening? Was there any witnesses?
## Combat
### Offense

|                  | Total | Base | Mod |     |
| ---------------- | ----- | ---- | --- | --- |
| Melee / Block    |       |      |     | Str |
| Ranged / Finesse |       |      |     | Dex |
| Spell Save DC    |       | 8    |     | Cha |
| Spell Attack     |       |      |     | Int |
### Defenses

|        | Total | Base | Mod |     |                                           |
| ------ | ----- | ---- | --- | --- | ----------------------------------------- |
| Shield |       |      |     |     | Shielded Hit Points                       |
| HP     |       | 25   |     | Con | Hit Points - 25 + (CON * LVL)             |
| Prot   | 0     |      |     |     | Protection - Reduce Physical Damage Taken |

|       | Total | Base | Mod |     |             |
| ----- | ----- | ---- | --- | --- | ----------- |
| AC    |       | 8    |     | Dex | Armor Class |
| Fort  |       | 8    |     | Con | Fortitude   |
| Res   |       | 8    |     | Wis | Resistance  |
| Dodge |       | 8    |     | Dex | Dodge       |
### Resources

|     | Total | Base | Mod |     |                                                   |
| --- | ----- | ---- | --- | --- | ------------------------------------------------- |
| WP  |       | 3    |     | Int | Willpower - Used to Cast Magic or Alter Abilities |
## Abilities
### Combat Style

### Role

### Cantrips

### 1st Level Abilities