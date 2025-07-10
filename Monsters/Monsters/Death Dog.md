
```statblock
layout: Basic ToV Layout
cr: 1
languages: —
senses: darkvision 120 ft.
perception: 15
ac: 12
size: Medium
speed: 40 ft.
stats: ['+2', '+2', '+2', '−4', '+1', '−2']
actions:
  - name: Multiattack.
    desc: "The death dog makes two Bite attacks."
  - name: Bite.
    desc: "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target.  *Hit:* 7 (2d4 + 2) piercing damage. If the target is a creature, it must succeed on a DC 12 CON save or contract a disease. Until the disease is cured, the target is [[../../Conditions/Poisoned|poisoned]]. Every 24 hours that elapse, the infected creature must repeat the save, reducing its HP maximum by 5 (2d4) on a failure. This reduction lasts until the creature finishes a long rest after the disease is cured. The creature dies if the disease reduces its HP maximum to 0."
subtype: Animal
name: Death Dog
hp: 40
type: Monstrosity
bonus_actions:
  - name: Dual Bark.
    desc: "The death dog’s two heads bark at creatures in two 15-foot cones. Each creature in the area of a cone must succeed on a DC 12 CON save or be [[../../Conditions/Deafened|deafened]] until the end of its next turn. If the cones overlap each other, each creature in overlapping cones must make only one save with disadvantage rather than one save for each cone."
traits:
  - name: Monstrosity Resilience.
    desc: "The death dog is resistant to exhaustion and to the frightened condition."
  - name: Multiple Heads.
    desc: "The death dog has two heads and is resistant to the blinded, charmed, deafened, frightened, stunned, and unconscious conditions."
resistant: Multiple Heads, Monstrosity Resilience
stealth: 14
```

#animal #cr1 #medium #monstrosity
