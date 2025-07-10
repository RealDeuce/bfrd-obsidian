
```statblock
layout: Basic ToV Layout
hp: 138
type: Fiend
stealth: 12
bonus_actions:
  - name: Animate Chains.
    desc: "The chain devil commands chains it can see within 60 feet of it that aren’t being worn or carried to grab up to two creatures it can see within 10 feet of at least one commanded chain. Each creature must succeed on a DC 15 DEX save or be [[../../Conditions/Restrained|restrained]]. A creature, including the restrained creature, can take its action to free the restrained creature by succeeding on a DC 15 STR check.\n\nThe devil can have up to two creatures restrained in this way at a time. If it uses this bonus action to restrain a third, the effect ends on one of the previous targets (the devil’s choice)."
traits:
  - name: Devil’s Sight.
    desc: "Magical darkness doesn’t impede the devil’s darkvision."
  - name: Devilish Resilience.
    desc: "The devil is resistant to cold damage and to bludgeoning, piercing, and slashing damage from nonmagical attacks. In addition, it is immune to fire damage and poison damage and to the poisoned condition."
  - name: Magic Resistance.
    desc: "The devil has advantage on saves against spells and other magical effects."
resistant: grappled | Devilish Resilience
name: Chain Devil
stats: ['+4', '+2', '+7', '+0', '+4', '+5']
actions:
  - name: Multiattack.
    desc: "The devil makes four Chain attacks."
  - name: Chain.
    desc: "*Melee Weapon Attack:* +7 to hit, reach 10 ft., one target.  *Hit:* 8 (1d8 + 4) slashing damage plus 7 (2d6) piercing damage, and the target is [[../../Conditions/Grappled|grappled]] (escape DC 15). Until the grapple ends, the target is [[../../Conditions/Restrained|restrained]] and takes 14 (4d6) piercing damage at the start of each of its turns, and the chain devil can’t use the same Chain on another target."
subtype: Outsider, Devil
ac: 16 (natural armor)
size: Medium
speed: 30 ft.
perception: 14
senses: darkvision 120 ft.
languages: Infernal, telepathy 120 ft.
immune: Devilish Resilience
reactions:
  - name: Unnerving Mask.
    desc: "When a creature the devil can see starts its turn within 30 feet of the devil, the devil can command its mask to shift to look like one of the creature’s departed loved ones or bitter enemies. If the creature can see the mask, it must succeed on a DC 15 WIS save or be [[../../Conditions/Frightened|frightened]] until the end of its turn."
cr: 8
```

#cr8 #devil #fiend #medium #outsider
