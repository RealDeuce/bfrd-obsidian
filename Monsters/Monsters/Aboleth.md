
```statblock
layout: Basic ToV Layout
speed: 10 ft., swim 40 ft.
ac: 17 (natural armor)
size: Large
actions:
  - name: Multiattack.
    desc: "The aboleth makes three Tentacle or Psychic Bolt attacks. If two Tentacle attacks hit one target, the target must succeed on a DC 16 CON save or contract the *slime pox* disease (see the Slime Pox trait)."
  - name: Tentacle.
    desc: "*Melee Weapon Attack:* +9 to hit, reach 10 ft., one target.  *Hit:* 15 (3d6 + 5) bludgeoning damage."
  - name: Psychic Bolt.
    desc: "*Ranged Spell Attack:* +8 to hit, range 120 ft., one target.  *Hit:* 14 (3d6 + 4) psychic damage."
  - name: Psychic Torrent (Recharge 5–6).
    desc: "The aboleth floods the minds of up to three creatures it can see within 60 feet of it with random and horrific memories from its eons-long life. Each target must make a DC 16 WIS save. On a failure, a creature takes 49 (14d6) psychic damage and is [[../../Conditions/Incapacitated|incapacitated]] until the end of its next turn, as its mind reels from the torrent of images, thoughts, and memories. On a success, a creature takes half the damage and isn’t incapacitated."
stats: ['+5', '−1', '+6', '+8', '+6', '+4']
name: Aboleth
legendary_actions:
  - name: Detect.
    desc: "The aboleth automatically detects every creature and trap within 60 feet of it, pinpointing the current location of each."
  - name: Swim.
    desc: "The aboleth swims up to half its speed without provoking opportunity attacks."
  - name: Slime Drain (Costs 2 Actions).
    desc: "One creature infected with *slime pox* within 30 feet of the aboleth takes 10 (3d6) acid damage, and the aboleth regains HP equal to the damage the creature takes."
traits:
  - name: Aberrant Resilience.
    desc: "The aboleth is resistant to the charmed, frightened, paralyzed, and stunned conditions, and it has advantage on saves against spells or effects that would alter its form."
  - name: Amphibious.
    desc: "The aboleth can breathe air and water."
  - name: Legendary Resistance (3/Day).
    desc: "If the aboleth fails a save, it can choose to succeed instead."
  - name: Probing Telepathy.
    desc: "If a creature the aboleth can see communicates telepathically with the aboleth, the aboleth learns the creature’s greatest desires."
  - name: Slime Pox.
    desc: "Characterized by the slimy pustules that erupt across the victim’s body, *slime pox* is a disease that infects creatures attacked by an aboleth or that come into contact with an aboleth’s slime. Until the disease is cured, the infected creature can breathe air and water, can’t regain HP except when underwater, and takes 6 (1d12) acid damage for every 1 hour it remains outside of water or without moisture applied to its skin. Every 24 hours that elapse, the infected creature must make a DC 16 CHA save. Each time a creature fails this save, it views the infecting aboleth more and more favorably, becoming the aboleth’s doting and protective thrall after three failed saves. The successes and failures don’t need to be consecutive, but once a creature has acquired three of a kind, it no longer has to make this save, resulting in either the creature becoming a thrall of the aboleth or an autonomous—though infected—creature. Slime pox can be cured only by the *[[../Spells/Heal|heal]]* spell or similar magic."
  - name: Slimy Skin.
    desc: "The aboleth is coated in an otherworldly mucus. A creature that touches the aboleth or that hits it with a melee attack while within 5 feet of it must succeed on a DC 16 CON save or be infected with *slime pox* (see the Slime Pox trait)."
resistant: acid | Aberrant Resilience
stealth: 9
type: Aberration
hp: 165
cr: 10
immune: psychic
languages: Deep Speech, telepathy 120 ft.
senses: darkvision 120 ft.
legendary_description: The aboleth can take 3 legendary actions, choosing from the options below. Only one legendary action option can be used at a time and only at the end of another creature’s turn. The aboleth regains spent legendary actions at the start of its turn.
perception: 20
```

#aberration #cr10 #large
