
```statblock
layout: Basic ToV Layout
name: Triceratops
stealth: 9
bonus_actions:
  - name: Warning Bugle.
    desc: "The triceratops emits a piercing call in a 30‑foot cone, signaling its impending attack. Each creature in the area must succeed on a DC 14 WIS save or be [[../../../Conditions/Frightened|frightened]] until the end of its next turn. If the triceratops uses this bonus action before moving the requisite 20 feet for Trampling Charge, the target of its charge has disadvantage on this save, and the triceratops can make a Stomp attack against the prone target without needing to use a bonus action, provided the target fails the STR save from the charge."
traits:
  - name: Hardy.
    desc: "Any critical hit against the dinosaur becomes a normal hit."
  - name: Trampling Charge.
    desc: "If the triceratops moves at least 20 feet straight toward a creature and then hits it with a Gore attack on the same turn, that target must succeed on a DC 14 STR save or be knocked [[../../../Conditions/Prone|prone]]. If the target is prone, the triceratops can make one Stomp attack against it as a bonus action."
hp: 126
type: Beast
speed: 50 ft.
ac: 13 (natural armor)
size: Huge
actions:
  - name: Multiattack.
    desc: "The triceratops makes two Gore attacks."
  - name: Gore.
    desc: "*Melee Weapon Attack:* +9 to hit, reach 5 ft., one target.  *Hit:* 19 (3d8 + 6) piercing damage."
  - name: Stomp.
    desc: "*Melee Weapon Attack:* +9 to hit, reach 5 ft., one prone creature.  *Hit:* 17 (2d10 + 6) bludgeoning damage."
stats: ['+6', '−1', '+3', '−4', '+0', '−3']
senses: —
languages: —
perception: 10
cr: 5
```

#beast #cr5 #huge
