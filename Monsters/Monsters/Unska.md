
```statblock
layout: Basic ToV Layout
hp: 88
type: Fiend
bonus_actions:
  - name: Whirl of Ink.
    desc: "Tattoos leap off the unska’s body and latch onto a creature the unska can see within 30 feet of it. The target must succeed on a DC 14 WIS save or be [[../../Conditions/Charmed|charmed]], disoriented, or [[../../Conditions/Frightened|frightened]] (the unska’s choice) until the end of its next turn. When a disoriented creature moves, it moves in a random direction."
traits:
  - name: Demonic Resilience.
    desc: "The unska is resistant to cold, fire, and lightning damage. In addition, it is immune to poison damage and to the poisoned condition."
  - name: Magic Resistance.
    desc: "The unska has advantage on saves against spells and other magical effects."
resistant: Demonic Resilience
stealth: 12
name: Unska
stats: ['+3', '+2', '+2', '−1', '+0', '+2']
subtype: Outsider, Demon
actions:
  - name: Multiattack.
    desc: "The unska makes two Claw attacks and one Tongue attack, or it makes three Ink Blast attacks."
  - name: Claw.
    desc: "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one target.  *Hit:* 10 (2d6 + 3) slashing damage plus 3 (1d6) poison damage, and the target must succeed on a DC 14 CON save or be [[../../Conditions/Poisoned|poisoned]] for 1 minute. While poisoned, the target has disadvantage on saves against the unska’s Whirl of Ink. The target can repeat the save at the end of each of its turns, ending the effect on itself on a success."
  - name: Tongue.
    desc: "*Melee Weapon Attack:* +6 to hit, reach 10 ft., one target.  *Hit:* 12 (2d8 + 3) piercing damage. The target must succeed on a DC 14 CON save, or its HP maximum is reduced by an amount equal to the damage taken. This reduction lasts until the target finishes a long rest. The target dies if its HP maximum is reduced to 0."
  - name: Ink Blast.
    desc: "*Ranged Spell Attack:* +5 to hit, range 60 ft., one target.  *Hit:* 12 (3d6 + 2) poison damage, and the target must succeed on a DC 14 CON save or have disadvantage on the next save it makes against the unska’s Whirl of Ink before the start of the unska’s next turn."
ac: 17 (natural armor)
size: Medium
speed: 20 ft., climb 20 ft.
perception: 10
languages: Abyssal, Common
senses: darkvision 60 ft.
immune: charmed, frightened | Demonic Resilience
cr: 5
```

#cr5 #demon #fiend #medium #outsider
