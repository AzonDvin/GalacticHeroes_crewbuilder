# Vehicle Rules (pp. 59–74)

Design intent: light/agile vehicles zipping around, not tabletop-dominating tanks — heavy armor is deliberately restricted to Large/Huge hulls.

## Vehicle stats (sample base vehicles)

| Vehicle | Size | Damage Pts. | Passengers | Move" | Special |
|---|---|---|---|---|---|
| Jet Bike | Small | 2 | 1 | 12 | Agile, Hover, Fast |
| Motorcycle | Small | 2 | 1 | 10 | Agile |
| Skimmer | Medium | 3 | 2 | 8 | Hover, Durable |
| Command Car | Medium | 3 | 3 | 8 | Light Armor |
| Scout Walker | Medium | 3 | 0 | 10 | Light Armor, Walker, Fast |
| Cargo Truck | Large | 4 | 6 | 6 | Transport |
| Armored Transport | Large | 4 | 6 | 6 | Light Armor, Turret, Transport |
| Battle Walker | Large | 4 | 3 | 6 | Light Armor, Walker |
| Hover Barge | Large | 4 | 3 | 6 | Hover, Agile |
| Tank | Large | 4 | 3 | 6 | Heavy Armor, Treads, Turret |
| Heavy Tank | Huge | 6 | 5 | 4 | Heavy Armor, Treads, Turret |
| Battle Wagon | Huge | 6 | 7 | 6 | Fast, Transport |

Generic size baseline (from the intro table): Small = 2 Damage Pts/1 passenger/12" move, Medium = 3/2/8, Large = 4/0(base)/6, Huge = 6/6/5 — the sample table above supersedes this for specific named vehicles.

## Operation

