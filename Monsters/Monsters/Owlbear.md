
```statblock
layout: Basic ToV Layout
hp: 80
type: Monstrosity
stealth: 11
bonus_actions:
  - name: Rend.
    desc: "The owlbear violently wrenches a Medium or smaller creature it is currently grappling. The target must make a DC 15 STR save, taking 9 (2d8) slashing damage on a failed save, or half as much damage on a successful one."
resistant: Monstrosity Resilience
traits:
  - name: Glide.
    desc: "The owlbear has long, sturdy feathers along its forelimbs and sides that expand while falling to slow its rate of descent to 60 feet per round, landing on its feet and taking no falling damage. It can move up to 5 feet horizontally for every 1 foot it falls. The owlbear can’t gain height with its gliding feathers alone. If subjected to a strong wind or lift of any kind, it can use the updraft to glide farther."
  - name: Heightened Sight and Smell.
    desc: "The owlbear’s Perception is 18 when perceiving by sight or smell."
  - name: Monstrosity Resilience.
    desc: "The owlbear is resistant to exhaustion and to the frightened condition."
subtype: Animal
name: Owlbear
stats: ['+5', '+1', '+3', '−4', '+1', '−2']
actions:
  - name: Multiattack.
    desc: "The owlbear makes one Beak attack and one Claws attack. If both attacks hit a Medium or smaller target, the target is [[../../Conditions/Grappled|grappled]] (escape DC 15)."
  - name: Beak.
    desc: "*Melee Weapon Attack:* +7 to hit, reach 5 ft., one creature.  *Hit:* 10 (1d10 + 5) piercing damage."
  - name: Claws.
    desc: "*Melee Weapon Attack:* +7 to hit, reach 5 ft., one target.  *Hit:* 14 (2d8 + 5) slashing damage."
  - name: Vicious Bound (44 HP or Fewer).
    desc: "The owlbear roars and barrels through creatures. It moves up to 20 feet in a straight line and can move through the space of any Medium or smaller creature. The first time it enters a creature’s space during this move, that creature must make a DC 15 STR save. On a failure, a creature takes 18 (4d8) bludgeoning damage and is knocked [[../../Conditions/Prone|prone]]. On a success, a creature takes half the damage and isn’t knocked prone."
ac: 14 (natural armor)
size: Large
speed: 40 ft.
perception: 13
senses: darkvision 60 ft.
languages: —
cr: 3
```

#animal #cr3 #large #monstrosity
