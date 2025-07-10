
```statblock
layout: Basic ToV Layout
hp: 185
type: Plant
bonus_actions:
  - name: Halt Intruders.
    desc: "The treant calls to the roots beneath up to two creatures it can see within 30 feet of it. Each target must succeed on a DC 17 STR save or be [[../../Conditions/Restrained|restrained]] by roots until the end of its next turn. The treant can target only creatures in contact with the ground and can’t target creatures in contact with a manufactured floor, such as the wooden floor of a building."
traits:
  - name: False Appearance.
    desc: "While the treant remains motionless, it is indistinguishable from a normal tree."
  - name: Plant Resilience.
    desc: "The treant is resistant to exhaustion and to the paralyzed, petrified, and unconscious conditions."
  - name: Siege Monster.
    desc: "The treant deals double damage to objects and structures."
  - name: Speak with Plants.
    desc: "The treant can communicate with Plants and nonmagical plants as if they shared a language."
resistant: bludgeoning, piercing | Plant Resilience
stealth: 9
vulnerable: fire
name: Treant
stats: ['+6', '−1', '+9', '+1', '+7', '+1']
actions:
  - name: Multiattack.
    desc: "The treant makes three Slam attacks, or it makes two Throw Rock attacks. If two Slam attacks hit one creature, the target must succeed on a DC 17 STR save or be knocked [[../../Conditions/Prone|prone]]."
  - name: Slam.
    desc: "*Melee Weapon Attack:* +10 to hit, reach 5 ft., one target.  *Hit:* 22 (4d6 + 6) bludgeoning damage."
  - name: Throw Rock.
    desc: "*Ranged Weapon Attack:* +10 to hit, range 60/180 ft., one target.  *Hit:* 33 (5d10 + 6) bludgeoning damage."
  - name: Animate Trees (1/Day).
    desc: "The treant magically animates 2 trees or 2d6 shrubs it can see within 60 feet of it. The trees use the statistics of an **[[Awakened Tree|awakened tree]]**, and the shrubs use the statistics of an **[[Awakened Shrub|awakened shrub]]**. The animated plants act as allies of the treant, obeying its spoken commands. The plants remain for 1 hour, until the treant dies, or until the treant dismisses them as a bonus action."
size: Huge
ac: 16 (natural armor)
speed: 30 ft.
perception: 17
languages: Common, Druidic, Elvish, Sylvan
senses: tremorsense 30 ft.
cr: 9
```

#cr9 #huge #plant
