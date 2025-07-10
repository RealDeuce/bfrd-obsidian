
```statblock
layout: Basic ToV Layout
cr: 4
reactions:
  - name: Split.
    desc: "When a pudding that is Medium or larger is subjected to lightning or slashing damage, it splits into two new puddings if it has at least 10 HP. Each new pudding has HP equal to half the original pudding’s, rounded down. New puddings are one size smaller than the original pudding."
senses: keensense 60 ft. (can’t sense beyond this radius)
languages: —
immune: acid, lightning, slashing | grappled | Ooze Resilience
perception: 8
ac: 7
size: Large
speed: 20 ft., climb 20 ft.
stats: ['+5', '−3', '+3', '−5', '−2', '−5']
actions:
  - name: Multiattack.
    desc: "The black pudding makes two Pseudopod attacks."
  - name: Pseudopod.
    desc: "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one target.  *Hit:* 6 (1d6 + 3) bludgeoning damage plus 9 (2d8) acid damage. In addition, nonmagical armor worn by the target is partly dissolved and takes a permanent and cumulative −1 penalty to the AC it offers. Armor reduced to an AC of 10 is destroyed."
name: Black Pudding
hp: 122
type: Ooze
stealth: 9
bonus_actions:
  - name: Dampen Light.
    desc: "The black pudding dims the light around it. The radius of each light source within 60 feet of it is halved until the start of its next turn. The pudding can’t use this action while in sunlight."
resistant: Ooze Resilience
traits:
  - name: Amorphous.
    desc: "The pudding can move through a space as narrow as 1 inch wide without squeezing."
  - name: Corrosive Form.
    desc: "A creature that touches the pudding or hits it with a melee attack while within 5 feet of it takes 4 (1d8) acid damage. Any nonmagical weapon made of metal or wood that hits the pudding corrodes. After dealing damage, the weapon takes a permanent and cumulative −1 penalty to damage rolls. If its penalty drops to −5, the weapon is destroyed. Nonmagical ammunition made of metal or wood that hits the pudding is destroyed after dealing damage. The pudding can eat through a panel of nonmagical wood or metal in its space that is up to 2 inches thick in 1 round."
  - name: Ooze Nature.
    desc: "The pudding doesn’t require sleep."
  - name: Ooze Resilience.
    desc: "The pudding is resistant to the restrained condition, and it is immune to exhaustion and to the blinded, charmed, deafened, frightened, and prone conditions."
  - name: Spider Climb.
    desc: "The pudding can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check."
```

#cr4 #large #ooze
