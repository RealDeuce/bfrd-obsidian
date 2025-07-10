
```statblock
layout: Basic ToV Layout
speed: 30 ft.
ac: 15 (scale mail)
size: Medium
actions:
  - name: Multiattack.
    desc: "The mechanist makes two Warhammer or Light Crossbow attacks."
  - name: Warhammer.
    desc: "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one target.  *Hit:* 7 (1d8 + 3) bludgeoning damage, or 8 (1d10 + 3) bludgeoning damage if used with two hands."
  - name: Light Crossbow.
    desc: "*Ranged Weapon Attack:* +3 to hit, range 80/320 ft., one target.  *Hit:* 5 (1d8 + 1) piercing damage."
  - name: Repair (Recharge 4–6).
    desc: "The mechanist touches one friendly Construct it can see. The target regains 5 (2d4) HP."
stats: ['+3', '+1', '+1', '+5', '+0', '+0']
name: Mechanist
subtype: Any Lineage
bonus_actions:
  - name: Quick Creation (Recharge 4–6).
    desc: "The mechanist cobbles together various machine parts it is carrying and creates a Tiny Construct. The Construct obeys the mechanist’s spoken commands. It uses the statistics of a **[[Solodron Mechadron|solodron]]** but it isn’t a mechadron or part of the Plan. The mechanist can have up to two such Constructs under its control at one time. Each Construct remains for 1 minute, until the mechanist dies, or until the mechanist uses this bonus action again to dismiss one or both of them."
traits:
  - name: Tools of the Trade.
    desc: "The mechanist is proficient with tinker tools and doubles its proficiency bonus for any ability check it makes with tinker tools."
stealth: 11
type: Humanoid
hp: 60
cr: 2
reactions:
  - name: Magnetic Pulse.
    desc: "When a creature the mechanist can see attacks it with a weapon made at least partially of metal while within 5 feet of it, the mechanist can release a magical, magnetic pulse. The attacker must succeed on a DC 13 DEX save or have disadvantage on the attack roll."
languages: Common, plus any two languages
senses: —
perception: 10
```

#cr2 #humanoid #medium
