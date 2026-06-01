# Runes and Reels

A fishing card game for 2–4 players. Draft lures, cast your line, and land the biggest catch. First player to collect **20 points** worth of fish wins.

---

## Core Concepts

**Line Slack** — the stat on each fish card. Represents how much give a fish allows on the line. Big powerful fish run slow and heavy, keeping slack low. Small skittish fish dart and pull tight, giving the angler more room to work with.

**Line Tension** — the sum of all lure values, snag values, and active effects during a catch attempt. Must stay **equal to or under** the fish's Line Slack or the line snaps.

> A Master-tier fish has low Line Slack (1–2). You must use very low-tension lures to land it.
> A Small-tier fish has high Line Slack (7–9). Almost any lure combination will stay under the threshold.

---

## Components

### Player Lure Decks (1 per player)

Each player begins with an identical deck of 20 cards.

| Qty | Tension Value | Suits |
|-----|--------------|-------|
| 4 | 1 | Red, Yellow, Blue, Green (1 each) |
| 4 | 2 | Red, Yellow, Blue, Green (1 each) |
| 4 | 3 | Red, Yellow, Blue, Green (1 each) |
| 4 | 4 | Red, Yellow, Blue, Green (1 each) |
| 2 | 0 (Wild) | Any suit |
| 1 | 1 or 5 | Red or Blue |
| 1 | 2 or 3 | Green or Yellow |

> **Split Cards:** Orient the card so the value you want to use is on the side closest to the center of the tackle deck. The other value is ignored.

> **Wild Cards:** May be declared as any suit. Counts as the fish's suit when resolving tiebreakers.

---

### Shared Decks

**Fish Deck**
- Each fish has a **Line Slack** value and a **Suit** (Red, Yellow, Blue, or Green)
- Fish are scored by bracket (see Scoring)
- Some fish have **Effects** that apply for the round they are revealed

**Snag Deck** (40 cards)
- When revealed face-up, snag cards add **1–3** to your line tension
- Some snag cards have special effects when flipped:

| Qty | Effect |
|-----|--------|
| 4 | Draw a card |
| 3 | Advance your dock position by 1 |
| 3 | Reduce your line tension by 1 instead |

**Shop Deck** (50 cards)
- Each shop lure has a **Tension Value**, a **Suit**, a **Cast Effect** (used when played from hand), and an **Enchant Effect** (used when placed permanently into a rune slot)
- A lure's suit is determined by its slot category: **Hook = Red, Line = Blue, Rod = Green, Reel = Yellow**

---

### Rune Slots

Each player has four permanent equipment slots that persist across all rounds. A slot can hold one enchantment at a time and may be **overwritten** by placing a new lure into it.

| Slot | Effect Category |
|------|----------------|
| **Hook** | Line tension management (reduce tension, re-roll snag values) |
| **Line** | Snag interaction (ignore snags, reduce snag tension) |
| **Rod** | Casting (play 2 lures, draw before casting) |
| **Reel** | Draw and hand management (draw extra, retrieve from discard) |

---

### Locations (4 cards)

The dock 1 angler chooses a location each round. Each location grants a bonus to the player(s) with the **lowest current score**.

| Location | Trailing Player Bonus |
|----------|-----------------------|
| **Creek** | Hand size is 8 whenever drawing cards this round |
| **River** | May discard the first revealed fish to reveal a new one |
| **Pond** | May discard up to 2 cards before drawing at end of each Fish On phase |
| **Lake** | May remove one snag card from hand, then draw a replacement |

> **Tied for last:** All tied players receive the bonus. If all players are tied, nobody receives it.

---

### Scoring Brackets

| Bracket | Points | Line Slack |
|---------|--------|------------|
| Small | 1 pt | 7–9 |
| Average | 2 pts | 5–6 |
| Big | 3 pts | 3–4 |
| Master | 5 pts | 1–2 |

---

## Gameplay

Each round consists of **Morning Prep** followed by **three Fish On phases**.

---

### Morning Prep

#### 1. Draft Lures

