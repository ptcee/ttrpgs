# Runes and Reels

---

*Every spring, when the ice breaks on Lake Embervast and the amber water runs cold and clear, the anglers come.*

*They come from Glimmerhold and the Ashridge settlements, from the shore hamlets and the waypost towns along the southern road. They come with rune-carved rods and enchanted tackle, with family lures passed down through generations and new gear bought that morning from the Embervast dockside shops. They come to fish, to compete, and to carve their names into the weathered post at the end of the Big Dock.*

*Lake Embervast is the deepest body of water in southern Orrelia. Its floor has never been charted. The fish here run larger and stranger than anywhere else in the region, fed by mineral-rich runoff from the Ashridge peaks that turns the water a warm amber at dusk. Locals say things live in the lower water that have never been seen. The runesmiths who certify tackle at the dawn inspection say the same enchants behave differently here, like they force the lake to pay attention.*

*The Embervast Derby began as a tithe-fishing event three hundred years ago, when the shore settlements needed a hard winter feed and one good season could make the difference. The angler who contributed most was granted a season's debt forgiveness by the Glimmerhold merchant charters. The debt forgiveness is ceremonial now, but the Embervast Charter, a legal document granting the winner naming rights to one unnamed feature of the lake for a year, is still technically binding. People take it seriously.*

*The Gilded Seer has been landed three times in the derby's recorded history. Each winner's name is carved into Big Dock's post below the waterline, visible only at low water. Nobody knows who carved there first or when.*

*Tight lines.*

---

## Core Concepts

**Line Slack** - the stat on each fish card. Represents how much give a fish allows on the line. Big powerful fish run slow and heavy, keeping slack low. Small skittish fish dart and pull tight, giving the angler more room to work with.

**Line Tension** - the sum of all lure values, snag values, and active effects during a catch attempt. Must stay **equal to or under** the fish's Line Slack or the line snaps.

> A Master-tier fish has low Line Slack (1-2). You must use very low-tension lures to land it.
> A Small-tier fish has high Line Slack (7-9). Almost any lure combination will stay under the threshold.

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
- When revealed face-up, snag cards add **1-3** to your line tension
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

Each player has four permanent equipment slots that persist across all rounds. Each player may place up to 1 lure into a rune slot during Morning Prep.

If that slot already contains an enchantment, the new enchantment replaces it.

Players may have one enchantment in each of the four rune slots.

Enchantments are either **passive** or **active**:

**Passive enchantments** trigger automatically whenever their condition is met. They are always on and require no decision to activate.

**Active enchantments** are marked *Once per round* and must be deliberately triggered. You may activate **one active enchantment per revealed fish**, regardless of how many active runes you have slotted. You may use a different active rune on each of the three Fish On phases.

| Slot | Suit | Effect Category |
|------|------|----------------|
| **Hook** | Red | Line tension management (reduce tension, re-roll snag values) |
| **Line** | Blue | Snag interaction (ignore snags, reduce snag tension) |
| **Rod** | Green | Casting (play 2 lures, draw before casting) |
| **Reel** | Yellow | Draw and hand management (draw extra, retrieve from discard) |

---

### Locations (4 cards)

The angler in dock slot 1 chooses a location each round. Each location grants a bonus to the player(s) with the **fewest pouches of gold**.

| Location | Trailing Player Bonus |
|----------|-----------------------|
| **Creek** | Hand size is 8 whenever drawing cards this round |
| **River** | May discard the first revealed fish to reveal a new one |
| **Pond** | May discard up to 2 cards before drawing at end of each Fish On phase |
| **Lake** | May remove one snag card from hand, then draw a replacement |

> **Tied for last:** All tied players receive the bonus. If all players are tied, nobody receives it.

---

### Scoring Brackets

Fish are worth **pouches of gold** when caught. The winner is the first angler to collect **20 pouches of gold**.

| Bracket | Pouches of Gold | Line Slack |
|---------|----------------|------------|
| Small | 1 pouch | 7-9 |
| Average | 2 pouches | 5-6 |
| Big | 3 pouches | 3-4 |
| Master | 5 pouches | 1-2 |

---

## Gameplay

Each round consists of **Morning Prep** followed by **three Fish On phases**.

---

### Morning Prep

#### 1. Draft Lures

Starting with the angler in dock slot 1 (or randomly on the first round):

- **a)** Reveal lures from the shop deck equal to the number of players.
- **b)** Players draft one lure each.
- The first drafter rotates each set.
```
Set 1: 4 → 3 → 2 → 1
Set 2: 3 → 2 → 1 → 4
Set 3: 2 → 1 → 4 → 3
```
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

#### Step 1 - Reveal the Fish

- Flip the top card of the fish deck face-up.
- Note the fish's **Line Slack**, **Suit**, **Bracket**, and any **Effects** for this phase.

#### Step 2 - Cast

In dock order:
- Each player selects 1 lure from their hand and places it **face-down**.
- The lure must **match the fish's suit** if possible.
- Enchantments are activated depending on each rune's conditions.
- If you have **no matching suit** in hand, take the **top card of the snag deck** and place it face-down **horizontally beneath** your lure.

