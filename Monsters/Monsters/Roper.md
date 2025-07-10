
```statblock
layout: Basic ToV Layout
perception: 16
languages: —
senses: darkvision 60 ft.
reactions:
  - name: Snapping Tendril.
    desc: "When a Grasping Tendril that is grappling a creature is destroyed, the roper can quickly pull the remains of that tendril back to it with a whipping snap. Each creature within 10 feet of the roper must succeed on a DC 15 DEX save or be knocked [[../../Conditions/Prone|prone]]."
cr: 5
traits:
  - name: Climbing Tendrils.
    desc: "If at least four of the roper’s Grasping Tendrils aren’t grappling creatures, the roper has a climbing speed of 30 feet."
  - name: False Appearance.
    desc: "While the roper remains motionless, it is indistinguishable from a normal conical or spire-like cave formation, such as a stalagmite or stalactite."
  - name: Grasping Tendrils.
    desc: "The roper can have up to six Grasping Tendrils at a time. Each Grasping Tendril can be attacked (AC 20; 10 HP; vulnerable to thunder damage; immune to poison and psychic damage). Destroying a Grasping Tendril deals no damage to the roper, which can extrude a replacement tendril on its next turn. A Grasping Tendril can also be broken if a creature takes an action and succeeds on a DC 15 STR check against it."
  - name: Monstrosity Resilience.
    desc: "The roper is resistant to exhaustion and to the frightened condition."
  - name: Spider Climb.
    desc: "The roper can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check."
bonus_actions:
  - name: Reel.
    desc: "The roper pulls each creature grappled by it up to 25 feet straight toward it."
resistant: Monstrosity Resilience
stealth: 15
type: Monstrosity
hp: 111
name: Roper
vulnerable: thunder
actions:
  - name: Multiattack.
    desc: "The roper makes one Bite attack and three Grasping Tendril attacks."
  - name: Bite.
    desc: "*Melee Weapon Attack:* +7 to hit, reach 5 ft., one target.  *Hit:* 22 (4d8 + 4) piercing damage."
  - name: Grasping Tendril.
    desc: "*Melee Weapon Attack:* +7 to hit, reach 50 ft., one creature.  *Hit:* 6 (1d4 + 4) bludgeoning damage, and the target is [[../../Conditions/Grappled|grappled]] (escape DC 15). Until the grapple ends, the target is [[../../Conditions/Restrained|restrained]] and has disadvantage on STR checks and STR saves, and the roper can’t use the same Grasping Tendril on another target. A creature immune to the poisoned condition doesn’t have disadvantage on STR checks and STR saves from the tendril."
stats: ['+7', '−1', '+3', '−2', '+3', '−2']
speed: 15 ft., climb 10 ft.
size: Large
ac: 20 (natural armor)
```

#cr5 #large #monstrosity
