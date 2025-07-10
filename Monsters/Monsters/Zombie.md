
```statblock
layout: Basic ToV Layout
cr: 1/4
immune: Undead Resilience
senses: darkvision 60 ft.
languages: understands the languages it knew in life but can’t speak
perception: 10
speed: 20 ft.
size: Medium
ac: 8
actions:
  - name: Slam.
    desc: "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target.  *Hit:* 5 (1d6 + 2) bludgeoning damage. The target is [[../../Conditions/Grappled|grappled]] (escape DC 12) if it is a Medium or smaller creature, and the zombie doesn’t already have a creature grappled."
stats: ['+2', '−2', '+3', '−4', '+0', '−3']
name: Zombie
stealth: 8
bonus_actions:
  - name: Rotten Hold.
    desc: "The zombie gnaws idly on the creature grappled by it. The target must succeed on a DC 12 CON save or take 2 (1d4) poison damage. A Humanoid slain by this bonus action rises 24 hours later as a **zombie**, unless the Humanoid is restored to life or its body is destroyed."
traits:
  - name: Undead Fortitude.
    desc: "If damage reduces the zombie to 0 HP, it must make a CON save with a DC equal to 5 + the damage taken, unless the damage is radiant or from a critical hit. On a success, the zombie drops to 1 HP instead."
  - name: Undead Nature.
    desc: "The zombie doesn’t require air, food, drink, or sleep."
  - name: Undead Resilience.
    desc: "The zombie is immune to poison damage, to exhaustion, and to the poisoned condition."
type: Undead
hp: 16
```

#cr1-4 #medium #undead
