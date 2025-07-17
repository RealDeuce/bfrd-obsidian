
```statblock
layout: Basic ToV Layout
name: Gynosphinx
stealth: 12
legendary_actions:
  - name: Teleport.
    desc: "The sphinx magically teleports, along with any equipment it is wearing or carrying, up to 120 feet to an unoccupied space it can see."
  - name: Cast a Spell (Costs 2 Actions).
    desc: "The sphinx uses Spellcasting."
  - name: Psychic Burst (Costs 2 Actions).
    desc: "The sphinx sends out a burst of psychic energy. Each creature within 20 feet of the sphinx that has an INT of 8 or higher must succeed on a DC 17 INT save or be [[../../Conditions/Incapacitated|incapacitated]] until the end of its next turn, as it reels from the psychic onslaught."
resistant: bludgeoning, piercing, and slashing damage from nonmagical attacks | Monstrosity Resilience
bonus_actions:
  - name: Psychic Connection.
    desc: "One creature the sphinx can see within 60 feet of it must succeed on a DC 17 WIS save or be mentally connected to the sphinx until the sphinx chooses to end it or until the sphinx dies or the target dies. While connected in this way, the sphinx can cause the target to experience one of the following effects at the start of each of the target’s turns. The effect lasts until the start of the target’s next turn or until the connection ends. The target can repeat the save at the end of each of its turns, ending the connection on a success.\n* **Disoriented.** When the target moves, it moves in a random direction.\n* **Distracted.** When the target casts a spell, it must succeed on a DC 17 WIS save or be unable to cast the spell, using the action, bonus action, or reaction to cast the spell but not expending the spell slot or similar limited use of the spell.\n* 3819 The target has disadvantage on weapon attack rolls."
traits:
  - name: Inscrutable.
    desc: "The sphinx is immune to any effect that would sense its emotions or read its thoughts, as well as any divination spell that it refuses. WIS (Insight) checks made to ascertain the sphinx’s intentions or sincerity have disadvantage."
  - name: Monstrosity Resilience.
    desc: "The sphinx is resistant to exhaustion and to the frightened condition."
  - name: Psychic Claws.
    desc: "The sphinx’s Claw attacks are magical. When the sphinx hits with a Claw attack, the Claw deals an extra 3d6 psychic damage (included in the attack)."
hp: 204
type: Monstrosity
subtype: Outsider
speed: 40 ft., fly 60 ft.
ac: 17 (natural armor)
size: Large
actions:
  - name: Multiattack.
    desc: "The sphinx makes three Claw attacks, or it makes four Psychic Bolt attacks. It can replace one attack with a use of Spellcasting."
  - name: Claw.
    desc: "*Melee Weapon Attack:* +8 to hit, reach 5 ft., one target.  *Hit:* 15 (2d10 + 4) slashing damage plus 10 (3d6) psychic damage."
  - name: Psychic Bolt.
    desc: "*Ranged Spell Attack:* +9 to hit, range 120 ft., one target.  *Hit:* 19 (4d6 + 5) psychic damage."
  - name: Spellcasting.
    desc: "The sphinx casts one of the following spells, requiring no spell components and using CHA as the spellcasting ability (spell save DC 17).  \nAt will: *[[../Spells/Detect Magic|detect magic]], [[../Spells/Minor Illusion|minor illusion]], [[../Spells/Prestidigitation|prestidigitation]]*  \n3/day each: *[[../Rituals/Augury|Augury]]* (as an action), *[[../Spells/Major Image|major image]], [[../Spells/Suggestion|suggestion]]*   tongues  \n1/day: *[[../Rituals/Hallucinatory Terrain|Hallucinatory Terrain]]* (as an action)"
stats: ['+8', '+2', '+3', '+8', '+8', '+5']
immune: psychic | charmed, frightened
senses: truesight 120 ft.
languages: Common, Sphinx, telepathy 120 ft.
legendary_description: The sphinx can take 3 legendary actions, choosing from the options below. Only one legendary action option can be used at a time and only at the end of another creature’s turn. The sphinx regains spent legendary actions at the start of its turn.
perception: 18
cr: 11
```

#cr11 #large #monstrosity
