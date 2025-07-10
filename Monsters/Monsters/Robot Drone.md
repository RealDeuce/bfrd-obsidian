
```statblock
layout: Basic ToV Layout
stealth: 15
traits:
  - name: Construct Nature.
    desc: "The drone doesn’t require air, food, drink, or sleep."
  - name: Construct Resilience.
    desc: "The drone is immune to poison and psychic damage, and it is immune to exhaustion and the charmed, frightened, paralyzed, petrified, and poisoned conditions."
  - name: Electrical Malfunction.
    desc: "Whenever the drone takes lightning damage, it must succeed on a DC 11 WIS save or be [[../../Conditions/Incapacitated|incapacitated]] until the end of its next turn."
  - name: Point-Blank Shots.
    desc: "When the drone makes a ranged attack, it doesn’t have disadvantage on the attack roll from being within 5 feet of a hostile creature, though it may still have disadvantage from other sources."
bonus_actions:
  - name: Fueled Escape.
    desc: "The drone takes the Dash or Disengage action, leaving a small cloud of fuel fumes behind it. Each creature within 5 feet must succeed on a DC 13 CON save or be [[../../Conditions/Poisoned|poisoned]] until the end of its next turn."
hp: 21
type: Construct
vulnerable: lightning
name: Robot Drone
actions:
  - name: Slam.
    desc: "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one target.  *Hit:* 7 (1d8 + 3) bludgeoning damage."
  - name: Flame Jet.
    desc: "*Ranged Weapon Attack:* +5 to hit, range 20/60 ft., one target.  *Hit:* 8 (2d4 + 3) fire damage."
stats: ['−2', '+3', '+1', '−3', '+1', '−2']
speed: 20 ft., fly 40 ft. (hover)
ac: 15 (natural armor)
size: Tiny
perception: 15
immune: prone | Construct Resilience
senses: darkvision 60 ft.
languages: understands the languages of its creator but can’t speak
cr: 1/2
```

#construct #cr1-2 #tiny
