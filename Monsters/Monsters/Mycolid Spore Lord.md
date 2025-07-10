
```statblock
layout: Basic ToV Layout
immune: poison
senses: keensense 120 ft. (can’t sense beyond this radius)
languages: understands Druidic and Sylvan but can’t speak, telepathy 60 ft.
perception: 14
cr: 3
name: Mycolid Spore Lord
stealth: 12
bonus_actions:
  - name: Fetid Feast.
    desc: "The spore lord draws sustenance from a Medium or larger pile of carrion or rotting vegetation within 5 feet of it. It regains 7 (2d6) HP. The spore lord can’t use Fetid Feast on a pile of carrion or vegetation if it or another mycolid has already used Fetid Feast on that pile."
resistant: Plant Resilience
traits:
  - name: Fungal Toxicity.
    desc: "A creature that hits the mycolid with a melee attack while within 5 feet of it must succeed on a DC 13 CON save or be [[../../Conditions/Poisoned|poisoned]] for 5 hours. If the poison isn’t neutralized before 5 hours have passed, the creature must succeed on a DC 14 CON save, taking 9 (2d8) poison damage on a failed save, or half as much damage on a successful one."
  - name: Mycolid Connection.
    desc: "The spore lord can pinpoint the location of each friendly mycolid within 1 mile of it. In addition, its telepathy range increases to 1 mile when communicating with other mycolids."
  - name: Plant Resilience.
    desc: "The mycolid is resistant to exhaustion and to the paralyzed, petrified, and unconscious conditions."
hp: 68
type: Plant
speed: 15 ft.
ac: 14 (natural armor)
size: Medium
actions:
  - name: Multiattack.
    desc: "The spore lord makes two Fungal Staff attacks or uses Hurl Sap twice."
  - name: Fungal Staff.
    desc: "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one target.  *Hit:* 6 (1d6 + 3) bludgeoning damage plus 9 (2d8) poison damage."
  - name: Hurl Sap.
    desc: "*Ranged Weapon Attack:* +4 to hit, range 30/120 ft., one target.  *Hit:* 11 (2d8 + 2) poison damage, and the sap sticks to the target. While the sap is stuck, the target takes 4 (1d8) poison damage at the start of each of its turns. A creature can use an action to scrape away the sap, ending the effect."
  - name: Mushroom Ring (Recharge 5–6).
    desc: "The spore lord causes fungal growth to erupt from a point on the ground it can sense within 120 feet of it. A ring of mushrooms sprouts in a 15-foot radius around that point. Each creature that isn’t a mycolid within that ring must make a DC 14 CON save, taking 13 (3d8) poison damage on a failed save, or half as much damage on a successful one. Each mycolid within that ring gains 5 (2d4) temporary HP."
  - name: Slumber Spores (Recharge 5–6).
    desc: "The spore lord ejects sleep-inducing spores from its body. Each creature that isn’t a mycolid within 10 feet of the spore lord must make a DC 14 WIS save. On a failure, a creature takes 9 (2d8) poison damage and falls [[../../Conditions/Unconscious|unconscious]] for 1 minute. On a success, a creature takes half the damage and doesn’t fall unconscious. The unconscious creature wakes if it takes damage or if a creature uses an action to wake it."
stats: ['+3', '+2', '+1', '−1', '+4', '−1']
```

#cr3 #medium #plant
