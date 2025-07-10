
```statblock
layout: Basic ToV Layout
type: Monstrosity
hp: 80
stealth: 10
traits:
  - name: Charge.
    desc: "If the minotaur moves at least 10 feet straight toward a target and then hits it with a Gore attack on the same turn, the target takes an extra 7 (2d6) piercing damage. If the target is a creature, it must succeed on a DC 14 STR save or be pushed up to 10 feet away from the minotaur and knocked [[../../Conditions/Prone|prone]]."
  - name: Labyrinthine Recall.
    desc: "The minotaur can perfectly recall any path it has traveled."
  - name: Monstrosity Resilience.
    desc: "The minotaur is resistant to exhaustion and to the frightened condition."
  - name: Reckless.
    desc: "At the start of its turn, the minotaur can gain advantage on all melee weapon attack rolls it makes during that turn, but attack rolls against it have advantage until the start of its next turn."
  - name: Siege Monster.
    desc: "The minotaur deals double damage to objects and structures."
bonus_actions:
  - name: Bleeding Frenzy (44 HP or Fewer).
    desc: "The minotaur enters a frenzy until the start of its next turn. Until the frenzy ends, the minotaur deals an extra 3 (1d6) damage of the weapon’s type each time it hits with a melee weapon attack, and the minotaur takes an extra 3 (1d6) damage of the weapon’s type the first time it is hit with a melee weapon attack before the frenzy ends."
resistant: Monstrosity Resilience
name: Minotaur
stats: ['+6', '+0', '+3', '−2', '+3', '−1']
actions:
  - name: Multiattack.
    desc: "The minotaur makes one Gore attack and one Greataxe attack."
  - name: Gore.
    desc: "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one target.  *Hit:* 11 (2d6 + 4) piercing damage."
  - name: Greataxe.
    desc: "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one target.  *Hit:* 17 (2d12 + 4) slashing damage."
ac: 14 (natural armor)
size: Large
speed: 40 ft.
perception: 17
senses: darkvision 60 ft.
languages: Abyssal
cr: 3
```

#cr3 #large #monstrosity
