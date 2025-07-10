
```statblock
layout: Basic ToV Layout
stats: ['+8', '+8', '+13', '+6', '+10', '+7']
actions:
  - name: Multiattack.
    desc: "The pit fiend makes one Bite attack, one Gore attack, one Mace attack, and one Tail attack, or it makes four Hurl Flame attacks. If two Hurl Flame attacks hit one creature, each creature within 10 feet of the target must make a DC 21 DEX save as the fire bursts outward from the target, taking 14 (4d6) fire damage on a failed save, or half as much damage on a successful one."
  - name: Bite.
    desc: "*Melee Weapon Attack:* +14 to hit, reach 5 ft., one target.  *Hit:* 22 (4d6 + 8) piercing damage plus 14 (4d6) fire damage and 13 (3d8) poison damage. The target must succeed on a DC 21 CON save or be [[../../Conditions/Poisoned|poisoned]]. While poisoned in this way, the target can’t regain HP. The target can repeat the save at the end of each of its turns, ending the effect on itself on a success."
  - name: Gore.
    desc: "*Melee Weapon Attack:* +14 to hit, reach 10 ft., one target.  *Hit:* 17 (2d8 + 8) piercing damage plus 14 (4d6) fire damage."
  - name: Mace.
    desc: "*Melee Weapon Attack:* +14 to hit, reach 10 ft., one target.  *Hit:* 15 (2d6 + 8) bludgeoning damage plus 14 (4d6) fire damage."
  - name: Tail.
    desc: "*Melee Weapon Attack:* +14 to hit, reach 10 ft., one target.  *Hit:* 24 (3d10 + 8) bludgeoning damage plus 14 (4d6) fire damage, and the target must succeed on a DC 21 STR save or be knocked [[../../Conditions/Prone|prone]]."
  - name: Hurl Flame.
    desc: "*Ranged Spell Attack:* +10 to hit, range 120 ft., one target.  *Hit:* 25 (6d6 + 4) fire damage."
subtype: Outsider, Devil
ac: 19 (natural armor)
size: Large
speed: 30 ft., fly 60 ft.
hp: 323
type: Fiend
stealth: 18
resistant: Devilish Resilience
traits:
  - name: Aura of the Devil Lord.
    desc: "Each hostile creature that starts its turn within 20 feet of the pit fiend must succeed on a DC 21 WIS save or be frightened until the start of its next turn. Each friendly devil within 20 feet of the pit fiend is immune to the charmed and frightened conditions and has advantage on the first attack roll it makes on each of its turns."
  - name: Devilish Resilience.
    desc: "The devil is resistant to cold damage and to bludgeoning, piercing, and slashing damage from nonmagical attacks. In addition, it is immune to fire damage and poison damage and to the poisoned condition."
  - name: Flaming Weapons.
    desc: "The pit fiend’s weapon attacks are magical. When the fiend hits with any weapon, the weapon deals an extra 4d6 fire damage (included in the attack)."
  - name: Magic Resistance.
    desc: "The pit fiend has advantage on saves against spells and other magical effects."
name: Pit Fiend
cr: 20
perception: 20
senses: truesight 120 ft.
languages: Infernal, telepathy 120 ft.
immune: charmed, frightened | Devilish Resilience
```

#cr20 #devil #fiend #large #outsider
