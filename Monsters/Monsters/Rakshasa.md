
```statblock
layout: Basic ToV Layout
perception: 18
languages: Abyssal, Common, Infernal
senses: truesight 60 ft.
immune: bludgeoning, piercing, and slashing damage from nonmagical attacks | prone
cr: 13
hp: 166
type: Fiend
bonus_actions:
  - name: Charming Gaze.
    desc: "The rakshasa turns its gaze toward one creature it can see within 60 feet of it. If the target can see the rakshasa, the target must succeed on a DC 18 CHA save or be [[../../Conditions/Charmed|charmed]] for 1 minute. A charmed creature can repeat the save at the end of each of its turns, ending the effect on itself on a success. The rakshasa can have up to three creatures charmed in this way at a time."
  - name: Illusory Appearance.
    desc: "The rakshasa covers itself and anything it is wearing or carrying with a magical illusion that makes it look like another creature of its general size and Humanoid shape. The illusion ends if the rakshasa takes a bonus action to end it or if the rakshasa dies.\n\nThe changes wrought by this effect fail to hold up to physical inspection. For example, a creature touching the disguised rakshasa might feel its fur instead of Humanoid flesh. Otherwise, a creature must take an action to visually inspect the illusion and succeed on a DC 25 INT (Investigation) check to discern that the rakshasa is disguised."
traits:
  - name: Limited Magic Immunity.
    desc: "The rakshasa can’t be affected or detected by spells of 6th level or lower unless it wishes to be. It has advantage on saves against all other spells and magical effects."
stealth: 18
vulnerable: piercing damage from magical attacks
name: Rakshasa
stats: ['+2', '+8', '+4', '+1', '+8', '+10']
actions:
  - name: Multiattack.
    desc: "The rakshasa makes four Claw or Arcane Bolt attacks. It can replace one attack with a use of Spellcasting. If two Claw attacks hit one creature, the target is cursed. While cursed, the target gains no benefit from finishing a short or long rest. The curse lasts until removed by the *[[../Spells/Remove Curse|remove curse]]* spell or similar magic."
  - name: Claw.
    desc: "*Melee Weapon Attack:* +8 to hit, reach 5 ft., one target.  *Hit:* 12 (2d8 + 3) slashing damage plus 10 (3d6) force damage."
  - name: Arcane Bolt.
    desc: "*Ranged Spell Attack:* +10 to hit, range 60 ft., one target.  *Hit:* 22 (5d6 + 5) force damage."
  - name: Travel the Planes (1/Day).
    desc: "The rakshasa magically transports itself to a different plane of existence. This works like the *[[../Spells/Plane Shift|plane shift]]* spell, except the rakshasa can affect only itself and can’t use this action to banish an unwilling creature."
  - name: Spellcasting.
    desc: "The rakshasa casts one of the following spells, requiring no material components and using CHA as the spellcasting ability (spell save DC 18).  \nAt will: *[[../Spells/Detect Thoughts|detect thoughts]], [[../Spells/Mage Hand|mage hand]], [[../Spells/Minor Illusion|minor illusion]]*  \n3/day each: *[[../Spells/Major Image|major image]], [[../Spells/Suggestion|suggestion]]*  \n1/day: *[[../Spells/Dominate|dominate]]*"
ac: 16 (natural armor)
size: Medium
speed: 40 ft., fly 30 ft. (hover)
```

#cr13 #fiend #medium
