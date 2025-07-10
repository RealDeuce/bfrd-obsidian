
```statblock
layout: Basic ToV Layout
ac: 17 (natural armor)
size: Large
speed: 40 ft., fly 60 ft.
stats: ['+6', '+1', '+7', '+7', '+6', '+7']
actions:
  - name: Multiattack.
    desc: "The efreeti makes three Scimitar or Hurl Flame attacks."
  - name: Scimitar.
    desc: "*Melee Weapon Attack:* +10 to hit, reach 5 ft., one target.  *Hit:* 13 (2d6 + 6) slashing damage plus 10 (3d6) fire damage."
  - name: Hurl Flame.
    desc: "*Ranged Spell Attack:* +7 to hit, range 120 ft., one target.  *Hit:* 24 (6d6 + 3) fire damage."
  - name: Create Fire Elemental (1/Day).
    desc: "The efreeti magically creates one fire-based Elemental of CR 5 or lower in an unoccupied space the efreeti can see within 30 feet of it. The elemental acts as an ally of the efreeti, obeying its spoken commands. The elemental remains for 1 hour, until the efreeti dies, or until the efreeti dismisses it as a bonus action."
  - name: Travel the Planes (1/Day).
    desc: "The efreeti transports itself to a different plane of existence. This works like the *[[../Spells/Plane Shift|plane shift]]* spell, except it can affect only itself and can’t use this action to banish an unwilling creature."
name: Efreeti
hp: 223
subtype: Outsider
type: Elemental
stealth: 11
bonus_actions:
  - name: Blazing Palisade.
    desc: "The efreeti magically creates a translucent wall of fire along a solid surface at a point it can see within 30 feet of it. The wall can be up to 1 foot thick, up to 45 feet long, and up to 5 feet high, and it can be any shape. Each creature in a space where the fire appears must succeed on a DC 15 DEX save or take 7 (2d6) fire damage. A creature that successfully saves can move to the wall’s edge, out of the fire. A creature that enters the wall for the first time on a turn or ends its turn within 5 feet of the wall must succeed on a DC 15 DEX save or take 7 (2d6) fire damage. The efreeti can have only one fire wall active at a time. If it creates another, the previous fire wall disappears."
  - name: Genie Shape.
    desc: "The efreeti magically transforms into a Medium cloud of thick smoke filled with sparks of fire or back into its bipedal form. Its statistics are the same in each form. Any equipment it is wearing or carrying transforms with it. It reverts to its bipedal form if it dies. The efreeti can’t use this bonus action to transform into its bipedal form while inside a Medium or smaller container."
traits:
  - name: Nebulous (Cloud Form Only).
    desc: "The efreeti’s Stealth is 16, it can hover while flying, can’t manipulate objects or attack, and it can pass through any space air can pass through without squeezing. In addition, it can enter and hide in any Tiny or larger container, such as a pouch, lamp, backpack, or barrel."
cr: 11
senses: darkvision 120 ft.
languages: Common, Ignan
immune: fire
perception: 16
```

#cr11 #elemental #large #outsider
