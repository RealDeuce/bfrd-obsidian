
```statblock
layout: Basic ToV Layout
stats: ['−4', '+4', '+0', '−5', '+0', '−1']
actions:
  - name: Feeding Paddles.
    desc: "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one creature.  *Hit:* 5 (1d6 + 2) necrotic damage. The crimson jelly gains temporary HP equal to the necrotic damage dealt, and it attaches to the target. If the jelly had advantage on this attack, it attaches to the target’s face, leaving the target unable to breathe or speak while the jelly is attached.\n\nWhile attached, the crimson jelly can use only the Feeding Paddles action, and it moves with the target whenever the target moves, requiring none of the jelly’s movement. The Crimson jelly can detach itself by spending 5 feet of its movement. A creature, including the target, can take its action to detach the jelly by succeeding on a DC 12 STR check."
ac: 12
size: Tiny
speed: 0 ft., fly 60 ft. (hover), swim 30 ft.
hp: 20
type: Ooze
bonus_actions:
  - name: Reproduce (Requires Temporary HP).
    desc: "While the crimson jelly has 1 or more temporary HP, it can split part of itself off into a new crimson jelly with HP equal to the original crimson jelly’s temporary HP. The original crimson jelly then loses any temporary HP it has. The new crimson jelly otherwise has all the same statistics as its parent, except the new jelly can’t gain temporary HP from Feeding Paddles attacks until it finishes a long rest."
traits:
  - name: Amorphous.
    desc: "The crimson jelly can move through space as narrow as 1 inch wide without squeezing."
  - name: Blood Sense.
    desc: "The crimson jelly can pinpoint, by scent, the location of creatures that aren’t Constructs or Undead and that don’t have all of their HP within 60 feet of it and can sense the general direction of such creatures within 1 mile of it."
  - name: Ooze Nature.
    desc: "The crimson jelly doesn’t require sleep."
  - name: Ooze Resilience.
    desc: "The crimson jelly is resistant to the restrained condition, and it is immune to exhaustion and to the blinded, charmed, deafened, frightened, and prone conditions."
  - name: Tainted Attacks.
    desc: "A creature that is reduced to 0 HP by a crimson jelly must succeed on a DC 9 CHA save or suffer one level of [[../../Conditions/Exhaustion|exhaustion]]. While a creature suffers from this exhaustion, it loses most of its memories aside from basic information about itself, such as its name and its capabilities, and it is wracked with nightmarish visions that include a crimson rune."
  - name: Transparent.
    desc: "While in an area of dim or bright light, the crimson jelly is [[../../Conditions/Invisible|invisible]]. While in darkness, creatures without darkvision can see the jelly’s faint crimson glow."
resistant: Ooze Resilience
stealth: 14
name: Crimson Jelly
cr: 1/2
perception: 10
languages: —
senses: keensense 10 ft. (can’t sense beyond this radius)
immune: necrotic | grappled | Ooze Resilience
```

#cr1-2 #ooze #tiny
