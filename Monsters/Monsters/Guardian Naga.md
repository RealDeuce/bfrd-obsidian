
```statblock
layout: Basic ToV Layout
perception: 18
senses: darkvision 60 ft.
languages: Abyssal, Celestial, Common, Infernal
immune: poison | charmed, poisoned
cr: 10
type: Monstrosity
hp: 176
stealth: 18
traits:
  - name: Divine Strikes.
    desc: "The naga’s weapon attacks are magical. When the naga hits with any weapon attack, the weapon deals an extra 3d8 necrotic damage or radiant damage (included in the attack), the naga’s choice."
  - name: Monstrosity Resilience.
    desc: "The naga is resistant to exhaustion and to the frightened condition."
  - name: Rejuvenation.
    desc: "If it dies, the naga returns to life in 1d6 days, regaining all its HP and becoming active again. Only a wish spell can prevent this trait from functioning."
bonus_actions:
  - name: Protector’s Step.
    desc: "The naga magically teleports, along with any equipment it is wearing or carrying, up to 120 feet to an unoccupied space within the sacred site or temple it protects or within 30 feet of the exterior of such a site. Swirls of golden light or tendrils of inky shadow (the naga’s choice) appear at the origin and destination when it uses this bonus action."
resistant: necrotic, radiant | Monstrosity Resilience
name: Guardian Naga
stats: ['+4', '+8', '+7', '+7', '+8', '+8']
actions:
  - name: Multiattack.
    desc: "The guardian naga makes three Slam or Spit Poison attacks, or it makes one Constrict attack and two Slam attacks. It can replace one attack with a use of Spellcasting."
  - name: Constrict.
    desc: "*Melee Weapon Attack:* +8 to hit, reach 10 ft., one target.  *Hit:* 8 (1d8 + 4) bludgeoning damage plus 13 (3d8) necrotic damage or radiant damage (the naga’s choice), and the target is [[../../Conditions/Grappled|grappled]] (escape DC 16) if it is a Large or smaller creature. Until this grapple ends, the target is [[../../Conditions/Restrained|restrained]], and the naga can’t Constrict another target."
  - name: Slam.
    desc: "*Melee Weapon Attack:* +8 to hit, reach 5 ft., one target.  *Hit:* 11 (2d6 + 4) bludgeoning damage plus 13 (3d8) necrotic damage or radiant damage (the naga’s choice)."
  - name: Spit Poison.
    desc: "*Ranged Weapon Attack:* +8 to hit, range 20/60 ft., one target.  *Hit:* 11 (2d6 + 4) poison damage plus 13 (3d8) necrotic damage or radiant damage (the naga’s choice)."
  - name: Spellcasting.
    desc: "The guardian naga casts one of the following spells, requiring only verbal components and using WIS as the spellcasting ability (spell save DC 16).  \nAt will: *[[../Rituals/Augury|Augury]]* (as an action), *[[../Spells/Command|command]], [[../Spells/Mending|mending]], [[../Spells/Thaumaturgy|thaumaturgy]]*  \n3/day each: *[[../Spells/Bestow Curse|bestow curse]], [[../Spells/Cure Wounds|cure wounds]]*  \n2/day each: *[[../Spells/Freedom of Movement|freedom of movement]], [[../Spells/Hold|hold]]*  \n1/day: *[[../Rituals/Geas|Geas]]* (as an action)"
ac: 18 (natural armor)
size: Large
speed: 40 ft.
```

#cr10 #large #monstrosity
