
```statblock
layout: Basic ToV Layout
cr: 2
reactions:
  - name: Barnacle Block.
    desc: "When the hag takes damage from a source it can see, the hag can shift the barnacles and scales on its body to absorb some of the impact, reducing the damage by 4 (1d8)."
senses: darkvision 60 ft.
languages: Aquan, Common, Giant
immune: frightened
perception: 11
ac: 14 (natural armor)
size: Medium
speed: 30 ft., swim 40 ft.
stats: ['+3', '+1', '+2', '+1', '+1', '+1']
actions:
  - name: Multiattack.
    desc: "The hag uses Death Glare. It then makes two Claw attacks."
  - name: Claw.
    desc: "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one target.  *Hit:* 10 (2d6 + 3) slashing damage."
  - name: Death Glare.
    desc: "One creature the hag can see within 30 feet of it must succeed on a DC 12 WIS save or be [[../../Conditions/Frightened|frightened]] until the end of its next turn. If the target is already frightened and fails the save, it is reduced to 0 HP instead. If reduced to 0 HP in this way, the creature is stable."
name: Sea Hag
type: Fey
hp: 51
stealth: 13
traits:
  - name: Amphibious.
    desc: "The sea hag can breathe air and water."
  - name: Fey Resilience.
    desc: "The sea hag is resistant to the charmed and unconscious conditions."
  - name: Horrific Appearance.
    desc: "When a Humanoid that can see the hag’s true form starts its turn within 30 feet of the hag, the hag can force it to make a DC 12 WIS save. On a failure, the creature is [[../../Conditions/Frightened|frightened]] until the start of its next turn.\n\nUnless surprised or the revelation of the hag’s true form is sudden, such as the ending of Illusory Appearance, a creature can avert its eyes to avoid the save at the start of its turn. If the creature does so, it can’t see the hag until the start of its next turn, when it can avert its eyes again. If the creature looks at the hag in the meantime, it must immediately make the save."
  - name: Underwater Camouflage.
    desc: "The hag’s Stealth is 18 while underwater and not using Illusory Appearance."
bonus_actions:
  - name: Illusory Appearance.
    desc: "The hag covers itself and anything it is wearing or carrying with a magical illusion that makes it look like another creature of its general size and Humanoid shape. The illusion ends if the hag takes a bonus action to end it or if the hag dies.\n\nThe changes from this effect fail to hold up to physical inspection. For example, the hag could appear to have smooth skin, but someone touching it would feel its scaly flesh. Otherwise, a creature must take an action to visually inspect the illusion and succeed on a DC 20 INT (Investigation) check to discern that the hag is disguised."
resistant: Fey Resilience
```

#cr2 #fey #medium
