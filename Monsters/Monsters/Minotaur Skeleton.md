
```statblock
layout: Basic ToV Layout
stealth: 10
traits:
  - name: Charge.
    desc: "If the minotaur skeleton moves at least 10 feet straight toward a target and then hits it with a Gore attack on the same turn, the target takes an extra 7 (2d6) piercing damage. If the target is a creature, it must succeed on a DC 14 STR save or be pushed up to 10 feet away from the skeleton and knocked [[../../Conditions/Prone|prone]]."
  - name: False Appearance.
    desc: "While the minotaur skeleton remains motionless and prone, it is indistinguishable from an inanimate minotaur skeleton."
  - name: Labyrinthine Memories.
    desc: "The minotaur skeleton has advantage on checks and saves to avoid becoming lost or to recall a path it has previously traveled."
  - name: Undead Nature.
    desc: "The skeleton doesn’t require air, food, drink, or sleep."
  - name: Undead Resilience.
    desc: "The skeleton is immune to poison damage, to exhaustion, and to the poisoned condition."
resistant: piercing
type: Undead
hp: 63
name: Minotaur Skeleton
vulnerable: bludgeoning
actions:
  - name: Greataxe.
    desc: "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one target.  *Hit:* 17 (2d12 + 4) slashing damage."
  - name: Gore.
    desc: "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one target.  *Hit:* 11 (2d6 + 4) piercing damage."
stats: ['+4', '+0', '+2', '−2', '−1', '−3']
speed: 40 ft.
ac: 12 (natural armor)
size: Large
perception: 9
immune: Undead Resilience
senses: darkvision 60 ft.
languages: understands the languages it knew in life but can’t speak
reactions:
  - name: Counterattack (Recharge 6).
    desc: "When a creature the minotaur skeleton can see hits it with a melee attack while within 5 feet of it, the skeleton can make one Gore attack against the attacker."
cr: 2
```

#cr2 #large #undead
