
```statblock
layout: Basic ToV Layout
name: Ghast
type: Undead
hp: 48
stealth: 13
traits:
  - name: Hungry Dead Nature.
    desc: "The ghast doesn’t require air or sleep. In addition, it must consume at least 2 pounds of raw meat every 24 hours, or it loses its immunity to exhaustion and risks starvation until it does so. While it has any levels of exhaustion from starvation, the ghast can’t remove levels of exhaustion until it consumes at least 4 pounds of raw meat."
  - name: Spider Climb.
    desc: "The ghast can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check."
  - name: Stench.
    desc: "A creature that starts its turn within 5 feet of the ghast must succeed on a DC 13 CON save or be poisoned until the start of its next turn. On a success, the creature is immune to the ghast’s Stench for 24 hours."
  - name: Turning Defiance.
    desc: "The ghast and any ghouls within 30 feet of it have advantage on saves against effects that turn undead."
  - name: Undead Resilience.
    desc: "The ghast is immune to poison damage, to exhaustion, and to the poisoned condition."
resistant: necrotic
ac: 13
size: Medium
speed: 30 ft., climb 30 ft.
stats: ['+3', '+3', '+0', '+0', '+2', '−1']
actions:
  - name: Multiattack.
    desc: "The ghast makes one Bite attack and two Claws attacks. If one Bite attack and at least one Claws attack hit a creature that isn’t a Construct or Undead, the target must succeed on a DC 13 CON save or contract *ghoul hunger* (see the Ghoul Hunger sidebar)."
  - name: Bite.
    desc: "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one target.  *Hit:* 7 (1d8 + 3) piercing damage."
  - name: Claws.
    desc: "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one target.  *Hit:* 8 (2d4 + 3) slashing damage. If the target is a creature that isn’t a Construct or Undead, it must succeed on a DC 13 CON save or be [[../../Conditions/Paralyzed|paralyzed]] for 1 minute. The target can repeat the save at the end of each of its turns, ending the effect on itself on a success."
senses: darkvision 60 ft.
languages: Common
immune: charmed | Undead Resilience
perception: 12
cr: 2
```

#cr2 #medium #undead
