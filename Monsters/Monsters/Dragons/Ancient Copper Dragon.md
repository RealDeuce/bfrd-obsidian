
```statblock
layout: Basic ToV Layout
hp: 297
type: Dragon
legendary_actions:
  - name: Detect.
    desc: "The dragon automatically detects every creature and trap within 30 feet of it, pinpointing the current location of each."
  - name: Tail Attack.
    desc: "The dragon makes a Tail attack."
  - name: Elemental Roar (Costs 2 Actions).
    desc: "The dragon roars at up to two creatures of its choice within 120 feet of it. Each target must succeed on a DC 18 CHA save or be vulnerable to acid damage until the end of its next turn. A target resistant to acid damage isn’t resistant to it for the duration. A target immune to acid damage is still immune to it, even if the target fails the save."
  - name: Wing Attack (Costs 2 Actions).
    desc: "The dragon beats its wings. Each creature within 15 feet of the dragon must succeed on a DC 22 DEX save or take 15 (2d6 + 8) bludgeoning damage and be knocked [[../../Conditions/Prone|prone]]. The dragon can then fly up to half its flying speed without provoking opportunity attacks."
bonus_actions:
  - name: Change Shape.
    desc: "The dragon magically transforms into a Beast or Humanoid that has a challenge rating no higher than its own, or back into its true form, which is Dragon. Any equipment it is wearing or carrying transforms with it or is borne by the new form (the dragon’s choice). It reverts to its true form if it dies. In a new form, the dragon retains its Legendary Resistance trait and its HP, ability to speak, proficiencies, and INT, WIS, and CHA scores, as well as this bonus action. Its statistics and capabilities are otherwise replaced by those of the new form, except any class features or legendary actions of that form."
traits:
  - name: Corrosive Scales.
    desc: "When the copper dragon hasn’t spit its Acid Breath, the acid built up within the dragon causes the patina on its scales to spread to weapons that strike it. While the dragon’s Acid Breath is available, any weapon made of metal that hits the dragon corrodes. After dealing damage, the weapon takes a permanent and cumulative −1 penalty to damage rolls. If a nonmagical weapon’s penalty drops to −5, the weapon is destroyed. Nonmagical ammunition made of metal that hits the dragon is destroyed after dealing damage. A magical weapon can’t have a penalty greater than −5, and a magical weapon removes this penalty after 24 hours or after its attuned wielder finishes a long rest."
  - name: Legendary Resistance (3/Day).
    desc: "If the dragon fails a save, it can choose to succeed instead."
stealth: 16
name: Ancient Copper Dragon
stats: ['+8', '+6', '+13', '+5', '+9', '+10']
actions:
  - name: Multiattack.
    desc: "The dragon uses its Frightful Presence. It then makes one Bite attack and two Claw attacks. It can replace its Bite attack with a use of Slowing Breath, if available."
  - name: Bite.
    desc: "*Melee Weapon Attack:* +15 to hit, reach 15 ft., one target.  *Hit:* 19 (2d10 + 8) piercing damage."
  - name: Claw.
    desc: "*Melee Weapon Attack:* +15 to hit, reach 10 ft., one target.  *Hit:* 15 (2d6 + 8) slashing damage."
  - name: Tail.
    desc: "*Melee Weapon Attack:* +15 to hit, reach 20 ft., one target.  *Hit:* 17 (2d8 + 8) bludgeoning damage."
  - name: Frightful Presence.
    desc: "Each creature of the dragon’s choice that is within 120 feet of the dragon and aware of it must succeed on a DC 18 WIS save or be frightened for 1 minute. A creature can repeat the save at the end of each of its turns, ending the effect on itself on a success. If a creature’s save is successful or the effect ends for it, the creature is immune to the dragon’s Frightful Presence for the next 24 hours."
  - name: Acid Breath (Recharge 5–6).
    desc: "The dragon exhales acid in a 120-foot line that is 10 feet wide. Each creature in that line must make a DC 21 DEX save, taking 76 (17d8) acid damage on a failed save, or half as much damage on a successful one."
  - name: Slowing Breath (Recharge 6).
    desc: "The dragon exhales slowing gas in a 90-foot cone. Each creature in that area must make a DC 21 CON save. On a failure, the creature can’t use reactions, its speed is halved, and it can’t make more than one attack on its turn. In addition, the creature can use either an action or a bonus action on its turn, not both. These effects last for 1 minute. The creature can repeat the save at the end of each of its turns, ending the effect on itself on a success."
size: Gargantuan
ac: 21 (natural armor)
speed: 40 ft., climb 40 ft., fly 80 ft.
perception: 27
legendary_description: The dragon can take 3 legendary actions, choosing from the options below. Only one legendary action can be used at a time and only at the end of another creature’s turn. The dragon regains spent legendary actions at the start of its turn.
languages: Common, Draconic
senses: darkvision 120 ft., keensense 60 ft.
immune: acid
cr: 18
```

#cr18 #dragon #gargantuan
