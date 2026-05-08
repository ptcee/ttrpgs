# ANVIL

> A TTRPG about a dwarven strike force carrying out missions deep in enemy territory 200 years before the Gobfather establishes the Underhold. Four players, one GM.

> 100 years after the craters were first discovered evil things began to crawl out from the depths of the world. With them they brought the arcane. Dwarves, being born of the depths themselves found themselves uniquely resilient to these magical effects, thus ANVIL was created. A secret strike force of the most elite and explosive dwarves, assembled to carry out the most dangerous missions for the Queen of Glimmerhold. You are one such strike force. These are your missions. Get in, drop 'em like stones and get out.

## Table of Contents

    - What you need
    - Gameplay Loop
    - Core Mechanics
      - Rolling Stones
      - Standard Actions
      - Explosive Actions
      - Aftermath
      - Alarm clock and noise
      - Combat
      - Social
    - Assembling the Squad (chargen)
      - CMP & TNT
      - Skills & Scars
      - Equipment
    - HQ - The Overhold (downtime)
      - Missions
      - Preparing
      - Embarking
      - Advancement
    - On Missions (dungeons)
      - Factions

> TODO: 
> reaction mechanics; rolling social reaction, states changing. the dungeons reaction state and it moving as well
> 
> how to build missions and some examples
> 
> preparing for missions
> 
> embarking on missions (choosing a drop point etc)
> 
> leveling up
> 
> outlining some factions
> 
> HQ stash items
>
> HQ funding tracker, getting noticed makes it harder for ANVIL to move in the shadows, the glimmerhold council doesn't know ANVIL exists, only the queen and her hand
> 
> traps and enemies
> 
> example object tmpr to go off of
>
> a clean compact gameplay loop and what players need to play (design op sheets and mission sheets, HQ sheet as well)
>
> tables for skills and scars, table for hammers, table for items

# CORE

### Every ANVIL op starts with:

- CMP die & TNT die
- 3 Skills (relevant actions change dice sizes)
- 1 ANVIL assigned Runeaxe (d6 CMP)
- 1 Explosives Kit (d6 TNT)
- 5 item slots to fill from prep

## DICE

d6 Composure
d6 Explosive

Skills define whether they step up or down a die and which.

### Rolling Stones

#### Standard Actions

Roll CMP and TNT dice. Assign one to FUSE and 1 die to BLAST.

- FUSE is your speed, precision and control; ability to get the job done.
  - Low FUSE is quick, efficient, clean.
  - High FUSE is messy, slow and overcomplicated.
- BLAST is noise, force, commotion; how loud you're being.
  - Low BLAST is quiet, doesn't 
  - High BLAST is large, loud and powerful.
  - The number on the BLAST die ticks the alarm clock up that many ticks.

#### Explosive Actions

Roll stones as normal.

- FUSE: How many turns before detonation. Low fuse means happens immediately, high fuse means you have time.
- BLAST: Roll that many d6 explosion dice. (6s on explosion dice always explode; roll another d6.)
  - Every 4+ destroys something.
    - Everything in the world has Temper (TMPR) levels, this is the amount of 4+ dice it takes to destroy whatever it is.
    - Player describes intent, GM narrates what actually gets levelled.
    - All dice from the explosion pool, hits and misses, become aftermath dice.

### Aftermath

The world doesn't wait for the players to act. Aftermath dice represent the GM's ability to act, react, and escalate. The GM uses aftermath dice to Roll Stones for enemies, traps, and anything else.

#### Generating Aftermath

The GM gains aftermath dice from the following sources:

- **Mission start:** GM gains aftermath dice equal to the number of players x2
- **Every 3 turns:** GM gains 1 aftermath die
- **Roll stones shows any 1s:** GM gains 1 aftermath die
- **GM's BLAST die shows a 6:** GM gains 2 aftermath dice

#### Spending Aftermath

The GM spends aftermath dice to roll stones for the world. When an enemy acts, a trap triggers, or the world threatens the players, the GM pulls dice from the aftermath pool and rolls them as FUSE and BLAST, assigning one to each as normal.

