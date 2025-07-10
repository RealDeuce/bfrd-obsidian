
```statblock
layout: Basic ToV Layout
cr: 13
perception: 17
legendary_description: The vampire can take 3 legendary actions, choosing from the options below. Only one legendary action option can be used at a time and only at the end of another creature’s turn. The vampire regains spent legendary actions at the start of its turn.
senses: darkvision 120 ft.
languages: the languages it knew in life
immune: Vampiric Resilience
stats: ['+4', '+9', '+4', '+3', '+7', '+9']
actions:
  - name: Multiattack.
    desc: "The vampire can use Charm. It then makes three Bite or Claw attacks. It can replace one attack with a Draining Bite attack. If two Claw attacks hit one Large or smaller creature, the target is [[../../Conditions/Grappled|grappled]] (escape DC 17)."
  - name: Bite (Bat, Rat, or Wolf Form Only).
    desc: "*Melee Weapon Attack:* +9 to hit, reach 5 ft., one target.  *Hit:* 11 (2d6 + 4) piercing damage plus 14 (4d6) necrotic damage."
  - name: Claw (Vampire Form Only).
    desc: "*Melee Weapon Attack:* +9 to hit, reach 5 ft., one target.  *Hit:* 11 (2d6 + 4) slashing damage plus 14 (4d6) necrotic damage."
  - name: Draining Bite (Bat or Vampire Form Only).
    desc: "*Melee Weapon Attack:* +9 to hit, reach 5 ft., one willing creature, or a creature that is grappled by the vampire, incapacitated, or restrained.  *Hit:* 9 (2d4 + 4) piercing damage plus 14 (4d6) necrotic damage. The target’s HP maximum is reduced by an amount equal to the necrotic damage taken, and the vampire regains HP equal to that amount. The reduction lasts until the target finishes a long rest. The target dies if this effect reduces its HP maximum to 0. A Humanoid slain in this way and then fed at least one drop of the vampire’s blood rises the following night as a **[[Vampire Spawn|vampire spawn]]** under the vampire’s control."
  - name: Charm (Vampire Form Only).
    desc: "One Humanoid the vampire can see within 30 feet of it must succeed on a DC 17 WIS save or be magically [[../../Conditions/Charmed|charmed]] for 1 day, until the vampire dies, or until the vampire takes a bonus action to end the effect. The charmed target obeys the vampire’s verbal commands and is a willing target for the vampire’s Draining Bite attack. If the target suffers any harm or receives a suicidal command, it can repeat the save, ending the effect on itself on a success.   The vampire can have up to two creatures charmed in this way at a time. If it charms a third, the effect on the first target ends."
  - name: Children of the Night.
    desc: "The vampire magically calls 2d4 **[[Bat, Swarm of Bats|swarms of bats]]** or **[[Rat, Swarm of Rats|rats]]**, provided that the sun isn’t up. While outdoors, the vampire can call 3d6 **[[Wolf|wolves]]** instead. The called creatures arrive in 1d4 rounds, acting as allies of the vampire and obeying its spoken commands. The Beasts remain for 1 hour, until the vampire dies, or until the vampire dismisses them as a bonus action. The vampire can have any number of such Beasts under its control at one time, provided the combined total CR of the Beasts is no higher than 4."
ac: 16 (natural armor)
size: Medium
speed: 30 ft., climb 30 ft. (40 ft. in wolf form, fly 30 ft. in bat form, swim 20 ft. in rat form)
hp: 177
type: Undead
stealth: 19
bonus_actions:
  - name: Change Shape.
    desc: "The vampire transforms into a Tiny bat, Tiny rat, Medium wolf, or back into its true form, which is Undead. Its statistics, other than its size and speed, are the same in each form. Any equipment it is wearing transforms with it, but anything it is carrying doesn’t transform with it. It reverts to its true form if it dies."
  - name: Mist Form.
    desc: "The vampire transforms into a Medium cloud of mist or back into its true form, which is Undead. While in mist form, it can’t take any actions, speak, or manipulate objects. It is weightless, has a flying speed of 20 feet, can hover, and can enter a hostile creature’s space and stop there. In addition, if air can pass through a space, the mist can do so without squeezing, and it can’t pass through water. It has advantage on STR, DEX, and CON saves, and it is immune to all nonmagical damage, except the damage it takes from sunlight."
legendary_actions:
  - name: Move.
    desc: "The vampire moves up to its speed without provoking opportunity attacks."
  - name: Call Children (Costs 2 Actions).
    desc: "The vampire uses Children of the Night."
  - name: Excessive Bleeding (Costs 2 Actions).
    desc: "Each creature within 15 feet of the vampire that doesn’t have all its HP must succeed on a DC 17 CON save or lose 14 (4d6) HP as its wounds bleed profusely. Before the end of its next turn, the vampire has advantage on the next attack roll it makes against a creature that failed this save."
traits:
  - name: Hungry Dead Nature.
    desc: "The vampire doesn’t require air or sleep. In addition, it must consume at least 80 ounces of blood (approximately half the blood in a Medium Humanoid’s body) every 24 hours, or it loses its immunity to exhaustion and risks starvation until it does so. While it has any levels of exhaustion from starvation, the vampire can’t remove levels of exhaustion until it consumes at least 160 ounces of blood."
  - name: Legendary Resistance (3/Day).
    desc: "If the vampire fails a save, it can choose to succeed instead."
  - name: Misty Escape.
    desc: "When it drops to 0 HP outside its resting place, the vampire transforms into a cloud of mist (as in the Mist Form bonus action) instead of falling unconscious, provided it isn’t in sunlight or running water. If it can’t transform, it is destroyed. While it has 0 HP in mist form, it can’t revert to its vampire form, and it must reach its resting place within 2 hours or be destroyed. Once in its resting place, it reverts to its vampire form. It is then [[../../Conditions/Paralyzed|paralyzed]] until it regains at least 1 HP. After spending 1 hour in its resting place with 0 HP, it regains 1 HP."
  - name: Regeneration.
    desc: "The vampire regains 20 HP at the start of its turn if it has at least 1 HP and isn’t in sunlight or running water. If the vampire takes radiant damage or damage from holy water, this trait doesn’t function at the start of the vampire’s next turn."
  - name: Resting Place.
    desc: "The vampire has a coffin, grave, sarcophagus, or similar location just large enough for it to lie down designated as its resting place. While in its resting place, the vampire doesn’t suffer exhaustion levels from starvation and has keensense out to a range of 120 feet."
  - name: Spider Climb.
    desc: "The vampire can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check."
  - name: Vampire Weaknesses.
    desc: "The vampire has the following flaws:  \n*Forbiddance.* The vampire can’t enter a residence without an invitation from one of the occupants.  \n*Harmed by Running Water.* The vampire takes 20 acid  damage if it ends its turn in running water.  \n*Stake to the Heart.* If a piercing weapon made of wood  is driven into the vampire’s heart while the vampire is [[../../Conditions/Incapacitated|incapacitated]] in its resting place, the vampire is [[../../Conditions/Paralyzed|paralyzed]] until the stake is removed.  \n*Sunlight Hypersensitivity.* The vampire takes 20 radiant  damage when it starts its turn in sunlight. While in sunlight,  it has disadvantage on attack rolls and ability checks."
  - name: Vampiric Resilience.
    desc: "The vampire is immune to exhaustion."
resistant: necrotic; bludgeoning, piercing, and slashing damage from nonmagical attacks | charmed
subtype: Shapechanger
name: Vampire
```

#cr13 #medium #shapechanger #undead
