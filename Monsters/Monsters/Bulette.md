
```statblock
layout: Basic ToV Layout
ac: 17 (natural armor)
size: Large
speed: 40 ft., burrow 40 ft.
stats: ['+7', '+0', '+5', '−4', '+0', '−3']
actions:
  - name: Multiattack.
    desc: "The bulette makes two Bite attacks."
  - name: Bite.
    desc: "*Melee Weapon Attack:* +7 to hit, reach 5 ft., one target.  *Hit:* 20 (3d10 + 4) piercing damage."
  - name: Deadly Leap (Recharge 5–6).
    desc: "The bulette leaps up to 30 feet, diving onto a point it can see or sense within that range and landing on its feet with a thunderous crash. It occupies a space of its choice within 5 feet of that point, and each creature within 10 feet of that point must make a DC 15 STR save. On a failure, a creature takes 14 (4d6) bludgeoning damage and 14 (4d6) thunder damage and is knocked [[../../Conditions/Prone|prone]]. On a success, a creature takes half the damage and isn’t knocked prone. Any creature in the bulette’s space is then pushed into an unoccupied space within 5 feet of the bulette. If no unoccupied space is within range, the creature instead falls [[../../Conditions/Prone|prone]] in the bulette’s space."
name: Bulette
hp: 108
type: Monstrosity
stealth: 10
bonus_actions:
  - name: Seek Prey.
    desc: "The bulette looks and sniffs around for new prey, releasing a satisfied, guttural chirp when it settles on one. One creature the bulette can see or sense within 30 feet of it and that can see or hear the bulette must make a DC 15 WIS save. On a failure, the target is [[../../Conditions/Frightened|frightened]] until the end of its next turn, and the bulette has advantage on the next attack roll it makes against the creature before the start of its next turn."
resistant: bludgeoning | Monstrosity Resilience
traits:
  - name: Monstrosity Resilience.
    desc: "The bulette is resistant to exhaustion and to the frightened condition."
  - name: Standing Leap.
    desc: "The bulette’s long jump is up to 30 feet and its high jump is up to 15 feet, with or without a running start."
cr: 5
senses: darkvision 60 ft., tremorsense 60 ft.
languages: —
perception: 16
```

#cr5 #large #monstrosity
