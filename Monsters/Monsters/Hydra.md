
```statblock
layout: Basic ToV Layout
cr: 8
perception: 16
senses: darkvision 60 ft.
languages: —
actions:
  - name: Multiattack.
    desc: "The hydra makes as many Bite attacks as it has heads."
  - name: Bite.
    desc: "*Melee Weapon Attack:* +8 to hit, reach 10 ft., one target.  *Hit:* 10 (1d10 + 5) piercing damage."
  - name: Noxious Breath (Recharge Special).
    desc: "The hydra exhales poisonous gas in a 30-foot cone. Each creature in that area must make a DC 16 CON save, taking 40 (9d8) poison damage on a failed save, or half as much damage on a successful one. While the hydra has five or more heads, this action has a recharge of 6. The recharge range increases for each head the hydra has below five. For example, a hydra that starts its turn with two heads can recharge this feature on a 3, 4, 5, or 6."
stats: ['+5', '+1', '+5', '−4', '+0', '−2']
speed: 30 ft., swim 30 ft.
ac: 15 (natural armor)
size: Huge
stealth: 14
traits:
  - name: Hold Breath.
    desc: "The hydra can hold its breath for 1 hour."
  - name: Multiple Heads.
    desc: "The hydra has five heads and is resistant to the blinded, charmed, deafened, frightened, stunned, and unconscious conditions.\n\nWhenever the hydra takes 25 or more damage in a single turn, one of its heads dies. If all its heads die, the hydra dies. At the end of its turn, it grows two heads for each of its heads that died since its last turn, unless it has taken fire damage since its last turn. The hydra regains 10 HP for each head regrown in this way."
  - name: Reactive Heads.
    desc: "For each head the hydra has beyond one, it gets an extra reaction that can be used only for opportunity attacks."
  - name: Wakeful.
    desc: "While the hydra sleeps, at least one of its heads is awake."
bonus_actions:
  - name: Bloody Burst (Has Fewer Than Five Heads).
    desc: "The hydra squeezes the stumps of its severed heads, spraying blood and gore. Each creature within 5 feet of the hydra must succeed on a DC 16 CON save or be [[../../Conditions/Incapacitated|incapacitated]] until the end of its next turn and [[../../Conditions/Poisoned|poisoned]] for 1 minute. A poisoned creature can repeat the save at the end of each of its turns, ending the effect on itself on a success."
resistant: Multiple Heads
type: Dragon
hp: 166
name: Hydra
```

#cr8 #dragon #huge
