
```statblock
layout: Basic ToV Layout
stats: ['+6', '+6', '+10', '+6', '+7', '+8']
actions:
  - name: Multiattack.
    desc: "The dragon uses its Frightful Presence. It then makes one Bite attack and two Claw attacks."
  - name: Bite.
    desc: "*Melee Weapon Attack:* +11 to hit, reach 10 ft., one target.  *Hit:* 17 (2d10 + 6) piercing damage plus 7 (2d6) poison damage."
  - name: Claw.
    desc: "*Melee Weapon Attack:* +11 to hit, reach 5 ft., one target.  *Hit:* 13 (2d6 + 6) slashing damage."
  - name: Tail.
    desc: "*Melee Weapon Attack:* +11 to hit, reach 15 ft., one target.  *Hit:* 15 (2d8 + 6) bludgeoning damage."
  - name: Frightful Presence.
    desc: "Each creature of the dragon’s choice that is within 120 feet of the dragon and aware of it must succeed on a DC 16 WIS save or be [[../../Conditions/Frightened|frightened]] for 1 minute. A creature can repeat the save at the end of each of its turns, ending the effect on itself on a success. If a creature’s save is successful or the effect ends for it, the creature is immune to the dragon’s Frightful Presence for the next 24 hours."
  - name: Poison Breath (Recharge 5–6).
    desc: "The dragon exhales poisonous gas in a 60-foot cone. Each creature in that area must make a DC 18 CON save, taking 56 (16d6) poison damage on a failed save, or half as much damage on a successful one."
ac: 19 (natural armor)
size: Huge
speed: 40 ft., fly 80 ft., swim 40 ft.
type: Dragon
hp: 255
stealth: 16
traits:
  - name: Amphibious.
    desc: "The dragon can breathe air and water."
  - name: Hallucinogenic Gas.
    desc: "After the green dragon exhales its Poison Breath, wisps of poisonous gas laced with the alchemical taint that permeates the dragon’s body linger around it. While the dragon’s Poison Breath is unavailable, each creature that starts its turn within 20 feet of the dragon must succeed on a DC 18 WIS save or be terrified until the start of its next turn, as the gas causes the creature to experience frightful hallucinations. A terrified creature is [[../../Conditions/Frightened|frightened]], and its speed is reduced to 0."
  - name: Legendary Resistance (3/Day).
    desc: "If the dragon fails a save, it can choose to succeed instead."
legendary_actions:
  - name: Detect.
    desc: "The dragon automatically detects every creature and trap within 30 feet of it, pinpointing the current location of each."
  - name: Tail Attack.
    desc: "The dragon makes a Tail attack."
  - name: Elemental Roar (Costs 2 Actions).
    desc: "The dragon roars at up to two creatures of its choice within 120 feet of it. Each target must succeed on a DC 16 CHA save or be vulnerable to poison damage until the end of its next turn. A target resistant to poison damage isn’t resistant to it for the duration. A target immune to poison damage is still immune to it, even if the target fails the save."
  - name: Wing Attack (Costs 2 Actions).
    desc: "The dragon beats its wings. Each creature within 10 feet of the dragon must succeed on a DC 19 DEX save or take 13 (2d6 + 6) bludgeoning damage and be knocked [[../../Conditions/Prone|prone]]. The dragon can then fly up to half its flying speed without provoking opportunity attacks."
name: Adult Green Dragon
cr: 15
perception: 22
legendary_description: The dragon can take 3 legendary actions, choosing from the options below. Only one legendary action can be used at a time and only at the end of another creature’s turn. The dragon regains spent legendary actions at the start of its turn.
senses: darkvision 120 ft., keensense 60 ft.
languages: Common, Draconic
immune: poison | poisoned
```

#cr15 #dragon #huge
