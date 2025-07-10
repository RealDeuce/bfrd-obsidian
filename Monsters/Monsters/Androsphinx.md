
```statblock
layout: Basic ToV Layout
legendary_description: The sphinx can take 3 legendary actions, choosing from the  options below. Only one legendary action option can be  used at a time and only at the end of another creature’s turn.  The sphinx regains spent legendary actions at the start of its  turn.
perception: 20
immune: psychic; bludgeoning, piercing, and slashing damage from nonmagical attacks | charmed, frightened
senses: truesight 120 ft.
languages: Common, Sphinx
cr: 17
stealth: 15
bonus_actions:
  - name: Roar.
    desc: "The sphinx emits one of the following magical roars. Each roar is audible up to 300 feet away. When it roars, the sphinx chooses up to three creatures it can see within 120 feet of it to be affected by the roar. A creature that fails a save and is affected by an ongoing effect can repeat the save at the end of each of its turns, ending the effect on itself on a success.\n* **Rumbling Roar.** This deep roar rumbles through each target’s body, rattling it to its bones. Each target must succeed on a DC 18 CON save or deal only half damage with weapon attacks that use STR or DEX for 1 minute.\n* **Terrifying Roar.** This shrill roar tugs at the self-preservation instincts within creatures. Each target must succeed on a DC 18 WIS save or be [[../../Conditions/Frightened|frightened]] for 1 minute. While frightened, a creature’s speed is 0. If a creature fails the save by 5 or more, it is also [[../../Conditions/Paralyzed|paralyzed]] while frightened.\n* **Thunderous Roar.** This booming roar slams against the chosen creatures. Each target must succeed on a DC 18 STR save or be pushed up to 15 feet away from the sphinx, knocked [[../../Conditions/Prone|prone]], and [[../../Conditions/Deafened|deafened]] for 1 minute."
legendary_actions:
  - name: Teleport.
    desc: "The sphinx magically teleports, along with any equipment it is wearing or carrying, up to 120 feet to an unoccupied space it can see."
  - name: Cast a Spell (Costs 2 Actions).
    desc: "The sphinx uses Spellcasting."
  - name: Lacerating Swipe (Costs 2 Actions).
    desc: "The sphinx rears up on its hind legs, wings fluttering, and swipes in a wide arc with both its forepaws. Each creature in a 15-foot cone must succeed on a DC 18 DEX save or take 11 (2d10) slashing damage and suffer a bleeding wound. A creature with a bleeding wound loses 5 (1d10) HP at the start of each of its turns. Any creature can take an action to stanch the wound with a successful DC 18 WIS (Medicine) check. The wound also closes if the bleeding creature receives magical healing."
resistant: Monstrosity Resilience
traits:
  - name: Inscrutable.
    desc: "The sphinx is immune to any effect that would sense its emotions or read its thoughts, as well as any divination spell that it refuses. WIS (Insight) checks made to ascertain the sphinx’s intentions or sincerity have disadvantage."
  - name: Magical Claws.
    desc: "The sphinx’s Claw attacks are magical. When the sphinx hits with a Claw attack, the Claw deals an extra 2d8 force damage (included in the attack)."
  - name: Monstrosity Resilience.
    desc: "The sphinx is resistant to exhaustion and to the frightened condition."
type: Monstrosity
hp: 284
name: Androsphinx
actions:
  - name: Multiattack.
    desc: "The sphinx makes four Claw or Arcane Bolt attacks. It can replace one attack with a use of Spellcasting."
  - name: Claw.
    desc: "*Melee Weapon Attack:* +12 to hit, reach 5 ft., one target.  *Hit:* 17 (2d10 + 6) slashing damage plus 9 (2d8) force damage."
  - name: Arcane Bolt.
    desc: "*Ranged Spell Attack:* +12 to hit, range 120 ft., one target.  *Hit:* 24 (4d8 + 6) force damage."
  - name: Spellcasting.
    desc: "The sphinx casts one of the following spells, requiring no material components and using WIS as the spellcasting ability (spell save DC 18).  \nAt will: *[[../Spells/Command|command]], [[../Spells/Detect Evil and Good|detect evil and good]], [[../Spells/Thaumaturgy|thaumaturgy]]*  \n3/day each: *[[../Spells/Dispel Magic|dispel magic]], [[../Spells/Restoration|restoration]], [[../Spells/Tongues|tongues]], [[../Spells/Zone of Truth|zone of truth]]*  \n2/day each: *[[../Spells/Freedom of Movement|freedom of movement]], [[../Spells/Greater Restoration|greater restoration]]*  \n1/day: *[[../Spells/Heal|heal]]*"
stats: ['+6', '+5', '+11', '+9', '+10', '+6']
speed: 40 ft., fly 60 ft.
ac: 17 (natural armor)
size: Large
```

#cr17 #large #monstrosity
