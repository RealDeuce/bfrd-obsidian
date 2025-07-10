
```statblock
layout: Basic ToV Layout
stealth: 13
traits:
  - name: Badlands Strider.
    desc: "Difficult terrain composed of sand, mud, or rock doesn’t cost the lamia extra movement. In addition, the lamia leaves no tracks or other traces of its passage when moving through sandy, muddy, or rocky terrain."
  - name: Monstrosity Resilience.
    desc: "The lamia is resistant to exhaustion and to the frightened condition."
bonus_actions:
  - name: Intoxicating Gaze.
    desc: "The lamia gazes at one creature it can see within 30 feet of it. The target must succeed on a DC 13 CHA save or be [[../../Conditions/Charmed|charmed]] until the end of its next turn and cursed for 1 hour. While cursed, the target has disadvantage on WIS saves and on all ability checks."
resistant: charmed | Monstrosity Resilience
type: Monstrosity
hp: 95
name: Lamia
actions:
  - name: Multiattack.
    desc: "The lamia makes two Hooves attacks and one Dagger attack, or it makes three Arcane Bolt attacks. It can replace one attack with a use of Spellcasting."
  - name: Dagger.
    desc: "*Melee or Ranged Weapon Attack:* +5 to hit, reach 5 ft. or range 20/60 ft., one target.  *Hit:* 5 (1d4 + 3) piercing damage."
  - name: Hooves.
    desc: "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one target.  *Hit:* 14 (2d10 + 3) bludgeoning damage."
  - name: Arcane Bolt.
    desc: "*Ranged Spell Attack:* +5 to hit, range 60 ft., one target.  *Hit:* 12 (2d8 + 3) force damage."
  - name: Spellcasting.
    desc: "The lamia casts one of the following spells, requiring no material components and using CHA as the spellcasting ability (spell save DC 13).  \nAt will: *[[../Spells/Minor Illusion|minor illusion]], [[../Spells/Silent Image|silent image]], [[../Spells/Suggestion|suggestion]]*  \n3/day each: *[[../Spells/Charm|charm]], [[../Spells/Command|command]], [[../Spells/Major Image|major image]]*  \n1/day: *[[../Spells/Compulsion|compulsion]]*"
stats: ['+3', '+1', '+2', '+2', '+2', '+5']
speed: 30 ft.
size: Large
ac: 13 (natural armor)
perception: 12
senses: darkvision 60 ft.
languages: Abyssal, Common
cr: 4
```

#cr4 #large #monstrosity
