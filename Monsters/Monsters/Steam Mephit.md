
```statblock
layout: Basic ToV Layout
perception: 13
languages: Aquan, Ignan
senses: darkvision 60 ft.
immune: fire, poison | poisoned, prone
cr: 1/2
hp: 27
type: Elemental
bonus_actions:
  - name: Hazy Form (1/Day).
    desc: "The mephit casts the *[[../Spells/Blur|blur]]* spell, requiring no material components and using WIS as the spellcasting ability."
traits:
  - name: Death Burst.
    desc: "When the mephit dies, it explodes in a cloud of steam. Each creature within 5 feet of the mephit must succeed on a DC 11 DEX save or be scalded for 1 minute. A scalded creature has disadvantage on weapon attack rolls and on ability checks that require manual dexterity. A scalded creature can repeat the save at the end of each of its turns, ending the effect on itself on a success."
  - name: Elemental Nature.
    desc: The mephit doesn’t require air, food, drink, or sleep.
  - name: False Appearance.
    desc: "While the mephit remains motionless and hovering, it is indistinguishable from an ordinary cloud of steam."
stealth: 14
vulnerable: cold, thunder
name: Steam Mephit
stats: ['−3', '+2', '+0', '−2', '+1', '+0']
actions:
  - name: Claws.
    desc: "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target.  *Hit:* 4 (1d4 + 2) slashing damage plus 2 (1d4) fire damage."
  - name: Steam Blast.
    desc: "*Ranged Weapon Attack:* +4 to hit, range 20/60 ft., one target.  *Hit:* 4 (1d4 + 2) bludgeoning damage plus 2 (1d4) fire damage"
  - name: Steam Breath (Recharge 6).
    desc: "The mephit exhales superheated breath in a 15-foot cone. Each creature in that area must make a DC 11 CON save. On a failure, a creature takes 5 (2d4) fire damage and suffers one level of [[../../Conditions/Exhaustion|exhaustion]]. On a success, a creature takes half the damage and doesn’t suffer exhaustion. A creature can’t suffer more than two levels of exhaustion from a steam mephit’s Steam Breath, regardless of the number of times it fails the save or the number of steam mephits using Steam Breath against it."
ac: 12
size: Small
speed: 30 ft., fly 30 ft. (hover)
```

#cr1-2 #elemental #small
