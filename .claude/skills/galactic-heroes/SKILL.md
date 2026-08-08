---
name: galactic-heroes
description: Rules referee, Crew builder, and game-master assistant for "Fistful of Lead: Galactic Heroes" (2nd Edition), a d10 card-activated sci-fi skirmish wargame. Use whenever the user asks a rules question about Galactic Heroes / Fistful of Lead, wants to build or validate a Crew (Leader/Specialist/Regulars/Grunts, Traits, Equipment slots, weapons/armor), wants help running or refereeing a turn (card activation order, shooting, close combat, wounds, recovery, tasks), asks about vehicles, psionics, alien monsters, scenarios, campaign/Renown rules, or wants a pre-built faction from the Codex Galactica.
---

# Galactic Heroes (Fistful of Lead, 2nd Edition) — Rules Assistant

Source of truth: `Rules - GH - 2nd Edition - Bookmarks.pdf` in this project (a 93-page rulebook, copyright Jaye Wiley / Wiley Games 2022). This skill packages that book into reference files so rules answers are accurate and citable instead of guessed from memory.

This skill covers three jobs, often needed together:
- **Referee** — answer rules questions precisely, resolve edge cases and interactions.
- **Crew builder** — create or validate a legal Crew (roster slots, Traits, Equipment).
- **Game master** — run an actual turn: card order, shooting/close combat/wound/recovery resolution, marker tracking.

## How to use this skill

1. Figure out which job (or combination) the user needs.
2. Before answering anything non-trivial, **Read or Grep the relevant reference file(s) below** rather than relying on the summary in this file or on general knowledge — the reference files contain the fuller rule text and exact numbers.
3. Always show the modifier chain explicitly (base target number, then each `+`/`−` applied and why), not just a final number — players will want to check the math against their own miniature's Trait/Wound/Shock state.
4. Never invent a rule. This book is fairly complete, but if something genuinely isn't covered, say so and offer the book's own stated fallback (Introduction, p.2): *"players should try to come up with a mutually agreeable solution. If that doesn't work, roll a die!"* — and note that per the book, house-ruling is explicitly endorsed ("these are ultimately your rules").
5. Don't fabricate dice results. If running a game turn, ask the user what they rolled, or if asked to simulate/roll for them, clearly label it as a simulated roll and show the number.

## Reference files (load on demand)

- `references/core-rules.md` — turn/card sequence, Special Cards, Actions (move/jump/creep/fall), Terrain & Cover, Shooting, Close Combat, Wounding, Recovery, other actions (Ready, Retreat, Gruesome Death/Heroic Sacrifice), Tasks (incl. swimming/hiding/fire), Leaders. **Load this for almost any rules or GM question.**
- `references/crew-building.md` — Crew roster structure (Leader/Specialist/Regular/Grunt), full Traits list (positive, negative, Crew-wide), Alien Monsters & Galactic Heroes/Villains, Psionics (Light/Dark Templar powers).
- `references/weapons-armor-gear.md` — Equipment slots, Armor & Shields, full weapon-by-weapon rules, the Weapon Chart table, weapon properties (Ammo Hog/AP/Blast/Burst/Deadly/Inaccurate/Limited Ammo/Polearm/Reload/Specialist/Splash/Team), Weapon Teams, the "Other Gear" d100 table.
- `references/vehicles.md` — vehicle stat blocks, driving/Control tests/Collisions, Damaging a Vehicle, Passengers, Vehicle Combat (shooting from/at a vehicle, Close Combat vs vehicles), Vehicle Weapons & Traits & Armor, Anti-Vehicle weapons, Minefields, sample vehicle templates.
- `references/scenarios-campaign.md` — the 5 built-in scenarios with setup/forces/special rules/victory conditions, Campaign rules (Renown, spending Renown, Promotion), Post-Game survival rolls, Guns for Hire, Useless Crews, Luck (optional rule).
- `references/codex-galactica.md` — ~20 ready-to-use pastiche factions (space-opera Rebels/Empire, grimdark Marines/Guardsmen/Orks/Aeldaren/Daemons, Star Trek-style Federation, time-travelling-scientist companions, robot hive-minds, Barsoom/Mars pulp factions, colonial Mars & Venus) with full stat blocks.

## Quick-reference core numbers

