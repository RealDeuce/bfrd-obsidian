
```statblock
layout: Basic ToV Layout
traits:
  - name: Construct Nature.
    desc: "The golem doesn’t require air, food, drink, or sleep."
  - name: Golem Resilience.
    desc: "The golem is immune to poison and psychic damage and to bludgeoning, piercing, and slashing damage from nonmagical attacks. In addition, it is immune to exhaustion and to the charmed, frightened, paralyzed, petrified, and poisoned conditions."
  - name: Fire Absorption.
    desc: "Whenever the golem is subjected to fire damage, it takes no damage and instead regains HP equal to the fire damage dealt."
  - name: Immutable Form.
    desc: "The golem is immune to any spell or effect that would alter its form."
  - name: Magic Resistance.
    desc: "The golem has advantage on saves against spells and other magical effects."
  - name: Magic Weapons.
    desc: "The golem’s weapon attacks are magical."
  - name: Warrior Stance.
    desc: "At the start of each of its turns, the iron golem chooses one of the following fighting stances to adopt, which lasts until the start of the golem’s next turn.\n* **Aggressive.** When the golem uses Multiattack, it can replace one additional Spear Arm attack with a Shield Bash attack. If it does so, its AC is reduced by 2 until the start of its next turn.\n* **Retributive.** The next time the golem is hit by a melee weapon attack from a creature within 5 feet of it before the start of its next turn, the golem can slam its shoulder into the attacker as a reaction. The attacker must succeed on a DC 18 STR save or be pushed up to 10 feet away from the golem and knocked [[../../Conditions/Prone|prone]].\n* **Defensive.** The golem’s AC increases by 4, but it can’t make Shield Bash attacks until the start of its next turn."
stealth: 9
perception: 15
type: Construct
hp: 201
name: Iron Golem
immune: fire | Golem Resilience
languages: understands the languages of its creator but can’t speak
senses: darkvision 120 ft.
actions:
  - name: Multiattack.
    desc: "The golem makes four Spear Arm attacks. It can replace one Spear Arm attack with a Shield Bash attack."
  - name: Shield Bash.
    desc: "*Melee Weapon Attack:* +12 to hit, reach 5 ft., one target.  *Hit:* 29 (4d10 + 7) bludgeoning damage, and the target must succeed on a DC 18 STR save or be knocked [[../../Conditions/Prone|prone]]."
  - name: Spear Arm.
    desc: "*Melee Weapon Attack:* +12 to hit, reach 10 ft., one target.  *Hit:* 25 (4d8 + 7) piercing damage."
  - name: Expel Poisonous Gas (Recharge 5–6).
    desc: "The golem vents poisonous gas from small holes across its body. Each creature within 15 feet of the golem must make a DC 18 CON save, taking 54 (12d8) poison damage on a failed save, or half as much damage on a successful one."
stats: ['+12', '−1', '+5', '−4', '+0', '−5']
speed: 30 ft.
ac: 20 (natural armor, shield)
size: Large
cr: 16
```

#construct #cr16 #large
