
```statblock
layout: Basic ToV Layout
ac: 13
size: Medium
speed: 30 ft., climb 30 ft.
stats: ['+2', '+3', '+1', '−3', '+3', '−1']
actions:
  - name: Multiattack.
    desc: "The ettercap makes one Bite attack and one Claws attack, or it makes two Spit Poison attacks."
  - name: Bite.
    desc: "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one creature.  *Hit:* 7 (1d8 + 3) piercing damage plus 4 (1d8) poison damage. The target must succeed on a DC 13 CON save or be [[../../Conditions/Poisoned|poisoned]] for 1 minute. The target can repeat the save at the end of each of its turns, ending the effect on itself on a success."
  - name: Claws.
    desc: "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one target.  *Hit:* 10 (2d6 + 3) slashing damage."
  - name: Spit Poison.
    desc: "*Ranged Weapon Attack:* +5 to hit, range 20/60 ft., one target.  *Hit:* 11 (2d8 + 3) poison damage."
name: Ettercap
hp: 54
type: Monstrosity
stealth: 13
resistant: Monstrosity Resilience
bonus_actions:
  - name: Web (Recharge 4–6).
    desc: "The ettercap launches a gob of webbing at one creature it can see within 30 feet of it. The target must succeed on a DC 13 DEX save or be [[../../Conditions/Restrained|restrained]]. A creature, including the restrained target, can take its action to free the target from the webbing by succeeding on a DC 13 STR check. The webbing can also be attacked and destroyed (AC 10; HP 5; vulnerability to fire damage; immunity to bludgeoning, poison, and psychic damage)."
traits:
  - name: Monstrosity Resilience.
    desc: "The ettercap is resistant to exhaustion and to the frightened condition."
  - name: Spider Climb.
    desc: "The ettercap can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check."
  - name: Web Sense.
    desc: "While in contact with a web, the ettercap knows the exact location of any other creature in contact with the same web."
  - name: Web Walker.
    desc: "The ettercap ignores movement restrictions caused by webbing."
cr: 2
senses: darkvision 60 ft.
languages: —
immune: poison | poisoned
perception: 13
```

#cr2 #medium #monstrosity
