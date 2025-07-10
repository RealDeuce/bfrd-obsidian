
```statblock
layout: Basic ToV Layout
name: Otyugh
type: Aberration
hp: 108
stealth: 10
traits:
  - name: Aberrant Resilience.
    desc: "The otyugh is resistant to the charmed, frightened, paralyzed, and stunned conditions, and it has advantage on saves against spells or effects that would alter its form."
  - name: Limited Telepathy.
    desc: "The otyugh can magically transmit simple messages and images to any creature within 120 feet of it that can understand a language. This form of telepathy doesn’t allow the receiving creature to telepathically respond."
  - name: Stench.
    desc: "Each creature that starts its turn within 10 feet of the otyugh must succeed on a DC 15 CON save or be [[../../Conditions/Poisoned|poisoned]] until the start of its next turn."
resistant: Aberrant Resilience
size: Large
ac: 14 (natural armor)
speed: 30 ft.
stats: ['+3', '+0', '+7', '−2', '+1', '−2']
actions:
  - name: Multiattack.
    desc: "The otyugh makes one Bite attack and two Tentacle attacks. It can replace both Tentacle attacks with a use of Tentacle Slam."
  - name: Bite.
    desc: "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one target.  *Hit:* 12 (2d8 + 3) piercing damage. If the target is a creature, it must succeed on a DC 15 CON save or become infected with a disease. Until the disease is cured, the target is [[../../Conditions/Poisoned|poisoned]]. Every 24 hours that elapse, the infected creature must repeat the save, reducing its HP maximum by 5 (1d10) on a failure. The disease is cured on a success. The creature dies if the disease reduces its HP maximum to 0. This reduction to the creature’s HP maximum lasts until it finishes a long rest after the disease is cured."
  - name: Tentacle.
    desc: "*Melee Weapon Attack:* +6 to hit, reach 10 ft., one target.  *Hit:* 6 (1d6 + 3) bludgeoning damage plus 9 (2d8) piercing damage. If the target is Medium or smaller, it is [[../../Conditions/Grappled|grappled]] (escape DC 13). The otyugh has two tentacles, each of which can grapple one target."
  - name: Tentacle Slam.
    desc: "The otyugh slams creatures grappled by it into each other or into a solid surface. Each creature must make a DC 15 STR save. On a failure, a creature takes 14 (4d6) bludgeoning damage and is [[../../Conditions/Stunned|stunned]] until the end of its next turn. On a success, a creature takes half the damage and isn’t stunned."
senses: darkvision 120 ft.
languages: Otyugh
immune: poison | poisoned
perception: 11
cr: 5
```

#aberration #cr5 #large
