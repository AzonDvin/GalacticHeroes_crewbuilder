# Core Rules (pp. 4–21)

## Turn Sequence

Each turn has 2 phases:

1. **Shuffle** — gather ALL cards (discards + unplayed) and shuffle together before each turn, so every round has a fresh chance at Special Cards.
2. **Deal & Activate** — each player is dealt 1 card per miniature they control. Play proceeds from **King → Queen → Jack → 10 → 9 … → 2** (a designated Caller calls out each rank). Every player holding that rank throws it down and activates one model. A card activates exactly one model for **2 actions**; cards cannot be saved for later. Once activated, a model can't be reactivated until next turn.

**Suit precedence for ties** (when 2+ players hold the same rank): ♠ Spades → ♥ Hearts → ♦ Diamonds → ♣ Clubs (last).

**Aces are wild** — can represent any rank, but must be played "in sequence" (i.e., an Ace used as a "7" must be played when sevens are called). A *real* card of that rank always goes before an Ace impersonating it. If multiple Aces impersonate the same rank, Spade > Heart > Diamond > Club order applies among them.

If a model is eliminated before its card is drawn, the extra card is held and discarded at end of turn (not replayed).

**Quality die**: default is d10. Traits can change this: Veteran = d12 for ALL rolls, Green = d8 for ALL rolls, Ranged Fighter = d12 for Shooting / d8 for Close Combat (other rolls stay d10), Grunts = d8 always.

Roll of "1" is generally bad, "10" (the 0 face) or above is generally good; some conditions trigger specifically off these.

## Special Cards

Played just like a normal activation card, but grants a bonus:

| Card | Effect |
|---|---|
| Queen of Hearts | If the activated model has Wounds, heal ONE (remove a Wound counter instantly; may stand if prone). Still gets 2 actions. |
| Queen of Spades | If the activated model is Shaken, it recovers instantly (remove ALL Shock markers). Still gets 2 actions. |
| One-Eyed Jacks (♥♠) | +1 to Shooting rolls this turn. |
| Two-Eyed Jacks (♦♣) | +1 to Close Combat rolls this turn. |
| Sevens (any suit) | Re-roll any ONE die result this turn. |
| Sixes (any suit) | Automatic reload (overrides normal 2-action reload rule). Model still gets 2 actions. |
| Twos (any suit) | May roll 2 dice once for any Shooting/Close Combat/Task/Recovery roll and keep the best. |
| Aces (any suit) | Wild — see above. |

## Actions

Each activation = **2 actions**, which can be any combination of: Move, Shoot, pick up/drop something, get on/off a mount, switch weapons, recover from Shaken/Prone, Aim, Reload, complete a Task, or anything else players agree on. Actions can repeat (e.g., move twice, shoot twice) or differ (move then shoot).

- Recovering from Shaken or standing after Wounded costs 1 action, only 1 attempt/turn. Fail → no further actions except falling back. Succeed → get 1 more action.
- Reload / auto-remove-one-Shaken costs 2 uninterrupted actions.

### Movement

Base rates per action: **Creeping 3" · Walking 5" · Mounted 8" · Vehicle 6"**. Any number of turns/facing changes allowed mid-move. Moving within 1" of an enemy forces a stop and triggers Close Combat. Miniatures see/act in all directions (no facing for combat purposes). Miniatures can't be pushed off-table involuntarily — they just stop at the edge.

**Jumping**: max jump = distance moved that action in a straight line beforehand (a model with 5" move that moved 5" can jump up to 5", counted against total move — can't move 5" + jump 5" + move 5" more in one turn). Max 1" up, 3" down. Roll a d10 before jumping: natural "1" = misjudged, results in a fall. Can't jump over other figures without a skill allowing it.

**Falling**: roll d10 +1 per 3" fallen on the Wound Chart.

