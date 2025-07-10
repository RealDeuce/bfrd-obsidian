
```statblock
layout: Basic ToV Layout
reactions:
  - name: Startled Shriek.
    desc: "When bright light or a creature other than a Plant moves to within 30 feet of the shrieker, the shrieker can use Shriek, if it isn’t already shrieking."
cr: 0
perception: 6
senses: keensense 30 ft. (blind beyond this radius)
languages: —
immune: blinded, deafened, frightened
stats: ['−5', '−5', '+0', '−5', '−4', '−5']
actions:
  - name: Thunderous Burst.
    desc: "The shrieker emits a concentrated burst of sound at one creature it can sense within 30 feet of it. The target must make a DC 10 DEX save, taking 2 (1d4) thunder damage on a failed save, or half as much damage on a successful one."
ac: 5
size: Medium
speed: 10 ft.
hp: 7
type: Plant
stealth: 5
bonus_actions:
  - name: Shriek.
    desc: "The shrieker emits a high-pitched shriek audible within 300 feet of it. Each creature within 30 feet of it that isn’t a Plant and that can hear the shriek must succeed on a DC 10 WIS save or be frightened until the shriek ends. The shrieker must use a bonus action on its subsequent turns to continue shrieking. It can stop shrieking at any time. The shriek ends if the shrieker is incapacitated.\n\nA frightened creature can repeat the save at the end of each of its turns, ending the effect on itself on a success. A creature that successfully saves is immune to the frightened effect of this shrieker’s Shriek for the next 24 hours."
traits:
  - name: False Appearance.
    desc: "While the shrieker remains motionless, it is indistinguishable from an ordinary fungus."
  - name: Plant Resilience.
    desc: "The shrieker is resistant to exhaustion and to the paralyzed, petrified, and unconscious conditions."
resistant: thunder | Plant Resilience
name: Shrieker
```

#cr0 #medium #plant
