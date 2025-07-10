
```statblock
layout: Basic ToV Layout
perception: 13
immune: lightning | grappled, paralyzed, prone, restrained, unconscious | Undead Resilience
senses: darkvision 120 ft.
languages: the languages it knew in life
reactions:
  - name: Consume Life.
    desc: "When a creature the will-o’-wisp can see within 15 feet of it is reduced to 0 HP, the will-o’-wisp can consume some of that creature’s fading life. The will-o’-wisp gains 7 (2d6) temporary HP, and the creature has disadvantage on the next death save it makes before the end of the wisp’s next turn."
cr: 2
stealth: 14
traits:
  - name: Ephemeral.
    desc: "The will-o’-wisp can’t wear or carry anything. In addition, it adds its WIS modifier to its AC (included above)."
  - name: Incorporeal Movement.
    desc: "The will-o’-wisp can move through other creatures and objects as if they were difficult terrain. It takes 5 (1d10) force damage if it ends its turn inside an object."
  - name: Variable Illumination.
    desc: "The will-o’-wisp sheds bright light in a 5- to 20-foot radius and dim light for an additional number of feet equal to the chosen radius. The will-o’-wisp can alter the radius as a bonus action."
  - name: Undead Nature.
    desc: "The will-o’-wisp doesn’t require air, food, drink, or sleep."
  - name: Undead Resilience.
    desc: "The will-o’-wisp is immune to poison damage, to exhaustion, and to the poisoned condition."
bonus_actions:
  - name: Beckon.
    desc: "The will-o’-wisp pulses its lightly gently toward one creature it can see within 30 feet of it. The target must succeed on a DC 13 WIS save or use its reaction to move up to its speed toward the will-o’-wisp by the most direct route. It doesn’t avoid opportunity attacks or damaging terrain when moving."
resistant: acid, cold, fire, necrotic, thunder; bludgeoning, piercing, and slashing damage from nonmagical attacks
type: Undead
hp: 31
name: Will-o’-Wisp
actions:
  - name: Multiattack.
    desc: "The will-o’-wisp makes two Shock attacks."
  - name: Shock.
    desc: "*Melee Spell Attack:* +5 to hit, reach 5 ft., one target.  *Hit:* 10 (2d6 + 3) lightning damage."
  - name: Invisibility.
    desc: "The will-o’-wisp and its light magically become [[../../Conditions/Invisible|invisible]] until it attacks or uses its Beckon, or until its concentration ends (as if concentrating on a spell)."
stats: ['−5', '+4', '+0', '+1', '+3', '+0']
speed: 0 ft., fly 50 ft. (hover)
ac: 17 (Ephemeral)
size: Tiny
```

#cr2 #tiny #undead
