
```statblock
layout: Basic ToV Layout
perception: 19
legendary_description: The mummy lord can take 3 legendary actions, choosing from the options below. Only one legendary action option can be used at a time and only at the end of another creature’s turn. The mummy lord regains spent legendary actions at the start of its turn.
languages: the languages it knew in life
senses: darkvision 60 ft.
immune: necrotic; bludgeoning, piercing, and slashing damage from nonmagical attacks | charmed, frightened, paralyzed | Undead Resilience
cr: 15
type: Undead
hp: 270
traits:
  - name: Legendary Resistance (3/Day).
    desc: "If the mummy lord fails a save, it can choose to succeed instead."
  - name: Magic Resistance.
    desc: "The mummy lord has advantage on saves against spells and other magical effects."
  - name: Rejuvenation.
    desc: "A destroyed mummy lord gains a new body in 24 hours if its heart is intact, regaining all its HP and becoming active again. The new body appears within 5 feet of the mummy lord’s heart."
  - name: Turning Defiance.
    desc: "The mummy lord and any friendly Undead within 30 feet of it have advantage on saves against effects that turn undead."
  - name: Undead Nature.
    desc: "The mummy lord doesn’t require air, food, drink, or sleep."
  - name: Undead Resilience.
    desc: "The mummy lord is immune to poison damage, to exhaustion, and to the poisoned condition."
legendary_actions:
  - name: Detect Life.
    desc: "The mummy lord automatically detects every creature that isn’t a Construct or Undead within 30 feet of it, pinpointing the current location of each."
  - name: Sandy Teleport.
    desc: "The mummy lord transforms into loose sand and teleports up to 60 feet to an unoccupied space it can see, reforming in that space. Any equipment it is wearing or carrying transforms with it."
  - name: Call Servitors (Costs 2 Actions).
    desc: "The mummy lord uses Undead Servitors."
  - name: Unleash Divine Energy (Costs 2 Actions).
    desc: "The mummy lord unleashes a wave of divine energy. Each creature within 10 feet of it must make a DC 17 CON save. On a failure, a creature takes 14 (4d6) necrotic damage or radiant damage (the mummy lord’s choice) and is [[../../Conditions/Stunned|stunned]] until the end of its next turn. On a success, a creature takes half the damage and isn’t stunned."
bonus_actions:
  - name: Bolster Undead.
    desc: "The mummy lord sends necrotic power into up to three friendly Undead it can see, other than itself, within 30 feet of it. Each target regains 14 (4d6) HP and has advantage on the next attack roll it makes before the start of the mummy lord’s next turn."
  - name: Dreadful Glare.
    desc: "The mummy lord glares at up to two creatures it can see within 60 feet of it. Each target must succeed on a DC 17 WIS save or be [[../../Conditions/Frightened|frightened]] until the end of its next turn. If the target fails the save by 5 or more, it is also [[../../Conditions/Paralyzed|paralyzed]] for the same duration."
stealth: 10
name: Mummy Lord
vulnerable: fire
stats: ['+4', '+0', '+8', '+5', '+9', '+8']
actions:
  - name: Multiattack.
    desc: "The mummy makes two Blessed Khopesh attacks and one Rotting Fist attack, or it makes four Divine Bolt attacks. It can replace one attack with a use of Spellcasting."
  - name: Blessed Khopesh.
    desc: "*Melee Weapon Attack:* +9 to hit, reach 5 ft., one target.  *Hit:* 11 (2d6 + 4) slashing damage plus 14 (4d6) necrotic damage or radiant damage (the mummy lord’s choice)."
  - name: Rotting Fist.
    desc: "*Melee Weapon Attack:* +9 to hit, reach 5 ft., one target.  *Hit:* 13 (2d8 + 4) bludgeoning damage plus 21 (6d6) necrotic damage, and the target must succeed on a DC 17 CON save or be cursed with [[../../Running the Game/Environmental Hazard Descriptions/Curse Descriptions#Mummy Rot|mummy rot]]."
  - name: Divine Bolt.
    desc: "*Ranged Spell Attack:* +9 to hit, range 120 ft., one target.  *Hit:* 21 (5d6 + 4) necrotic damage or radiant damage (the mummy lord’s choice)."
  - name: Undead Servitors.
    desc: "The mummy lord magically calls 2d6 **[[Skeleton|skeletons]]** or **[[Zombie|zombies]]**, 1d4 **[[Specter|specters]]**, or 2 **[[Mummy|mummies]]**. The called creatures arrive in 1d4 rounds, acting as allies of the mummy lord and obeying its spoken commands. The Undead remain for 1 hour, until the mummy lord dies, or until the mummy lord dismisses them as a bonus action. The mummy lord can have any number of Undead under its control at one time, provided the combined total CR of the Undead is no higher than 6."
  - name: Spellcasting.
    desc: "The mummy lord casts one of the following spells, using WIS as the spellcasting ability (spell save DC 17).  \nAt will: *[[../Spells/Command|command]], [[../Spells/Guidance|guidance]], [[../Spells/Thaumaturgy|thaumaturgy]]*  \n3/day each: *[[../Spells/Dispel Magic|dispel magic]], [[../Spells/Hold|hold]], [[../Spells/Silence|silence]]*  \n1/day each: *[[../Spells/Contagion|contagion]], [[../Spells/Insect Plague|insect plague]]*"
ac: 17 (natural armor)
size: Medium
speed: 20 ft.
```

#cr15 #medium #undead
