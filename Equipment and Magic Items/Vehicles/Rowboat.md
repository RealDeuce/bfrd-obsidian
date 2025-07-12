Rowboats are powered by rowing and current. They can’t be rowed against any significant current, but they can be pulled upstream by draft animals on the shore. A rowboat weighs 100 pounds for portage purposes.

```statblock
layout: Basic ToV Vehicle Layout
name: Keelboat
size: Large
type: Water Vehicle (10 ft. by 5 ft.)
ac: 11 (damage threshold 0)
hp: 50
speed: 15 ft. (maneuverable), 3 mph (72 miles per day)
immune: Vehicle Resilience
initiative: 8
crew: 2
passengers: 2
cargo_capacity: 500 lbs.
stats: ["+0", "−1", "+0", "—", "—", "—"]
traits:
  - name: Lightweight.
    desc: "If the rowboat is going downstream, add the speed of the current (typically 3 miles per hour) to its speed. The rowboat’s speed is 0 ft. while traveling against any significant current."
  - name: Maneuverable.
    desc: "The rowboat can move up to its speed and make one 90-degree turn."
actions:
  - name: Row Hard.
    desc: "The rowboat takes the Dash action."
```
