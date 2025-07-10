
```statblock
layout: Basic ToV Layout
stats: ['+7', '+7', '+10', '+2', '+7', '+8']
actions:
  - name: Multiattack.
    desc: "The dragon uses its Frightful Presence. It then makes one Bite attack and two Claw attacks."
  - name: Bite.
    desc: "*Melee Weapon Attack:* +12 to hit, reach 10 ft., one target.  *Hit:* 18 (2d10 + 7) piercing damage plus 4 (1d8) acid damage."
  - name: Claw.
    desc: "*Melee Weapon Attack:* +12 to hit, reach 5 ft., one target.  *Hit:* 14 (2d6 + 7) slashing damage."
  - name: Tail.
    desc: "*Melee Weapon Attack:* +12 to hit, reach 15 ft., one target.  *Hit:* 16 (2d8 + 7) bludgeoning damage."
  - name: Frightful Presence.
    desc: "Each creature of the dragon’s choice that is within 120 feet of the dragon and aware of it must succeed on a DC 16 WIS save or be frightened for 1 minute. A creature can repeat the save at the end of each of its turns, ending the effect on itself on a success. If a creature’s save is successful or the effect ends for it, the creature is immune to the dragon’s Frightful Presence for the next 24 hours."
  - name: Acid Breath (Recharge 5–6).
    desc: "The dragon exhales acid in a 60-foot line that is 5 feet wide. Each creature in that line must make a DC 18 DEX save, taking 49 (11d8) acid damage on a failed save, or half as much damage on a successful one."
size: Huge
ac: 19 (natural armor)
speed: 40 ft., fly 80 ft., swim 40 ft.
hp: 238
type: Dragon
stealth: 17
legendary_actions:
  - name: Detect.
    desc: "The dragon automatically detects every creature and trap within 30 feet of it, pinpointing the current location of each."
  - name: Tail Attack.
    desc: "The dragon makes a Tail attack."
  - name: Elemental Roar (Costs 2 Actions).
    desc: "The dragon roars at up to two creatures of its choice within 120 feet of it. Each target must succeed on a DC 16 CHA save or be vulnerable to acid damage until the end of its next turn. A target resistant to acid damage isn’t resistant to it for the duration. A target immune to acid damage is still immune to it, even if the target fails the save."
  - name: Wing Attack (Costs 2 Actions).
    desc: "The dragon beats its wings. Each creature within 10 feet of the dragon must succeed on a DC 20 DEX save or take 14 (2d6 + 7) bludgeoning damage and be knocked [[../../Conditions/Prone|prone]]. The dragon can then fly up to half its flying speed without provoking opportunity attacks."
traits:
  - name: Acidic Vapors.
    desc: "After the black dragon uses its Acid Breath, acid clings to its mouth, throat, and nostrils for a time, evaporating as the dragon breathes. While the dragon’s Acid Breath is unavailable, acidic vapors surround it, and each creature that starts its turn within 20 feet of the dragon must succeed on a DC 18 CON save or be [[../../Conditions/Poisoned|poisoned]] until the start of its next turn."
  - name: Amphibious.
    desc: "The dragon can breathe air and water."
  - name: Legendary Resistance (3/Day).
    desc: "If the dragon fails a save, it can choose to succeed instead."
name: Adult Black Dragon
cr: 14
perception: 22
legendary_description: The dragon can take 3 legendary actions, choosing from the options below. Only one legendary action can be used at a time and only at the end of another creature’s turn. The dragon regains spent legendary actions at the start of its turn.
senses: darkvision 120 ft., keensense 60 ft.
languages: Common, Draconic
immune: acid | poisoned
```

#cr14 #dragon #huge
