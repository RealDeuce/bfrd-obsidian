
```statblock
layout: Basic ToV Layout
cr: 4
senses: darkvision 60 ft.
languages: any languages it knew in life
immune: cold, necrotic | charmed, frightened, grappled, paralyzed, petrified, prone, restrained | Undead Resilience
perception: 13
ac: 12
size: Medium
speed: 0 ft., fly 40 ft. (hover)
stats: ['−2', '+2', '+0', '+0', '+3', '+4']
actions:
  - name: Multiattack.
    desc: "The ghost makes two Withering Touch or Telekinetic Throw attacks."
  - name: Withering Touch.
    desc: "*Melee Spell Attack:* +6 to hit, reach 5 ft., one target.  *Hit:* 18 (4d6 + 4) necrotic damage."
  - name: Telekinetic Throw.
    desc: "*Ranged Weapon Attack:* +4 to hit, range 20/60 ft., one target.  *Hit:* 17 (6d4 + 2) bludgeoning, piercing, or slashing damage, depending on the type of object thrown. The ghost can throw only Small or smaller objects within range that aren’t being worn or carried."
  - name: Horrify (Recharge 5–6).
    desc: "The ghost speaks a haunting phrase, reveals the wounds from its death, or performs some other expression to scare creatures in a 30-foot cone. Each creature in that area must make a DC 14 WIS save. On a failure, a creature takes 21 (6d6) psychic damage and is [[../../Conditions/Frightened|frightened]] until the end of its next turn. On a success, a creature takes half the damage and isn’t frightened. A creature that fails the save by 5 or more increases its age in years by 10 percent, rounded up. This aging can be reversed with a *[[../Spells/Greater Restoration|greater restoration]]* spell or similar magic, but only within 24 hours of the aging occurring."
name: Ghost
type: Undead
hp: 68
stealth: 11
bonus_actions:
  - name: Etherealness.
    desc: "The ghost enters the Ethereal Plane from the Material Plane, or vice versa. It is visible on the Material Plane while it is in the Ethereal Plane, and vice versa, yet it can’t affect or be affected by anything on the other plane."
resistant: acid, fire, lightning, thunder; bludgeoning, piercing, and slashing from nonmagical attacks
traits:
  - name: Ethereal Sight.
    desc: "The ghost can see 60 feet into the Ethereal Plane when it is on the Material Plane, and vice versa."
  - name: Incorporeal Movement.
    desc: "The ghost can move through other creatures and objects as if they were difficult terrain. It takes 5 (1d10) force damage if it ends its turn inside an object."
  - name: Undead Nature.
    desc: "The ghost doesn’t require air, food, drink, or sleep."
  - name: Undead Resilience.
    desc: "The ghost is immune to poison damage, to exhaustion, and to the poisoned condition."
  - name: Unfinished Business.
    desc: "Unless its unfinished business is fulfilled, a destroyed ghost returns in 1d4 days, regaining all its HP and becoming active again within 10 feet of where it died. If presented with an object or piece of information related to its unfinished business, the ghost must succeed on a DC 13 WIS save or be [[../../Conditions/Incapacitated|incapacitated]] until the end of its next turn. After it has been incapacitated by a particular source, the ghost can’t be incapacitated by that same source again for 24 hours. If presented with everything it needs to complete its unfinished business, the ghost permanently dies after completing it."
```

#cr4 #medium #undead