A driver is dealt a card like any Crew member and gets 2 actions. Getting in/out of a vehicle costs 1 action (so you can't foot-move and then drive the same activation).

**Driver actions** (choose 2 per activation):
- **Move Straight** — up to full Move rate; reverse is half rate.
- **Turn** — up to 90° left/right; may then move up to half rate.
- **Shoot** — open-topped/unenclosed driver may fire a sidearm at −1, or fire a driver-operated mounted weapon.
- **Recovery** — attempt a Recovery roll (no other action that activation).

**Driver Out of Action**: roll d10 — the die's "point" gives the vehicle's new facing, the number gives distance in inches it drifts.

## Control tests

A **Task roll** (d10, d12 for Veterans, d8 for Green) is required when:

| Trigger | Difficulty |
|---|---|
| Moving through Difficult terrain | Easy 3+ |
| Driver or vehicle is hit | Regular 5+ |
| Avoiding a collision | Hard 8+ |

Modifiers: −1 per existing Wound/Shock marker on the driver, −1 if the vehicle is already Damaged, +/− per Vehicle Traits (e.g. Stabilizers +1).

**Losing control**: vehicle spins in a random direction (or backs up 2" if stationary); this is temporary — normal control resumes next activation. A natural "1" on a Control test also gives the driver a Shock marker.

## Collisions

Triggered when a vehicle's move brings it into contact with another vehicle, a miniature on foot, or an obstacle.

- **Vehicle vs Vehicle** — both drivers make an immediate Hard (8+) Task roll. A driver who fails spins randomly and bounces 2" away from the other vehicle, then rolls on the Vehicle Damage chart with a size-based modifier for the *other* vehicle: Small +1, Medium +2, Large +3, Huge +4.
- **Vehicle vs Crew (foot)** — the miniature makes a Hard (8+) Task roll to dodge clear (moved the appropriate distance if successful); on failure, roll on the Wound Chart with the same size-based modifiers as above (based on the vehicle's size). The vehicle itself is unaffected by hitting infantry.
- **Vehicle vs Obstacle/building** — roll on the Vehicle Damage chart **twice**, using the modifier for the vehicle's *own* size.

## Damaging a Vehicle

Whenever a vehicle is hit by gunfire or a collision, roll on the Vehicle Damage chart (mirrors the Crew Wound Chart on purpose):

| Roll | Result |
|---|---|
| 0 or less | No effect |
| 1–5 | Check for Control |
| 6–8 | Damaged |
| 9–10+ | Out of Action |

+1 to the roll per Damage Point already on the vehicle. Each Damage Point gives −1" to movement per action. Out of Action = vehicle is done for the rest of the game (can be left on the table as cover/obstacle). Drivers/passengers aboard a vehicle that goes Out of Action must pass a Hard Task or roll on the Wound Chart themselves.

**Armor auto-saves vs small arms**: a vehicle with any armor automatically passes its Armor Roll against weapons that lack Blast/Team/Deadly/AP properties — i.e., ordinary small-arms fire can, at worst, force a Control check, never directly Damage an armored vehicle.

## Passengers

Anyone aboard who isn't the driver; activates on their own card as normal (Shoot, Recovery, Reload, etc., same as on foot). Jumping on/off a **moving** vehicle needs a Hard (8+) Task roll — fail = immediate roll on the Wound Chart. A vehicle counts as "moving" if it moved this turn, or moved last turn and the driver hasn't activated yet this turn.

## Vehicle Combat

**Shooting from a vehicle**: normal Shooting rules, plus a flat −1 for firing from a moving vehicle.

**Shooting at a vehicle**: declare whether you're targeting the vehicle itself or its driver/passengers.
- Enclosed crew compartment → passengers/driver can't be targeted directly.
- Exposed crew → target is randomized unless caught under a Burst/Blast template; there's a −1 to hit Crew in a moving vehicle, and they count as in cover (extra −1/−2 if the vehicle itself has armor).
- The vehicle itself: no −1 penalty to hit for most vehicles (they're big); Small vehicles (motorcycles, jet-bikes) still get the −1 (fast/small target).

**Close Combat vs a vehicle**: a boarding Crew member fights the driver normally; the driver adds a **size bonus** to their Close Combat roll: Small +1, Medium +2, Large +3, Huge +4. If the driver is put Out of Action, the attacker may take control of the vehicle; defeated boarders are thrown overboard. Vehicles can never be pushed back or held in Close Combat.

## Vehicle Weapons

Slots available scale with size (and happen to equal the vehicle's Damage Points): Small 2, Medium 3, Large 4, Huge 6.

Heavy weapons that normally need a Team (Machine Gun, Heavy Laser, Heavy Blaster, etc.) can be vehicle-mounted for **2 slots**. Larger dedicated "Big Gun" mounts need their own crew (taking up Passenger spots):

| Gun class | Slots | Crew needed | Special rules |
|---|---|---|---|
| Light | 2 | 1 | AP1 |
| Medium | 3 | 2 | AP2, Blast 3 |
| Heavy | 4 | 3 | AP2, Blast 5, +1 DMG |

Fire arcs must be declared per mount (front/side/rear line, or Turret for all-around).

## Vehicle Armor

No Armor / Light Armor (8+, effectively) / Heavy Armor (6+, effectively) — vehicle armor tiers only matter against weapons with Blast/Team/Deadly/AP properties (ordinary small arms auto-fail to damage an armored vehicle, forcing only a Control check). An AP1 weapon vs. Heavy-armored vehicle drops its effective save to 8+ (one tier down); AP2 would drop it further.

## Vehicle Traits (3 points to spend per vehicle; cost shown after name)

- **Advanced Sights** (1) — +1 to Shoot roll.
- **Agile** (1) — may turn up to 180°/action.
- **Amphibious** (1) — full move rate through water.
- **Durable** (1) — +1 Damage Point for its size.
- **Fast** (1) — +2" per move action.
- **Flamer** (1) — equipped with a Flamer.
- **Heavy Armor** (2) — armor roll 6+ (Large/Huge only).
- **Hi-Tech** (1) — guns need 1 fewer crew to man.
- **Hover** (2) — crosses rough terrain (incl. water) with no Control test.
- **Hull Mount** (0) — guns need 1 fewer crew but are fixed forward-facing.
- **Indirect Fire** (1) — vehicle's gun can fire without direct LOS if a Drone/Crew spotter has LOS to a target >12" away.
- **Light Armor** (1) — armor roll 8+.
- **Stabilizers** (1) — driver gets +1 on Control tests.
- **Transport** (1) — +2 passenger spots.
- **Treads** (0) — crosses Rough terrain with no Control test, but only 45° turns.
- **Turret** (1) — gun may fire in any direction.
- **Walker** (1) — +1 to Control tests when moving through Rough terrain.

## Anti-Vehicle Weapons

- **Anti-Tank Missiles** — as a Missile/Rocket Launcher, but gain **Deadly** against Armored targets (natural 10+ Shoot roll = auto Out of Action for the vehicle). Specialist-carried.
- **Minefields** — define an area ≤1'×1'; any model/vehicle crossing it makes a Hard Task roll per 3" traveled (Hover vehicles only need a Regular Task); fail = immediate roll on the Wound/Vehicle Damage chart at **+3**.

## Sample vehicle templates (reference only — full deck-plan diagrams are in the PDF, pp. 66–74)

Jet Bike, Motorcycle, Skimmer, Command Car, Scout Walker, Cargo Truck, Armored Transport, Battle Walker, Hover Barge, Tank, Heavy Tank, Battle Wagon — stats as in the table above. Each has a driver/passenger seating diagram in the book useful for physically tracking who's aboard.
