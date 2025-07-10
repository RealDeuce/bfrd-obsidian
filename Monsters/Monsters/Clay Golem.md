
```statblock
layout: Basic ToV Layout
cr: 9
perception: 9
immune: acid | Golem Resilience
senses: darkvision 60 ft.
languages: understands the languages of its creator but can’t speak
actions:
  - name: Multiattack.
    desc: "The golem makes three Slam attacks."
  - name: Slam.
    desc: "*Melee Weapon Attack:* +9 to hit, reach 5 ft., one target.  *Hit:* 21 (3d10 + 5) bludgeoning, piercing, or slashing damage, as determined by Mold Hand. The target must succeed on a DC 16 STR save or suffer an effect based on the type of damage: knocked [[../../Conditions/Prone|prone]] (bludgeoning), pushed up to 10 feet away from the golem (piercing), or its speed is reduced by 10 feet until the end of its next turn (slashing)."
  - name: Haste (Recharge 5–6).
    desc: "Until the end of its next turn, the golem magically gains a +2 bonus to its AC, has advantage on DEX saves, and can make a Slam attack as a bonus action."
stats: ['+5', '−1', '+4', '−4', '−1', '−5']
speed: 20 ft.
size: Large
ac: 14 (natural armor)
stealth: 9
bonus_actions:
  - name: Mold Hand.
    desc: "The clay golem molds its hand into the shape of a weapon or back into a hand. The golem’s Slam attack deals bludgeoning, piercing, or slashing damage, depending on the type of weapon chosen, until the golem uses this bonus action again. For example, a hand shaped like an axe deals slashing damage."
traits:
  - name: Acid Absorption.
    desc: "Whenever the golem is subjected to acid damage, it takes no damage and instead regains HP equal to the acid damage dealt."
  - name: Construct Nature.
    desc: "The golem doesn’t require air, food, drink, or sleep."
  - name: Fire Weakness.
    desc: "When the clay golem takes fire damage, its body temporarily hardens like baked clay. Until the end of its next turn, the golem’s speed is reduced by 10 feet, it can’t use Mold Hand, and its AC becomes 18."
  - name: Golem Resilience.
    desc: "The golem is immune to poison and psychic damage and to bludgeoning, piercing, and slashing damage from nonmagical attacks. In addition, it is immune to exhaustion and to the charmed, frightened, paralyzed, petrified, and poisoned conditions."
  - name: Immutable Form.
    desc: "The golem is immune to any spell or effect that would alter its form."
  - name: Magic Resistance.
    desc: "The golem has advantage on saves against spells and other magical effects."
  - name: Magic Weapons.
    desc: "The golem’s weapon attacks are magical."
type: Construct
hp: 163
name: Clay Golem
```

#construct #cr9 #large
