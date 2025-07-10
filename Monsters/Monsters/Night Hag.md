
```statblock
layout: Basic ToV Layout
cr: 5
languages: Abyssal, Common, Infernal, Primordial
senses: truesight 120 ft.
immune: charmed, unconscious
perception: 15
ac: 17 (natural armor)
size: Medium
speed: 30 ft.
stats: ['+4', '+2', '+3', '+3', '+2', '+6']
actions:
  - name: Multiattack.
    desc: "The night hag can use Cause Sorrow. It then makes two Claw or Arcane Bolt attacks. It can replace one Claw or Arcane Bolt attack with a use of Spellcasting."
  - name: Claw (Hag Form Only).
    desc: "*Melee Weapon Attack:* +7 to hit, reach 5 ft., one target.  *Hit:* 18 (4d6 + 4) slashing damage."
  - name: Arcane Bolt.
    desc: "*Ranged Spell Attack:* +6 to hit, range 60 ft., one target.  *Hit:* 19 (3d10 + 3) force damage."
  - name: Cause Sorrow.
    desc: "One creature the hag can see within 10 feet of it must succeed on a DC 14 CHA save or be filled with sorrow for 1 minute. While filled with sorrow, a creature is [[../../Conditions/Incapacitated|incapacitated]] and experiences visions or memories of sorrowful events. The target can repeat the save at the end of each of its turns (if conscious) or end of each hour (if unconscious), ending the effect on itself on a success.\n\nFor each hour an unconscious creature is affected, its HP maximum is reduced by 5 (1d10). This reduction lasts until removed by the greater restoration spell or similar magic. The creature dies if this effect reduces its HP maximum to 0. If an unconscious creature suffers from Cause Sorrow for at least 1 hour, it doesn’t gain any benefits from the rest.\n\nThe hag can have only one creature filled with sorrow at a time. If it uses Cause Sorrow on another, the effect on the previous creature ends."
  - name: Spellcasting.
    desc: "The hag casts one of the following spells, requiring no material components and using CHA as the spellcasting ability (spell save DC 14).  \nAt will: *[[../Spells/Ray of Enfeeblement|ray of enfeeblement]], [[../Spells/Silent Image|silent image]]*  \n2/day each: *[[../Spells/Detect Thoughts|detect thoughts]], [[../Spells/Plane Shift|plane shift]]* (self only), *[[../Spells/Sleep|sleep]]*"
name: Night Hag
type: Fiend
hp: 104
bonus_actions:
  - name: Change Shape.
    desc: "The hag magically transforms into Medium or smaller Humanoid, or back into its true form, which is Fiend. Its statistics, other than its size, are the same in each form. Any equipment it is wearing or carrying transforms with it. It reverts to its true form if it dies."
  - name: Etherealness.
    desc: "The hag magically enters the Ethereal Plane from the Material Plane, or vice versa. The hag can use Cause Sorrow on an unconscious creature not on its plane; otherwise, the hag can’t affect or be affected by anything on the other plane."
traits:
  - name: Magic Resistance.
    desc: "The hag has advantage on saves against spells and other magical effects."
resistant: cold, fire; bludgeoning, piercing, and slashing damage from nonmagical attacks
stealth: 15
```

#cr5 #fiend #medium
