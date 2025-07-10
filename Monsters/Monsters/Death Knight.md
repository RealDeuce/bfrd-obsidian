
```statblock
layout: Basic ToV Layout
vulnerable: radiant
name: Death Knight
type: Undead
hp: 140
bonus_actions:
  - name: Champion’s Challenge.
    desc: "The death knight challenges one creature it can see within 30 feet of it. The target must succeed on a DC 15 CHA save or have disadvantage on attack rolls against creatures that aren’t the knight until the end of its next turn."
traits:
  - name: Disgraced Rejuvenation.
    desc: "Unless redeemed, a destroyed death knight returns in 1d4 days, regaining all its HP and becoming active again within 10 feet of where it died."
  - name: Magic Resistance.
    desc: "The death knight has advantage on saves against spells and other magical effects."
  - name: Undead Nature.
    desc: "The death knight doesn’t require air, food, drink, or sleep."
  - name: Undead Resilience.
    desc: "The death knight is immune to poison damage, to exhaustion, and to the poisoned condition."
stealth: 5 (10 without armor)
size: Medium
ac: 18 (plate)
speed: 30 ft.
stats: ['+4', '+0', '+3', '+1', '+5', '+4']
actions:
  - name: Multiattack.
    desc: "The death knight makes three Greatsword or Necrotic Bolt attacks."
  - name: Greatsword.
    desc: "*Melee Weapon Attack:* +7 to hit, reach 5 ft., one target.  *Hit:* 11 (2d6 + 4) slashing damage and 7 (2d6) necrotic damage."
  - name: Necrotic Bolt.
    desc: "*Ranged Spell Attack:* +7 to hit, range 60 ft., one target.  *Hit:* 18 (4d6 + 4) necrotic damage."
languages: Common
senses: darkvision 90 ft.
immune: necrotic | frightened | Undead Resilience
perception: 15
cr: 8
reactions:
  - name: Parry.
    desc: "The death knight adds 3 to its AC against one melee attack that would hit it. To do so, the death knight must see the attacker and be wielding a melee weapon."
  - name: Soul Drain.
    desc: "When the death knight reduces a Humanoid to 0 HP, it can absorb the creature’s soul. The target must succeed on a DC 15 WIS save or immediately die, its soul becoming trapped in the death knight’s sword. The death knight has advantage on attack rolls for 1 minute after absorbing a soul.\n\nThe creature can’t be restored to life until the death knight is permanently destroyed."
```

#cr8 #medium #undead
