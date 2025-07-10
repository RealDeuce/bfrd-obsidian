
```statblock
layout: Basic ToV Layout
reactions:
  - name: Shimmering Shield.
    desc: "When a creature the unicorn can see within 30 feet of it, including the unicorn, is attacked, the unicorn can surround it with a shimmering shield of radiant light. The target adds 3 to its AC against the attack."
cr: 5
legendary_description: The unicorn can take 3 legendary actions, choosing from the options below. Only one legendary action option can be used at a time and only at the end of another creature’s turn. The unicorn regains spent legendary actions at the start of its turn.
perception: 16
immune: poison | charmed, frightened, paralyzed, poisoned
languages: Celestial, Elvish, Sylvan, telepathy 60 ft.
senses: darkvision 60 ft.
actions:
  - name: Multiattack.
    desc: "The unicorn makes one Hooves attack and one Horn attack, or it makes two Horn Bolt attacks."
  - name: Hooves.
    desc: "*Melee Weapon Attack:* +7 to hit, reach 5 ft., one target.  *Hit:* 11 (2d6 + 4) bludgeoning damage."
  - name: Horn.
    desc: "*Melee Weapon Attack:* +7 to hit, reach 5 ft., one target.  *Hit:* 8 (1d8 + 4) piercing damage plus 10 (3d6) radiant damage."
  - name: Horn Bolt.
    desc: "*Ranged Spell Attack:* +6 to hit, range 60 ft., one target.  *Hit:* 13 (3d6 + 3) radiant damage."
  - name: Unicorn Magic.
    desc: "The unicorn can cast the *[[../Spells/Dancing Lights|dancing lights]]* and *[[../Spells/Druidcraft|druidcraft]]* cantrips at will, requiring no material components and using WIS as the spellcasting ability."
  - name: Healing Touch (3/Day).
    desc: "The unicorn touches another creature with its horn. The target magically regains 11 (2d8 + 2) HP and is freed from all curses, diseases, and poisons afflicting it."
stats: ['+4', '+2', '+2', '+0', '+6', '+6']
speed: 50 ft.
ac: 12
size: Large
traits:
  - name: Celestial Resilience.
    desc: "The unicorn is resistant to radiant damage."
  - name: Magic Resistance.
    desc: "The unicorn has advantage on saves against spells and other magical effects."
  - name: Magic Weapons.
    desc: "The unicorn’s weapon attacks are magical."
  - name: Sense the Unnatural.
    desc: "The unicorn can pinpoint the location of Aberrations and Undead within 60 feet of it."
  - name: Speak with Beasts and Plants.
    desc: "The unicorn can communicate with Beasts and Plants as if they shared a language."
  - name: Woodland Walk.
    desc: "Difficult terrain composed of nonmagical plants doesn’t cost the unicorn extra movement. In addition, the unicorn can pass through nonmagical plants without being slowed by them and without taking damage from them if they have thorns, spines, or a similar hazard."
legendary_actions:
  - name: Canter.
    desc: "The unicorn moves up to half is speed without provoking opportunity attacks."
  - name: Radiant Stomp (Costs 2 Actions).
    desc: "The unicorn raises its hooves glowing with golden light and brings them down with a reverberating stomp. Each hostile creature within 10 feet of the unicorn must make a DC 14 STR save. On a failure, a creature takes 10 (3d6) radiant damage and is knocked [[../../Conditions/Prone|prone]]. On a success, a creature takes half the damage and isn’t knocked prone."
  - name: Heal Self (Costs 3 Actions).
    desc: "The unicorn magically regains 11 (2d8 + 2) HP."
resistant: Celestial Resilience
stealth: 12
type: Celestial
hp: 92
name: Unicorn
```

#celestial #cr5 #large
