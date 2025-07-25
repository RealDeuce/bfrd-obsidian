
```statblock
layout: Basic ToV Layout
hp: 34
type: Undead
perception: 12
stealth: 14
traits:
  - name: Hungry Dead Nature.
    desc: "The ghoul doesn’t require air or sleep. In addition, it must consume at least 2 pounds of raw meat every 24 hours, or it loses its immunity to exhaustion and risks starvation until it does so. While it has any levels of exhaustion from starvation, the ghoul can’t remove levels of exhaustion until it consumes at least 4 pounds of raw meat."
  - name: Spider Climb.
    desc: "The ghoul can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check."
  - name: Undead Resilience.
    desc: "The ghoul is immune to poison damage, to exhaustion, and to the poisoned condition."
senses: darkvision 60 ft.
languages: Common
immune: charmed | Undead Resilience
name: Ghoul
stats: ['+0', '+3', '+0', '−2', '+2', '−2']
actions:
  - name: Multiattack.
    desc: "The ghoul makes one Bite attack and one Claws attack. If both attacks hit a creature that isn’t a Construct or Undead, the target must succeed on a DC 13 CON save or contract *ghoul hunger* (see the Ghoul Hunger sidebar)."
  - name: Bite.
    desc: "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one target.  *Hit:* 7 (1d8 + 3) piercing damage."
  - name: Claws.
    desc: "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one target.  *Hit:* 8 (2d4 + 3) slashing damage. If the target is a creature that isn’t a Construct or Undead, it must succeed on a DC 13 CON save or be [[../../Conditions/Paralyzed|paralyzed]] for 1 minute. The target can repeat the save at the end of each of its turns, ending the effect on itself on a success."
ac: 13
cr: 1
size: Medium
speed: 30 ft., climb 30 ft.
```

#cr1 #medium #undead
