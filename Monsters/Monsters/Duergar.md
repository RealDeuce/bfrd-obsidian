
```statblock
layout: Basic ToV Layout
name: Duergar
hp: 36
type: Humanoid
resistant: poison | poisoned | Duergar Resilience
bonus_actions:
  - name: Enlarge.
    desc: "The duergar magically increases in size, along with any equipment it is wearing or carrying. While enlarged, the duergar is Large, doubles its damage dice on weapon attacks (included in the attacks), and makes STR checks and saves with advantage. While enlarged, it also can no longer use the Invisibility action. If the duergar lacks the room to become Large, this bonus action fails."
traits:
  - name: Duergar Resilience.
    desc: "The duergar is resistant to the charmed and paralyzed conditions, and it has advantage on saves against spells and illusions."
  - name: Reduce.
    desc: "If the duergar starts its turn enlarged, it can choose to end the effect and return to its normal size (no action required)."
  - name: Sunlight Sensitivity.
    desc: "While in sunlight, the duergar has disadvantage on attack rolls, and its Perception is 5 when perceiving by sight."
stealth: 12
ac: 16 (scale mail, shield)
size: Medium
speed: 25 ft.
stats: ['+2', '+0', '+2', '+0', '+0', '−1']
actions:
  - name: War Pick.
    desc: "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target.  *Hit:* 6 (1d8 + 2) piercing damage, or 11 (2d8 + 2) piercing damage while enlarged."
  - name: Javelin.
    desc: "*Melee or Ranged Weapon Attack:* +4 to hit, reach 5 ft. or range 30/120 ft., one target.  *Hit:* 5 (1d6 + 2) piercing damage, or 9 (2d6 + 2) piercing damage while enlarged."
  - name: Invisibility.
    desc: "The duergar magically turns [[../../Conditions/Invisible|invisible]] until it attacks or uses Enlarge, or until its concentration ends (as if concentrating on a spell). Any equipment the duergar wears or carries is invisible with it."
languages: Dwarvish, Undercommon
senses: darkvision 120 ft.
perception: 10
cr: 1
reactions:
  - name: Shield Wall.
    desc: "The duergar adds 2 to its AC against one weapon attack that would hit it. To do so, the duergar must be wielding a shield and within 5 feet of another duergar that is also wielding a shield."
```

#cr1 #humanoid #medium
