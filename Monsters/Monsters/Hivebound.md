
```statblock
layout: Basic ToV Layout
speed: 25 ft., fly 40 ft.
ac: 15 (natural armor)
size: Small
actions:
  - name: Multiattack.
    desc: "The hivebound makes one Bite attack and two Claw attacks, or it makes three Spit Insect attacks."
  - name: Bite.
    desc: "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one target.  *Hit:* 12 (2d8 + 3) piercing damage plus 10 (3d6) poison damage."
  - name: Claw.
    desc: "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one target.  *Hit:* 8 (2d4 + 3) slashing damage."
  - name: Spit Insect.
    desc: "*Ranged Weapon Attack:* +6 to hit, range 30/120 ft., one target.  *Hit:* 5 (1d4 + 3) piercing damage plus 7 (2d6) poison damage, and the target must succeed on a DC 15 DEX save or be pestered until the end of its next turn. A pestered creature has disadvantage on the next attack roll it makes before the pester ends."
  - name: Swarm Breath (Recharge 5–6).
    desc: "The hivebound exhales stinging insects in a 30-foot cone. Each creature in the area must make a DC 15 DEX save, taking 10 (4d4) piercing damage and 17 (5d6) poison damage on a failed save, or half as much damage on a successful one. A swarm of insects under the hivebound’s control then forms in an unoccupied space in that area."
stats: ['+2', '+3', '+4', '−2', '+2', '−2']
name: Hivebound
bonus_actions:
  - name: Swift Flight.
    desc: "The hivebound flies up to half its speed without provoking opportunity attacks."
traits:
  - name: Collective Mind.
    desc: "The hivebound’s individual insects and swarms under its control are connected via a hive mind. It can telepathically communicate with any of its individual insects and swarms within 1 mile of it, and it can’t be surprised. It can have up to five swarms of insects under its control at a time."
  - name: Monstrosity Resilience.
    desc: "The hivebound is resistant to exhaustion and to the frightened condition."
  - name: Reinforced Mind.
    desc: "If the hivebound starts its turn afflicted by an ongoing effect that allows a repeated INT, WIS, or CHA save to end the effect, such as the *[[.../Spells/Hold|hold]]* spell, the hivebound can make the save at the start of the turn instead of the end and has advantage on the save."
resistant: bludgeoning | charmed | Monstrosity Resilience
stealth: 12
type: Monstrosity
hp: 108
cr: 5
immune: blinded
languages: understands Common but can’t speak
senses: keensense 60 ft. (can’t sense beyond this radius)
perception: 12
```

#cr5 #monstrosity #small
