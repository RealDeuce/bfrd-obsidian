
```statblock
layout: Basic ToV Layout
type: Monstrosity
hp: 112
resistant: Fey Ancestry, Monstrosity Resilience
traits:
  - name: Fey Ancestry.
    desc: "The drider is resistant to the charmed condition, and magic can’t put the drider to sleep."
  - name: Monstrosity Resilience.
    desc: "The drider is resistant to exhaustion and to the frightened condition."
  - name: Spider Climb.
    desc: "The drider can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check."
  - name: Sunlight Sensitivity.
    desc: "While in sunlight, the drider has disadvantage on attack rolls, and its Perception is 10 when perceiving by sight."
  - name: Web Sense.
    desc: "While in contact with a web, the drider knows the exact location of any other creature in contact with the same web."
  - name: Web Walker.
    desc: "The drider ignores movement restrictions caused by webbing."
stealth: 19
name: Drider
stats: ['+3', '+6', '+4', '+1', '+2', '+1']
actions:
  - name: Multiattack.
    desc: "The drider makes one Longsword attack and two Skewer attacks, or it makes three Web Shot attacks."
  - name: Longsword.
    desc: "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one target.  *Hit:* 7 (1d8 + 3) slashing damage, or 8 (1d10 + 3) slashing damage if used with two hands."
  - name: Skewer.
    desc: "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one creature.  *Hit:* 6 (1d6 + 3) piercing damage plus 13 (3d8) poison damage."
  - name: Web Shot.
    desc: "*Ranged Weapon Attack:* +6 to hit, range 30/60 ft., one target.  *Hit:* 14 (2d10 + 3) bludgeoning damage, and the target must succeed on a DC 15 STR save or be [[../../Conditions/Restrained|restrained]] by webbing. A creature, including the restrained target, can take its action to break the webbing and free the restrained target by succeeding on a DC 15 STR check."
ac: 18 (natural armor)
size: Large
speed: 30 ft., climb 30 ft.
perception: 15
languages: Elvish, Undercommon
senses: darkvision 120 ft.
immune: poison | poisoned
cr: 6
```

#cr6 #large #monstrosity
