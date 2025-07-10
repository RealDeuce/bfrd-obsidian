
```statblock
layout: Basic ToV Layout
speed: 20 ft., fly 80 ft.
ac: 13 (natural armor)
size: Large
cr: 6
actions:
  - name: Multiattack.
    desc: "The wyvern makes one Bite attack and one Stinger attack. While flying, it can replace one attack with a Claws attack."
  - name: Bite.
    desc: "*Melee Weapon Attack:* +7 to hit, reach 5 ft., one creature.  *Hit:* 11 (2d6 + 4) piercing damage."
  - name: Claws.
    desc: "*Melee Weapon Attack:* +7 to hit, reach 5 ft., one target.  *Hit:* 13 (2d8 + 4) slashing damage."
  - name: Stinger.
    desc: "*Melee Weapon Attack:* +7 to hit, reach 15 ft., one creature.  *Hit:* 15 (2d10 + 4) piercing damage plus 18 (4d8) poison damage. The target must succeed on a DC 15 CON save or be [[../../Conditions/Poisoned|poisoned]] for 1 minute. A poisoned creature can repeat the save at the end of each of its turns, ending the effect on itself on a success."
stats: ['+4', '+0', '+3', '−3', '+1', '−2']
reactions:
  - name: Reflexive Tail Whip.
    desc: "When a creature moves into a space within 15 feet of the wyvern, it can whip its tail at the creature. The target must succeed on a DC 15 STR save or be knocked [[../../Conditions/Prone|prone]]."
vulnerable: Clumsy
name: Wyvern
immune: poison | poisoned
languages: —
senses: darkvision 60 ft.
traits:
  - name: Clumsy.
    desc: "While not flying, the wyvern is vulnerable to the grappled, prone, and restrained conditions."
stealth: 10
perception: 14
type: Dragon
hp: 147
```

#cr6 #dragon #large
