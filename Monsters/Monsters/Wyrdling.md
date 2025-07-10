
```statblock
layout: Basic ToV Layout
name: Wyrdling
stealth: 12
traits:
  - name: Intuition.
    desc: "The wyrdling rolls two dice for initiative, taking the higher number. In addition, the wyrdling has advantage on WIS (Insight) checks."
  - name: Read Fate.
    desc: "The wyrdling can spend 1 minute communing with fate on behalf of one creature that remains within 10 feet of it for the duration. The creature must ask a single question concerning a specific goal, event, or activity to occur within 7 days. At the end of the minute, the wyrdling pronounces the result of the target’s inquiry. This trait works like the *[[../Rituals/Divination|divination]]* spell, except it can’t be used to answer a specific creature’s question more than once every 3 days, regardless if the creature asks a different question."
bonus_actions:
  - name: Pronounce Fate.
    desc: "The wyrdling pronounces the fate, either fortune or doom (the wyrdling’s choice), of one creature it can see within 30 feet of it. The target rolls a d4 and adds (fortune) or subtracts (doom) the number rolled to the next attack roll or save it makes before the start of the wyrdling’s next turn."
resistant: psychic | charmed, frightened
hp: 40
type: Humanoid
speed: 30 ft.
ac: 12
size: Medium
actions:
  - name: Psychic Burst.
    desc: "*Melee or Ranged Spell Attack:* +5 to hit, reach 5 ft. or range 60 ft., one target.  *Hit:* 13 (3d6 + 3) psychic damage."
stats: ['+0', '+2', '+1', '+1', '+5', '+2']
senses: —
languages: Common
perception: 13
cr: 1
reactions:
  - name: Call on Fate.
    desc: "When the wyrdling is attacked by a creature it can see, it can pluck the strands of fate around the creature, imposing disadvantage on that attack roll. If the attack misses, the wyrdling or one friendly creature it can see within 30 feet of it has advantage on the next attack roll it makes against the attacker before the end of the wyrdling’s next turn."
```

#cr1 #humanoid #medium
