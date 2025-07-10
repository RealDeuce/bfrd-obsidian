
```statblock
layout: Basic ToV Layout
actions:
  - name: Multiattack.
    desc: "The mummy makes two Rotting Fist attacks. If both attacks hit one creature that isn’t a Construct or Undead, the target must succeed on a DC 13 CON save or be cursed with mummy rot (see the Mummy Rot sidebar)."
  - name: Rotting Fist.
    desc: "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one target.  *Hit:* 7 (1d8 + 3) bludgeoning damage plus 7 (2d6) necrotic damage."
stats: ['+3', '−1', '+3', '−2', '+2', '+1']
speed: 20 ft.
ac: 13 (natural armor)
size: Medium
stealth: 9
bonus_actions:
  - name: Dreadful Glare.
    desc: "The mummy glares at one creature it can see within 60 feet of it. The target must succeed on a DC 13 WIS save or be [[../../Conditions/Frightened|frightened]] until the end of its next turn. If the target fails the save by 5 or more, it is also [[../../Conditions/Paralyzed|paralyzed]] for the same duration."
traits:
  - name: Undead Nature.
    desc: "The mummy doesn’t require air, food, drink, or sleep."
  - name: Undead Resilience.
    desc: "The mummy is immune to poison damage, to exhaustion, and to the poisoned condition."
resistant: bludgeoning, piercing, and slashing damage from nonmagical attacks
type: Undead
hp: 80
name: Mummy
vulnerable: fire
cr: 3
perception: 12
immune: necrotic | charmed, frightened, paralyzed | Undead Resilience
senses: darkvision 60 ft.
languages: the languages it knew in life
```

#cr3 #medium #undead
