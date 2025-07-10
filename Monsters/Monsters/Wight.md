
```statblock
layout: Basic ToV Layout
name: Wight
hp: 69
type: Undead
stealth: 14
traits:
  - name: Martial Adept.
    desc: "A manufactured weapon, such as a sword or bow, deals one extra die of its damage when the wight hits with it (included in the attack)."
  - name: Sunlight Sensitivity.
    desc: "While in sunlight, the wight has disadvantage on attack rolls, and its Perception is 8 when perceiving by sight."
  - name: Undead Nature.
    desc: "The wight doesn’t require air, food, drink, or sleep."
  - name: Undead Resilience.
    desc: "The wight is immune to poison damage, to exhaustion, and to the poisoned condition."
bonus_actions:
  - name: Command Horde.
    desc: "The wight commands up to five friendly skeletons or zombies to do one of the following:\n* **Protect.** Until the start of the wight’s next turn, each time a friendly creature within 5 feet of a target is attacked, the target can use its reaction to intercept the attack, becoming the target instead.\n* **Overwhelm.** Until the start of the wight’s next turn, each target has advantage on attack rolls against a creature on its turn if at least one other target is within 5 feet of the creature and the allied target isn’t incapacitated.\n* **Shamble.** Each target uses its reaction to move up to its    speed in a direction chosen by the wight. If this movement provokes an opportunity attack, that attack is made with disadvantage."
resistant: necrotic; bludgeoning, piercing, and slashing damage from nonmagical attacks
ac: 14 (studded leather)
size: Medium
speed: 30 ft.
stats: ['+3', '+2', '+3', '+0', '+1', '+2']
actions:
  - name: Multiattack.
    desc: "The wight makes two Longsword or Longbow attacks. It can replace one attack with a Life Drain attack."
  - name: Life Drain.
    desc: "*Melee Spell Attack:* +5 to hit, reach 5 ft., one creature.  *Hit:* 10 (2d6 + 3) necrotic damage. The target must succeed on a DC 13 CON save or its HP maximum is reduced by an amount equal to the damage taken. This reduction lasts until the target finishes a long rest. The target dies if this effect reduces its HP maximum to 0. A Humanoid slain by this attack rises 24 hours later as a **[[Zombie|zombie]]** under the wight’s control, unless the Humanoid is restored to life or its body is destroyed. The wight can have no more than twelve zombies under its control at one time."
  - name: Longsword.
    desc: "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one target.  *Hit:* 12 (2d8 + 3) slashing damage, or 14 (2d10 + 3) slashing damage if used with two hands."
  - name: Longbow.
    desc: "*Ranged Weapon Attack:* +4 to hit, range 150/600 ft., one target.  *Hit:* 11 (2d8 + 2) piercing damage."
senses: darkvision 60 ft.
languages: the languages it knew in life
immune: Undead Resilience | frightened
perception: 13
cr: 3
```

#cr3 #medium #undead