#### Step 3 - Reveal

All players flip their lures face-up simultaneously.

**Determine catch order** (highest lure tension value goes first):

1. Highest lure tension value
2. Tie → lowest dock slot number wins
3. Still tied → matching suit wins
4. Still tied → each tied player reveals one additional lure; higher value wins

#### Step 4 - Catch Attempt

The leading player attempts to land the fish:

1. **Flip up** any snag card beneath your lure.
2. **Play one additional lure** from your hand.
3. Calculate **line tension**: cast lure + additional lure + snag value + any active effects.
4. Compare to the fish's Line Slack:
   - **Line Tension ≤ Line Slack** → Fish caught. Take the fish card and place it beside your tackle deck.
   - **Line Tension > Line Slack** → Line snaps. If you had a snag in play, place it on the **bottom of your tackle deck**.

If the fish is not caught, the **next player in catch order** attempts in the same manner. Continue until the fish is caught or all players have failed (fish gets away).

#### Step 5 - Draw Up

All players draw back up to **7 cards**.

> If your tackle deck runs out, shuffle your discard pile to form a new tackle deck.

---

## Winning

The first player to collect **20 pouches of gold** wins the Embervast Derby.

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
  └─ Reveal lures - highest tension value goes first in catch order
  └─ Catch attempt: flip snag, play 1 more lure, check line tension vs line slack
  └─ Next player in catch order attempts if fish not caught
  └─ All draw up to 7

