
```statblock
layout: Basic ToV Layout
stats: ['−2', '+4', '+3', '+1', '+2', '+2']
actions:
  - name: Multiattack.
    desc: "The wraith makes two Life Drain attacks."
  - name: Life Drain.
    desc: "*Melee Weapon Attack:* +7 to hit, reach 5 ft., one creature.  *Hit:* 18 (4d6 + 4) necrotic damage. The target must succeed on a DC 15 CON save or its HP maximum is reduced by an amount equal to the damage taken. This reduction lasts until the target finishes a long rest. The target dies if this effect reduces its HP maximum to 0."
  - name: Create Specter.
    desc: "The wraith targets one Humanoid it can see within 10 feet of it that has been dead for no longer than 1 minute and died violently. The target’s spirit rises as a **[[Specter|specter]]** in the space of its corpse or in the nearest unoccupied space. The specter is under the wraith’s control. The wraith can have no more than seven specters under its control at one time."
ac: 14
size: Medium
speed: 0 ft., fly 60 ft. (hover)
hp: 85
type: Undead
bonus_actions:
  - name: Trail of Death (Recharge 4–6).
    desc: "The wraith moves up to 30 feet in a straight line. This distance is not reduced by moving through creatures or objects, and this movement doesn’t provoke opportunity attacks. The first time it enters a creature’s space during this move, that creature must succeed on a DC 15 DEX save or be afflicted with wasting doom. While afflicted with wasting doom, a creature takes 3 (1d6) necrotic damage at the start of each of its turns. Wasting doom ends if a creature starts its turn in sunlight or regains HP."
resistant: acid, cold, fire, lightning, thunder; bludgeoning, piercing, and slashing damage from nonmagical attacks
traits:
  - name: Incorporeal Movement.
    desc: "The wraith can move through other"
  - name: creatures and objects as if they were difficult terrain.
    desc: "It takes 5 (1d10) force damage if it ends its turn inside an object."
  - name: Sunlight Sensitivity.
    desc: "While in sunlight, the wraith has disadvantage on attack rolls, and its Perception is 7 when perceiving by sight."
  - name: Undead Nature.
    desc: "The wraith doesn’t require air, food, drink, or sleep."
  - name: Undead Resilience.
    desc: "The wraith is immune to poison damage, to exhaustion, and to the poisoned condition."
stealth: 17
name: Wraith
vulnerable: radiant
reactions:
  - name: Unravel Life.
    desc: "When a creature the wraith can see within 30 feet of it and that isn’t a Construct or Undead regains HP, the wraith can corrupt the healing energies, halving the amount of healing that creature receives."
cr: 5
perception: 12
languages: the languages it knew in life
senses: darkvision 60 ft.
immune: necrotic | charmed, grappled, paralyzed, petrified, prone, restrained | Undead Resilience
```

#cr5 #medium #undead
