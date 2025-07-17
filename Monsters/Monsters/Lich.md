
```statblock
layout: Basic ToV Layout
reactions:
  - name: Absorb Spell.
    desc: "When a creature the lich can see within 60 feet of it casts a spell, the lich can absorb the spell’s energy, countering it. This works like the *[[../Spells/Counterspell|counterspell]]* spell, except the lich must always make a spellcasting ability check, no matter the spell's circle. Its ability check for this is +12. If it successfully counters the spell, the lich gains 5 temporary HP for each circle of the spell."
cr: 21
legendary_description: The lich can take 3 legendary actions, choosing from the options below. Only one legendary action option can be used at a time and only at the end of another creature’s turn. The lich regains spent legendary actions at the start of its turn.
perception: 19
immune: bludgeoning, piercing, and slashing damage from nonmagical attacks | charmed, frightened, paralyzed | Undead Resilience
languages: Common plus up to five other languages
senses: truesight 120 ft.
actions:
  - name: Multiattack.
    desc: "The lich uses Lich’s Gaze. It then makes four Arcane Death Burst attacks, or it makes three Arcane Death Burst attacks and one Death-Infused Rod attack. It can replace one attack with a use of Spellcasting."
  - name: Arcane Death Burst.
    desc: "*Melee or Ranged Spell Attack:* +12 to hit, reach 5 ft. or range 120 ft., one target.  *Hit:* 23 (4d8 + 5) force damage plus 17 (5d6) necrotic damage."
  - name: Death-Infused Rod.
    desc: "*Melee Weapon Attack:* +10 to hit, reach 5 ft., one target.  *Hit:* 21 (4d8 + 3) bludgeoning damage plus 17 (5d6) necrotic damage, and the target must succeed on a DC 20 CON save or be [[../../Conditions/Paralyzed|paralyzed]] for 1 minute. The target can repeat the save at the end of each of its turns, ending the effect on itself on a success."
  - name: Lich’s Gaze.
    desc: "The lich fixes its gaze on one creature it can see within 30 feet of it. The target must succeed on a DC 20 CHA save or be [[../../Conditions/Charmed|charmed]] or [[../../Conditions/Frightened|frightened]] (the lich’s choice) until the end of its next turn."
  - name: Spellcasting.
    desc: "The lich casts one of the following spells, using INT as the spellcasting ability (spell save DC 20).  \nAt will: *[[../Spells/Detect Magic|detect magic]], [[../Spells/Disguise Self|disguise self]], [[../Spells/Mage Hand|mage hand]], [[../Spells/Message|message]]*   prestidigitation  \n3/day each: *[[../Spells/Charm|charm]], [[../Spells/Detect Thoughts|detect thoughts]], [[../Spells/Dispel Magic|dispel magic]]*   invisibility (self only), mirror image  \n2/day each: *[[../Spells/Bestow Curse|bestow curse]], [[../Spells/Cloudkill|cloudkill]], [[../Spells/Dimension Door|dimension door]]*   greater hold  \n1/day each: *[[../Spells/Plane Shift|plane shift]]* (self only), *[[../Spells/Power Word Stun|power word stun]]*   wall of force"
stats: ['+0', '+3', '+10', '+12', '+9', '+3']
speed: 30 ft.
ac: 17 (natural armor)
size: Medium
legendary_actions:
  - name: Move.
    desc: "The lich moves up to its speed without provoking opportunity attacks. If the lich is levitating, it can use this legendary action to move horizontally, propelling itself with a blast of arcane power."
  - name: Cast a Spell (Costs 2 Actions).
    desc: "The lich uses Spellcasting."
  - name: Disrupt Life (Costs 3 Actions).
    desc: "Each creature within 20 feet of the lich that isn’t Undead must make a DC 20 CON save, taking 21 (6d6) necrotic damage on a failed save, or half as much damage on a successful one. The lich regains HP equal to the single highest amount of necrotic damage dealt."
resistant: cold, lightning, necrotic
bonus_actions:
  - name: Levitate.
    desc: "The lich can rise or descend vertically up to 20 feet and can remain suspended there. This bonus action works like the *[[../Spells/Levitate|levitate]]* spell, except there is no duration, and the lich doesn’t need to concentrate to continue levitating each round."
traits:
  - name: Arcane Mastery.
    desc: "The lich can concentrate on two spells simultaneously. If it casts a third spell that requires concentration, the lich loses concentration on the oldest spell. If the lich is concentrating on two spells and loses concentration because of taking damage, it loses concentration only on the oldest spell."
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
stealth: 13
type: Undead
hp: 314
name: Lich
```

#cr21 #medium #undead
