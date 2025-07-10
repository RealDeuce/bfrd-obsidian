
```statblock
layout: Basic ToV Layout
senses: darkvision 120 ft.
languages: Deep Speech, telepathy 60 ft.
immune: prone
perception: 14
cr: 3
name: Mordovermis
type: Aberration
hp: 72
stealth: 12
traits:
  - name: Aberrant Resilience.
    desc: "The mordovermis is resistant to the charmed, frightened, paralyzed, and stunned conditions, and it has advantage on saves against spells or effects that would alter its form."
  - name: Sinuous Form.
    desc: "The mordovermis can easily move through any opening large enough for a Small creature. It can squeeze through any opening large enough for a Tiny creature. The mordovermis’s destination must still have suitable room to accommodate its volume."
  - name: Sunlight Sensitivity.
    desc: "While in sunlight, the mordovermis has disadvantage on attack rolls, and its Perception is 9 when perceiving by sight."
bonus_actions:
  - name: Transfixing Gaze.
    desc: "The mordovermis focuses its gaze on one creature it can see within 30 feet of it. The target must succeed on a DC 13 WIS save or be [[../../Conditions/Charmed|charmed]] until the end of its next turn. While charmed, the creature is [[../../Conditions/Incapacitated|incapacitated]] and has a speed of 0."
resistant: bludgeoning | Aberrant Resilience
size: Large
ac: 13 (natural armor)
speed: 10 ft., fly 40 ft. (hover)
stats: ['+3', '+2', '+2', '−2', '+2', '+3']
actions:
  - name: Multiattack.
    desc: "The mordovermis makes two Sting attacks. If both Sting attacks hit one Large or smaller creature, the mordovermis can use Consume on the creature without the need for the target to be incapacitated."
  - name: Sting.
    desc: "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one target.  *Hit:* 7 (1d8 + 3) piercing damage."
  - name: Consume.
    desc: "The mordovermis wraps its body around an incapacitated creature. The target must make a DC 13 STR save. On a failure, the target takes 5 (2d4) piercing damage and 9 (2d8) acid damage and is [[../../Conditions/Grappled|grappled]] (escape DC 13). On a success, the target takes half the damage and isn’t grappled. Until this grapple ends, the target is [[../../Conditions/Restrained|restrained]] and takes 18 (4d8) acid damage at the start of each of its turns, and the mordovermis can’t use Consume."
```

#aberration #cr3 #large
