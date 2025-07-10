
```statblock
layout: Basic ToV Layout
immune: blinded, deafened | Construct Resilience
senses: keensense 60 ft. (can’t sense beyond this radius)
languages: —
perception: 8
cr: 2
vulnerable: fire
name: Rug of Smothering
stealth: 14
traits:
  - name: Antimagic Susceptibility.
    desc: "The rug is [[../../Conditions/Incapacitated|incapacitated]] while in the area of an *[[../Spells/Antimagic Field|antimagic field]]*. If targeted by *[[../Spells/Dispel Magic|dispel magic]]*, the rug must succeed on a CON save against the caster’s spell save DC or fall [[../../Conditions/Unconscious|unconscious]] for 1 minute."
  - name: Construct Nature.
    desc: "The rug doesn’t require air, food, drink, or sleep."
  - name: Construct Resilience.
    desc: "The rug is immune to poison and psychic damage, and it is immune to exhaustion and the charmed, frightened, paralyzed, petrified, and poisoned conditions."
  - name: Damage Transfer.
    desc: "While it is grappling a creature, the rug takes only half the damage dealt to it (rounded down), and the creature grappled by the rug takes the other half."
  - name: False Appearance.
    desc: "While the rug remains motionless and isn’t flying, it is indistinguishable from a normal rug."
bonus_actions:
  - name: Rolling Charge (25 HP or Fewer).
    desc: "If it isn’t grappling a creature, the rug curls up and rolls along the ground up to triple its speed straight toward a creature it can sense. If it stops within 5 feet of the target, it can make one Smother attack against the target."
hp: 45
type: Construct
speed: 10 ft., fly 15 ft. (hover)
ac: 12
size: Large
actions:
  - name: Smother.
    desc: "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one Medium or smaller creature.  *Hit:* 12 (2d8 + 3) bludgeoning damage, and the target is [[../../Conditions/Grappled|grappled]] (escape DC 13). Until this grapple ends, the target is [[../../Conditions/Restrained|restrained]], [[../../Conditions/Blinded|blinded]], and unable to breathe, and the rug can’t fly and can’t Smother another target."
  - name: Squeeze Prey.
    desc: "The rug of smothering tightens around a creature it is grappling. The target must make a DC 13 STR save, taking 18 (4d8) bludgeoning damage on a failed save, or half as much damage on a successful one. A breathing creature that fails this save by 5 or more has the remaining air squeezed from its lungs and begins suffocating."
stats: ['+3', '+2', '+0', '−5', '−4', '−5']
```

#construct #cr2 #large