Starting with the angler in dock position 1 (or randomly on the first round):

- **a)** Reveal lures from the shop deck equal to the number of players.
- **b)** Players snake draft one lure each.
- On your draft turn, you may **forgo your pick** to immediately place your angler card at the earliest open dock slot. You are locked out of all remaining picks this draft.

Repeat steps **a** and **b** two more times (three draft sets total).

After each draft set, any player who has taken their final pick places their angler card at the earliest available dock slot. Dock order is resolved from slot 1 (earliest) to slot 4 (latest) and determines play order for the rest of the round.

#### 2. Prepare Your Tackle

1. Each player may place **1 lure** face-down into a rune slot as an enchantment.
2. Place all remaining drafted cards onto your **tackle deck**.
3. The angler in **dock slot 1** chooses a location.
4. Shuffle your tackle deck and draw **7 cards**.

---

### Fish On

Repeat this phase **three times** per round.

#### Step 1 — Reveal the Fish

- Flip the top card of the fish deck face-up.
- Note the fish's **Line Slack**, **Suit**, **Bracket**, and any **Effects** for this phase.

#### Step 2 — Cast

In dock order:
- Each player selects 1 lure from their hand and places it **face-down**.
- The lure must **match the fish's suit** if possible.
- Players may **activate one imbued enchantment** at this point.
- If you have **no matching suit** in hand, take the **top card of the snag deck** and place it face-down **horizontally beneath** your lure.

#### Step 3 — Reveal

All players flip their lures face-up simultaneously.

**Determine catch order** (highest lure tension value goes first):

1. Highest lure tension value
2. Tie → lowest dock slot number wins
3. Still tied → matching suit wins
4. Still tied → each tied player reveals one additional lure; higher value wins

#### Step 4 — Catch Attempt

The leading player attempts to land the fish:

1. **Flip up** any snag card beneath your lure.
2. **Play one additional lure** from your hand.
3. Calculate **line tension**: cast lure + additional lure + snag value + any active effects.
4. Compare to the fish's Line Slack:
   - **Line Tension ≤ Line Slack** → Fish caught. Take the fish card and place it beside your tackle deck.
   - **Line Tension > Line Slack** → Line snaps. If you had a snag in play, place it on the **bottom of your tackle deck**.

If the fish is not caught, the **next player in catch order** attempts in the same manner. Continue until the fish is caught or all players have failed (fish gets away).

#### Step 5 — Draw Up

All players draw back up to **7 cards**.

> If your tackle deck runs out, shuffle your discard pile to form a new tackle deck.

---

## Winning

The first player to accumulate **20 or more points** wins.

---

## Reference: Turn Order Summary

```
MORNING PREP
  └─ Draft lures (3 sets, snake order from dock slot 1)
  └─ Place angler card at dock when last pick is taken (or forgo pick to go immediately)
  └─ Place 1 enchantment
  └─ Dock slot 1 chooses location
  └─ Shuffle tackle deck, draw 7

FISH ON (× 3)
  └─ Reveal fish (note Line Slack, Suit, Bracket, Effects)
  └─ Players cast lures face-down in dock order (+ snag if no suit)
  └─ Activate enchantment (optional)
  └─ Reveal lures — highest tension value catches first
  └─ Catch attempt: flip snag, play 1 more lure, check line tension vs line slack
  └─ Next player in catch order attempts if fish not caught
  └─ All draw up to 7

REPEAT
```
---

# Runes and Reels — Fish Deck (40 cards)

Each fish has a **Line Slack** value, a **Suit**, a **Scoring Bracket**, and optional **Effects**.

Line Tension during a catch attempt must stay **equal to or under** Line Slack or the line snaps.

| Bracket | Points | Line Slack |
|---------|--------|------------|
| Small | 1 pt | 7–9 |
| Average | 2 pts | 5–6 |
| Big | 3 pts | 3–4 |
| Master | 5 pts | 1–2 |

Suit distribution: 10 Red, 10 Yellow, 10 Blue, 10 Green.

---

## Master (5 pts, Slack 1–2) — 6 cards

