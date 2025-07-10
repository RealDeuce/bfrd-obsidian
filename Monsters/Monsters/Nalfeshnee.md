
```statblock
layout: Basic ToV Layout
reactions:
  - name: Sudden Feast.
    desc: "When a creature the nalfeshnee can see within 20 feet of it is reduced to 0 HP or dies, the nalfeshnee can move up to its speed toward the creature without provoking opportunity attacks then feast on the creature, if it moves to within 5 feet of the creature. The nalfeshnee regains HP equal to twice the creature’s CR or class level, and the creature has disadvantage on the next death save it makes, if it is making death saves."
cr: 13
perception: 16
immune: Demonic Resilience
languages: Abyssal, telepathy 120 ft.
senses: truesight 120 ft.
subtype: Outsider, Demon
actions:
  - name: Multiattack.
    desc: "The nalfeshnee makes one Bite attack, one Gore attack, and two Claw attacks."
  - name: Bite.
    desc: "*Melee Weapon Attack:* +10 to hit, reach 5 ft., one target.  *Hit:* 28 (4d8 + 5) piercing damage. If this attack hits a frightened creature, the nalfeshnee regains HP equal to half the damage dealt."
  - name: Claw.
    desc: "*Melee Weapon Attack:* +10 to hit, reach 10 ft., one target.  *Hit:* 19 (4d6 + 5) slashing damage."
  - name: Gore.
    desc: "*Melee Weapon Attack:* +10 to hit, reach 5 ft., one target.  *Hit:* 21 (3d10 + 5) piercing damage, and the target must succeed on a DC 16 STR save or be knocked [[../../Conditions/Prone|prone]]."
stats: ['+5', '+0', '+11', '+8', '+6', '+7']
speed: 20 ft., fly 30 ft.
ac: 18 (natural armor)
size: Large
traits:
  - name: Demonic Resilience.
    desc: "The nalfeshnee is resistant to cold, fire, and lightning damage. In addition, it is immune to poison damage and to the poisoned condition."
  - name: Horrific Nimbus.
    desc: "The nalfeshnee magically emits scintillating, multicolored light that disorients and frightens mortals. Each creature that isn’t an Aberration, Celestial, or Fiend and that starts its turn within 15 feet of the nalfeshnee must succeed on a DC 16 WIS save or be [[../../Conditions/Frightened|frightened]] until the start of its next turn. A creature that fails the save by 5 or more must take the Dash action on its turn and move away from the nalfeshnee by the safest available route, unless there is nowhere to move."
  - name: Magic Resistance.
    desc: "The nalfeshnee has advantage on saves against spells and other magical effects."
bonus_actions:
  - name: Teleport.
    desc: "The nalfeshnee magically teleports, along with any equipment it is wearing or carrying, up to 60 feet to an unoccupied space it can see."
resistant: bludgeoning, piercing, and slashing damage from nonmagical attacks | Demonic Resilience
stealth: 10
type: Fiend
hp: 196
name: Nalfeshnee
```

#cr13 #demon #fiend #large #outsider