(Sanity-check these against `core-rules.md` before relying on them for anything non-trivial — this is a condensed cheat sheet, not the full rule.)

**Turn structure**: shuffle the full deck (discards + unplayed) → deal 1 card per miniature the player controls → resolve in order King → Queen → Jack → 10 … → 2 (ties broken ♠ > ♥ > ♦ > ♣; a "real" card always beats an Ace impersonating that rank) → each card activates ONE miniature for **2 actions**. Aces are wild (must be played "in sequence" as whatever rank is announced). New turn once all cards are played.

**Dice**: default is d10 (Quality die). Some Traits swap this: Veteran = d12 for everything, Green = d8 for everything, Ranged Fighter = d12 Shoot / d8 Close Combat, Grunts = d8.

**Shooting**: hit on d10 ≥ 5 at Short range, ≥ 8 at Long range. Common modifiers: Light Cover −1, Heavy Cover −2, Small target −1 / Large +1 / Huge +2, −1 per Wound/Shock marker on the shooter, mounted shooter −1, mounted/creeping/prone target −1, aimed (spent 1st action to Aim) +1. Natural "1" = Out of Ammo (place marker; reload costs both actions, must be consecutive across one turn, can't split across turns).

**Wound chart** (roll d10, +1 for each Wound the target already has): 0 or less = No effect · 1–5 = Shock/Shaken · 6–8 = Wounded & Down · 9–10+ = Out of Action. 3 Wounds = Out of Action baseline (Traits like Tough as Nails/Large raise this to 4; Small/Weakling lower it to 2).

**Close Combat**: both sides roll d10 (+ modifiers) simultaneously; higher total wins and the margin gives a Wound-roll bonus: 1–2 margin → +0, 3–4 → +1, 5–6 → +2, 7+ → +3. Tie = no Wound roll, but the initiator may still push/hold. Natural "1" = Fumble → disarmed (in addition to whatever the Wound roll does).

**Recovery** (roll d10, −1 per existing Wound/Shock marker): Shaken — 6–10+ fully recovers (remove all Shock); 2–5 still shaken, falls back 5" and can't reroll this turn; ≤1 routs, model removed. Wounded — 6–10+ may stand; 2–5 still down, may crawl 2"; ≤1 succumbs, Out of Action.

**Tasks**: Easy 3+, Regular 5+, Hard 8+. Natural 10+ always succeeds regardless of difficulty; natural 1 = something bad happens. Failing without rolling a 1 bumps the Task one difficulty level harder on the next attempt. −1 per Shock marker on the roll.

## Running a game turn (GM mode)

Track per-miniature state: Wounds (0 up to max, usually 3), Shock markers, Ammo (Out of Ammo y/n), status flags (Ready/Creep/Hidden/Reload-in-progress), position/cover description. When walking through a turn:
1. Confirm the card being called and which player/model it activates.
2. For each of the model's 2 actions, resolve the action's roll with the full modifier breakdown before giving the final target number and outcome.
3. Update markers/state immediately after each resolved action (a Wound changes movement and all future rolls this same activation).
4. Note Special Card effects (Queen of Hearts/Spades, One/Two-Eyed Jacks, 7s, 6s, 2s, Aces) when the card played has one — see `core-rules.md`.

## Building a Crew (crew-builder mode)

Roster shape (see `crew-building.md` for the full Traits catalogue and `weapons-armor-gear.md` for costs):
- **Leader** (1, required unless a Crew Trait like Special Ops/Heroes All says otherwise): free Leader Trait + 3 chosen Traits, 5 Equipment slots.
- **Specialist** (1): 2 Traits, 4 Equipment slots.
- **Regulars** (3 slots, each may instead be replaced by one Grunt group): 1 Trait each, 3 Equipment slots each.
- **Grunts** (fill a Regular slot; group of 3, or 4 with Tough as Nails): d8 Quality die, 1 Wound each, share 1 group Trait, share one activation card, 2 Equipment slots (shared).
- Pick one **Crew Trait** for the whole Crew (see list in `crew-building.md`).
- No Crew member may have more than 5 Traits total (relevant once a campaign lets you buy more with Renown).
- A model may trade a Trait slot for a Negative Trait to gain one extra Positive Trait (max 1 Negative Trait per model).

Always total Equipment slot usage explicitly against the role's slot cap and flag anything over budget.
