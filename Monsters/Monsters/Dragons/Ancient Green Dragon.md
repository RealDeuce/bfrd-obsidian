
```statblock
layout: Basic ToV Layout
legendary_description: The dragon can take 3 legendary actions, choosing from the options below. Only one legendary action can be used at a time and only at the end of another creature’s turn. The dragon regains spent legendary actions at the start of its turn.
perception: 25
immune: poison | poisoned
languages: Common, Draconic
senses: darkvision 120 ft., keensense 60 ft.
cr: 19
traits:
  - name: Amphibious.
    desc: "The dragon can breathe air and water."
  - name: Hallucinogenic Gas.
    desc: "After the green dragon exhales its Poison Breath, wisps of poisonous gas laced with the alchemical taint that permeates the dragon’s body linger around it. While the dragon’s Poison Breath is unavailable, each creature that starts its turn within 30 feet of the dragon must succeed on a DC 21 WIS save or be terrified until the start of its next turn, as the gas causes the creature to experience frightful hallucinations. A terrified creature is [[../../Conditions/Frightened|frightened]], and its speed is reduced to 0."
  - name: Legendary Resistance (3/Day).
    desc: "If the dragon fails a save, it can choose to succeed instead."
legendary_actions:
  - name: Detect.
    desc: "The dragon automatically detects every creature and trap within 30 feet of it, pinpointing the current location of each."
  - name: Tail Attack.
    desc: "The dragon makes a Tail attack."
  - name: Elemental Roar (Costs 2 Actions).
    desc: "The dragon roars at up to two creatures of its choice within 120 feet of it. Each target must succeed on a DC 18 CHA save or be vulnerable to poison damage until the end of its next turn. A target resistant to poison damage isn’t resistant to it for the duration. A target immune to poison damage is still immune to it, even if the target fails the save."
  - name: Wing Attack (Costs 2 Actions).
    desc: "The dragon beats its wings. Each creature within 15 feet of the dragon must succeed on a DC 22 DEX save or take 22 (4d6 + 8) bludgeoning damage and be knocked [[../../Conditions/Prone|prone]]. The dragon can then fly up to half its flying speed without provoking opportunity attacks."
stealth: 17
type: Dragon
hp: 333
name: Ancient Green Dragon
actions:
  - name: Multiattack.
    desc: "The dragon uses its Frightful Presence. It then makes one Bite attack and two Claw attacks."
  - name: Bite.
    desc: "*Melee Weapon Attack:* +15 to hit, reach 15 ft., one target.  *Hit:* 19 (2d10 + 8) piercing damage plus 10 (3d6) poison damage."
  - name: Claw.
    desc: "*Melee Weapon Attack:* +15 to hit, reach 10 ft., one target.  *Hit:* 22 (4d6 + 8) slashing damage."
  - name: Tail.
    desc: "*Melee Weapon Attack:* +15 to hit, reach 20 ft., one target.  *Hit:* 17 (2d8 + 8) bludgeoning damage."
  - name: Frightful Presence.
    desc: "Each creature of the dragon’s choice that is within 120 feet of the dragon and aware of it must succeed on a DC 18 WIS save or be [[../../Conditions/Frightened|frightened]] for 1 minute. A creature can repeat the save at the end of each of its turns, ending the effect on itself on a success. If a creature’s save is successful or the effect ends for it, the creature is immune to the dragon’s Frightful Presence for the next 24 hours."
  - name: Poison Breath (Recharge 5–6).
    desc: "The dragon exhales poisonous gas in a 90-foot cone. Each creature in that area must make a DC 21 CON save, taking 84 (24d6) poison damage on a failed save, or half as much damage on a successful one."
stats: ['+8', '+7', '+13', '+7', '+9', '+10']
speed: 40 ft., fly 80 ft., swim 40 ft.
size: Gargantuan
ac: 21 (natural armor)
```

#cr19 #dragon #gargantuan
