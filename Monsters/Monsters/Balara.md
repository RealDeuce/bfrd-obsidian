
```statblock
layout: Basic ToV Layout
ac: 17 (natural armor)
size: Large
speed: 30 ft.
stats: ['+3', '+2', '+2', '−2', '+2', '−1']
actions:
  - name: Multiattack.
    desc: "The balara makes one Bite attack and two Claw attacks, or it makes three Necrotic Bolt attacks."
  - name: Bite.
    desc: "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one target.  *Hit:* 16 (3d8 + 3) piercing damage plus 4 (1d8) necrotic damage, and the target can’t regain HP until the start of the balara’s next turn."
  - name: Claw.
    desc: "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one target.  *Hit:* 13 (3d6 + 3) slashing damage."
  - name: Necrotic Bolt.
    desc: "*Ranged Spell Attack:* +5 to hit, range 60 ft., one target.  *Hit:* 15 (3d8 + 2) necrotic damage, and the target can’t regain HP until the start of the balara’s next turn."
name: Balara
hp: 114
type: Undead
stealth: 12
resistant: necrotic
traits:
  - name: Terrifying Luminance.
    desc: "When a creature that can see the balara’s glowing ribcage starts its turn within 30 feet of the balara, the balara can force it to make a DC 14 WIS save if the balara isn’t incapacitated and can see the creature. On a failure, the creature is [[../../Conditions/Frightened|frightened]] until the start of its next turn, as the visions, fear, and pain of the last moments of several animals flash through its mind. While frightened, the creature’s speed is reduced to 0, and it can’t use reactions.\n\nUnless surprised, a creature can avert its eyes to avoid the save at the start of its turn. If the creature does so, it can’t see the balara until the start of its next turn, when it can avert its eyes again. If the creature looks at the balara in the meantime, it must immediately make the save."
  - name: Undead Nature.
    desc: "The balara doesn’t require air, food, drink, or sleep."
  - name: Undead Resilience.
    desc: "The balara is immune to poison damage, to exhaustion, and to the poisoned condition."
cr: 6
reactions:
  - name: Relentless Pursuit.
    desc: "When a creature the balara can see moves away from it, the balara can move up to half its speed toward that creature. This movement doesn’t provoke opportunity attacks."
senses: darkvision 60 ft.
languages: understands the languages of its creator but can’t speak
immune: charmed, frightened | Undead Resilience
perception: 14
```

#cr6 #large #undead
