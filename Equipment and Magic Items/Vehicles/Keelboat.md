Keelboats are small sailing vessels that operate with
minimal crew. Keelboats are good for day trips or
transporting small amounts of cargo or passengers.
The keelboat stat block included here is outfitted with a
ballista, but less expensive keelboats without weaponry are
commonly available for purchase.

```statblock
layout: Basic ToV Vehicle Layout
name: Keelboat
size: Gargantuan
type: Water Vehicle (60 ft. by 20 ft.)
ac: 15 (damage threshold 10)
hp: 100
speed: 25 ft., 3 mph (72 miles per day)
immune: Vehicle Resilience
initiative: 7
crew: 3
passengers: 4
cargo_capacity: 1,000 lbs.
stats: ["+3", "−2", "+1", "—", "—", "—"]
traits:
  - name: Sails.
    desc: "While in initiative, the keelboat’s speed is reduced to 15 ft. when sailing against the wind. While sailing with the wind, its speed becomes 50 feet."
action_description: "On its turn, the keelboat can take one action, choosing from the options below. It can’t take any actions if it has fewer than 2 crew."
actions:
  - name: Fire Ballista.
    desc: "*Ranged Weapon Attack:* +6 hit, range 120/480 ft., one target. *Hit:* 16 (3d10 + 6) piercing damage."
  - name: Row.
    desc: "The keelboat takes the Dash action."
```
