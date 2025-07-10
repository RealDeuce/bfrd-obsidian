
```statblock
layout: Basic ToV Layout
type: Undead
hp: 91
bonus_actions:
  - name: Call Blood.
    desc: "The vampire calls to the blood within one injured creature it can see within 10 feet of it, causing blood to pour from the creature’s wounds. If the target doesn’t have all its HP, it must make a DC 14 CON save, losing 7 (2d6) HP on a failed save, or losing half as much HP on a successful one. Before the end of its next turn, the vampire has advantage on the next attack roll it makes against a creature that failed the save."
resistant: necrotic; bludgeoning, piercing, and slashing damage from nonmagical attacks
traits:
  - name: Hungry Dead Nature.
    desc: "The vampire spawn doesn’t require air or sleep. In addition, it must consume at least 80 ounces of blood (approximately half the blood in a Medium Humanoid’s body) every 24 hours, or it loses its immunity to exhaustion and risks starvation until it does so. While it has any levels of exhaustion from starvation, the vampire can’t remove levels of exhaustion until it consumes at least 160 ounces of blood."
  - name: Regeneration.
    desc: "The vampire spawn regains 10 HP at the start of its turn if it has at least 1 HP and isn’t in sunlight or running water. If the vampire takes radiant damage or damage from holy water, this trait doesn’t function at the start of the vampire’s next turn."
  - name: Resting Place.
    desc: "When it drops to 0 HP outside its resting place, the vampire spawn transforms into a cloud of mist (as in the Mist Form bonus action) instead of falling unconscious, provided it isn’t in sunlight or running water. If it can’t transform, it is destroyed. While it has 0 HP in mist form, it can’t revert to its vampire form, and it must reach its resting place within 2 hours or be destroyed. Once in its resting place, it reverts to its vampire form. It is then [[../../Conditions/Paralyzed|paralyzed]] until it regains at least 1 HP. After spending 1 hour in its resting place with 0 HP, it regains 1 HP."
  - name: Spider Climb.
    desc: "The vampire spawn can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check."
  - name: Vampire Weaknesses.
    desc: "The vampire has the following flaws:  \n*Forbiddance.* The vampire can’t enter a residence without an invitation from one of the occupants.  \n*Harmed by Running Water.* The vampire takes 20 acid  damage if it ends its turn in running water.  \n*Stake to the Heart.* If a piercing weapon made of wood  is driven into the vampire’s heart while the vampire is [[../../Conditions/Incapacitated|incapacitated]] in its resting place, the vampire is [[../../Conditions/Paralyzed|paralyzed]] until the stake is removed.  \n*Sunlight Hypersensitivity.* The vampire takes 20 radiant  damage when it starts its turn in sunlight. While in sunlight,  it has disadvantage on attack rolls and ability checks."
  - name: Vampiric Resilience.
    desc: "The vampire is immune to exhaustion."
stealth: 16
name: Vampire Spawn
stats: ['+3', '+6', '+3', '+0', '+3', '+1']
actions:
  - name: Multiattack.
    desc: "The vampire spawn makes two Claw attacks. It can replace one attack with a Draining Bite attack. If both Claw attacks hit one Large or smaller creature, the target is [[../../Conditions/Grappled|grappled]] (escape DC 14)."
  - name: Claw.
    desc: "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one creature.  *Hit:* 8 (2d4 + 3) slashing damage plus 10 (3d6) necrotic damage."
  - name: Draining Bite.
    desc: "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one willing creature, or a creature that is grappled by the vampire, incapacitated, or restrained.  *Hit:* 8 (2d4 + 3) piercing damage plus 10 (3d6) necrotic damage. The target’s HP maximum is reduced by an amount equal to the necrotic damage taken, and the vampire regains HP equal to that amount. The reduction lasts until the target finishes a long rest. The target dies if this effect reduces its HP maximum to 0."
ac: 15 (natural armor)
size: Medium
speed: 30 ft., climb 30 ft.
perception: 13
languages: the languages it knew in life
senses: darkvision 60 ft.
immune: Vampiric Resilience
cr: 5
```

#cr5 #medium #undead
