
```statblock
layout: Basic ToV Layout
immune: necrotic, poison | charmed, poisoned
senses: darkvision 60 ft.
languages: Abyssal, Celestial, Common, Infernal
perception: 15
cr: 8
name: Spirit Naga
vulnerable: radiant
stealth: 16
resistant: Monstrosity Resilience
bonus_actions:
  - name: Hidden Step.
    desc: "The spirit naga magically teleports, along with any equipment it is wearing or carrying, up to 30 feet to an unoccupied space it can see and takes the Hide action."
traits:
  - name: Guardian Projection.
    desc: "The spirit naga’s skeletal form is covered with a magical illusion that makes it look like the guardian naga it was in life. The naga can use a bonus action to dismiss this illusion until the end of its next turn.\n\nThe changes wrought by this illusion fail to hold up to physical inspection. For example, a creature touching the spirit naga would feel its rough, dry scales and exposed bones instead of the smooth, cool scales of a guardian naga. Otherwise, a creature must take an action to visually inspect the illusion and succeed on a DC 20 INT (Investigation) check to discern the spirit naga’s true appearance."
  - name: Monstrosity Resilience.
    desc: "The naga is resistant to exhaustion and to the frightened condition."
  - name: Necrotic Strikes.
    desc: "The naga’s weapon attacks are magical. When the naga hits with any weapon attack, the weapon deals an extra 4d8 necrotic damage (included in the attack)."
  - name: Rejuvenation.
    desc: "If it dies, the naga returns to life in 1d6 days, regaining all its HP and becoming active again. Only a wish spell can prevent this trait from functioning."
type: Monstrosity
hp: 166
speed: 40 ft.
ac: 15 (natural armor)
size: Large
actions:
  - name: Multiattack.
    desc: "The spirit naga makes two Bite or Spit Poison attacks. If both attacks hit one creature, the target must succeed on a DC 14 CON save or be [[../../Conditions/Poisoned|poisoned]] for 1 minute. A poisoned creature can repeat the save at the end of each of its turns, ending the effect on itself on a success."
  - name: Bite.
    desc: "*Melee Weapon Attack:* +7 to hit, reach 10 ft., one target.  *Hit:* 6 (1d4 + 4) piercing damage plus 5 (2d4) poison damage and 18 (4d8) necrotic damage."
  - name: Spit Poison.
    desc: "*Ranged Weapon Attack:* +6 to hit, range 20/60 ft., one target.  *Hit:* 10 (3d4 + 3) poison damage plus 18 (4d8) necrotic damage."
  - name: Spellcasting.
    desc: "The spirit naga casts one of the following spells, requiring only verbal components and using CHA as the spellcasting ability (spell save DC 14).  \nAt will: *[[../Spells/Command|command]], [[../Spells/Mage Hand|mage hand]], [[../Spells/Minor Illusion|minor illusion]]*  \n3/day each: *[[../Rituals/Augury|Augury]]* (as an action), *[[../Spells/Charm|charm]], [[../Spells/Sleep|sleep]]*  \n2/day each: *[[../Spells/Bestow Curse|bestow curse]], [[../Spells/Hold|hold]]*  \n1/day: *[[../Spells/Dominate|dominate]]*"
stats: ['+4', '+6', '+5', '+3', '+5', '+6']
```

#cr8 #large #monstrosity
