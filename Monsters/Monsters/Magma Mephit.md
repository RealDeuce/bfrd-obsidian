
```statblock
layout: Basic ToV Layout
cr: 1/2
senses: darkvision 60 ft.
languages: Ignan, Terran
immune: fire, poison | poisoned
perception: 12
ac: 12 (natural armor)
size: Small
speed: 30 ft., fly 30 ft.
stats: ['+2', '+0', '+0', '−2', '+0', '+1']
actions:
  - name: Claws.
    desc: "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target.  *Hit:* 4 (1d4 + 2) slashing damage plus 3 (1d6) fire damage."
  - name: Lob Magma.
    desc: "*Ranged Weapon Attack:* +2 to hit, range 20/60 ft., one target.  *Hit:* 7 (2d6) fire damage."
  - name: Pyroclastic Burst (Recharge 6).
    desc: "The mephit exhales an explosive blast of lava in a 15-foot cone. Each creature in the area must make a DC 11 STR save. On a failure, a creature takes 7 (2d6) fire damage and is pushed up to 10 feet away from the mephit and knocked [[../../Conditions/Prone|prone]]. On a success, a creature takes half the damage and isn’t pushed or knocked prone."
vulnerable: bludgeoning, cold
name: Magma Mephit
hp: 27
type: Elemental
stealth: 12
traits:
  - name: Death Burst.
    desc: "When the mephit dies, it explodes in a burst of lava. Each creature within 5 feet of it must succeed on a DC 11 DEX save or be pushed up to 10 feet away from the mephit, knocked [[../../Conditions/Prone|prone]], and catch on fire. Until a creature takes an action to douse the fire, the creature on fire takes 3 (1d6) fire damage at the start of each of its turns."
  - name: Elemental Nature.
    desc: The mephit doesn’t require air, food, drink, or sleep.
  - name: False Appearance.
    desc: "While the mephit remains motionless, it is indistinguishable from an ordinary mound of molten rock."
bonus_actions:
  - name: Pyrotechnic Display (1/Day).
    desc: "The mephit casts the *[[../Spells/Color Spray|color spray]]* spell (spell save DC 11), requiring no material components and using CHA as the spellcasting ability."
```

#cr1-2 #elemental #small
