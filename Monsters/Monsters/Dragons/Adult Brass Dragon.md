
```statblock
layout: Basic ToV Layout
name: Adult Brass Dragon
stealth: 15
bonus_actions:
  - name: Change Shape.
    desc: "The dragon magically transforms into a Beast or Humanoid that has a challenge rating no higher than its own, or back into its true form, which is Dragon. Any equipment it is wearing or carrying transforms with it or is borne by the new form (the dragon’s choice). It reverts to its true form if it dies. In a new form, the dragon retains its Legendary Resistance trait and its HP, ability to speak, proficiencies, and INT, WIS, and CHA scores, as well as this bonus action. Its statistics and capabilities are otherwise replaced by those of the new form, except any class features or legendary actions of that form."
legendary_actions:
  - name: Detect.
    desc: "The dragon automatically detects every creature and trap within 30 feet of it, pinpointing the current location of each."
  - name: Tail Attack.
    desc: "The dragon makes a Tail attack."
  - name: Elemental Roar (Costs 2 Actions).
    desc: "The dragon roars at up to two creatures of its choice within 120 feet of it. Each target must succeed on a DC 16 CHA save or be vulnerable to fire damage until the end of its next turn. A target resistant to fire damage isn’t resistant to it for the duration. A target immune to fire damage is still immune to it, even if the target fails the save."
  - name: Wing Attack (Costs 2 Actions).
    desc: "The dragon beats its wings. Each creature within 10 feet of the dragon must succeed on a DC 19 DEX save or take 13 (2d6 + 6) bludgeoning damage and be knocked [[../../Conditions/Prone|prone]]. The dragon can then fly up to half its flying speed without provoking opportunity attacks."
traits:
  - name: Legendary Resistance (3/Day).
    desc: "If the dragon fails a save, it can choose to succeed instead."
  - name: Suffocating Heat.
    desc: "After the brass dragon uses its Fire Breath, the air around it is devoid of moisture and lacking in breathable air. While the dragon’s Fire Breath is unavailable, each creature that requires air to breathe, other than the dragon, and that starts its turn within 20 feet of the dragon must succeed on a DC 18 CON save or begin suffocating. A creature that fails this save for two consecutive rounds falls [[../../Conditions/Unconscious|unconscious]] until it takes damage or another creature uses an action to wake it."
type: Dragon
hp: 225
speed: 40 ft., burrow 30 ft., fly 80 ft.
ac: 18 (natural armor)
size: Huge
actions:
  - name: Multiattack.
    desc: "The dragon uses its Frightful Presence. It then makes one Bite attack and two Claw attacks. It can replace its Bite attack with a use of Sleep Breath, if available."
  - name: Bite.
    desc: "*Melee Weapon Attack:* +11 to hit, reach 10 ft., one target.  *Hit:* 17 (2d10 + 6) piercing damage."
  - name: Claw.
    desc: "*Melee Weapon Attack:* +11 to hit, reach 5 ft., one target.  *Hit:* 13 (2d6 + 6) slashing damage."
  - name: Tail.
    desc: "*Melee Weapon Attack:* +11 to hit, reach 15 ft., one target.  *Hit:* 15 (2d8 + 6) bludgeoning damage."
  - name: Frightful Presence.
    desc: "Each creature of the dragon’s choice that is within 120 feet of the dragon and aware of it must succeed on a DC 16 WIS save or be frightened for 1 minute. A creature can repeat the save at the end of each of its turns, ending the effect on itself on a success. If a creature’s save is successful or the effect ends for it, the creature is immune to the dragon’s Frightful Presence for the next 24 hours."
  - name: Fire Breath (Recharge 5–6).
    desc: "The dragon exhales fire in a 90-foot line that is 5 feet wide. Each creature in that line must make a DC 18 DEX save, taking 45 (13d6) fire damage on a failed save, or half as much damage on a successful one."
  - name: Sleep Breath (Recharge 6).
    desc: "The dragon exhales sleep gas in a 60-foot cone. Each creature in that area must succeed on a DC 18 CON save or fall [[../../Conditions/Unconscious|unconscious]] for 5 minutes. This effect ends for a creature if the creature takes damage or another creature uses an action to wake it."
stats: ['+6', '+5', '+10', '+2', '+6', '+8']
immune: fire
senses: darkvision 120 ft., keensense 60 ft.
languages: Common, Draconic
legendary_description: The dragon can take 3 legendary actions, choosing from the options below. Only one legendary action can be used at a time and only at the end of another creature’s turn. The dragon regains spent legendary actions at the start of its turn.
perception: 21
cr: 13
```

#cr13 #dragon #huge
