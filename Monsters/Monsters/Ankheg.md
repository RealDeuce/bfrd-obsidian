
```statblock
layout: Basic ToV Layout
ac: 14 (natural armor)
size: Large
speed: 30 ft., burrow 10 ft.
stats: ['+5', '+0', '+1', '−5', '+1', '−2']
actions:
  - name: Bite.
    desc: "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one target.  *Hit:* 10 (2d6 + 3) slashing damage plus 9 (2d8) acid damage. If the target is a Large or smaller creature, it is [[../../Conditions/Grappled|grappled]] (escape DC 13). Until this grapple ends, the ankheg can’t Bite another target."
  - name: Acid Spray (Recharge 6).
    desc: "The ankheg spits acid in a line that is 30 feet long and 5 feet wide, provided it has no creature grappled. Each creature in that line must make a DC 13 DEX save, taking 18 (4d8) acid damage on a failed save, or half as much damage on a successful one."
subtype: Animal
name: Ankheg
type: Monstrosity
hp: 57
traits:
  - name: Monstrosity Resilience.
    desc: "The ankheg is resistant to exhaustion and to the frightened condition."
bonus_actions:
  - name: Save for Later.
    desc: "The ankheg quickly digs a small hole and stuffs one creature grappled by it into the hole, burying the creature and ending the grapple. A buried creature is [[../../Conditions/Restrained|restrained]] and unable to breathe or stand up. A creature, including the buried creature, can take its action to free the buried creature by succeeding on a DC 13 STR check."
resistant: acid | Monstrosity Resilience
stealth: 12
cr: 2
languages: —
senses: darkvision 60 ft., tremorsense 60 ft.
perception: 11
```

#animal #cr2 #large #monstrosity
