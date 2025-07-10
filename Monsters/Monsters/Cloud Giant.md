
```statblock
layout: Basic ToV Layout
name: Cloud Giant
vulnerable: Giant Attributes
traits:
  - name: Cloudsight.
    desc: "The cloud giant can see through areas obscured by clouds, fog, smoke, and steam without penalty."
  - name: Giant Attributes.
    desc: "The cloud giant is resistant to the stunned condition, and it is vulnerable to the prone condition."
  - name: Heightened Smell.
    desc: "The cloud giant’s Perception is 22 when perceiving by smell."
bonus_actions:
  - name: Cloud Cover.
    desc: "The cloud giant creates a 20-foot cube of clouds centered on a point it can see within 60 feet of it. The cube spreads around corners, and its area is heavily obscured. The cloud lasts for 1 minute, until the cloud giant dies, or until the cloud giant uses this bonus action again."
  - name: Condense.
    desc: "The cloud giant causes a 20-foot-radius sphere of cloud, fog, smoke, or steam centered on a point it can see within 60 feet of it to become as thick as mud, making the area difficult terrain for creatures moving through it. A creature that starts its turn in the hardened cloud must succeed on a DC 15 STR save or be [[../../Conditions/Restrained|restrained]] until the start of its next turn. The cloud remains condensed for 1 minute, until the cloud giant dies, or until the cloud giant uses this bonus action again."
resistant: cold | Giant Attributes
stealth: 10
type: Giant
hp: 175
speed: 40 ft., fly 60 ft.
ac: 14 (natural armor)
size: Huge
actions:
  - name: Multiattack.
    desc: "The cloud giant makes three Cloud-Coated Mace attacks, or it makes two Wind Burst attacks."
  - name: Cloud-Coated Mace.
    desc: "*Melee Weapon Attack:* +12 to hit, reach 10 ft., one target.  *Hit:* 18 (3d6 + 8) piercing damage plus 4 (1d8) cold damage."
  - name: Wind Burst.
    desc: "*Ranged Spell Attack:* +8 to hit, range 150 ft., one target.  *Hit:* 31 (5d10 + 4) bludgeoning damage, and the target must succeed on a DC 16 STR save or be pushed up to 10 feet away from the cloud giant and knocked [[../../Conditions/Prone|prone]]."
stats: ['+8', '+0', '+10', '+1', '+7', '+8']
languages: Giant
senses: —
perception: 17
cr: 9
reactions:
  - name: Cirrus Deflection.
    desc: "The cloud giant creates a bit of hardened cloud between it and an attacker, increasing the giant’s AC by 4. To do so, it must be able to see the attacker."
```

#cr9 #giant #huge
