
```statblock
layout: Basic ToV Layout
languages: Draconic
senses: darkvision 90 ft.
immune: lightning
perception: 16
cr: 11
name: Behir
type: Monstrosity
hp: 223
resistant: Monstrosity Resilience
traits:
  - name: Lightning Absorption.
    desc: "Whenever the behir is subjected to lighting damage, it takes no damage and instead regains a number of HP equal to the lightning damage dealt."
  - name: Monstrosity Resilience.
    desc: "The behir is resistant to exhaustion and to the frightened condition."
stealth: 17
size: Huge
ac: 17 (natural armor)
speed: 50 ft., climb 40 ft.
stats: ['+10', '+3', '+4', '−2', '+6', '+1']
actions:
  - name: Multiattack.
    desc: "The behir makes one Bite attack and one Constrict attack. It can replace its Bite attack with a use of Swallow."
  - name: Bite.
    desc: "*Melee Weapon Attack:* +10 to hit, reach 10 ft., one target.  *Hit:* 22 (3d10 + 6) piercing damage plus 27 (6d8) lightning damage."
  - name: Constrict.
    desc: "*Melee Weapon Attack:* +10 to hit, reach 5 ft., one Large or smaller creature.  *Hit:* 17 (2d10 + 6) bludgeoning damage. If the target is Large or smaller and the behir isn’t already grappling a creature, the target is [[../../Conditions/Grappled|grappled]] (escape DC 16). Until this grapple ends, the target is [[../../Conditions/Restrained|restrained]], and the behir can’t Constrict another target."
  - name: Swallow.
    desc: "The behir makes one Bite attack against a Medium or smaller target it is grappling. If the attack hits, the target is also swallowed, and the grapple ends. While swallowed, the target is [[../../Conditions/Blinded|blinded]] and [[../../Conditions/Restrained|restrained]], it has total cover against attacks and other effects outside the behir, and it takes 21 (6d6) acid damage at the start of each of the behir’s turns. A behir can have only one creature swallowed at a time.\n\nIf the behir takes 30 damage or more on a single turn from the swallowed creature, the behir must succeed on a DC 14 CON save at the end of that turn or regurgitate the creature, which falls [[../../Conditions/Prone|prone]] in a space within 10 feet of the behir. If the behir dies, a swallowed creature is no longer restrained by it and can escape from the corpse by using 15 feet of movement, exiting [[../../Conditions/Prone|prone]]."
  - name: Lightning Breath (Recharge 5–6).
    desc: "The behir exhales lightning in a 30-foot line that is 5 feet wide. Each creature in that line must make a DC 16 Dexterity saving throw, taking 54 (12d8) lightning damage on a failed save, or half as much damage on a successful one."
```

#cr11 #huge #monstrosity
