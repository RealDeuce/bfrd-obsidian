
```statblock
layout: Basic ToV Layout
name: Ochre Jelly
type: Ooze
hp: 71
traits:
  - name: Amorphous.
    desc: "The ochre jelly can move through a space as narrow as 1 inch wide without squeezing."
  - name: Ooze Nature.
    desc: "The ochre jelly doesn’t require sleep."
  - name: Ooze Resilience.
    desc: "The ochre jelly is resistant to the restrained condition, and it is immune to exhaustion and to the blinded, charmed, deafened, frightened, and prone conditions."
  - name: Overwhelming Stench.
    desc: "A creature that starts its turn within 10 feet of the ochre jelly must succeed on a DC 13 CON save or be [[../../Conditions/Poisoned|poisoned]] until the start of its next turn. If a creature fails the save by 5 or more, it must spend its turn retching uncontrollably and be unable to move or act."
  - name: Spider Climb.
    desc: "The ochre jelly can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check."
resistant: acid | Ooze Resilience
stealth: 8
ac: 8
size: Large
speed: 15 ft., climb 15 ft.
stats: ['+3', '−2', '+2', '−4', '−2', '−5']
actions:
  - name: Pseudopod.
    desc: "*Melee Weapon Attack:* +5 to hit, reach 10 ft., one target.  *Hit:* 10 (2d6 + 3) bludgeoning damage plus 7 (2d6) acid damage. If the target is poisoned, it must succeed on a DC 13 CON save or also take 5 (2d4) poison damage."
languages: —
senses: keensense 60 ft. (can’t sense beyond this radius)
immune: lightning, slashing | grappled, poisoned | Ooze Resilience
perception: 8
cr: 2
reactions:
  - name: Split.
    desc: "When an ochre jelly that is Medium or larger is subjected to lightning or slashing damage, it splits into two new ochre jellies if it has at least 10 HP. Each new jelly has HP equal to half the original jelly’s, rounded down. New jellies are one size smaller than the original jelly."
```

#cr2 #large #ooze