**Creeping**: 3" instead of 5", place a Creep marker (removed on normal move/shoot/coming within 12" of enemy). Enemies shooting at a creeping model do so at −1.

### Terrain movement modifiers

| Modifier | Effect |
|---|---|
| Wounds | −1" move per Wound, per move action |
| Shock | −1" move per Shock marker, per move action |
| Difficult terrain (woods, tall crops, marsh, shallow streams, rubble) | Half rate (2.5" foot / 4" mounted) |
| Impassable (cliffs, wide/deep rivers) | Can't cross |
| Obstacles: low wall/fence (half miniature height) | −1" per Move action |
| Obstacles: high wall (miniature height) | Full action |
| Up/down a floor in a building | −3" |

Mounts can't enter buildings. Entering/exiting a building is free unless the scenario says the door is locked/closed. Roof access from ground floor costs the stair-equivalent measured from entry point unless the building has defined interiors.

## Shooting

Line of sight must be a straight, unobstructed line (no passing through other models/terrain). Models are only visible inside terrain/buildings if within 1" of a door/window/treeline edge (same for shooting out). 360° field of fire, no facing.

**To hit**: roll the Quality die. **Short range = 5+. Long range = 8+.**

**Out of Ammo**: rolling a natural "1" on a Shoot roll places an Out of Ammo marker; the model can't shoot again until it spends 2 consecutive actions reloading (can't split across turns — but the other action that turn can be used for something else, e.g. moving to cover).

### Shooting modifiers

| Category | Modifier |
|---|---|
| Light Cover | −1 |
| Heavy Cover | −2 |
| Target Small | −1 |
| Target Large | +1 |
| Target Huge | +2 |
| Per Wound/Shock marker on the **shooter** | −1 each |
| Shooter mounted | −1 |
| Target mounted | −1 |
| Target Creeping | −1 |
| Target prone (only from being Wounded — can't voluntarily go prone) | −1 |
| Shooter used 1st action to Aim | +1 |

**Cover**: behind a linear obstacle like a wall = Heavy Cover (−2) unless the shooter can outflank it (same building/side of wall). Behind something less substantial (wooden fence) = Light Cover (−1).

**Area terrain** (woods, tall crops — must have a defined edge, agreed pre-game): must be within 1" of the edge to shoot out or be targeted; automatically Light Cover (−1); models >1" from the edge can't be targeted; two models sharing the same area terrain feature only have 6" visibility of each other.

**Darkness**: line of sight capped at 12" and all weapon ranges halved, unless a scenario says otherwise.

**Shooting into groups**: measure to the intended target; if the tape crosses any other miniature, that model is also a potential target. Roll to hit as normal; on a hit, randomize who's struck (2 targets = odds/evens; 3 targets = 1–3/4–6/7–9, reroll a 10).

## Close Combat

Triggered automatically when a model ends movement within 1" of an enemy (even mid-move with actions still left), or must be initiated deliberately with an action otherwise (max 1 initiated Close Combat per activation unless a Trait says otherwise — other models can still initiate more, creating Multiple Combats). If a model starts its turn within 1" of an enemy, it **must** use its first action to fight (overrides Recovery).

**Resolution**: both sides roll their Quality die + modifiers. Higher **modified** total wins; margin (winner's total − loser's total) sets the Wound-roll bonus:

| Margin | Wound roll bonus |
|---|---|
| 1–2 | +0 |
| 3–4 | +1 |
| 5–6 | +2 |
| 7+ | +3 |

Tie: no Wound roll, but the initiator may still choose to hold, push, or swap positions.

**Winner may**: (A) stay locked in combat, (B) push the loser back up to 2" out of Close Combat range, or (C) switch positions with the loser (useful to avoid being backed off a ledge).

Models can't be "outflanked" — a newly-engaged model turns to face its attacker, so there's no rear-attack bonus.

**Natural "1" in Close Combat = Fumble**: in addition to the opponent's Wound roll effect, the model is disarmed (loses that weapon for the rest of the game unless re-armed or it spends an action to pick it back up — can't do so while still in Close Combat range).

**Multiple Combatants**: if a model is engaged by a second attacker while still fighting the first, all involved roll simultaneously (with modifiers); a model can beat one opponent and lose to another in the same activation.

