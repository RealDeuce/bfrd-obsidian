
```statblock
layout: Basic ToV Layout
name: Virtuoso Lich
hp: 185
type: Undead
stealth: 17
legendary_actions:
  - name: Call Muse.
    desc: "The lich uses Call Muse."
  - name: Move.
    desc: "The lich moves up to its speed without provoking opportunity attacks."
  - name: Cast a Spell (Costs 2 Actions).
    desc: "The lich uses Spellcasting."
  - name: Unrestrained Art (Costs 3 Actions).
    desc: "The lich unleashes the full force of its artistic talents. Each creature with 15 feet of the lich must make a DC 17 DEX save. On a failure, a creature takes 9 (2d8) damage of the type chosen with the Versatile Artist trait and is knocked [[../../Conditions/Prone|prone]]. On a success, a creature takes half the damage and isn’t knocked prone."
resistant: necrotic; bludgeoning, piercing, and slashing damage from nonmagical attacks
traits:
  - name: Legendary Resistance (3/Day).
    desc: "If the lich fails a save, it can choose to succeed instead."
  - name: Rejuvenation.
    desc: "If it has a phylactery, a destroyed lich gains a new body in 1d10 days, regaining all its HP and becoming active again. The new body appears within 5 feet of the phylactery."
  - name: Turn Resistance.
    desc: "The lich has advantage on saves against any effect that turns undead."
  - name: Undead Nature.
    desc: "The lich doesn’t require air, food, drink, or sleep."
  - name: Undead Resilience.
    desc: "The lich is immune to poison damage, to exhaustion, and to the poisoned condition."
  - name: Versatile Artist.
    desc: "At the end of each long rest, the lich chooses one form of artistic expression, such as song, poetry, dance, fashion, paint, or similar. Until it finishes a long rest, the lich has immunity to one type of damage, which is associated with its artistic expression. For example, a lich expressing art through song or poetry has immunity to thunder damage, a lich expressing art through fashion has immunity to slashing damage, and a lich expressing art through paint has immunity to acid damage. This trait can’t give the lich immunity to force, psychic, or radiant damage."
ac: 17 (natural armor)
size: Medium
speed: 30 ft.
stats: ['+0', '+7', '+2', '+2', '+5', '+9']
actions:
  - name: Multiattack.
    desc: "The virtuoso lich uses Corrupted Art. It then makes three Artistic Flourish attacks. It can replace one attack with a use of Spellcasting."
  - name: Artistic Flourish.
    desc: "*Melee or Ranged Spell Attack:* +9 to hit, reach 5 ft. or range 60 ft., one target.  *Hit:* 18 (3d8 + 5) damage of the type chosen with the Versatile Artist trait plus 9 (2d8) force damage."
  - name: Call Muse.
    desc: "The lich chooses one Beast or Humanoid it can see within 30 feet of it to be its muse. The target must succeed on a DC 17 WIS save or become the lich’s muse and be [[../../Conditions/Charmed|charmed]] by the lich for 1 minute. While charmed, the muse has a speed of 0 and is [[../../Conditions/Incapacitated|incapacitated]] as it watches or listens to the lich’s artistic expression. The muse can repeat the save at the end of each of its turns, ending the effect on itself on a success. If a creature’s save is successful or the effect ends for it, the creature is immune to the lich’s Call Muse for the next 24 hours. If the muse suffers harm from the lich, it is no longer charmed.\n\nThe lich can have only one muse at a time. If it charms another, the effect on the previous muse ends. If the lich is within 30 feet of its muse and can see its muse, the lich has advantage on its first Artistic Flourish attack each round against a creature that isn’t its muse."
  - name: Corrupted Art.
    desc: "The lich hums a discordant melody, paints a crumbling symbol of death in the air, performs a reality‑bending pirouette, or emulates some other expression of corrupted or twisted art and targets one creature it can see, other than itself, within 60 feet. This action’s effects change, depending on if the target is Undead.\n* **Non-Undead.** The target must make a DC 17 WIS save.    On a failure, a creature is [[../../Conditions/Blinded|blinded]], [[../../Conditions/Charmed|charmed]], or [[../../Conditions/Deafened|deafened]] (the lich’s choice) until the end of its next turn. On a success, a creature takes half the damage and isn’t incapacitated.\n* **Undead.** The target regains 18 (4d8) HP. Healing that exceeds the target’s HP maximum becomes temporary HP."
  - name: Spellcasting.
    desc: "The lich casts one of the following spells, using CHA as the spellcasting ability (spell save DC 17).    \nAt will: *[[../Spells/Disguise Self|disguise self]], [[../Spells/Mage Hand|mage hand]], [[../Spells/Message|message]], [[../Spells/Prestidigitation|prestidigitation]]*    \n3/day each: *[[../Spells/Charm|charm]], [[../Spells/Hideous Laughter|hideous laughter]], [[../Spells/Hold|hold]], [[../Spells/Invisibility|invisibility]]*    (self only)    \n2/day each: *[[../Spells/Dispel Magic|dispel magic]], [[../Spells/Fear|fear]], [[../Spells/Dimension Door|dimension door]]*    \n1/day each: *[[../Spells/Irresistible Dance|irresistible dance]], [[../Spells/Programmed Illusion|programmed illusion]]*    seeming"
senses: truesight 60 ft.
languages: Common plus up to two other languages
immune: blinded, deafened, charmed, frightened, paralyzed | Undead Resilience
perception: 15
legendary_description: The virtuoso lich can take 3 legendary actions, choosing from the options below. Only one legendary action can be used at a time and only at the end of another creature’s turn. The lich regains spent legendary actions at the start of its turn.
cr: 12
```

#cr12 #medium #undead