- **FUSE:** how effective the action is. Can be checked against the player's TMPR or used to oppose a player's roll.
- **BLAST:** how much noise and chaos the action generates. Ticks the alarm clock as normal.

The GM *must* use a minimum of 2 aftermath dice to roll stones. Spent dice are removed from the pool.

#### Free Moves

Free moves cost nothing. They are the world moving with or without the players. The GM can make a free move at any time without aftermath.

- A patrol completes its route and begins again
- A light goes out or comes on
- A door closes or locks on a timer
- An enemy becomes suspicious but takes no action
- The environment shifts, water rises, a fire spreads, rubble settles
- An NPC makes a decision that doesn't directly affect the players yet
- Foreshadow something bad without it arriving yet

Free moves never directly threaten or act against the players. The moment something becomes a threat it costs aftermath.

#### Aftermath in Play

A small aftermath pool means the world is quiet, players have breathing room. A large aftermath pool means the world is loaded and dangerous, the GM can act repeatedly and forcefully.

Players who move slow and quietely keep the pool starved. Players who act fast and blow things up feed it constantly. Both are valid, both have consequences.

When the GM rolls stones and assigns BLAST as a 6, that aftermath roll is refunded. Large brawls and loud confrontations can become self sustaining as the world escalates in response to escalation.

## CLOCKS, ALARMS & TURNS

When players start a strike mission begin it's alarm clock, every time players assign a BLAST die raise the alarm by the result of that die.
When a locations alarm hits it's thresholds the **hammer drops**.

Each mission location has a specific hammer/s and one or more alarm thresholds.

Track turns while players are on a mission. Mark a turn everytime a player takes a notable action or rolls stones. A turn represents a few minutes in world. 

## COMBAT & DAMAGE

The game of ANVIL doesn't have hit points. Everything in the world; guards, doors, walls, dwarves, gear, has Temper. Temper is how hard something is to destroy and how much punishment it can absorb before it's gone.

### Temper (TMPR)

Every object or creature has a TMPR value, or can be given one by the GM if needed.

- **The number** is the BLAST threshold. Your BLAST die must meet or beat it to act against it effectively.
- **The brackets** are the explosive threshold. The number of [+] symbols is how many successful explosive dice (4+) are needed to destroy it. No brackets means one successful explosive die destroys it.

**Examples:**

- `TMPR 2` - BLAST 2+ to handle, one blast die destroys it
- `TMPR 2[++]` - BLAST 2+ to handle, two blast dice to demolish
- `TMPR [++]` - can't be handled by hand, two explosive dice to demolish
- `TMPR 4[++]` - BLAST 4+ to handle, two explosive dice to demolish
- A low FUSE and a BLAST that beats TMRP clean is a single hit to take down an enemy. A high FUSE and a clean BLAST is a messy brawl but the dwarf comes out on top.

**How tempered is it?** If players are unsure of something's TMPR the GM should freely tell them. Not only does it speed up the game flow but it is also much easier to roll stones if you know what values you're aiming for.

### Hit Resolution

When a BLAST die is applied against a TMPR value:

- **BLAST beats TMPR:** Clean hit. Wipes all uses on whatever took the hit.
- **BLAST equals TMPR:** Maimed. Marks 1 use on whatever took the hit.
- **BLAST below TMPR:** Botched. Miss, glance, no marks.

This applies to both players acting against the world and the GM rolling stones against players.

### Player Characters & Damage

Dwarves don't track HP. Instead hits are absorbed by gear or skills then GRIT, as the fiction permits.

#### Absorbing Hits

When a GM's BLAST beats or equals your TMPR you can redirect the hit into something that can absorb it. The fiction must support it. If you're hit by a crossbow bolt your boots aren't going to help. However if you dive behind a crate and it clips your foot, that works.

**Absorption order:**

1. **Gear or Skills:**  redirect into a piece of equipment or skill
2. **GRIT:**  nothing left or available, the hit lands on you directly

#### Gear

All gear has 3 uses.

