
```statblock
layout: Basic ToV Layout
actions:
  - name: Multiattack.
    desc: "The marilith makes two Dagger attacks, two Mace attacks, and two Longsword attacks. It can replace two Dagger attacks with a Tail attack."
  - name: Dagger.
    desc: "*Melee or Ranged Weapon Attack:* +9 to hit, reach 5 ft. or range 20/60 ft., one target.  *Hit:* 9 (2d4 + 4) piercing damage plus 7 (2d6) fire damage."
  - name: Mace.
    desc: "*Melee Weapon Attack:* +9 to hit, reach 5 ft., one target.  *Hit:* 11 (2d6 + 4) bludgeoning damage plus 7 (2d6) fire damage."
  - name: Longsword.
    desc: "*Melee Weapon Attack:* +9 to hit, reach 5 ft., one target.  *Hit:* 13 (2d8 + 4) slashing damage plus 7 (2d6) fire damage."
  - name: Tail.
    desc: "*Melee Weapon Attack:* +9 to hit, reach 10 ft., one creature.  *Hit:* 20 (3d10 + 4) bludgeoning damage plus 7 (2d6) fire damage. If the target is Medium or smaller, it is [[../../Conditions/Grappled|grappled]] (escape DC 17). Until this grapple ends, the target is [[../../Conditions/Restrained|restrained]], the marilith can automatically hit the target with its Tail, and the marilith can’t make Tail attacks against other targets."
subtype: Outsider, Demon
stats: ['+9', '+5', '+10', '+4', '+8', '+10']
speed: 40 ft.
ac: 18 (natural armor)
size: Large
stealth: 15
resistant: bludgeoning, piercing, and slashing damage from nonmagical attacks | Demonic Resilience
bonus_actions:
  - name: Marilith Tactics.
    desc: "The marilith shouts one of the following commands at up to two friendly creatures it can see within 30 feet of it:\n* **March!** Each target can use a reaction to move up to half its speed in a direction of the marilith’s choice. This movement is unaffected by difficult terrain and doesn’t provoke    opportunity attacks.\n* **Protect Yourself!** Each target gains the marilith’s Parry reaction until the start of the marilith’s next turn.\n* **Remember Your Training!** Each target has advantage on the next weapon attack roll it makes before the start of the marilith’s next turn."
  - name: Teleport.
    desc: "The marilith magically teleports, along with any equipment it is wearing or carrying, up to 60 feet to an unoccupied space it can see."
traits:
  - name: Demonic Resilience.
    desc: "The marilith is resistant to cold, fire, and lightning damage. In addition, it is immune to poison damage and to the poisoned condition."
  - name: Flaming Weapons.
    desc: "The marilith’s weapon attacks are magical. When it hits with any weapon, the weapon deals an extra 2d6 fire damage (included in the attack)."
  - name: Magic Resistance.
    desc: "The marilith has advantage on saves against spells and other magical effects."
  - name: Reactive.
    desc: "The marilith gets up to five extra reactions, but these extra reactions can be used only for Parry."
hp: 217
type: Fiend
name: Marilith
reactions:
  - name: Parry.
    desc: "The marilith adds 5 to its AC against one melee attack that would hit it. To do so, the marilith must see the attacker and be wielding a melee weapon."
cr: 16
perception: 18
immune: Demonic Resilience.
senses: truesight 120 ft.
languages: Abyssal, telepathy 120 ft.
```

#cr16 #demon #fiend #large #outsider
