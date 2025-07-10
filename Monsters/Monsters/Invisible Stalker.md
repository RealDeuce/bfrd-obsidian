
```statblock
layout: Basic ToV Layout
name: Invisible Stalker
type: Elemental
hp: 121
traits:
  - name: Elemental Nature.
    desc: "The invisible stalker doesn’t require air, food, drink, or sleep."
  - name: Elemental Resilience.
    desc: "The stalker is resistant to bludgeoning, piercing, and slashing damage from nonmagical attacks. In addition, it is immune to poison damage, to exhaustion, and to the grappled, paralyzed, petrified, poisoned, prone, restrained, and unconscious conditions."
  - name: Faultless Tracker.
    desc: "At the end of each long rest, the invisible stalker can choose a creature it knows or has seen to be its quarry. A stalker summoned by another creature can choose only the quarry specified by its summoner, but the stalker also knows the location of its summoner while it continues to serve the summoner. The stalker always knows the direction and distance to its quarry, provided the two are on the same plane of existence."
  - name: Invisibility.
    desc: "The stalker is [[../../Conditions/Invisible|invisible]]. The condition’s effect on DEX (Stealth) checks has been included in the above Stealth value."
bonus_actions:
  - name: Steal Breath.
    desc: "The invisible stalker calls on the air in the lungs of one breathing creature it can see within 30 feet of it, causing the air to leave the creature. The target must succeed on a DC 15 CON save or be unable to speak or cast spells with verbal components until the end of its next turn. A creature that fails the save by 5 or more is also [[../../Conditions/Incapacitated|incapacitated]] and suffocating for the duration, as it coughs uncontrollably."
resistant: Elemental Resilience
stealth: 22
ac: 14
size: Medium
speed: 50 ft., fly 50 ft. (hover)
stats: ['+3', '+4', '+2', '+0', '+5', '+0']
actions:
  - name: Multiattack.
    desc: "The stalker makes two Slam attacks."
  - name: Slam.
    desc: "*Melee Weapon Attack:* +7 to hit, reach 5 ft., one target.  *Hit:* 13 (2d8 + 4) bludgeoning damage plus 9 (2d8) cold damage. If the target is the stalker’s quarry, the target must succeed on a DC 15 DEX save or its speed is halved until the end of its next turn."
languages: Auran, understands Common but can’t speak it
senses: darkvision 60 ft.
immune: Elemental Resilience
perception: 18
cr: 6
```

#cr6 #elemental #medium
