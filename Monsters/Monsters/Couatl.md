
```statblock
layout: Basic ToV Layout
ac: 17 (natural armor)
size: Medium
speed: 30 ft., fly 90 ft.
stats: ['+3', '+5', '+3', '+4', '+7', '+6']
actions:
  - name: Multiattack.
    desc: "The couatl makes one Bite attack and one Constrict attack."
  - name: Bite.
    desc: "*Melee Weapon Attack:* +7 to hit, reach 5 ft., one creature.  *Hit:* 8 (1d6 + 5) piercing damage plus 14 (4d6) poison damage. If the poison damage reduces the target to 0 HP, the couatl can choose for the target to be stable but [[../../Conditions/Poisoned|poisoned]] for 1 hour, even after regaining HP, and is [[../../Conditions/Unconscious|unconscious]] while poisoned in this way."
  - name: Constrict.
    desc: "*Melee Weapon Attack:* +7 to hit, reach 10 ft., one target.  *Hit:* 12 (2d6 + 5) bludgeoning damage, and the target is [[../../Conditions/Grappled|grappled]] (escape DC 15) if it is a Medium or smaller creature. Until this grapple ends, the target is [[../../Conditions/Restrained|restrained]], and the couatl can’t Constrict another target."
  - name: Healing Hiss (3/Day).
    desc: "The couatl croons a soothing hiss at a creature it can sense within 5 feet of it. The target magically regains 10 (3d6) HP and is freed from any disease or poison."
name: Couatl
hp: 77
type: Celestial
stealth: 15
traits:
  - name: Celestial Resilience.
    desc: "The couatl is resistant to radiant damage and to bludgeoning, piercing, and slashing damage from nonmagical attacks."
  - name: Inscrutable.
    desc: "The couatl is immune to any effect that would sense its emotions or read its thoughts, as well as divination spells or effects, such as scrying or detecting its location, that it refuses. WIS (Insight) checks made to ascertain the couatl’s intentions or sincerity have disadvantage."
  - name: Magic Resistance.
    desc: "The couatl has advantage on saves against spells and other magical effects."
  - name: Magic Weapons.
    desc: "The couatl’s weapon attacks are magical."
bonus_actions:
  - name: Change Shape.
    desc: "The couatl magically transforms into a Large or smaller Beast or Humanoid that has a challenge rating no higher than its own, or back into its true form, which is Celestial. Any equipment it is wearing or carrying transforms with it or is borne by the new form (the couatl’s choice). It reverts to its true form if it dies. In a new form, the couatl retains its Celestial Resilience and Inscrutable traits and its HP, HD, ability to speak, proficiencies, and INT, WIS, and CHA scores, as well as this bonus action and the Rainbow Shield reaction. Its statistics and capabilities are otherwise replaced by those of the new form, except any class features or legendary actions of that form."
resistant: Celestial Resilience
cr: 4
reactions:
  - name: Rainbow Shield.
    desc: "When a creature the couatl can see within 30 feet of it, including itself, is targeted with an attack, the couatl can interpose a shield of rainbow-hued light between the attacker and the creature. The attacker has disadvantage on the attack roll. If the protected creature hasn’t attacked or harmed another creature within the last minute, the attacker’s attack misses instead."
senses: truesight 120 ft.
languages: all, telepathy 120 ft.
immune: psychic
perception: 17
```

#celestial #cr4 #medium
