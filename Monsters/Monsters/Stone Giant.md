
```statblock
layout: Basic ToV Layout
type: Giant
hp: 156
stealth: 15
resistant: lightning | petrified | Giant Attributes
bonus_actions:
  - name: Wrestle.
    desc: "The stone giant performs one of the following wrestling maneuvers against one creature it is grappling. The target must succeed on a DC 17 STR save or suffer the listed effect until the stone giant uses this bonus action again or until the grapple ends.\n* **Armbar.** The target has disadvantage on attack rolls and on checks made to escape the grapple.\n* **Chinlock.** The target can’t speak and can’t cast spells with verbal components.\n* **Takedown.** The target is knocked [[../../Conditions/Prone|prone]] and [[../../Conditions/Restrained|restrained]].\n* **Throw.** The target is thrown up to 30 feet in a random direction and knocked [[../../Conditions/Prone|prone]], ending the grapple. If a thrown target strikes a solid surface, the target takes 3 (1d6) bludgeoning damage for every 10 feet it was thrown. If the target is thrown at another creature, that creature must succeed on a DC 17 DEX save or take the same damage and be knocked [[../../Conditions/Prone|prone]]."
traits:
  - name: Giant Attributes.
    desc: "The stone giant is resistant to the stunned condition, and it is vulnerable to the prone condition."
  - name: Stone Camouflage.
    desc: "The giant’s Stealth is 20 while in rocky terrain."
vulnerable: thunder | Giant Attributes
name: Stone Giant
stats: ['+6', '+5', '+8', '+0', '+4', '−1']
actions:
  - name: Multiattack.
    desc: "The giant makes two Stony Fist or Rock attacks."
  - name: Stony Fist.
    desc: "*Melee Weapon Attack:* +9 to hit, reach 10 ft., one target.  *Hit:* 24 (4d8 + 6) bludgeoning damage. The target is [[../../Conditions/Grappled|grappled]] (escape DC 17) if it is a Large or smaller creature and the stone giant isn’t already grappling a creature."
  - name: Rock.
    desc: "*Ranged Weapon Attack:* +9 to hit, range 60/240 ft., one target.  *Hit:* 28 (4d10 + 6) bludgeoning damage. If the target is a creature, it must succeed on a DC 17 STR save or be knocked [[../../Conditions/Prone|prone]]."
ac: 17 (natural armor)
size: Huge
speed: 40 ft.
perception: 14
senses: darkvision 60 ft.
languages: Giant
reactions:
  - name: Missile Deflection.
    desc: "If a creature the giant can see makes a ranged weapon attack against the giant, the giant can add 3 to its AC. If the attack misses, the giant can catch the missile, provided the attack included a projectile, and throw it back at the attacker, using the giant’s normal ranged weapon attack bonus and the weapon’s normal damage."
cr: 7
```

#cr7 #giant #huge