REPEAT
```

---

# Fish Deck (40 cards)

Each fish has a **Line Slack** value, a **Suit**, a **Scoring Bracket**, and optional **Effects**.

Line Tension during a catch attempt must stay **equal to or under** Line Slack or the line snaps.

| Bracket | Pouches of Gold | Line Slack |
|---------|----------------|------------|
| Small | 1 pouch | 7-9 |
| Average | 2 pouches | 5-6 |
| Big | 3 pouches | 3-4 |
| Master | 5 pouches | 1-2 |

Suit distribution: 10 Red, 10 Yellow, 10 Blue, 10 Green.

---

## Master (5 pouches, Slack 1-2) - 6 cards

*Tight window. Low-tension lures only. Any snag is extremely dangerous.*

| # | Name | Slack | Suit | Effect |
|---|------|-------|------|--------|
| 1 | The Gilded Seer | 1 | Red | Only the player with the lowest tension cast among players matching the fish's suit may attempt. |
| 2 | Old Slate | 1 | Blue | - |
| 3 | The Deepwalker | 2 | Green | The catching player must succeed on their first attempt or the fish escapes (no chain). |
| 4 | Ambervast Queen | 2 | Yellow | Players may not activate enchantments this round. |
| 5 | Greymantle | 2 | Red | - |
| 6 | The Pale Runner | 2 | Blue | Each player must discard 1 card before casting. |

---

## Big (3 pouches, Slack 3-4) - 10 cards

*Forgiving enough for mid-range lures. Snags still threaten on Slack 3.*

| # | Name | Slack | Suit | Effect |
|---|------|-------|------|--------|
| 7 | Ashridge Pike | 3 | Green | - |
| 8 | Stoneback | 3 | Red | - |
| 9 | Coldwater Brak | 3 | Blue | - |
| 10 | Kelwick's Carp | 3 | Yellow | Each player draws 1 card before casting. |
| 11 | Gloomfin | 4 | Green | Catch order is reversed this round (lowest tension cast goes first). |
| 12 | Silverthread | 4 | Yellow | Each player must take a snag regardless of suit in hand. |
| 13 | Copperscale | 4 | Red | Players may play 2 lures this round. Line tension is the sum of both. |
| 14 | The Embervast Long | 4 | Blue | - |
| 15 | Duskfin | 4 | Green | - |
| 16 | Mudgut | 4 | Red | The first player to fail a catch attempt this round draws 2 cards. |

---

## Average (2 pouches, Slack 5-6) - 14 cards

*The bread and butter of most rounds.*

| # | Name | Slack | Suit | Effect |
|---|------|-------|------|--------|
| 17 | Shoremouth Char | 5 | Blue | - |
| 18 | Gollow | 5 | Yellow | - |
| 19 | Thornback | 5 | Green | Snag cards this round add +1 to their tension value. |
| 20 | The Watcher | 5 | Red | All players must cast their highest tension lure this round. |
| 21 | Flatstone | 5 | Yellow | - |
| 22 | Greyeye | 5 | Blue | - |
| 23 | Brackenfin | 6 | Green | - |
| 24 | Redgill | 6 | Red | - |
| 25 | Tallow Bream | 6 | Yellow | - |
| 26 | Deepcaller | 6 | Blue | - |
| 27 | Stillwater Bass | 6 | Green | Players may not activate enchantments this round. |
| 28 | The Itch | 6 | Red | This fish may only be caught by a player with no snag in play. |
| 29 | Amber Drifter | 6 | Yellow | Each player may discard 1 card and draw 1 card before casting. |
| 30 | Snapper | 6 | Blue | The angler in dock slot 1 must cast first and reveal their lure immediately. |

---

## Small (1 pouch, Slack 7-9) - 10 cards

*Wide window. Almost any combination lands these.*

| # | Name | Slack | Suit | Effect |
|---|------|-------|------|--------|
| 31 | Gillyfish | 7 | Yellow | - |
| 32 | Pebbleback | 7 | Blue | - |
| 33 | Mudmover | 7 | Green | - |
| 34 | Shore Dart | 7 | Red | - |
| 35 | Tallow Pip | 8 | Yellow | - |
| 36 | Coppernose | 8 | Red | - |
| 37 | Rockwriggler | 8 | Green | - |
| 38 | Shimmer | 8 | Blue | - |
| 39 | The Lucky One | 9 | Yellow | The player who catches this fish draws 2 cards. |
| 40 | Snagbait | 9 | Blue | Snags reduce cast lure tension by 1 this round (minimum 0). |

---

## Fish Deck Design Notes

- **Master fish** are rare (6 cards) and punishing. A single snag on a Slack 1 fish almost certainly snaps the line. Low-tension builds and Line/Hook enchants are essential.
- **Small fish** have wide slack windows (7-9). They are mostly incidental catches unless a player needs 1 pouch to close out the game.
- **Effects density:** 14 of 40 fish have effects. Punishing effects appear at Big and Average tiers. Rewarding effects are spread across tiers.

---

# Shop Deck (50 cards)

Each shop lure has:
- **Tension Value** - added to line tension when cast from hand
- **Suit** - determined by enchant slot category (see below)
- **Cast Effect** - triggers when played as a lure during Fish On
- **Enchant Effect** - triggers when placed into a rune slot (persistent, activates once per Fish On phase unless stated)

**Suit by slot:**

| Slot | Suit |
|------|------|
| Hook | Red |
| Line | Blue |
| Rod | Green |
| Reel | Yellow |

A lure's suit is fixed to its slot category. A Hook lure is always Red regardless of which slot it is eventually enchanted into. Drafting toward a rune build also shapes your casting hand's suit coverage.

---

## Hook Lures - Line Tension Management (13 cards) · Suit: Red

*Hook enchants reduce or manipulate your line tension during catch attempts.*

| # | Name | Tension | Cast Effect | Enchant Effect |
|---|------|---------|-------------|----------------|
| 1 | Barbed Jig | 2 | Your line tension counts as 1 lower this catch attempt. | Once per round: reduce your line tension by 1 before resolving a catch attempt. |
| 2 | Weighted Sinker | 3 | Ignore the tension from one snag card this catch attempt. | Snag cards in your catch attempts add a maximum of 1 tension regardless of face value. |
| 3 | Treble Hook | 4 | If you catch the fish, draw 1 card. | Whenever you catch a fish, draw 1 card. |
| 4 | Offset Hook | 1 | Your line tension is treated as 0 if you have no snag in play. | If you have no snag in play during a catch attempt, your lure tension counts as 1 lower. |
| 5 | Circle Hook | 2 | Re-roll any one snag's tension value and use the new result. | Once per round: re-roll one snag tension value after it is revealed. |
| 6 | Drop Shot Rig | 3 | Your line tension counts as 1 lower for each fish you have caught today (max -2). | Your line tension counts as 1 lower for each fish you have caught this round (max -2). |
| 7 | Gap Hook | 2 | If your lure matches the fish suit, your line tension counts as 2 lower. | Matching-suit catch attempts reduce your line tension by 1. |
| 8 | Worm Hook | 1 | Draw 1 card after this catch attempt resolves, regardless of outcome. | Whenever your line snaps, draw 1 card. |
| 9 | Aberdeen Hook | 3 | Treat your total line tension as halved (round up) this catch attempt. | Once per round: treat one snag's tension value as 1. |
| 10 | Needle Point | 4 | If your line tension exactly equals the fish's line slack, you catch it and draw 2 cards. | Whenever your line tension exactly equals the fish's line slack, you catch it and draw 1 card. |
| 11 | Siwash Hook | 2 | Discard 1 card from hand to reduce your line tension by 1 this catch attempt. | Once per round: discard 1 card to reduce your line tension by 1. |
| 12 | Kahle Hook | 3 | If you fail this catch attempt, choose which player attempts next instead of following catch order. | Once per round: if you fail a catch attempt, choose which player attempts next. |
| 13 | Octopus Hook | 2 | This lure's tension counts as 0 if you cast a matching suit. | Matching-suit lures you cast have their tension reduced by 1 (minimum 0). |

---

## Line Lures - Snag Interaction (12 cards) · Suit: Blue

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

## Rod Lures - Casting (13 cards) · Suit: Green

*Rod enchants change how you play lures during the cast phase.*

| # | Name | Tension | Cast Effect | Enchant Effect |
|---|------|---------|-------------|----------------|
| 26 | Popper | 3 | Play a second lure face-down alongside this one. Use the higher value for catch order; sum both for line tension. | Once per round: play 2 lures face-down. Use the higher for catch order; sum both for li
