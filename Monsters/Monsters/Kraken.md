
```statblock
layout: Basic ToV Layout
name: Kraken
legendary_actions:
  - name: Swim.
    desc: "The kraken swims up to half its swimming speed without provoking opportunity attacks."
  - name: Tentacle Attack.
    desc: "The kraken makes one Tentacle attack."
  - name: Lightning Storm (Costs 2 Actions).
    desc: "The kraken magically calls bolts of lightning to strike up to two creatures it can see or sense within 120 feet of it. Each creature must make a DC 22 DEX save, taking 22 (4d10) lightning damage on a failed save, or half as much damage on a successful one."
traits:
  - name: Amphibious.
    desc: "The kraken can breathe air and water."
  - name: Freedom of Movement.
    desc: "The kraken ignores difficult terrain, and magical effects can’t reduce its speed or cause it to be restrained. It can spend 5 feet of movement to escape from nonmagical restraints or being grappled."
  - name: Legendary Resistance (3/Day).
    desc: "If the kraken fails a save, it can choose to succeed instead."
  - name: Monstrosity Resilience.
    desc: "The kraken is resistant to exhaustion and to the frightened condition."
  - name: Siege Monster.
    desc: "The kraken deals double damage to objects and structures."
bonus_actions:
  - name: Fling.
    desc: "One Large or smaller object held or creature grappled by the kraken is thrown up to 60 feet in a random direction and knocked [[../../Conditions/Prone|prone]]. If a thrown target strikes a solid surface, the target takes 3 (1d6) bludgeoning damage for every 10 feet it was thrown. If the target is thrown at another creature, that creature must succeed on a DC 22 DEX save or take the same damage and be knocked [[../../Conditions/Prone|prone]]."
  - name: Reel.
    desc: "The kraken pulls up to two creatures grappled by it up to 25 feet straight toward it."
resistant: Monstrosity Resilience
stealth: 17
hp: 475
type: Monstrosity
speed: 20 ft., swim 60 ft.
size: Gargantuan
ac: 18 (natural armor)
actions:
  - name: Multiattack.
    desc: "The kraken makes three Tentacle attacks. It can replace one Tentacle attack with a Bite attack."
  - name: Bite.
    desc: "*Melee Weapon Attack:* +17 to hit, reach 5 ft., one target.  *Hit:* 28 (4d8 + 10) piercing damage. If the target is a Large or smaller creature grappled by the kraken, that creature is swallowed, and the grapple ends. While swallowed, the creature is [[../../Conditions/Blinded|blinded]] and [[../../Conditions/Restrained|restrained]], it has total cover against attacks and other effects outside the kraken, and it takes 42 (12d6) acid damage at the start of each of the kraken’s turns.\n\nIf the kraken takes 50 damage or more on a single turn from a creature inside it, the kraken must succeed on a DC 24 CON save at the end of that turn or regurgitate all swallowed creatures, which fall [[../../Conditions/Prone|prone]] in a space within 10 feet of the kraken. If the kraken dies, a swallowed creature is no longer restrained by it and can escape from the corpse using 15 feet of movement, exiting [[../../Conditions/Prone|prone]]."
  - name: Tentacle.
    desc: "*Melee Weapon Attack:* +17 to hit, reach 30 ft., one target.  *Hit:* 24 (4d6 + 10) bludgeoning damage, and the target is [[../../Conditions/Grappled|grappled]] (escape DC 22). Until this grapple ends, the target is [[../../Conditions/Restrained|restrained]]. The kraken has ten tentacles, each of which can grapple one target."
  - name: Ink Cloud (Recharge 6).
    desc: "While underwater, the kraken expels an ink cloud in a 30-foot-radius centered on the kraken. The cloud spreads around corners, and the area is heavily obscured. Each creature in the area when it first appears must make a DC 22 CON save, taking 110 (20d10) poison damage on a failed save, or half as much damage on a successful one. A creature that enters the ink cloud for the first time on a turn or starts its turn there must succeed on a DC 22 CON save or take 11 (2d10) poison damage and be [[../../Conditions/Poisoned|poisoned]] until the start of its next turn. The cloud lasts for 1 minute or until dispersed by a strong current."
stats: ['+17', '+7', '+14', '+13', '+11', '+5']
immune: lightning; bludgeoning, piercing, and slashing damage from nonmagical attacks | frightened, paralyzed
languages: understands Abyssal, Celestial, Infernal, and Primordial but can’t speak, telepathy 120 ft.
senses: keensense 60 ft., truesight 120 ft.
legendary_description: The kraken can take 3 legendary actions, choosing from the  options below. Only one legendary action option can be  used at a time and only at the end of another creature’s turn.  The kraken regains spent legendary actions at the start of its  turn.
perception: 21
cr: 23
```

#cr23 #gargantuan #monstrosity
