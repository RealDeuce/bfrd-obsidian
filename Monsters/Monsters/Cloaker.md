
```statblock
layout: Basic ToV Layout
resistant: Aberrant Resilience
bonus_actions:
  - name: Cloak of Shadows (3/Day).
    desc: "While the cloaker isn’t in bright light, it pulls shadows around itself, partially obscuring its form. For 1 minute or until the cloaker is hit with an attack, the cloaker’s Stealth is 20, and creatures have disadvantage on attack rolls against the cloaker."
traits:
  - name: Aberrant Resilience.
    desc: "The cloaker is resistant to the charmed, frightened, paralyzed, and stunned conditions, and it has advantage on saves against spells or effects that would alter its form."
  - name: Damage Transfer.
    desc: "While attached to a creature, the cloaker takes only half the damage dealt to it (rounded down), and that creature takes the other half."
  - name: False Appearance.
    desc: "While the cloaker remains motionless without its underside exposed, it is indistinguishable from a dark leather cloak."
  - name: Light Sensitivity.
    desc: "While in bright light, the cloaker has disadvantage on attack rolls, and its Perception is 6 when perceiving by sight."
stealth: 15
hp: 105
type: Aberration
name: Cloaker
actions:
  - name: Multiattack.
    desc: "The cloaker makes one Bite attack and two Tail attacks."
  - name: Bite.
    desc: "*Melee Weapon Attack:* +7 to hit, reach 5 ft., one creature.  *Hit:* 18 (4d6 + 4) piercing damage, and if the target is Large or smaller, the cloaker attaches to it. If the cloaker has advantage on the attack roll, the cloaker attaches to the target’s head, and the target is [[../../Conditions/Blinded|blinded]] and unable to breathe while the cloaker is attached. While attached, the cloaker can’t make Bite attacks, and at the start of each of the cloaker’s turns, the target takes 18 (4d6 + 4) piercing damage.\n\nThe attached cloaker moves with the target whenever the target moves, requiring none of the cloaker’s movement. It can detach itself by spending 5 feet of its movement on its turn. A creature, including the target, can take its action to detach the cloaker by succeeding on a DC 15 STR check."
  - name: Tail.
    desc: "*Melee Weapon Attack:* +7 to hit, reach 10 ft., one target.  *Hit:* 17 (3d8 + 4) slashing damage."
  - name: Moan (Recharge 6).
    desc: "The cloaker releases a deep, thrumming moan that rattles the nerves of all who hear it. Each creature within 30 feet of the cloaker that can hear the moan and that isn’t an Aberration must make a DC 15 WIS save. On a failure, a creature takes 40 (9d8) psychic damage and is [[../../Conditions/Frightened|frightened]] until the end of its next turn. On a success, a creature takes half the damage and isn’t frightened."
stats: ['+4', '+5', '+1', '+1', '+1', '+2']
speed: 10 ft., fly 40 ft.
ac: 14 (natural armor)
size: Large
perception: 11
languages: Deep Speech, Undercommon
senses: darkvision 60 ft.
cr: 8
```

#aberration #cr8 #large
