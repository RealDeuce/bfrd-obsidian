
```statblock
layout: Basic ToV Layout
type: Swarm of Tiny Beasts
name: Snake, Swarm of Poisonous Snakes
hp: 48
resistant: poison | poisoned | Swarm Resilience
traits:
  - name: Poisonous Swarm.
    desc: "The hissing, spitting, and constant nipping of snakes in the swarm leaves the swarm’s space dripping with poison. A creature that starts its turn in the swarm’s space must succeed on a DC 14 CON save or be [[../../Conditions/Poisoned|poisoned]] until the start of its next turn."
  - name: Swarm.
    desc: "The swarm can occupy another creature’s space and vice versa, and the swarm can move through any opening large enough for a Tiny snake. The swarm can’t regain HP or gain temporary HP."
  - name: Swarm Resilience.
    desc: "The swarm is resistant to bludgeoning, piercing, and slashing damage, and it is immune to the charmed, frightened, grappled, paralyzed, petrified, prone, restrained, and stunned conditions."
stealth: 14
ac: 14
size: Medium
speed: 30 ft., swim 30 ft.
stats: ['−1', '+4', '+0', '−5', '+0', '−4']
actions:
  - name: Bites.
    desc: "*Melee Weapon Attack:* +6 to hit, reach 0 ft., one creature in the swarm’s space.  *Hit:* 10 (4d4) piercing damage, or 5 (2d4) piercing damage if the swarm has half of its HP or fewer. The target must make a DC 14 CON save, taking 18 (4d8) poison damage on a failed save, or half as much damage on a successful one."
languages: —
senses: keensense 10 ft.
immune: Swarm Resilience
perception: 10
cr: 2
```

#beast #cr2 #medium #swarm