### Close Combat modifiers

| Modifier | Value |
|---|---|
| Per Wound/Shock marker on the model | −1 each |
| Charging (moved in from outside the defender's 1" zone) | +1 (not if already in Close Combat) |
| Mounted vs dismounted | +1 (defeated dismounted model is dragged from mount if Wounded) |
| Outnumbered | −1 per attacker beyond the first (−1 for 2 attackers, −2 for 3, etc.) |
| Prone or no weapon | −1 |
| Close Combat weapon bonus | per weapon, see weapons-armor-gear.md |
| Defending a wall/defensive terrain | +1 |

**Recommended resolution order** (per the book): roll dice → total modifiers → apply to get final roll → compare totals → roll on Wound Chart.

**Knocking down doors/fences**: treated like Close Combat vs. a fixed defense roll — Wooden fence 3, Door 4, Reinforced door 6, Stone wall/rubble 7. Beat the roll, then use the margin on the Wound Chart as normal (Shock = no effect, Wound = damages it, Out of Action = destroys it / 2"-wide hole). Structures can be assigned Wounds (suggested: 3).

## Wounding

Roll on the **Wound Chart** whenever a miniature is hit by Shooting, Close Combat, or falling. Add +1 to the roll for each Wound the target already has.

| Roll | Result |
|---|---|
| 0 or less | No effect |
| 1–5 | Shaken (Shock marker) |
| 6–8 | Wounded & Down |
| 9–10+ | Out of Action |

**3 Wounds = Out of Action** (baseline; some Traits raise/lower the cap — Tough as Nails/Large = 4, Small/Weakling = 2).

**Shaken**: no damage, but a Shock marker is added. If from Shooting while in cover, the model stays put; if in the open, it must immediately move toward the nearest cover (never toward an enemy). If from Close Combat, the winner may hold, push 2", or swap positions; loser gets the Shock marker. Next activation, the model may attempt Recovery (if not within 1" of an enemy). Each Shock marker gives −1 to Shooting/Close Combat/Task/Recovery rolls and −1" move per action, cumulative and stacking with Wound penalties.

**Wounded & Down**: model drops prone (mark "Down"). −1 per Wound to Shooting/Close Combat/Task/Recovery rolls, and −1" move per Wound, per action — stacks with Shock. A down/wounded model doesn't exert the 1" Close Combat zone of control. If attacked in Close Combat while down, it stays down and takes the Wound penalty **plus** an additional −1 for being down, plus any Shock penalty. If it wins that fight, it may immediately attempt a Recovery roll to stand. Falling wounded within 1" of a rooftop edge: roll d10, even = falls wounded on the roof, odd = falls off (roll again on Wound Chart, +1 per 3" fallen).

