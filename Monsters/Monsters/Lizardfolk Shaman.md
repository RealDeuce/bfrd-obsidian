
```statblock
layout: Basic ToV Layout
perception: 15
senses: —
languages: Common, Draconic
cr: 2
stealth: 12
bonus_actions:
  - name: Poisoned Body (32 HP or Fewer).
    desc: "The shaman coats itself in poison until the start of its next turn. It takes 3 (1d6) poison damage. In addition, the next time a creature hits the shaman with a melee attack while within 5 feet of the shaman before the start of the shaman’s next turn, the attacker takes 7 (2d6) poison damage."
traits:
  - name: Heightened Smell and Taste.
    desc: "The lizardfolk’s Perception is 20 when perceiving by smell or taste."
  - name: Hold Breath.
    desc: "The lizardfolk shaman can hold its breath for 15 minutes."
resistant: poison | poisoned
type: Humanoid
hp: 57
name: Lizardfolk Shaman
actions:
  - name: Multiattack.
    desc: "The lizardfolk makes one Bite attack and one Ritual Staff attack, or it makes two Swamp Bolt attacks."
  - name: Bite.
    desc: "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target.  *Hit:* 5 (1d6 + 2) piercing damage."
  - name: Ritual Staff.
    desc: "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target.  *Hit:* 6 (1d8 + 2) bludgeoning damage plus 7 (2d6) poison damage."
  - name: Swamp Bolt.
    desc: "*Ranged Spell Attack:* +5 to hit, range 60 ft., one target.  *Hit:* 10 (2d6 + 3) poison damage, and the target must succeed on a DC 13 CON save or be [[../../Conditions/Poisoned|poisoned]] until the end of its next turn."
  - name: Spellcasting.
    desc: "The lizardfolk shaman casts one of the following spells, using WIS as the spellcasting ability (spell save DC 13).  \nAt will: *[[../Spells/Druidcraft|druidcraft]], [[../Spells/Guidance|guidance]], [[../Spells/Mending|mending]]*  \n2/day each: *[[../Spells/Cure Wounds|cure wounds]], [[../Spells/Entangle|entangle]], [[../Spells/Grease|grease]]*  \n1/day: *[[../Spells/Ray of Enfeeblement|ray of enfeeblement]]*"
stats: ['+2', '+0', '+1', '+0', '+5', '+0']
speed: 30 ft., climb 15 ft., swim 30 ft.
ac: 13 (natural armor)
size: Medium
```

#cr2 #humanoid #medium