- **Clean hit:**  wipes all 3 uses, item is destroyed
- **Maim:**  marks 1 use

When gear runs out of uses it is destroyed and gone for the mission. A dwarf who loses their greathelm, their jack, and their pack is fighting naked. The fiction changes and their options narrow.

A dwarf with no gear to use has d4 for both CMP and TNT.

#### Skills

Skills also have 3 uses but uses are only ever marked by absorbing hits, never by using the skill.

- **Clean hit:**  wipes all 3 uses, skill is unavailable for the rest of the mission
- **Maim:**  marks 1 use

A skill that has absorbed hits can still be used to step up dice until all uses are gone. When a skill is wiped it cannot step up dice for the rest of the mission. The dwarf is still capable, they just lost the edge that training gave them.

Enemies and traps can target skills directly. A disorienting gas doesn't damage your armour. A veteran interrogator doesn't slash at your kit. Some
threats know exactly what to hit.

#### GRIT

GRIT is your final resolve. When there is nothing left to absorb a hit, no gear in the way, no skill to spend, no positioning argument, the hit lands on the dwarf directly.

Every dwarf starts with **4 GRIT**.

- **Clean hit to GRIT:** marks all GRIT, dwarf is dead
- **Maim to GRIT:**  marks 1 GRIT

A dwarf on their last GRIT is one hit from death. They should be moving toward extraction asap.

**If all 4 GRIT are marked the dwarf is dead.**

Skills can boost GRIT. A skill like Ironborn might give a dwarf an additional GRIT use, representing a body and will that simply refuses to quit.

#### Base TMPR

Every dwarf has a base TMPR of 3. This represents flesh, bone, and dwarven stubbornness. Skills can modify this upward. Without gear and without skills a dwarf is TMPR 3, tough but not invincible.

### Combat Flow

Combat in ANVIL is not a separate phase. There is no initiative, no combat round, no turn order distinct from normal play. Violence is just another
action that gets rolled.

When a player acts against an enemy they Roll Stones and assign FUSE and BLAST.

- **FUSE** dictates how clean the action is.
- **BLAST** is checked against TMPR and ticks the alarm clock.

When the GM acts against a player they spend aftermath dice and Roll Stones, assigning FUSE and BLAST as normal.

- **GM FUSE** dictates how succesful the world's reaction was.
- **GM BLAST** checks against the dwarf's TMPR and ticks the alarm clock.

The fiction determines what's possible. A dwarf who slips a knife into a guard from the shadows can roll stones against TMPR 1 with a favourable die. A dwarf in a straight fight against a plated veteran is rolling against TMPR 4 and hoping their dice get there.

### Enemy TMPR

Enemies are defined by their TMPR and what they're carrying. A guard in leather is TMPR 2. A guard in plate is TMPR 4. A guard in blast resistant
platemail is TMPR 4[++]. A shambling creature from the depths with flesh like stone is TMPR 5[+++].

Enemies can also have gear and skills that absorb hits just like players. A veteran soldier doesn't go down on the first clean hit, their training
or equipment absorb it first. The GM decides what enemies will sacrifice to avoid death.

### Runeaxe & Explosives Kit

Equipment have 3 uses but you do not mark a use when you use them, except for certain consumable items tagged [✖︎]. 

An item tagged [▼] is explosive and if marked by outside means (damage, targeted, but not by using it) it explodes. (Roll a d6, roll that many explosive dice.)

Every ANVIL op is assigned a Runeaxe and an Explosives Kit. These are are not merely equipment, they are valuable mission tools that change your base dice.

The Runeaxe is a weapon and a tool. Losing it mid mission to block a hit is a real tactical loss. Without it a dwarf is rolling stones with nothing but their fists and their nerve. **Your Runeaxe gives you a base CMP die of d6.**

The Explosive Kit is [▼] but does not mark uses. **This kit has infinite small TNT uses and gives a base TNT die of d6.** Other explosives can be taken from the prep stash during mission preparation.

## SOCIAL

### Reaction Rolls