*Tight window. Low-tension lures only. Snags are extremely dangerous.*

| # | Name | Slack | Suit | Effect |
|---|------|-------|------|--------|
| 1 | Golden Mahseer | 1 | Red | Only the player with the lowest tension cast may attempt. If they fail, the fish escapes. |
| 2 | Taimen | 1 | Blue | — |
| 3 | Sturgeon | 2 | Green | The catching player must succeed on their first attempt or the fish escapes (no chain). |
| 4 | Arapaima | 2 | Yellow | Players may not activate enchantments this round. |
| 5 | Giant Trevally | 2 | Red | — |
| 6 | Siamese Carp | 2 | Blue | Each player must discard 1 card before casting. |

---

## Big (3 pts, Slack 3–4) — 10 cards

*Forgiving enough for mid-range lures. Snags still threaten on Slack 3.*

| # | Name | Slack | Suit | Effect |
|---|------|-------|------|--------|
| 7 | Pike | 3 | Green | — |
| 8 | Wels Catfish | 3 | Red | — |
| 9 | Lake Trout | 3 | Blue | — |
| 10 | Common Carp | 3 | Yellow | Each player draws 1 card before casting. |
| 11 | Grass Carp | 4 | Green | Catch order is reversed this round (lowest tension cast goes first). |
| 12 | Silver Carp | 4 | Yellow | Each player must take a snag regardless of suit in hand. |
| 13 | Bighead Carp | 4 | Red | Players may play 2 lures this round. Line tension is the sum of both. |
| 14 | Huchen | 4 | Blue | — |
| 15 | Chalkstream Trout | 4 | Green | — |
| 16 | Asp | 4 | Red | The first player to fail a catch attempt this round draws 2 cards. |

---

## Average (2 pts, Slack 5–6) — 14 cards

*The bread and butter of most rounds. Effects appear here to keep mid-game interesting.*

| # | Name | Slack | Suit | Effect |
|---|------|-------|------|--------|
| 17 | River Trout | 5 | Blue | — |
| 18 | Zander | 5 | Yellow | — |
| 19 | Barbel | 5 | Green | Snag cards this round add +1 to their tension value. |
| 20 | Grayling | 5 | Red | All players must cast their highest tension lure this round. |
| 21 | Bream | 5 | Yellow | — |
| 22 | Tench | 5 | Blue | — |
| 23 | Perch | 6 | Green | — |
| 24 | Rudd | 6 | Red | — |
| 25 | Nase | 6 | Yellow | — |
| 26 | Vimba | 6 | Blue | — |
| 27 | Burbot | 6 | Green | Players may not activate enchantments this round. |
| 28 | Bitterling | 6 | Red | This fish may only be caught by a player with no snag in play. |
| 29 | Flounder | 6 | Yellow | Each player may discard 1 card and draw 1 card before casting. |
| 30 | Vendace | 6 | Blue | The angler in dock slot 1 must cast first and reveal their lure immediately. |

---

## Small (1 pt, Slack 7–9) — 10 cards

*Wide window. Almost any lure lands these. Strong effects here create risk-reward decisions on low-value fish.*

| # | Name | Slack | Suit | Effect |
|---|------|-------|------|--------|
| 31 | Sunfish | 7 | Yellow | — |
| 32 | Minnow | 7 | Blue | — |
| 33 | Mudskipper | 7 | Green | — |
| 34 | Dace | 7 | Red | — |
| 35 | Pumpkinseed | 8 | Yellow | — |
| 36 | Roach | 8 | Red | — |
| 37 | Stone Loach | 8 | Green | — |
| 38 | Bleak | 8 | Blue | — |
| 39 | Chub | 9 | Yellow | The player who catches this fish draws 2 cards. |
| 40 | Rock Bass | 9 | Blue | Snags reduce cast lure tension by 1 this round (minimum 0). |

---

## Design Notes

