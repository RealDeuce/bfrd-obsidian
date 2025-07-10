
```statblock
layout: Basic ToV Layout
cr: 2
reactions:
  - name: Prey Shield.
    desc: "When a creature the mimic can see hits it with an attack while it is grappling a creature, the mimic can roll the grappled creature in front of the blow, forcing the grappled creature to take the damage instead."
immune: acid | prone
languages: —
senses: keensense 60 ft.
perception: 11
speed: 20 ft.
ac: 12 (natural armor)
size: Medium
actions:
  - name: Multiattack.
    desc: "The mimic makes two Pseudopod attacks. If it is grappling a creature, it can replace one attack with a Bite attack."
  - name: Bite.
    desc: "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one grappled creature.  *Hit:* 7 (1d8 + 3) piercing damage plus 7 (2d6) acid damage."
  - name: Pseudopod.
    desc: "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one target.  *Hit:* 10 (2d6 + 3) bludgeoning damage. If the mimic is in object form, the target is subjected to its Adhesive trait."
stats: ['+3', '+1', '+2', '−3', '+1', '−1']
name: Mimic
vulnerable: cold
subtype: Shapechanger
traits:
  - name: Adhesive (Object Form Only).
    desc: "The mimic adheres to anything that touches it. A Huge or smaller creature adhered to the mimic is also [[../../Conditions/Grappled|grappled]] by it (escape DC 13). Ability checks made to escape this grapple have disadvantage."
  - name: False Appearance (Object Form Only).
    desc: "While the mimic remains motionless, it is indistinguishable from an ordinary object."
  - name: Grappler.
    desc: "The mimic has advantage on attack rolls against any creature grappled by it."
  - name: Monstrosity Resilience.
    desc: "The mimic is resistant to exhaustion and to the frightened condition."
bonus_actions:
  - name: Change Shape.
    desc: "The mimic transforms into a Large or smaller object or back into its true, amorphous form, which is a Monstrosity. Its statistics are the same in each form. Any equipment it is wearing or carrying isn’t transformed. It reverts to its true form if it dies."
resistant: grappled | Monstrosity Resilience
stealth: 13
hp: 58
type: Monstrosity
```

#cr2 #medium #monstrosity #shapechanger
