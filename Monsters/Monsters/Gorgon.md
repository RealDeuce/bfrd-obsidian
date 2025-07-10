
```statblock
layout: Basic ToV Layout
cr: 5
reactions:
  - name: Poisonous Retort.
    desc: "When the gorgon is hit by an attack from a creature it can see within 10 feet of it, the gorgon can snort angrily, releasing a puff of poisonous gas at the creature. The attacker must succeed on a DC 16 CON save or be [[../../Conditions/Poisoned|poisoned]] until the end of its next turn."
senses: darkvision 60 ft.
languages: —
immune: poison | petrified, poisoned
perception: 15
ac: 18 (natural armor)
size: Large
speed: 40 ft.
stats: ['+5', '+0', '+4', '−4', '+2', '−2']
actions:
  - name: Multiattack.
    desc: "The gorgon makes one Gore attack and one Hooves attack."
  - name: Gore.
    desc: "*Melee Weapon Attack:* +8 to hit, reach 5 ft., one target.  *Hit:* 18 (2d12 + 5) piercing damage."
  - name: Hooves.
    desc: "*Melee Weapon Attack:* +8 to hit, reach 5 ft., one target.  *Hit:* 16 (2d10 + 5) bludgeoning damage."
  - name: Petrifying Breath (Recharge 5–6).
    desc: "The gorgon exhales poisonous, petrifying gas in a 30-foot cone. Creatures in the area must make a DC 13 CON save. On a failure, a creature takes 21 (6d6) poison damage and is [[../../Conditions/Restrained|restrained]] as it begins to turn to stone. On a success, a creature takes half the damage and isn’t restrained. A restrained creature must repeat the save at the end of its next turn. On a success, the effect ends on the creature. On a failure, the creature is [[../../Conditions/Petrified|petrified]] until freed by the *[[../Spells/Greater Restoration|greater restoration]]* spell or other magic."
name: Gorgon
type: Monstrosity
hp: 96
stealth: 10
traits:
  - name: Monstrosity Resilience.
    desc: "The gorgon is resistant to exhaustion and to the frightened condition."
  - name: Trampling Charge.
    desc: "If the gorgon moves at least 20 feet straight toward a creature and then hits it with a Gore attack on the same turn, that target must succeed on a DC 16 STR save or be knocked [[../../Conditions/Prone|prone]]. If the target is prone, the gorgon can make one Hooves attack against it as a bonus action."
resistant: Monstrosity Resilience
```

#cr5 #large #monstrosity
