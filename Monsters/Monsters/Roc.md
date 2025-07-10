
```statblock
layout: Basic ToV Layout
stealth: 14
traits:
  - name: Heightened Sight.
    desc: "The roc’s Perception is 19 when perceiving by sight."
  - name: Monstrosity Resilience.
    desc: "The roc is resistant to exhaustion and to the frightened condition."
  - name: Seabird.
    desc: "The roc can swim up to 60 feet on its turn, but it must start and end its movement either flying or on a solid surface, such as a ship or beach. If it is swimming at the end of its turn, it must succeed on a DC 19 CON save or it immediately begins to sink and suffocate. A suffocating roc must succeed on a DC 19 STR check to fly out of the substance where it is sinking."
bonus_actions:
  - name: Territorial Shriek.
    desc: "The roc shrieks a territorial challenge at up to two creatures it can see within 60 feet of it. Each target must succeed on a DC 17 CHA save or be [[../../Conditions/Frightened|frightened]] until the end of its next turn. While frightened by this shriek, a creature must take the Dash action on its turn and move away from the roc by the safest available route, unless there is nowhere to move."
resistant: Monstrosity Resilience
hp: 235
type: Monstrosity
name: Roc
vulnerable: blinded
subtype: Animal
actions:
  - name: Multiattack.
    desc: "The roc makes one Beak attack and two Talon attacks. If both Talon attacks hit one Huge or Gargantuan creature, the target is [[../../Conditions/Grappled|grappled]] (escape DC 17). Until this grapple ends, the target is [[../../Conditions/Restrained|restrained]], and the roc can’t use its Talons on another target."
  - name: Beak.
    desc: "*Melee Weapon Attack:* +13 to hit, reach 10 ft., one target.  *Hit:* 27 (4d8 + 9) piercing damage."
  - name: Talon.
    desc: "*Melee Weapon Attack:* +13 to hit, reach 5 ft., one target.  *Hit:* 23 (4d6 + 9) slashing damage, and the target is [[../../Conditions/Grappled|grappled]] (escape DC 17) if it is a Large or smaller creature. Until this grapple ends, the target is [[../../Conditions/Restrained|restrained]], and the roc can’t use its Talons on another target."
stats: ['+9', '+4', '+9', '−4', '+4', '+3']
speed: 20 ft., fly 120 ft.
ac: 15 (natural armor)
size: Gargantuan
perception: 14
senses: —
languages: —
cr: 11
```

#animal #cr11 #gargantuan #monstrosity