- **Master fish** are rare (6 cards) and punishing. A single snag on a Slack 1 fish almost certainly snaps the line. Low-tension builds and Line/Hook enchants are essential for reliably landing these.
- **Small fish** have wide slack windows (7–9) so even a 4+4+3 snag combination (total 11) would snap only the most extreme rolls. They are catch-and-release territory unless a player needs 1pt to cross the 20pt threshold.
- **Effects density:** 14 of 40 fish have effects. Punishing effects appear at Big and Average tiers. Rewarding effects are spread across tiers.

---

# Runes and Reels — Shop Deck (50 cards)

Each shop lure has:
- **Tension Value** — added to line tension when cast from hand
- **Suit** — determined by enchant slot category (see below)
- **Cast Effect** — triggers when played as a lure during Fish On
- **Enchant Effect** — triggers when placed into a rune slot (persistent, activates once per Fish On phase unless stated)

**Suit by slot:**

| Slot | Suit |
|------|------|
| Hook | Red |
| Line | Blue |
| Rod | Green |
| Reel | Yellow |

A lure's suit is fixed to its slot category. A Hook lure is always Red regardless of which slot it is eventually enchanted into. This means drafting toward a rune build also shapes your casting hand's suit coverage.

---

## Hook Lures — Line Tension Management (13 cards) · Suit: Red

*Hook enchants reduce or manipulate your line tension during catch attempts.*

| # | Name | Tension | Cast Effect | Enchant Effect |
|---|------|---------|-------------|----------------|
| 1 | Barbed Jig | 2 | Your line tension counts as 1 lower this catch attempt. | Once per round: reduce your line tension by 1 before resolving a catch attempt. |
| 2 | Weighted Sinker | 3 | Ignore the tension from one snag card this catch attempt. | Snag cards in your catch attempts add a maximum of 1 tension regardless of face value. |
| 3 | Treble Hook | 4 | If you catch the fish, draw 1 card. | Whenever you catch a fish, draw 1 card. |
| 4 | Offset Hook | 1 | Your line tension is treated as 0 if you have no snag in play. | If you have no snag in play during a catch attempt, your lure tension counts as 1 lower. |
| 5 | Circle Hook | 2 | Re-roll any one snag's tension value and use the new result. | Once per round: re-roll one snag tension value after it is revealed. |
| 6 | Drop Shot Rig | 3 | Your line tension counts as 1 lower for each fish you have caught today (max –2). | Your line tension counts as 1 lower for each fish you have caught this round (max –2). |
| 7 | Gap Hook | 2 | If your lure matches the fish suit, your line tension counts as 2 lower. | Matching-suit catch attempts reduce your line tension by 1. |
| 8 | Worm Hook | 1 | Draw 1 card after this catch attempt resolves, regardless of outcome. | Whenever your line snaps, draw 1 card. |
| 9 | Aberdeen Hook | 3 | Treat your total line tension as halved (round up) this catch attempt. | Once per round: treat one snag's tension value as 1. |
| 10 | Needle Point | 4 | If your line tension exactly equals the fish's line slack, you catch it and draw 2 cards. | Whenever your line tension exactly equals the fish's line slack, you catch it and draw 1 card. |
| 11 | Siwash Hook | 2 | Discard 1 card from hand to reduce your line tension by 1 this catch attempt. | Once per round: discard 1 card to reduce your line tension by 1. |
| 12 | Kahle Hook | 3 | If you fail this catch attempt, choose which player attempts next instead of following catch order. | Once per round: if you fail a catch attempt, choose which player attempts next. |
| 13 | Octopus Hook | 2 | This lure's tension counts as 0 if you cast a matching suit. | Matching-suit lures you cast have their tension reduced by 1 (minimum 0). |

---

## Line Lures — Snag Interaction (12 cards) · Suit: Blue

*Line enchants change how snag cards contribute to your line tension.*

