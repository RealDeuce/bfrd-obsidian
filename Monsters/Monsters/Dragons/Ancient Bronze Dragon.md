
```statblock
layout: Basic ToV Layout
cr: 19
languages: Common, Draconic
senses: darkvision 120 ft., keensense 60 ft.
immune: lightning
perception: 27
legendary_description: The dragon can take 3 legendary actions, choosing from the options below. Only one legendary action can be used at a time and only at the end of another creature’s turn. The dragon regains spent legendary actions at the start of its turn.
ac: 21 (natural armor)
size: Gargantuan
speed: 40 ft., fly 80 ft., swim 40 ft.
stats: ['+9', '+6', '+14', '+4', '+9', '+11']
actions:
  - name: Multiattack.
    desc: "The dragon uses its Frightful Presence. It then makes one Bite attack and two Claw attacks. It can replace its Bite attack with a use of Repulsion Breath, if available."
  - name: Bite.
    desc: "*Melee Weapon Attack:* +15 to hit, reach 15 ft., one target.  *Hit:* 20 (2d10 + 9) piercing damage."
  - name: Claw.
    desc: "*Melee Weapon Attack:* +15 to hit, reach 10 ft., one target.  *Hit:* 16 (2d6 + 9) slashing damage."
  - name: Tail.
    desc: "*Melee Weapon Attack:* +15 to hit, reach 20 ft., one target.  *Hit:* 18 (2d8 + 9) bludgeoning damage."
  - name: Frightful Presence.
    desc: "Each creature of the dragon’s choice that is within 120 feet of the dragon and aware of it must succeed on a DC 19 WIS save or be frightened for 1 minute. A creature can repeat the save at the end of each of its turns, ending the effect on itself on a success. If a creature’s save is successful or the effect ends for it, the creature is immune to the dragon’s Frightful Presence for the next 24 hours."
  - name: Lightning Breath (Recharge 5–6).
    desc: "The dragon exhales lightning in a 120-foot line that is 10 feet wide. Each creature in that line must make a DC 22 DEX save, taking 88 (16d10) lightning damage on a failed save, or half as much damage on a successful one."
  - name: Repulsion Breath (Recharge 6).
    desc: "The dragon exhales repulsion energy in a 90-foot cone. Each creature in that area must succeed on a DC 22 STR save or be pushed up to 45 feet away from the dragon."
name: Ancient Bronze Dragon
hp: 314
type: Dragon
bonus_actions:
  - name: Change Shape.
    desc: "The dragon magically transforms into a Beast or Humanoid that has a challenge rating no higher than its own, or back into its true form, which is Dragon. Any equipment it is wearing or carrying transforms with it or is borne by the new form (the dragon’s choice). It reverts to its true form if it dies. In a new form, the dragon retains its Legendary Resistance trait and its HP, ability to speak, proficiencies, and INT, WIS, and CHA scores, as well as this bonus action. Its statistics and capabilities are otherwise replaced by those of the new form, except any class features or legendary actions of that form."
legendary_actions:
  - name: Detect.
    desc: "The dragon automatically detects every creature and trap within 30 feet of it, pinpointing the current location of each."
  - name: Tail Attack.
    desc: "The dragon makes a Tail attack."
  - name: Elemental Roar (Costs 2 Actions).
    desc: "The dragon roars at up to two creatures of its choice within 120 feet of it. Each target must succeed on a DC 19 CHA save or be vulnerable to lightning damage until the end of its next turn. A target resistant to lightning damage isn’t resistant to it for the duration. A target immune to lightning damage is still immune to it, even if the target fails the save."
  - name: Wing Attack (Costs 2 Actions).
    desc: "The dragon beats its wings. Each creature within 15 feet of the dragon must succeed on a DC 23 DEX save or take 16 (2d6 + 9) bludgeoning damage and be knocked [[../../Conditions/Prone|prone]]. The dragon can then fly up to half its flying speed without provoking opportunity attacks."
traits:
  - name: Amphibious.
    desc: "The dragon can breathe air and water."
  - name: Legendary Resistance (3/Day).
    desc: "If the dragon fails a save, it can choose to succeed instead."
  - name: Lightning Extraction.
    desc: "After the bronze dragon uses its Lightning Breath, its body begins recharging with lightning, pulling electricity from nearby creatures. While the dragon’s Lightning Breath is unavailable, each creature that starts its turn within 30 feet of the dragon must make a DC 22 CON save. On a failure, a creature can use either an action or a bonus action on its turn, not both."
stealth: 16
```

#cr19 #dragon #gargantuan
