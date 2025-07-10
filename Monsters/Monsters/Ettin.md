
```statblock
layout: Basic ToV Layout
hp: 95
type: Giant
stealth: 9
traits:
  - name: Giant Attributes.
    desc: "The ettin is resistant to the stunned condition, and it is vulnerable to the prone condition."
  - name: Multiple Heads.
    desc: "The ettin has two heads and is resistant to the blinded, charmed, deafened, frightened, stunned, and unconscious conditions."
  - name: Obstinate.
    desc: "The ettin has advantage on WIS and CHA saves."
  - name: Wakeful.
    desc: "When one of the ettin’s heads is asleep, its other head is awake."
bonus_actions:
  - name: That One!
    desc: "One of the ettin’s heads picks a creature the ettin can see within 30 feet of it, gaining advantage on its next attack against that creature. The other head doesn’t like being told what to do and has disadvantage on its next attack against that creature. Each weapon attack notes which head controls that weapon."
resistant: Giant Attributes, Multiple Heads
name: Ettin
vulnerable: Giant Attributes
stats: ['+5', '−1', '+3', '−2', '+0', '−1']
actions:
  - name: Multiattack.
    desc: "The ettin makes one Knobbed Club attack and one Spiked Club attack."
  - name: Knobbed Club.
    desc: "*Melee Weapon Attack:* +7 to hit, reach 5 ft., one target.  *Hit:* 18 (3d8 + 5) bludgeoning damage, and the target must succeed on a DC 15 STR save or be [[../../Conditions/Incapacitated|incapacitated]] until the end of its next turn, as the blow knocks the wind out of the target. This weapon is wielded by the right head."
  - name: Spiked Club.
    desc: "*Melee Weapon Attack:* +7 to hit, reach 5 ft., one target.  *Hit:* 18 (3d8 + 5) piercing damage, and the target must succeed on a DC 15 CON save or be [[../../Conditions/Poisoned|poisoned]] for 1 minute, as bits of rotten meat clinging to the club’s spikes coat the target’s wound. The target can repeat the save at the end of each of its turns, ending the effect on itself on a success. This weapon is wielded by the left head."
ac: 12 (natural armor)
size: Large
speed: 40 ft.
perception: 14
senses: darkvision 60 ft.
languages: Giant, Orc
cr: 4
```

#cr4 #giant #large
