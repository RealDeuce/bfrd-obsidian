
```statblock
layout: Basic ToV Layout
actions:
  - name: Pseudopod.
    desc: "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one creature.  *Hit:* 10 (3d6) acid damage."
  - name: Engulf.
    desc: "The cube moves up to its speed. While doing so, it can enter a Large or smaller creature’s space. When the cube enters a creature’s space, the creature must make a DC 13 DEX save. On a success, the creature can choose to be pushed 5 feet back or to the side of the cube. A creature that chooses not to be pushed suffers the consequences of a failed save. On a failed save, the cube enters the creature’s space, the creature takes 10 (3d6) acid damage, and is engulfed. The engulfed creature can’t breathe, is [[../../Conditions/Restrained|restrained]], and takes 21 (6d6) acid damage at the start of each of the cube’s turns. When the cube moves, the engulfed creature moves with it.\n\nAn engulfed creature can try to escape by taking an action to make a DC 13 STR check. On a success, the creature escapes and enters a space of its choice within 5 feet of the cube."
stats: ['+3', '−3', '+5', '−5', '−2', '−5']
speed: 15 ft.
size: Large
ac: 6
resistant: Ooze Resilience
traits:
  - name: Ooze Cube.
    desc: "The cube takes up its entire space. Other creatures can enter the space, but are subjected to the cube’s Engulf and have disadvantage on the save. Creatures inside the cube can be seen but have total cover.\n\nA creature within 5 feet of the cube can take an action to pull a creature or object out of the cube. Doing so requires a successful DC 12 STR check, and the creature making the attempt takes 10 (3d6) acid damage.\n\nThe cube can hold only one Large creature or up to four Medium or smaller creatures inside it at a time."
  - name: Ooze Nature.
    desc: "The cube doesn’t require sleep."
  - name: Ooze Resilience.
    desc: "The cube is resistant to the grappled and restrained conditions, and it is immune to exhaustion and to the blinded, charmed, deafened, frightened, and prone conditions."
  - name: Transparent.
    desc: "While motionless, the cube’s Stealth is 15, even when the cube is in plain sight."
stealth: 7
hp: 75
type: Ooze
name: Gelatinous Cube
vulnerable: cold
reactions:
  - name: Skewer Prey.
    desc: "When the gelatinous cube is subjected to piercing damage, it can move a random creature engulfed by it to intercept the attack. The creature takes the piercing damage as if it were the target."
cr: 2
perception: 8
immune: acid, piercing | Ooze Resilience
languages: —
senses: keensense 60 ft. (can’t sense beyond this radius)
```

#cr2 #large #ooze
