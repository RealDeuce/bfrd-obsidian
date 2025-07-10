
```statblock
layout: Basic ToV Layout
reactions:
  - name: Stormy Rebuke.
    desc: "When a creature the storm giant can see hits it with a melee attack while within 5 feet of the giant, the giant can send a stormy blast at the creature. The attacker must succeed on a DC 17 STR save or be pushed up to 15 feet away from the giant and knocked [[../../Conditions/Prone|prone]]."
cr: 13
perception: 19
languages: Common, Giant
senses: —
immune: lightning, thunder
stats: ['+14', '+2', '+10', '+3', '+9', '+9']
actions:
  - name: Multiattack.
    desc: "The giant makes three Greatsword attacks, or it makes four Lightning Bolt attacks."
  - name: Greatsword.
    desc: "*Melee Weapon Attack:* +14 to hit, reach 10 ft., one target.  *Hit:* 30 (6d6 + 9) slashing damage."
  - name: Lightning Bolt.
    desc: "*Ranged Spell Attack:* +9 to hit, range 150 ft., one target.  *Hit:* 22 (4d8 + 4) lightning damage. If the giant scores a critical hit, the target must succeed on a DC 17 CON save or be [[../../Conditions/Paralyzed|paralyzed]] until the end of its next turn."
  - name: Thunderous Strike (Recharge 5–6).
    desc: "The giant hurls a magical lightning bolt at a point it can see within 500 feet of it. Each creature within 10 feet of that point must make a DC 17 DEX save. On a failure, a creature takes 36 (8d8) lightning damage and 21 (6d6) thunder damage and is [[../../Conditions/Stunned|stunned]] until the end of its next turn. On a success, a creature takes half the damage and isn’t stunned."
ac: 16 (scale mail)
size: Huge
speed: 50 ft., swim 50 ft.
type: Giant
hp: 243
resistant: cold | Giant Attributes
traits:
  - name: Amphibious.
    desc: "The giant can breathe air and water."
  - name: Giant Attributes.
    desc: "The giant is resistant to the stunned condition, and it is vulnerable to the prone condition."
  - name: Influence Weather.
    desc: "Nearby weather responds to the storm giant’s desires. At the start of each minute, the storm giant can choose to change the precipitation, temperature, and wind within 3 miles of it by one stage, up or down (no action required). This effect works like the changing weather conditions aspect of the *[[../Rituals/Control Weather|control weather]]* spell, except the conditions change immediately and the storm giant can’t change the temperature by more than one stage up or down from the area’s standard temperature."
  - name: Stormsight.
    desc: "The storm giant can see through areas obscured by clouds, fog, rain, snow, and storms without penalty."
  - name: Updraft.
    desc: "While in an area open to the sky, the storm giant has a flying speed of 30 feet."
stealth: 12
name: Storm Giant
vulnerable: Giant Attributes
```

#cr13 #giant #huge
