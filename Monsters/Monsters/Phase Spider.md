
```statblock
layout: Basic ToV Layout
perception: 10
senses: darkvision 60 ft.
languages: Phase Spider
immune: poison | poisoned
cr: 3
type: Monstrosity
hp: 73
stealth: 15
bonus_actions:
  - name: Ethereal Jaunt.
    desc: "The phase spider magically shifts from the Material Plane to the Ethereal Plane, or vice versa."
traits:
  - name: Ethereal Sight.
    desc: "The phase spider can see 60 feet into the Ethereal Plane when it is on the Material Plane, and vice versa."
  - name: Monstrosity Resilience.
    desc: "The phase spider is resistant to exhaustion and to the frightened condition."
  - name: Spider Climb.
    desc: "The spider can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check."
  - name: Web Walker.
    desc: "The spider ignores movement restrictions caused by webbing."
resistant: Monstrosity Resilience
name: Phase Spider
stats: ['+2', '+3', '+1', '−2', '+0', '−2']
actions:
  - name: Multiattack.
    desc: "The phase spider makes one Barbed Legs attack and one Bite attack. It can replace one attack with a Phasing Web attack."
  - name: Barbed Legs.
    desc: "*Melee Weapon Attack:* +5 to hit, reach 10 ft., one target.  *Hit:* 8 (2d4 + 3) piercing damage."
  - name: Bite.
    desc: "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one creature.  *Hit:* 7 (1d10 + 3) piercing damage, and the target must make a DC 13 CON save, taking 13 (3d8) poison damage on a failed save, or half as much damage on a successful one. If the poison damage reduces the target to 0 HP, the target is stable but [[../../Conditions/Poisoned|poisoned]] for 1 hour, even after regaining HP, and is [[../../Conditions/Paralyzed|paralyzed]] while poisoned in this way."
  - name: Phasing Web.
    desc: "*Ranged Weapon Attack:* +5 to hit, range 30/60 ft., one creature.  *Hit:* The target is [[../../Conditions/Restrained|restrained]] by webbing. While restrained in this way, the target can see and attack creatures on the Ethereal Plane, and the restrained target can be seen and attacked by creatures on the Ethereal Plane. A creature, including the restrained target, can take its action to free the target from the webbing by succeeding on a DC 13 STR check. The webbing can also be attacked and destroyed (AC 12; HP 10; vulnerability to fire damage; immunity to bludgeoning, poison, and psychic damage)."
size: Large
ac: 13 (natural armor)
speed: 30 ft., climb 30 ft.
```

#cr3 #large #monstrosity
