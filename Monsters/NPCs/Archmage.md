
```statblock
layout: Basic ToV Layout
ac: 17 (Magic Ward)
size: Medium
speed: 30 ft.
stats: ['+0', '+2', '+1', '+9', '+6', '+3']
actions:
  - name: Multiattack.
    desc: "The archmage makes three Arcane Blast attacks. It can replace one attack with a use of Spellcasting."
  - name: Arcane Blast.
    desc: "*Melee or Ranged Spell Attack:* +9 to hit, reach 5 ft. or range 60 ft., one target.  *Hit:* 27 (4d10 + 5) force damage, and the target must succeed on a DC 17 STR save or be pushed up to 10 feet away from the archmage and knocked [[../../Conditions/Prone|prone]]."
  - name: Burst of Magic (Recharge 5–6).
    desc: "The archmage releases a burst of swirling, multicolored, magical energy on a point it can see within 60 feet of it. Each creature within 20 feet of that point must make a DC 17 DEX save, taking 33 (6d10) force damage and 18 (4d8) acid, cold, fire, lightning, or thunder damage (the archmage’s choice) on a failed save, or half as much damage on a successful one."
  - name: Spellcasting.
    desc: "The archmage casts one of the following spells, using INT as the spellcasting ability (spell save DC 17).  \nAt will: *[[../Spells/Detect Magic|detect magic]], [[../Spells/Disguise Self|disguise self]], [[../Spells/Mage Hand|mage hand]], [[../Spells/Prestidigitation|prestidigitation]]*  \n3/day each: *[[../Spells/Charm|charm]], [[../Spells/Dispel Magic|dispel magic]], [[../Spells/Fly|fly]], [[../Spells/Invisibility|invisibility]]* (self only), *[[../Spells/Mirror Image|mirror image]]*  \n1/day each: *[[../Spells/Dimension Door|dimension door]], [[../Spells/Greater Hold|greater hold]], [[../Spells/Wall of Force|wall of force]]*"
subtype: Any Lineage
name: Archmage
type: Humanoid
hp: 212
stealth: 12
resistant: Magic Ward
bonus_actions:
  - name: Shimmering Step.
    desc: "The archmage teleports, along with any equipment it is wearing or carrying, up to 30 feet to an unoccupied space it can see. Sparks of arcane energy appear at the origin and destination when it uses this bonus action."
traits:
  - name: Magic Resistance.
    desc: "The archmage has advantage on saves against spells and other magical effects."
  - name: Magic Ward.
    desc: "While the archmage is conscious, wearing no armor, and not inside of an antimagic effect, it adds its INT modifier to its AC (included above). In addition, it is resistant to force damage."
cr: 12
reactions:
  - name: Counter Spell.
    desc: "When a creature the archmage can see within 30 feet of it casts a spell, the archmage can counter the spell, interrupting the casting. This reaction works like the *[[../Spells/Counterspell|counterspell]]* spell with a +5 spellcasting ability check, except the archmage must always make the ability check, regardless of the spell’s circle. The archmage has advantage on this check if the spell is on the Arcane source spell list."
senses: —
languages: any six languages
perception: 16
```

#cr12 #humanoid #medium
