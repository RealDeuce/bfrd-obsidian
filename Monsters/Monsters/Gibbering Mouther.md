
```statblock
layout: Basic ToV Layout
ac: 9
size: Medium
speed: 10 ft., swim 10 ft.
stats: ['+2', '−1', '+3', '−4', '+0', '−2']
actions:
  - name: Multiattack.
    desc: "The gibbering mouther makes two Bite attacks. If both attacks hit one Medium or smaller creature, the target must succeed on a DC 13 STR save or be knocked [[../../Conditions/Prone|prone]]."
  - name: Bite.
    desc: "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one creature.  *Hit:* 11 (2d8 + 2) piercing damage."
  - name: Rend Mind.
    desc: "One creature the mouther can see within 30 feet of it must succeed on a DC 13 WIS save or take 18 (4d8) psychic damage and suffer a random, short-term dread effect for 1 minute"
name: Gibbering Mouther
type: Aberration
hp: 72
bonus_actions:
  - name: Blinding Spittle.
    desc: "The mouther spits an otherworldly goo at up to two creatures it can see within 30 feet of it. Each target must succeed on a DC 13 DEX save or be [[../../Conditions/Blinded|blinded]] until the end of its next turn."
traits:
  - name: Aberrant Ground.
    desc: "The ground within 10 feet of the mouther is dough-like difficult terrain. A creature that starts its turn in the area must succeed on a DC 13 STR save or its speed is halved until the start of its next turn."
  - name: Aberrant Resilience.
    desc: "The mouther is resistant to the charmed, frightened, paralyzed, and stunned conditions, and it has advantage on saves against spells or effects that would alter its form."
  - name: Gibbering.
    desc: "The mouther babbles incoherently while it can see any creature and isn’t incapacitated. A creature that starts its turn within 20 feet of the mouther and that can hear the gibbering must succeed on a DC 13 WIS save or it can’t take reactions until the start of its next turn and must roll a d8 to determine what it does during its turn. On a 1 to 4, the creature does nothing. On a 5 or 6, the creature takes no action or bonus action and moves its full speed in a randomly determined direction. On a 7 or 8, the creature makes a melee attack against a randomly determined creature within its reach or does nothing if it can’t make such an attack."
resistant: Aberrant Resilience
stealth: 9
cr: 2
languages: —
senses: darkvision 60 ft.
immune: prone
perception: 10
```

#aberration #cr2 #medium
