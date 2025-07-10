
```statblock
layout: Basic ToV Layout
perception: 15
immune: charmed
senses: darkvision 60 ft.
languages: Abyssal, Common, Infernal, telepathy 60 ft.
reactions:
  - name: Defend Me, Love!
    desc: "When a creature the succubus can see within 5 feet of a creature charmed by the succubus attacks the succubus, the succubus can command the charmed creature to use its reaction to make one melee weapon attack against the attacker."
cr: 4
stealth: 15
traits:
  - name: Telepathic Bond.
    desc: "The succubus ignores the range restriction on its telepathy when communicating with a creature it has charmed. The two don’t even need to be on the same plane of existence."
bonus_actions:
  - name: Change Shape.
    desc: "The succubus transforms into a Small or Medium Humanoid or back into its true form, which is Fiend. Without wings, it loses its flying speed. Its statistics, other than its size, are the same in each form. Any equipment it is wearing or carrying isn’t transformed. It reverts to its true form if it dies."
  - name: Etherealness.
    desc: "The succubus magically enters the Ethereal Plane from the Material Plane, or vice versa."
resistant: cold, fire, lightning, poison; bludgeoning, piercing, and slashing damage from nonmagical attacks | frightened, poisoned
hp: 79
type: Fiend
name: Succubus
subtype: Shapechanger
actions:
  - name: Multiattack.
    desc: "The succubus makes two Claw attacks or one Claw attack and one Draining Kiss attack. It can replace one attack with Charm."
  - name: Claw (Fiend Form Only).
    desc: "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one target.  *Hit:* 10 (2d6 + 3) slashing damage plus 7 (2d6) psychic damage."
  - name: Draining Kiss.
    desc: "*Melee Spell Attack:* +7 to hit, reach 5 ft., one willing creature, or a creature that is charmed, incapacitated, or restrained.  *Hit:* 15 (3d6 + 5) psychic damage, and the target’s HP maximum is reduced by an amount equal to the damage taken. This reduction lasts until the target finishes a long rest. The target dies if this effect reduces its HP maximum to 0."
  - name: Charm.
    desc: "One Humanoid the succubus can see within 30 feet of it must succeed on a DC 15 WIS save or be magically [[../../Conditions/Charmed|charmed]] for 1 day, until the succubus dies, or until the succubus takes a bonus action to end the effect. The charmed target obeys the succubus’s verbal or telepathic commands. If the target suffers any harm or receives a suicidal command, it can repeat the save, ending the effect on itself on a success. If the target successfully saves against the effect, or if the effect on it ends, the target is immune to this succubus’s Charm for the next 24 hours.   The succubus can have only one target charmed at a time. If it charms another, the effect on the previous target ends."
stats: ['−1', '+3', '+1', '+2', '+1', '+7']
speed: 30 ft., fly 60 ft.
ac: 15 (natural armor)
size: Medium
```

#cr4 #fiend #medium #shapechanger
