
```statblock
layout: Basic ToV Layout
languages: Aquan, Auran
senses: darkvision 60 ft.
immune: cold, poison | poisoned
perception: 12
cr: 1/2
name: Ice Mephit
vulnerable: bludgeoning, fire
hp: 27
type: Elemental
bonus_actions:
  - name: Cloud of Snow (1/Day).
    desc: "The mephit casts the *[[../Spells/Fog Cloud|fog cloud]]* spell, requiring no material components and using CHA as the spellcasting ability."
traits:
  - name: Death Burst.
    desc: "When the mephit dies, it explodes in a burst of viscous ice. Each creature within 5 feet of it must succeed on a DC 11 DEX save or be [[../../Conditions/Restrained|restrained]] by ice for 1 minute. A creature, including the restrained creature, can take its action to free the restrained creature by succeeding on a DC 11 STR check. The ice melts immediately if the restrained creature takes fire damage, freeing the creature."
  - name: Elemental Nature.
    desc: The mephit doesn’t require air, food, drink, or sleep.
  - name: False Appearance.
    desc: "While the mephit remains motionless, it is indistinguishable from an ordinary shard of ice."
stealth: 14
size: Small
ac: 12
speed: 30 ft., fly 30 ft.
stats: ['−3', '+2', '+0', '−2', '+0', '+1']
actions:
  - name: Claws.
    desc: "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target.  *Hit:* 4 (1d4 + 2) slashing damage plus 3 (1d6) cold damage."
  - name: Ice Shard.
    desc: "*Ranged Weapon Attack:* +4 to hit, range 20/60 ft., one target.  *Hit:* 4 (1d4 + 2) piercing damage plus 3 (1d6) cold damage."
  - name: Frost Breath (Recharge 6).
    desc: "The mephit exhales freezing fog in a 15-foot cone. Each creature in that area must make a DC 11 CON save. On a failure, a creature takes 7 (2d6) cold damage and is [[../../Conditions/Restrained|restrained]] by ice until the end of its next turn. On a success, a creature takes half the damage and isn’t restrained."
```

#cr1-2 #elemental #small
