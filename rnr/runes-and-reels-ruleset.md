# Runes and Reels

---

*Every spring, when the ice breaks on Lake Embervast and the amber water runs cold and clear, the anglers come.*

*They come from Glimmerhold and the Ashridge settlements, from the shore hamlets and the waypost towns along the southern road. They come with rune-carved rods and enchanted tackle, with family lures passed down through generations and new gear bought that morning from the Embervast dockside shops. They come to fish, to compete, and to carve their names into the weathered post at the end of the Big Dock.*

*Lake Embervast is the deepest body of water in southern Orrelia. Its floor has never been charted. The fish here run larger and stranger than anywhere else in the region, fed by mineral-rich runoff from the Ashridge peaks that turns the water a warm amber at dusk. Locals say things live in the lower water that have never been seen. The runesmiths who certify tackle at the dawn inspection say the same enchants behave differently here, like they force the lake to pay attention.*

*The Embervast Derby began as a tithe-fishing event three hundred years ago, when the shore settlements needed a hard winter feed and one good season could make the difference. The angler who contributed most was granted a season's debt forgiveness by the Glimmerhold merchant charters. The debt forgiveness is ceremonial now, but the Embervast Charter, a legal document granting the winner naming rights to one unnamed feature of the lake for a year, is still technically binding. People take it seriously.*

*The Golden Mahseer has been landed three times in the derby's recorded history. Each winner's name is carved into Big Dock's post below the waterline, visible only at low water. Nobody knows who carved there first or when.*

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
- Enchantments are activated depending on each runes conditions.
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
| 1 | Golden Mahseer | 1 | Red | Only the player with the lowest tension cast among players matching the fish's suit may attempt. |
| 2 | Taimen | 1 | Blue | — |
| 3 | Sturgeon | 2 | Green | The catching player must succeed on their first attempt or the fish escapes (no chain). |
| 4 | Arapaima | 2 | Yellow | Players may not activate enchantments this round. |
| 5 | Giant Trevally | 2 | Red | — |
| 6 | Siamese Carp | 2 | Blue | Each player must discard 1 card before casting. |

---

## Big (3 pouches, Slack 3-4) - 10 cards

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

## Average (2 pouches, Slack 5-6) - 14 cards

*The bread and butter of most rounds.*

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

## Small (1 pouch, Slack 7-9) - 10 cards

*Wide window. Almost any combination lands these.*

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

## Fish Deck Design Notes

- **Master fish** are rare (6 cards) and punishing. A single snag on a Slack 1 fish almost certainly snaps the line. Low-tension builds and Line/Hook enchants are essential.
- **Small fish** have wide slack windows (7–9). They are mostly incidental catches unless a player needs 1 pouch to close out the game.
- **Effects density:** 14 of 40 fish have effects. Punishing effects appear at Big and Average tiers. Rewarding effects are spread across tiers.

---

# Shop Deck (50 cards)

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

A lure's suit is fixed to its slot category. A Hook lure is always Red regardless of which slot it is eventually enchanted into. Drafting toward a rune build also shapes your casting hand's suit coverage.

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

## Interactive Lures — Player Targeting (12 cards)

*These lures have effects that directly interact with other anglers. All effects are triggered by game state rather than named targets, no player is singled out by choice. Distributed across all four suits (3 per suit). These are additional shop cards.*

> **Designer note:** These are held separately so to test the base 50 card shop deck first and introduce interactive effects once the core loop is stable.

| # | Name | Suit | Tension | Cast Effect | Enchant Effect |
|---|------|------|---------|-------------|----------------|
| S1 | Sabiki Rig | Red | 2 | The player to your left must discard 1 card. | Once per round: when you successfully catch a fish, the player to your left discards 1 card. |
| S2 | Snag Transfer | Red | 3 | If you have a snag in play, pass it to the player ahead of you in catch order instead. They must include it in their attempt. | Once per round: pass your snag to the next player in catch order instead of resolving it yourself. |
| S3 | Fouled Cast | Red | 1 | Name a suit. Each player holding no cards of that suit must take a snag. | Once per round: name a suit. Each player who casts a non-matching lure this phase takes a snag in addition to any other effects. |
| S4 | Chumming | Blue | 2 | Each other player draws 1 card. You draw 2. | Once per round: each other player draws 1 card. You draw 2. |
| S5 | Undercut | Blue | 3 | If another player's cast lure is higher tension than yours, reduce theirs by 1 for catch order this phase. | Once per round: reduce the highest tension cast lure on the table by 1 for catch order purposes (not line tension). |
| S6 | Tangled Lines | Blue | 2 | Choose two other players. They swap their cast lures before catch order is resolved. | Once per round: two other players of your choice swap their cast lures before catch order is resolved. |
| S7 | Poach | Green | 4 | If you place second in catch order and the first player fails, your line tension counts as 1 lower for your attempt. | Once per round: if you place second in catch order, your line tension counts as 1 lower. |
| S8 | Cut Current | Green | 2 | The player in dock slot 1 must move to the last open dock slot next round. | Once per round: if you catch the fish, the player in dock slot 1 moves to the last open slot next round. |
| S9 | Lure Snatch | Green | 3 | Look at another player's cast lure before reveal. You may swap your cast lure with theirs. They do not see yours first. | Once per round: after casting but before reveal, look at one other player's face-down lure and swap yours with it if you choose. |
| S10 | Flood the Pool | Yellow | 1 | Each player draws 2 cards then discards 2 cards. | Once per round: each player draws 2 cards then discards 2 cards. |
| S11 | False Cast | Yellow | 2 | Place a lure face-down. Before reveal, you may swap it with any card from your hand without showing either. The player to your right must also reveal their lure one step later than normal. | Once per round: delay one other player's lure reveal by one step. You may change your own lure after seeing theirs. |
| S12 | Downrigger | Yellow | 3 | The player with the most pouches of gold must cast their highest tension lure this phase. | Once per round: the player with the most pouches of gold must cast their highest tension lure this phase. |

---

## Shop Deck Design Notes

**Tension value distribution (base 50):**

| Tension | Count |
|---------|-------|
| 1 | 8 |
| 2 | 20 |
| 3 | 15 |
| 4 | 7 |

**Master fish interaction:** With line slack of 1–2, a catch attempt using a Tension 1 lure + Tension 1 follow-up = 2. Any snag snaps the line on a Slack 1 fish. Hook and Line enchants are essential for reliably targeting Master-bracket fish.

**Interactive lure notes:**
- Snag Transfer and Lure Snatch are politically charged, watch table reactions. Both are game-state conditional rather than free-target, which should keep them from feeling personal.
- Downrigger is a soft leader punish that scales naturally without tracking.
- Cut Current is the most powerful dock manipulation in the deck...????
