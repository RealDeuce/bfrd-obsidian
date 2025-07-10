
```statblock
layout: Basic ToV Layout
cr: 2
reactions:
  - name: Defensive Kick.
    desc: "When a creature the centaur can see within 5 feet of it hits it with an attack, the centaur can kick the attacker. The attacker must succeed on a DC 14 STR save or be knocked prone or pushed up to 5 feet away from the centaur (the centaur’s choice)."
senses: —
languages: Elvish, Sylvan
perception: 13
speed: 50 ft.
ac: 12
size: Large
actions:
  - name: Multiattack.
    desc: "The centaur makes one Hooves attack and one Pike attack, or it makes three Longbow attacks."
  - name: Hooves.
    desc: "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one target.  *Hit:* 11 (2d6 + 4) bludgeoning damage."
  - name: Pike.
    desc: "*Melee Weapon Attack:* +6 to hit, reach 10 ft., one target.  *Hit:* 9 (1d10 + 4) piercing damage."
  - name: Longbow.
    desc: "*Ranged Weapon Attack:* +4 to hit, range 150/600 ft., one target.  *Hit:* 6 (1d8 + 2) piercing damage."
stats: ['+4', '+2', '+2', '−1', '+3', '+0']
name: Centaur
stealth: 12
resistant: Monstrosity Resilience
traits:
  - name: Monstrosity Resilience.
    desc: "The centaur is resistant to exhaustion and to the frightened condition."
  - name: Trampling Charge.
    desc: "If the centaur moves at least 30 feet straight toward a creature and then hits it with a Pike attack on the same turn, that target must succeed on a DC 14 STR save or be knocked [[../../Conditions/Prone|prone]]. If the target is prone, the centaur can make one Hooves attack against it as a bonus action."
type: Monstrosity
hp: 63
```

#cr2 #large #monstrosity
