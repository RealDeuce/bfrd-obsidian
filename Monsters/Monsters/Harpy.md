
```statblock
layout: Basic ToV Layout
cr: 1
perception: 10
languages: Common
senses: darkvision 120 ft.
stats: ['+1', '+3', '+1', '−2', '+0', '+1']
actions:
  - name: Multiattack.
    desc: "The harpy makes two Claw or Screech attacks. If both Screech attacks hit one Giant or Humanoid, the target has disadvantage on the next save it makes against the harpy’s Luring Song before the start of the harpy’s next turn."
  - name: Claw.
    desc: "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one target.  *Hit:* 8 (2d4 + 3) slashing damage."
  - name: Screech.
    desc: "*Ranged Spell Attack:* +4 to hit, range 30/120 ft., one target.  *Hit:* 8 (2d6 + 1) thunder damage."
ac: 13
size: Medium
speed: 20 ft., fly 40 ft.
hp: 38
type: Monstrosity
traits:
  - name: Monstrosity Resilience.
    desc: "The harpy is resistant to exhaustion and to the frightened condition."
bonus_actions:
  - name: Luring Song.
    desc: "The harpy sings a magical melody. Every Humanoid and Giant within 300 feet of the harpy that can hear the song must succeed on a DC 11 WIS save or be [[../../Conditions/Charmed|charmed]] until the song ends. The harpy must use a bonus action on its subsequent turns to continue singing. It can stop singing at any time. The song ends if the harpy is incapacitated.\n\nWhile charmed by the harpy, a target is incapacitated and ignores the songs of other harpies. If the charmed target is more than 5 feet away from the harpy, the target must move on its turn toward the harpy by the most direct route, trying to get within 5 feet. It doesn’t avoid opportunity attacks, but before moving into damaging terrain, such as lava or a pit, and whenever it takes damage from a source other than the harpy, the target can repeat the save. A charmed target can also repeat the save at the end of each of its turns. If the save is successful, the effect ends on it. A target that successfully saves is immune to this harpy’s song for the next 24 hours."
resistant: charmed | Monstrosity Resilience
stealth: 13
name: Harpy
```

#cr1 #medium #monstrosity
