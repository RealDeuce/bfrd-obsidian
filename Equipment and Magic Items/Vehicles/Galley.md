Galleys are massive vessels ideal for transporting cargo and used by merchants to carry trade goods. These weighty vessels are equipped with sails, but frequently rely on dozens of crew members rowing below decks for propulsion. Since galleys carry stores of cargo, they’re almost always equipped with weaponry and defended by squadrons of hired swords.

```statblock
layout: Basic ToV Vehicle Layout
name: Galley
size: Gargantuan
type: Water Vehicle (130 ft. by 20 ft.)
ac: 15 (damage threshold 20)
hp: 500
speed: 35 ft., 4 mph (96 miles per day)
immune: Vehicle Resilience
initiative: 4
crew: 80
passengers: 40
cargo_capacity: 150 tons
stats: ["+7","−3", "+5", "—", "—", "—"]
traits:
  - name: Sails.
    desc: While in initiative, the galley’s speed is reduced to 15 ft. when sailing against the wind. While sailing with the wind, its speed becomes 50 feet.
action_description: "On its turn, the galley can take two actions, choosing from the options below (it can take the same action multiple times). It can take only one action if it has fewer than 40 crew. It can’t move or take actions if it has fewer than 3 crew."
actions:
  - name: Fire Ballista.
    desc: "*Ranged Weapon Attack:* +7 hit, range 120/480 ft., one target. *Hit:* 23 (3d10 + 7) piercing damage."
  - name: Fire Mangonels.
    desc: "*Ranged Weapon Attack:* +7 hit, range 200/800 ft. (can’t hit targets within 60 feet), one target. *Hit:* 34 (5d10 + 7) bludgeoning damage."
  - name: Row.
    desc: "The galley takes the Dash action."
```
