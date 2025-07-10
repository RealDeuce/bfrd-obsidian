
```statblock
layout: Basic ToV Layout
cr: 1
reactions:
  - name: Repay the Gift.
    desc: "When a friendly vampire the thrall can see within 5 feet of it is hit by an attack that would reduce the vampire to 0 HP, the thrall can give some of its life force to save the vampire. The thrall loses 10 (3d6) HP, and the vampire regains HP equal to that amount."
languages: any one language (usually Common)
senses: darkvision 30 ft.
perception: 13
ac: 13
size: Medium
speed: 30 ft., climb 10 ft.
stats: ['+2', '+5', '+4', '+0', '+1', '+2']
actions:
  - name: Multiattack.
    desc: "The vampire thrall makes two Rapier attacks."
  - name: Rapier.
    desc: "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one target.  *Hit:* 7 (1d8 + 3) piercing damage."
subtype: Any Lineage
name: Vampire Thrall
type: Humanoid
hp: 40
resistant: exhaustion
traits:
  - name: Blood-Bound.
    desc: "If the thrall has not consumed 1 ounce of blood from a vampire within the past week, it is [[../../Conditions/Poisoned|poisoned]] for 1 week, and it loses darkvision and its Limited Regeneration, Spider Climb, and Sunlight Sensitivity traits until it consumes 1 ounce of vampire blood."
  - name: Limited Regeneration.
    desc: "The thrall regains 2 HP at the start of its turn if it has at least 1 HP and isn’t in sunlight. If the thrall takes radiant damage, this trait doesn’t function at the start of the thrall’s next turn."
  - name: Spider Climb.
    desc: "The thrall can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check."
  - name: Sunlight Sensitivity.
    desc: "While in sunlight, the thrall has disadvantage on attack rolls, and its Perception is 8 when perceiving by sight."
stealth: 14
```

#any-lineage #cr1 #humanoid #medium
