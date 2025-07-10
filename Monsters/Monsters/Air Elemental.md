
```statblock
layout: Basic ToV Layout
actions:
  - name: Multiattack.
    desc: "The elemental makes two Wind Lash or Lightning Bolt attacks."
  - name: Wind Lash.
    desc: "*Melee Weapon Attack:* +8 to hit, reach 5 ft., one target.  *Hit:* 18 (3d8 + 5) bludgeoning damage."
  - name: Lightning Bolt.
    desc: "*Ranged Weapon Attack:* +8 to hit, range 30/120 ft., one target.  *Hit:* 18 (3d8 + 5) lightning damage."
  - name: Whirlwind (Recharge 4–6).
    desc: "Each creature in the elemental’s space must make a DC 13 STR save. On a failure, a target takes 18 (3d8 + 5) bludgeoning damage and is flung up 20 feet away from the elemental in a random direction and knocked [[../../Conditions/Prone|prone]]. If a thrown target strikes an object, such as a wall or floor, the target takes 3 (1d6) bludgeoning damage for every 10 feet it was thrown. If the target is thrown at another creature, that creature must succeed on a DC 13 DEX save or take the same damage and be knocked [[../../Conditions/Prone|prone]].\n\nIf the save is successful, the target takes half the bludgeoning damage and isn’t flung away or knocked prone."
stats: ['+2', '+5', '+2', '−2', '+0', '−2']
speed: 0 ft., fly 90 ft. (hover)
ac: 15
size: Large
stealth: 15
traits:
  - name: Air Form.
    desc: "The elemental can enter a hostile creature’s space and stop there. It can move through a space as narrow as 1 inch wide without squeezing."
  - name: Cloud Camouflage.
    desc: "The elemental’s Stealth is 20 while in clouds, fog, or windy weather."
  - name: Elemental Nature.
    desc: "The elemental doesn’t require air, food, drink, or sleep."
  - name: Elemental Resilience.
    desc: "The elemental is resistant to bludgeoning, piercing, and slashing damage from nonmagical attacks. In addition, it is immune to poison damage, to exhaustion, and to the grappled, paralyzed, petrified, poisoned, prone, restrained, and unconscious conditions."
resistant: thunder | Elemental Resilience
type: Elemental
hp: 94
name: Air Elemental
reactions:
  - name: Thunderous Retreat.
    desc: "When a creature the air elemental can see deals damage to it, the elemental can expel a crack of thunder and move up to 15 feet to an unoccupied space it can see. Each creature within 5 feet of the space the elemental left must succeed on a DC 13 CON save or take 7 (2d6) thunder damage."
cr: 5
perception: 13
immune: lightning | Elemental Resilience
senses: darkvision 60 ft.
languages: Auran
```

#cr5 #elemental #large
