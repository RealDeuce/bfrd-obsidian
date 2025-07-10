
```statblock
layout: Basic ToV Layout
stats: ['+0', '+4', '+3', '+2', '+1', '+6']
actions:
  - name: Multiattack.
    desc: "The medusa makes one Snake Hair attack and two Shortsword attacks, or it makes three Longbow attacks."
  - name: Snake Hair.
    desc: "*Melee Weapon Attack:* +7 to hit, reach 10 ft., one target.  *Hit:* 6 (1d4 + 4) piercing damage plus 14 (4d6) poison damage."
  - name: Shortsword.
    desc: "*Melee Weapon Attack:* +7 to hit, reach 5 ft., one target.  *Hit:* 7 (1d6 + 4) piercing damage plus 7 (2d6) poison damage."
  - name: Longbow.
    desc: "*Ranged Weapon Attack:* +7 to hit, range 150/600 ft., one target.  *Hit:* 8 (1d8 + 4) piercing damage plus 7 (2d6) poison damage."
ac: 15 (natural armor)
size: Medium
speed: 30 ft.
hp: 112
type: Monstrosity
stealth: 15
resistant: petrified | Monstrosity Resilience
traits:
  - name: Monstrosity Resilience.
    desc: "The medusa is resistant to exhaustion and to the frightened condition."
  - name: Petrifying Gaze.
    desc: "When a creature that can see the medusa’s eyes starts its turn within 30 feet of the medusa, the medusa can force it to make a DC 14 CON save if the medusa isn’t incapacitated and can see the creature. If the save fails by 5 or more, the creature is instantly petrified. Otherwise, a creature that fails the save begins to turn to stone and is [[../../Conditions/Restrained|restrained]]. The restrained creature must repeat the save at the end of its next turn, becoming [[../../Conditions/Petrified|petrified]] on a failure or ending the effect on itself on a success. The petrification lasts until the creature is freed by the *[[../Spells/Greater Restoration|greater restoration]]* spell or other magic.\n\nUnless surprised, a creature can avert its eyes to avoid the save at the start of its turn. If the creature does so, it can’t see the medusa until the start of its next turn, when it can avert its eyes again. If the creature looks at the medusa in the meantime, it must immediately make the save.\n\nIf the medusa sees itself reflected on a polished surface within 30 feet of it and in an area of bright light, the medusa, due to its curse, is affected by its own gaze. A medusa isn’t resistant to its own gaze."
  - name: Snake Friend.
    desc: "The medusa can communicate with snakes as if they shared a language, and snakes can’t be petrified by the medusa’s Petrifying Gaze."
name: Medusa
reactions:
  - name: Interruptive Hiss.
    desc: "When a creature the medusa can see targets it with an attack, the medusa’s snakes can suddenly rise and hiss at the attacker. The attacker must succeed on a DC 14 WIS save or fail the attack roll."
cr: 6
perception: 14
senses: darkvision 60 ft.
languages: Common
immune: poison | poisoned
```

#cr6 #medium #monstrosity
