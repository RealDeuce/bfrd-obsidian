
```statblock
layout: Basic ToV Layout
cr: 2
senses: darkvision 60 ft.
languages: Aquan, Common
perception: 12
ac: 13 (natural armor)
size: Large
speed: 10 ft., swim 40 ft.
stats: ['+4', '+0', '+2', '−1', '+0', '−1']
actions:
  - name: Multiattack.
    desc: "The merrow makes one Bite attack and two Claw attacks. It can replace one Claw attack with a Harpoon attack."
  - name: Bite.
    desc: "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one target.  *Hit:* 8 (1d8 + 4) piercing damage."
  - name: Claw.
    desc: "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one target.  *Hit:* 7 (1d6 + 4) slashing damage."
  - name: Harpoon.
    desc: "*Melee or Ranged Weapon Attack:* +6 to hit, reach 5 ft. or range 20/60 ft., one target.  *Hit:* 7 (1d6 + 4) piercing damage, and the harpoon sticks in the target. While the harpoon is stuck, the merrow can’t make Harpoon attacks against other targets, and the target and merrow can’t move farther than 60 feet away from each other. A creature, including the target, can take its action to detach the harpoon by succeeding on a DC 14 STR check. Alternatively, the cord connecting the merrow to the harpoon can be attacked and destroyed (AC 10; HP 15; immune to bludgeoning, poison, and psychic damage), dislodging the harpoon into an unoccupied space within 5 feet of the target and preventing the merrow from using Recall Harpoon."
name: Merrow
type: Monstrosity
hp: 60
stealth: 10
bonus_actions:
  - name: Shoving Rush.
    desc: "The merrow takes the Dash action. If it moves, it can propel itself into one creature it can see along its path. The target must succeed on a DC 14 STR save or be knocked [[../../Conditions/Prone|prone]]. This movement doesn’t provoke opportunity attacks from a target that fails this save."
  - name: Recall Harpoon.
    desc: "The merrow pulls on the cord connected to its harpoon, returning the harpoon to its empty hand. If the harpoon is stuck in a creature, that creature must succeed on a DC 14 STR save or be pulled up to 20 feet toward the merrow. Regardless, the harpoon is dislodged and returned to the merrow’s hand."
resistant: Monstrosity Resilience
traits:
  - name: Amphibious.
    desc: "The merrow can breathe air and water."
  - name: Monstrosity Resilience.
    desc: "The merrow is resistant to exhaustion and to the frightened condition."
```

#cr2 #large #monstrosity
