# Runes and Reels

A fishing card game for 2-4 players. Draft lures, cast your line, and manage your tension to land the biggest catch. First player to collect **20 points** worth of fish wins.

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

> **Split Cards:** When playing a split card, orient it so the value you want to use is on the side closest to the center of the tackle deck. The other value is ignored.

> **Wild Cards:** A wild card can be declared as any suit. It counts as the fish's suit when resolving tiebreakers.

---

### Shared Decks

**Fish Deck**
- Each fish has a **Power** value (also its point value when scored)
- Each fish has a **Suit** (Red, Yellow, Blue, or Green)
- Some fish have **Effects** that apply for the round they are revealed

**Snag Deck** (40 cards)
- When revealed face-up, snag cards add **1-3** to your line tension
- Some snag cards have special effects when flipped up:

| Qty | Effect |
|-----|--------|
| 4 | Draw a card |
| 3 | Gain the First Player token |
| 3 | Reduce your line tension by 1 instead |

**Shop Deck** (50 cards)
- Each shop lure has a **Tension Value** and a **Cast Effect** (used when played from hand)
- Each shop lure also has an **Enchant Effect** (used when placed permanently into a rune slot)

---

### Rune Slots

Each player has four permanent equipment slots that persist across all rounds. A slot can hold one enchantment at a time and may be **overwritten** by placing a new lure into it.

| Slot | Effect Category |
|------|----------------|
| **Hook** | Tension calculation (e.g. reduce tension by 1, re-roll snag value) |
| **Line** | Snag interaction (e.g. ignore first snag, snags add 0 this round) |
| **Rod** | Casting (e.g. play 2 lures, draw before casting) |
| **Reel** | Draw / hand (e.g. draw an extra card, retrieve a card from discard) |

---

### Locations (4 cards)

The first player chooses one location each round. Each location grants a bonus to the player(s) with the **lowest current score**.

| Location | Trailing Player Bonus |
|----------|-----------------------|
| **Creek** | Hand size is 8 whenever drawing cards this round |
| **River** | May discard the first revealed fish to reveal a new one |
| **Pond** | May discard up to 2 cards before drawing at end of each Fish On phase |
| **Lake** | May remove one snag card from hand, then draw a replacement card |

> **Tied for last:** If multiple players share the lowest score, all of them receive the location bonus. If all players are tied, nobody receives it.

---

## Gameplay

Each round consists of **Morning Prep** followed by **three Fish On phases**.

---

### Morning Prep

#### 1. Draft Lures

Starting with the player who caught the fewest fish last round (or randomly on the first round):

- **a)** Reveal lures from the shop deck equal to the number of players.
- **b)** Players snake draft one lure each.
- On your draft turn, you may **forgo your pick** to claim the **First Player token** (arriving at the dock first). You take no lure that turn.

Repeat steps **a** and **b** two more times (three draft sets total).

#### 2. Prepare Your Tackle

1. Each player may place **1 lure** face-down into a rune slot as an enchantment.
2. Place all remaining drafted cards onto your **tackle deck**.
3. The **First Player** chooses a location.
4. Shuffle your tackle deck and draw **7 cards**.

---

### Fish On

Repeat this phase **three times** per round.

#### Step 1 — Reveal the Fish

- Flip the top card of the fish deck face-up.
- Note the fish's **Power**, **Suit**, and any **Effects** for this phase.

#### Step 2 — Cast

- Each player selects 1 lure from their hand and places it **face-down**.
- The lure must **match the fish's suit** if possible.
- Players may **activate one imbued enchantment** at this point.
- If you have **no matching suit** in hand, take the **top card of the snag deck** and place it face-down **horizontally beneath** your lure before you place it.

#### Step 3 — Reveal

All players flip their lures face-up simultaneously.

**Determine who attempts to catch first** (highest lure power goes first):

1. Highest lure power wins
2. Tie → First Player wins
3. Still tied → Same suit as fish wins
4. Still tied → Each tied player reveals one additional lure; higher value wins

#### Step 4 — Catch Attempt

The winning player attempts to land the fish:

1. **Flip up** any snag card played beneath your lure.
2. **Play one additional lure** from your hand.
3. Calculate your **line tension**: lure card + snag value + any other active effects.
4. Compare to the fish's Power:
   - **Tension ≤ Fish Power** → Fish caught! Take the fish card and place it beside your tackle deck.
   - **Tension > Fish Power** → Line snaps. If you had a snag in play, place it on the **bottom of your tackle deck**.

If the fish is not caught, the **next highest power player** attempts in the same manner. Continue until the fish is caught or all players have failed (fish gets away).

#### Step 5 — Draw Up

All players draw back up to **7 cards**.

> If your tackle deck runs out, shuffle your discard pile to form a new tackle deck.

---

## Winning

The first player to accumulate **20 or more points** worth of caught fish wins.

---

## Reference: Turn Order Summary

```
MORNING PREP
  └─ Draft lures (3 sets, snake order)
  └─ Place 1 enchantment
  └─ First player chooses location
  └─ Shuffle tackle deck, draw 7

FISH ON (× 3)
  └─ Reveal fish
  └─ Players cast lures face-down (+ snag if no suit)
  └─ Activate enchantment (optional)
  └─ Reveal lures — highest power catches first
  └─ Catch attempt: flip snag, play 1 more card, check tension
  └─ Next player attempts if fish not caught
  └─ All draw up to 7

REPEAT
```