| # | Name | Tension | Cast Effect | Enchant Effect |
|---|------|---------|-------------|----------------|
| 14 | Floating Minnow | 3 | Roll a d4. Subtract the result from your line tension this attempt. | Once per round: after revealing a snag, roll a d4 and subtract the result from its tension value (minimum 0). |
| 15 | Braided Leader | 2 | If you have a snag in play, it adds 0 tension this catch attempt. | Snags you reveal add 1 less tension (minimum 0). |
| 16 | Monofilament Wrap | 1 | Ignore the snag under your lure entirely this catch attempt. | Once per round: ignore one snag card entirely when revealed. |
| 17 | Wire Trace | 3 | If your line snaps, remove your snag from the game instead of placing it in your deck. | Whenever your line snaps and you had a snag in play, remove it from the game instead of placing it in your deck. |
| 18 | Shock Leader | 2 | If you take a snag this cast, draw 1 card. | Whenever you are forced to take a snag, draw 1 card. |
| 19 | Fluorocarbon Rig | 4 | Your snag adds 0 tension this cast. Discard it after. | Once per round: your snag adds 0 tension. Discard it after. |
| 20 | Tapered Leader | 2 | Look at the top 2 cards of the snag deck. You may swap them. | At the start of each Fish On phase, look at the top card of the snag deck before casting. |
| 21 | Stiff Rig | 3 | If the fish has line slack 4 or lower, your snag adds 0 tension this attempt. | Snags add 0 tension when you attempt to catch fish with line slack 3 or lower. |
| 22 | Hair Rig | 2 | You may take a snag voluntarily (even with a matching suit) to draw 2 cards. | Once per round: take a snag voluntarily to draw 2 cards. |
| 23 | Chod Rig | 1 | If your snag has a draw or dock effect, trigger it and it adds 0 tension. | Once per round: a snag you reveal triggers its special effect and adds 0 tension. |
| 24 | Blow-Back Rig | 3 | If your line snaps, return your snag to the snag deck instead of your tackle deck. | Whenever your line snaps, return your snag to the snag deck instead of your tackle deck. |
| 25 | Inline Lead | 2 | Reduce your snag's tension by 2 this catch attempt (minimum 0). | Snags you reveal have their tension reduced by 1 (minimum 1). |

---

## Rod Lures — Casting (13 cards) · Suit: Green

*Rod enchants change how you play lures during the cast phase.*

| # | Name | Tension | Cast Effect | Enchant Effect |
|---|------|---------|-------------|----------------|
| 26 | Popper | 3 | Play a second lure face-down alongside this one. Use the higher value for catch order; sum both for line tension. | Once per round: play 2 lures face-down. Use the higher for catch order; sum both for line tension. |
| 27 | Spinnerbait | 2 | Draw 1 card before the reveal step this Fish On phase. | Once per round: draw 1 card before lures are revealed. |
| 28 | Crankbait | 4 | If this is the highest tension lure revealed, draw 2 cards after the round resolves. | Whenever you place first in catch order, draw 1 card. |
| 29 | Jerkbait | 3 | After all lures are revealed, you may swap this lure with a card from your hand. | Once per round: after reveal, swap your cast lure with any card from your hand. |
| 30 | Swimbait | 2 | Cast this lure as any suit regardless of the fish's suit. It counts as matching. | Your lures always count as matching the fish's suit for catch attempts (not tiebreakers). |
| 31 | Buzzbait | 3 | If you place first in catch order and catch the fish, all other players discard 2 cards. | Once per round: if you place first in catch order and catch the fish, all other players discard 2 cards. |
| 32 | Blade Bait | 2 | This lure's tension value counts as +1 for every snag currently in the play area (all players), maximum +3. | Your cast lure's tension value counts as +1 for each snag in the play area, maximum +3. |
| 33 | Topwater Frog | 4 | If you do not place first in catch order, return this lure to your hand instead of discarding it. | Once per round: if you do not place first in catch order, return your cast lure to your hand. |
| 34 | Trolling Lure | 1 | Cast face-up instead of face-down. You may swap your lure after all others are revealed but before catch attempts begin. | Once per round: reveal your lure last. You may swap it after seeing all others. |
| 35 | Soft Plastic | 2 | Cast 2 cards face-down. Discard 1 unrevealed before the reveal step. | Once per round: cast 2 lures face-down; discard 1 before reveal without showing it. |
| 36 | Jigging Spoon | 3 | If your lure ties with another player for catch order, you automatically win the tiebreaker this round. | Once per round: you win any catch order tiebreaker regardless of dock slot or suit. |
| 37 | Jig Head | 1 | Add 1 to this lure's value for catch order, but add 1 to your line tension on a catch attempt. | Your cast lures count as +1 for catch order but add +1 to line tension on catch attempts. |
| 38 | Stickbait | 4 | If this lure matches the fish suit and places first in catch order, draw 1 card before your catch attempt. | Whenever you place first in catch order with a matching-suit lure, draw 1 card before your catch attempt. |

