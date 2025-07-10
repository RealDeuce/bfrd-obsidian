
```statblock
layout: Basic ToV Layout
name: Purple Worm
hp: 255
type: Monstrosity
stealth: 8
bonus_actions:
  - name: Rapid Digestion.
    desc: "The purple worm’s digestive system absorbs some of the already digested material from creatures it has swallowed. If the purple worm has at least one swallowed creature inside it, the purple worm regains 9 (2d8) HP. This healing increases by 4 (1d8) for each creature currently inside the purple worm, to a maximum of 10d8."
resistant: Monstrosity Resilience
traits:
  - name: Monstrosity Resilience.
    desc: "The purple worm is resistant to exhaustion and to the frightened condition."
  - name: Tunneler.
    desc: "The purple worm can burrow through solid rock at half its burrowing speed, and it leaves a 10-foot-diameter tunnel in its wake."
size: Gargantuan
ac: 18 (natural armor)
speed: 50 ft., burrow 30 ft.
stats: ['+9', '−2', '+11', '−5', '+4', '−3']
actions:
  - name: Multiattack.
    desc: "The worm makes one Bite attack and one Tail Stinger attack."
  - name: Bite.
    desc: "*Melee Weapon Attack:* +14 to hit, reach 10 ft., one target.  *Hit:* 22 (3d8 + 9) piercing damage. If the target is a Large or smaller creature, it must succeed on a DC 19 DEX save or be swallowed by the purple worm. A swallowed creature is [[../../Conditions/Blinded|blinded]] and [[../../Conditions/Restrained|restrained]], it has total cover against attacks and other effects outside of the worm, and it takes 21 (6d6) acid damage at the start of each of the worm’s turns.\n\nIf the worm takes 30 damage or more on a single turn from a creature inside it, the worm must succeed on a DC 21 CON save at the end of that turn or regurgitate all swallowed creatures, which fall [[../../Conditions/Prone|prone]] in a space within 10 feet of the worm. If the worm dies, a swallowed creature is no longer restrained by it and can escape from the corpse by using 20 feet of movement, exiting [[../../Conditions/Prone|prone]]."
  - name: Tail Stinger.
    desc: "*Melee Weapon Attack:* +14 to hit, reach 10 ft., one creature.  *Hit:* 19 (3d6 + 9) piercing damage, and the target must make a DC 19 CON save, taking 42 (12d6) poison damage on a failed save, or half as much damage on a successful one."
  - name: Thrash (Recharge 5–6).
    desc: "The purple worm convulses its large body, smashing everything around it. Each creature within 20 feet of the worm must make a DC 19 STR save. On a failure, a creature takes 54 (12d8) bludgeoning damage and is [[../../Conditions/Stunned|stunned]] until the end of its next turn. On a success, a creature takes half the damage and isn’t stunned."
senses: keensense 60 ft., tremorsense 60 ft.
languages: —
immune: prone
perception: 14
cr: 15
```

#cr15 #gargantuan #monstrosity