1. **Hostile:** attacking or raising the alarm immediately
2. **Suspicious:** not buying it, one wrong move
3. **Wary:** cautious, watching
4. **Neutral:** not their problem yet
5. **Friendly:** willing to help or look the other way
6. **Allied:** actively covering for the squad

### Mood & Doubt
Every NPC has a Mood (1-6) and a Doubt stat and track (1-3).

When a dwarf interacts with an NPC roll stones and assign FUSE and BLAST.

- FUSE must beat their current Mood value to move Mood up 1
- FUSE equals or below, Mood holds or drops, GMs can make this call based on the narrative
- If BLAST is below the NPC's Doubt score, advance the track 1

When Doubt hits its max the NPC turns Hostile regardless of Mood.

A boisterous dwarf keeping BLAST high keeps Doubt flat. A careful quiet dwarf rolling low BLAST is more suspicious. Very undwarfy.

NPC doubt does not reset unless they squad has a disguise.

# CHARACTER GENERATION

TODO!

- roll name and physique
- roll 3 other traits
- roll 3 skills
- roll Runeaxe and Explosive Kit style
- 5 open pack slots for Prep Stash gear

# DOWNTIME - THE OVERHOLD (the overhold is ANVIL's headquarters, a large brutalist building on the northwest edge of glimmerhold)

## ADVANCEMENT

Leveling up changes a skill, players can add to their skills by editing it's description.

Leveling up rolls for Scars. See SCARS.

Depending on the Funding track, players can add to the prep stash.

## SCARS

Between missions ANVIL ops return to the Overhold. Gear is restocked, GRIT fully recovers, skills reset. But the missions leave lasting marks.

### GRIT Recovery

All GRIT is fully recovered between missions. A dwarf who came back on their last mark starts the next mission at full 4 GRIT.

### Rolling for Scars

After every mission each surviving dwarf rolls for Scars.

Roll a d6. Add 1 extra d6 for every GRIT lost during the mission.

**If any die shows a 1 or 2, gain 1 Scar.**

Only ever gain 1 Scar per mission regardless of how many dice show 1-2.

**ie:**
- Lost no GRIT: roll 1d6, 33% chance
- Lost 1 GRIT: roll 2d6, 55% chance
- Lost 2 GRIT: roll 3d6, 70% chance
- Lost 3 GRIT: roll 4d6, 80% chance
- Lost all 4 GRIT: dead, no roll

A clean mission might leave a dwarf unmarked, a mission where they barely made it out almost certainly doesn't.

### Scars in Play

Scars are permanent. They cannot be removed, bought off, or healed. This job isn't easy and dwarves remember that whether they like it or not.

Each dwarf has **5 Scar slots**.

Scars are not purely negative. They are changes. A dwarf who lost their hearing on a job that went loud is different now. Not in any way lesser, just different. Some Scars step down a die in specific situations. Some have stranger effects. All of them tell a story.

When a dwarf gains a Scar roll on the Scar table or choose an appropriate entry with the GM. Name it. Describe what happened. Mark it down on your operative sheet.

### Scar Overflow

When a dwarf would gain a Scar and all 5 slots are full, they permanently lose 1 GRIT instead. The life of a strike force operative is perilous.

A dwarf with 5 Scars and reduced GRIT is on borrowed time and every mission is now a direct threat to their life. The math gets worse with each job.

**Veteran dwarves retire before the job makes the decision for them.**

This is the lifespan of an ANVIL op. Not a timer, not a hard stop - a slow accumulation of cost that makes the table ask how much longer this 
dwarf has left.

### Retirement

A dwarf can retire between any mission. They step away from ANVIL, alive and marked, carrying everything the job gave them. Retirement is a victory 
condition. Not every dwarf gets one.

When a dwarf retires the player rolls up a new op. Fresh sheet, no Scars, full GRIT. The Overhold only selects the best of the best.

If a dwarf dies mid mission, a player can roll up a new op immediately and the table can decide how they join the mission in progress. 

# MISSIONS 

Missions are effectively one shot dungeons. The dwarves always have a clear objective given to them by the ANVIL shadowy council.