---

## Reel Lures — Draw and Hand Management (12 cards) · Suit: Yellow

*Reel enchants affect how you draw, filter, and recover cards.*

| # | Name | Tension | Cast Effect | Enchant Effect |
|---|------|---------|-------------|----------------|
| 39 | Baitrunner | 2 | Draw 2 cards after this Fish On phase resolves. | Whenever your line snaps, draw 1 card. |
| 40 | Free Spool | 1 | Retrieve any 1 card from your discard pile and add it to your hand. | Once per round: retrieve 1 card from your discard pile. |
| 41 | Long Cast | 3 | Draw 3 cards, then discard 2. | At the start of each Fish On phase, draw 1 card then discard 1. |
| 42 | Drag Setter | 2 | Look at the top 3 cards of your tackle deck. Put them back in any order. | At the start of morning prep, look at the top 3 cards of your tackle deck and reorder them freely. |
| 43 | Line Counter | 1 | Draw 1 card. If you have 3 or more snags in your discard pile, draw 2 instead. | Draw 1 additional card during draw-up if you have 2 or more snags in your discard pile. |
| 44 | Bail Wire | 2 | Return 1 card from your discard pile to the bottom of your tackle deck. | Once per round: return 1 card from your discard to the bottom of your tackle deck. |
| 45 | Spinning Reel | 3 | Discard any number of cards from hand and draw that many plus 1. | Once per round: discard up to 2 cards and draw that many. |
| 46 | Baitcaster | 4 | Draw until you have 8 cards in hand. | Your hand size is 8 instead of 7. |
| 47 | Fly Reel | 2 | Place this card on the bottom of your tackle deck instead of discarding it after play. | Once per round: place any 1 card you would discard on the bottom of your tackle deck instead. |
| 48 | Level Wind | 1 | Draw 2 cards. Discard 1 card from your hand. | Whenever you draw cards during draw-up, draw 1 extra then discard 1. |
| 49 | Anti-Reverse | 3 | The next snag you would take this round goes to the bottom of your tackle deck instead of into play. | Once per round: the first snag you would take goes to the bottom of your tackle deck instead. |
| 50 | Centrepin | 2 | Reveal the top card of your tackle deck. You may discard it or leave it. | At the start of each Fish On phase, reveal the top card of your tackle deck and choose to discard it or leave it. |

---

## Design Notes

**Tension value distribution:**

| Tension | Count |
|---------|-------|
| 1 | 8 |
| 2 | 20 |
| 3 | 15 |
| 4 | 7 |

**Master fish interaction:** With line slack of 1–2, a catch attempt using a Tension 1 lure + Tension 1 follow-up = 2. Any snag snaps the line on a Slack 1 fish. Hook and Line enchants are essential for reliably targeting Master-bracket fish.

**Slot synergies to watch in playtesting:**
- Hook + Line creates very low line-tension builds optimised for Master fish
- Rod + Reel creates draw-engine builds with high catch-order presence
- Popper (Rod) + Drop Shot Rig (Hook) reward catching fish frequently and compound well
- Baitcaster (Reel) gives permanent hand size 8, overlapping with Creek's location bonus — acceptable since it costs a rune slot and a draft pick
- Stiff Rig (Line) references line slack 4 or lower for its cast effect and slack 3 or lower for enchant — confirm these thresholds feel right against the Big bracket (slack 3–4) in playtesting