Mounted models that are Wounded/defeated fall off; the mount runs off (or, if tracked separately, wanders d10" using the die's "point" for direction).

**Out of Action**: remove from the table (may be dead, incapacitated, or fled — narrative is up to you).

**Armor**: can reduce results by one step — see `weapons-armor-gear.md`.

### The 6 states a miniature can be in
Okay · Shaken · Wounded · Wounded & Down · Wounded & Shaken · Wounded, Shaken & Down (standing after Recovery from this last state still leaves the Wound and Shock — Shock needs a separate Recovery attempt).

## Recovery

**Shaken** (has Shock markers): on activation, the player may (a) do nothing and just eat the penalties, (b) spend **both** actions to automatically remove 1 Shock marker ("Rest" — not usable within 1" of an enemy), or (c) make a **Recovery roll**. If attacked in Close Combat while Shaken, the model still fights at −1 per Shock marker; winning removes all Shock. Queen of Spades activation = automatic full recovery, still get 2 actions.

**Wounded** (down): **must** attempt to recover if down/prone, unless starting the turn already in Close Combat (then it must fight instead). Queen of Hearts activation = automatic stand + remove 1 Wound, still get 2 actions. Only a Queen of Hearts or a Medic (see Traits) can remove a Wound.

**Recovery roll procedure** — roll d10, −1 per existing Shock marker or Wound (whichever chart applies):

| Roll | Shaken result | Wounded result |
|---|---|---|
| 6–10+ | Fully unshaken, remove ALL Shock, still has 1 action | May stand |
| 2–5 | Still shaken, may fall back up to 5", no reroll this turn | Still down, may crawl 2", no reroll this turn |
| 1 or below | Routs — removed from play ("lives to fight another day") | Succumbs to wounds — Out of Action |

## Other Actions

**Ready**: spend an action to hold/overwatch. Mark with a Ready token. Later in the turn, may interrupt to shoot at the specific unit that activated (must be in the Readied model's line of sight) at −1 to hit — Special Card bonuses from the activation card don't apply to this interrupt shot. A Readied model can also counter-charge if charged: pass a Regular Task (5+) to negate the charger's charge bonus, both models meet where their full moves would intersect. Ready status clears at end of turn.

**Gruesome Deaths / Heroic Sacrifice (optional)**: an Out of Action result from a natural 10+ is a Gruesome Death — allies within 6" must pass a Regular Task or take a Shock marker (Grunts are exempt from needing to check). A Wounded/Shocked model may make a Heroic Sacrifice: convert all its negative modifiers to positive for one final Close Combat attack, then is automatically Out of Action afterward regardless of outcome (has campaign consequences). Grunts cannot use this.

**Retreat**: if a model has MORE Shock markers than remaining Wounds, it must immediately fall back 2 full moves away from the enemy (ignoring terrain/Shock penalties, except impassable terrain), then excess Shock is removed until Shock markers = remaining Wounds. If it has nowhere to retreat to, it routs (removed permanently).

## Tasks

| Difficulty | Target |
|---|---|
| Easy | 3+ |
| Regular | 5+ |
| Hard | 8+ |

Natural 10+ always succeeds; natural 1 = something goes wrong. Failing without rolling a 1 bumps the Task one difficulty level harder next attempt (e.g., Regular fail → next try is Hard; fail again → 10+ needed from then on). −1 per Shock marker the model has. An enemy within close range/an enemy move away typically bumps difficulty up one level (referee/table judgment); players can agree to make some Tasks easier too.

**Swimming**: Easy Task (doesn't cost the action) crossing deep water; moves 5" on success. Wearing armor bumps it to Regular, Heavy Armor to Hard. Fail = take a Wound (must Recover next turn); natural 1 = sinks, Out of Action. Natural 10+ = an extra 5" move immediately. Shallow water = difficult terrain (half rate), no roll needed.

**Hiding**: action to hide while in terrain/cover and not currently in an enemy's line of sight. While hidden, can't be targeted unless spotted (enemy within 12", line of sight, Hard 8+ Task) — auto-spotted if an enemy comes within 6". Moving/shooting/acting reveals the model immediately (still benefits from whatever cover it's in once revealed). Re-hiding requires first breaking line of sight (can't shoot-then-hide in the same activation).

**Lighting fires**: model must be in base contact with a flammable structure (agree what's flammable pre-game). Regular Task (5+) to ignite; on success roll d10: 1–2 nothing, 3–8 place 1 fire marker, 9–10 place 2. Each turn-end, roll again to see fire growth (same table adds/removes markers depending on lighting vs. fighting the fire). A medium building collapses (kills anyone inside) at 6 fire markers (adjust for size). Fighting a fire uses the same Regular Task and d10 table but removes markers instead. Models inside/on-roof of a burning building roll on the Wound Chart each turn-end: Shock result = forced out, stops within 2", coughing; Wound result = must Recovery-roll to escape; Out of Action = succumbed to smoke/flame.

## Leaders

A Leader gives **+1** to any Recovery roll (Shock or Wounded-and-Down) attempted by a friendly model within **12" and line of sight** (not blocked by terrain) of the Leader. A natural "1" still routs/succumbs regardless of this bonus. Typical Crew size is 5–8 models with one Leader. (This is the same bonus granted by the free **Leader** Trait — see `crew-building.md`.)
