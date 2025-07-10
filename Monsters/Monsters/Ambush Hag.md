
```statblock
layout: Basic ToV Layout
perception: 16
immune: poison | poisoned
senses: darkvision 120 ft.
languages: Common, Sylvan
cr: 9
stealth: 18
bonus_actions:
  - name: Illusory Appearance.
    desc: "The hag covers itself and anything it is wearing or carrying with a magical illusion that makes it look like another creature of its general size and humanoid shape. The illusion ends if the hag takes a bonus action to end it or if the hag dies.\n\nThe changes wrought by this effect fail to hold up to physical inspection. For example, the hag could appear to have smooth skin, but someone touching it would feel its rough flesh. Otherwise, a creature must take an action to visually inspect the illusion and succeed on a DC 20 INT (Investigation) check to discern that the hag is disguised."
traits:
  - name: Fey Resilience.
    desc: "The ambush hag is resistant to the charmed and unconscious conditions."
  - name: Mimicry.
    desc: "The hag can mimic Animal sounds and Humanoid voices. A creature that hears the sounds can tell they are imitations with a successful DC 16 WIS (Insight) check."
  - name: Spider Climb.
    desc: "The ambush hag can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check."
resistant: Fey Resilience
hp: 156
type: Fey
name: Ambush Hag
actions:
  - name: Multiattack.
    desc: "The ambush hag makes two Claw attacks or three Poison Spray attacks. It can replace one attack with a use of Spellcasting."
  - name: Claw.
    desc: "*Melee Weapon Attack:* +8 to hit, reach 5 ft., one target.  *Hit:* 13 (2d8 + 4) slashing damage plus 18 (4d8) poison damage, and the target must succeed on a DC 16 CON save or be [[../../Conditions/Paralyzed|paralyzed]] for 1 minute. The creature can repeat the save at the end of each of its turns, ending the effect on itself on a success."
  - name: Poison Spray.
    desc: "*Ranged Spell Attack:* +8 to hit, range 60 ft., one target.  *Hit:* 22 (4d8 + 4) poison damage, and the target must succeed on a DC 16 STR save or be [[../../Conditions/Restrained|restrained]] until the end of its next turn."
  - name: Spellcasting.
    desc: "The ambush hag casts one of the following spells, requiring no material components and using CHA as the spellcasting ability (spell save DC 16):  \nAt will: *[[../Spells/Message|message]], [[../Spells/Minor Illusion|minor illusion]], [[../Spells/Prestidigitation|prestidigitation]]*  \n3/day each: *[[../Spells/Blur|blur]], [[../Spells/Charm|charm]], [[../Rituals/Hallucinatory Terrain|Hallucinatory Terrain]]* (as an action)  \n1/day each: *[[../Spells/Hypnotic Pattern|hypnotic pattern]], [[../Spells/Major Image|major image]], [[../Spells/Seeming|seeming]]*"
stats: ['+3', '+8', '+3', '+3', '+2', '+8']
speed: 30 ft., climb 30 ft.
ac: 16 (natural armor)
size: Medium
```

#cr9 #fey #medium
