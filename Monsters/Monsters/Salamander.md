
```statblock
layout: Basic ToV Layout
stealth: 12
bonus_actions:
  - name: Tighten Grip.
    desc: "The salamander tightens its grip around one creature it is grappling. Until the start of the salamander’s next turn, the target has disadvantage on any check made to escape the grapple, and other than a successful check to escape the grapple, the target can’t be moved, knocked prone, or otherwise removed from the salamander’s grasp without the salamander’s permission."
traits:
  - name: Heated Body.
    desc: "A creature that touches the salamander or hits it with a melee attack while within 5 feet of it takes 3 (1d6) fire damage."
  - name: Heated Weapons.
    desc: "When the salamander hits with a metal melee weapon, the weapon deals an extra 7 (2d6) fire damage (included in the attack)."
resistant: bludgeoning, piercing, and slashing damage from nonmagical attacks
type: Elemental
hp: 114
vulnerable: cold
name: Salamander
actions:
  - name: Multiattack.
    desc: "The salamander makes one Trident attack and one Tail attack, or it makes three Fire Bolt attacks. It can replace one Trident attack with a Tail attack."
  - name: Trident.
    desc: "*Melee or Ranged Weapon Attack:* +6 to hit, reach 5 ft. or range 20/60 ft., one target.  *Hit:* 10 (2d6 + 3) piercing damage, or 12 (2d8 + 3) piercing damage if used with two hands to make a melee attack, plus 7 (2d6) fire damage. If the target is wielding a weapon or shield, it must succeed on a DC 14 DEX save or drop the weapon or shield (the salamander’s choice if the target is wielding both)."
  - name: Tail.
    desc: "*Melee Weapon Attack:* +6 to hit, reach 10 ft., one target.  *Hit:* 10 (2d6 + 3) bludgeoning damage plus 7 (2d6) fire damage, and the target is [[../../Conditions/Grappled|grappled]] (escape DC 14). Until this grapple ends, the target is [[../../Conditions/Restrained|restrained]], the salamander can automatically hit the target with its tail, and the salamander can’t make tail attacks against other targets."
  - name: Fire Bolt.
    desc: "*Ranged Spell Attack:* +5 to hit, range 60 ft., one target.  *Hit:* 12 (3d6 + 2) fire damage."
stats: ['+3', '+2', '+2', '+0', '+0', '+2']
speed: 30 ft.
ac: 15 (natural armor)
size: Large
perception: 10
immune: fire
senses: darkvision 60 ft.
languages: Ignan
cr: 5
```

#cr5 #elemental #large
