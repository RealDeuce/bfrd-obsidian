
```statblock
layout: Basic ToV Layout
cr: 21
senses: darkvision 120 ft., keensense 60 ft.
languages: Common, Draconic
immune: fire
perception: 26
legendary_description: The dragon can take 3 legendary actions, choosing from the options below. Only one legendary action can be used at a time and only at the end of another creature’s turn. The dragon regains spent legendary actions at the start of its turn.
ac: 22 (natural armor)
size: Gargantuan
speed: 40 ft., climb 40 ft., fly 80 ft.
stats: ['+10', '+7', '+16', '+4', '+9', '+13']
actions:
  - name: Multiattack.
    desc: "The dragon uses its Frightful Presence. It then makes one Bite attack and two Claw attacks."
  - name: Bite.
    desc: "*Melee Weapon Attack:* +17 to hit, reach 15 ft., one target.  *Hit:* 21 (2d10 + 10) piercing damage plus 14 (4d6) fire damage."
  - name: Claw.
    desc: "*Melee Weapon Attack:* +17 to hit, reach 10 ft., one target.  *Hit:* 17 (2d6 + 10) slashing damage."
  - name: Tail.
    desc: "*Melee Weapon Attack:* +17 to hit, reach 20 ft., one target.  *Hit:* 19 (2d8 + 10) bludgeoning damage."
  - name: Frightful Presence.
    desc: "Each creature of the dragon’s choice that is within 120 feet of the dragon and aware of it must succeed on a DC 21 WIS save or be frightened for 1 minute. A creature can repeat the save at the end of each of its turns, ending the effect on itself on a success. If a creature’s save is successful or the effect ends for it, the creature is immune to the dragon’s Frightful Presence for the next 24 hours."
  - name: Fire Breath (Recharge 5–6).
    desc: "The dragon exhales fire in a 90‑foot cone. Each creature in that area must make a DC 24 DEX save, taking 105 (30d6) fire damage on a failed save, or half as much damage on a successful one."
name: Ancient Red Dragon
type: Dragon
hp: 382
stealth: 17
traits:
  - name: Boil Over.
    desc: "When the red dragon hasn’t unleashed its Fire Breath, the heat builds and rolls outward from it. While the dragon’s Fire Breath is available, it emits immense heat, and each creature that starts its turn within 30 feet of the dragon must succeed on a DC 24 CON save or take 7 (2d6) fire damage. A creature that fails this save by 5 or more also suffers one level of [[../../Conditions/Exhaustion|exhaustion]]."
  - name: Legendary Resistance (3/Day).
    desc: "If the dragon fails a save, it can choose to succeed instead."
legendary_actions:
  - name: Detect.
    desc: "The dragon automatically detects every creature and trap within 30 feet of it, pinpointing the current location of each."
  - name: Tail Attack.
    desc: "The dragon makes a Tail attack."
  - name: Elemental Roar (Costs 2 Actions).
    desc: "The dragon roars at up to two creatures of its choice within 120 feet of it. Each target must succeed on a DC 21 CHA save or be vulnerable to fire damage until the end of its next turn. A target resistant to fire damage isn’t resistant to it for the duration. A target immune to fire damage is still immune to it, even if the target fails the save."
  - name: Wing Attack (Costs 2 Actions).
    desc: "The dragon beats its wings. Each creature within 15 feet of the dragon must succeed on a DC 25 DEX save or take 17 (2d6 + 10) bludgeoning damage and be knocked [[../../Conditions/Prone|prone]]. The dragon can then fly up to half its flying speed without provoking opportunity attacks."
lair_description: "On initiative count 20 (losing initiative ties), the dragon can take a lair action to cause one of the following effects; the dragon can’t use the same effect two rounds in a row:"
lair_actions:
  - name: Collapse.
    desc: "The ceiling on a point the dragon can see within 120 feet of it collapses, covering a 20-foot square area on the ground directly below that point. Each creature in that area must succeed on a DC 15 DEX save or be knocked [[../../Conditions/Prone|prone]] and buried under the rubble. A buried creature is [[../../../Conditions/Restrained|restrained]] and unable to breathe or stand up. A creature, including the buried creature, can take its action to free the buried creature by succeeding on a DC 15 STR check while within reach of the buried creature."
  - name: Swirling Ash.
    desc: "Searing ash blasts a point the dragon can see within 120 feet of it. Each creature within 30 feet of that point must make a DC 15 CON save. On a failure, a creature takes 10 (3d6) fire damage and is [[../../Conditions/Blinded|blinded]] until the end of its next turn. On a success, a creature takes half the damage and isn’t blinded. The ash ignites flammable objects within 30 feet of that point that aren’t being worn or carried."
  - name: Conflagrate.
    desc: One creature the dragon can see within 120 feet of it becomes tethered to the Elemental Plane of Fire. The target must succeed on a DC 15 CHA save or be burned for 1 minute. While burned, the target takes 7 (2d6) fire damage at the start of each of its turns. The effect ends early if the target takes cold damage, is submerged in water, or the burn is removed with a greater restoration spell or similar magic.
regional_description: "The region containing a red dragon’s lair is suffused with fiery chaos, which creates one or more of the following effects:"
regional_effects:
  - name: Acid Rain.
    desc: Within 10 miles of the red dragon’s lair, precipitation is oily and stinks of sulfur. Snow in the area may be gray or black as it falls, appearing like ash, though its temperature is unchanged.
  - name: Incited Rage.
    desc: Creatures within 3 miles of the red dragon’s lair are quick to anger and slow to forgive. Such creatures have disadvantage on CHA checks, except CHA (Intimidation), and Beasts in the area that aren’t domesticated are more aggressive than normal.
  - name: Unnatural Heat.
    desc: Within 1 mile of the red dragon’s lair, temperatures are unnaturally high. Vegetation in the area withers and eventually crumbles to dust. Creatures in the area require twice as much water as normal each day to survive, and each creature in the area must succeed on a DC 10 CON save every hour it remains in the area or suffer one level of [[../../Conditions/Exhaustion|exhaustion]]. Creatures that are resistant or immune to fire damage are unaffected by this regional effect.
regional_end: If the dragon dies, these effects fade in 1d10 days.
```

#cr21 #dragon #gargantuan
