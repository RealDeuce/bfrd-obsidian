
```statblock
layout: Basic ToV Layout
traits:
  - name: Bound.
    desc: "The shield guardian is magically bound to an amulet. As long as the guardian and its amulet are on the same plane of existence, the guardian knows the distance and direction to the amulet’s wearer, and the amulet’s wearer can telepathically call the guardian, teleporting the guardian to an unoccupied space within 5 feet of the wearer after 1 minute. In addition, if the guardian is within 60 feet of the amulet’s wearer, half of any damage the wearer takes (rounded up) is taken by the guardian instead."
  - name: Construct Nature.
    desc: "The shield guardian doesn’t require air, food, drink, or sleep."
  - name: Construct Resilience.
    desc: "The shield guardian is immune to poison and psychic damage, and it is immune to exhaustion and the charmed, frightened, paralyzed, petrified, and poisoned conditions."
  - name: Regeneration.
    desc: "The shield guardian regains 10 HP at the start of its turn if it has at least 1 HP."
  - name: Spell Storing.
    desc: "A spellcaster who wears the shield guardian’s amulet can cause the guardian to store one spell of 4th level or lower. To do so, the wearer must cast the spell on the guardian. The spell has no effect but is stored within the guardian. When commanded to do so by the wearer or when a situation arises that was predefined by the spellcaster, the guardian casts the stored spell, using the appropriate action required by the spell, with any parameters set by the original caster, requiring no components. When the spell is cast or a new spell is stored, any previously stored spell is lost."
bonus_actions:
  - name: Protective Step.
    desc: "The guardian teleports up to 60 feet to an unoccupied space it can see within 5 feet of the amulet’s wearer."
stealth: 9
hp: 139
type: Construct
name: Shield Guardian
actions:
  - name: Multiattack.
    desc: "The shield guardian makes two Runed Fist attacks, or it makes three Rune Bolt attacks."
  - name: Runed Fist.
    desc: "*Melee Weapon Attack:* +7 to hit, reach 5 ft., one target.  *Hit:* 13 (2d8 + 4) bludgeoning damage plus 14 (4d8) force damage."
  - name: Rune Bolt.
    desc: "*Ranged Spell Attack:* +5 to hit, range 60 ft., one target.  *Hit:* 16 (4d6 + 2) force damage."
stats: ['+4', '−1', '+4', '−2', '+2', '−4']
speed: 30 ft.
ac: 17 (natural armor)
size: Large
perception: 12
immune: Construct Resilience
languages: understands the languages of its creator and the languages of the wearer of its amulet but can’t speak
senses: keensense 10 ft., darkvision 60 ft.
reactions:
  - name: Shield.
    desc: "When a creature the guardian can see makes an attack against the amulet’s wearer, the guardian grants a +2 bonus to the wearer’s AC if the guardian is within 5 feet of the wearer."
cr: 7
```

#construct #cr7 #large
