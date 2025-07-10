
```statblock
layout: Basic ToV Layout
resistant: cold, fire | Plant Resilience
bonus_actions:
  - name: Engulf.
    desc: "The shambling mound engulfs a Medium or smaller creature grappled by it. In addition to being grappled, the engulfed target is [[../../Conditions/Blinded|blinded]], [[../../Conditions/Restrained|restrained]], and unable to breathe, and it must succeed on a DC 14 CON save at the start of each of the mound’s turns or take 4 (1d8) bludgeoning damage and 3 (1d6) poison damage. If the mound moves, the engulfed target moves with it. The mound can have only one creature engulfed at a time."
traits:
  - name: Lightning Absorption.
    desc: "Whenever the shambling mound is subjected to lightning damage, it takes no damage and regains HP equal to the lightning damage dealt."
  - name: Plant Resilience.
    desc: "The shambling mound is resistant to exhaustion and to the paralyzed, petrified, and unconscious conditions."
  - name: Rotting Vegetation.
    desc: "The shambling mound emits the smell of rotting vegetation. A creature that starts its turn within 10 feet of the shambling mound must succeed on a DC 14 CON save or be [[../../Conditions/Poisoned|poisoned]] until the start of its next turn."
stealth: 12
hp: 110
type: Plant
name: Shambling Mound
actions:
  - name: Multiattack.
    desc: "The shambling mound makes two Slam attacks. If both attacks hit a Medium or smaller target, the target is [[../../Conditions/Grappled|grappled]] (escape DC 14)."
  - name: Slam.
    desc: "*Melee Weapon Attack:* +7 to hit, reach 5 ft., one target.  *Hit:* 13 (2d8 + 4) bludgeoning damage plus 7 (2d6) poison damage."
stats: ['+4', '−1', '+3', '−3', '+0', '−3']
speed: 20 ft., swim 20 ft.
ac: 15 (natural armor)
size: Large
perception: 10
immune: lightning | blinded, deafened
languages: —
senses: keensense 60 ft. (can’t sense beyond this radius)
cr: 5
```

#cr5 #large #plant
