# Statblock

```statblock
layout: Basic 5e Layout
image: [[Delerium Elemental BGR PNG.png]]
name: Deleruim Elemental
size: Large
type: [[Elemental]]
alignment: Unaligned
ac: 12 + the spell's level
hp: 60 + 10 for each spell level above 5th
speed: 40 ft., Burrow 40 ft. (walking geode only), Fly 60 ft. (living haze only), Swim 40 ft. (animated sludge only)
stats: [19, 14, 18, 5, 11, 7]
damage_resistances: Necrotic, Poison
condition_immunities: [[Contamination]], [[Exhaustion]], [[Paralyzed]], [[Petrified]], [[Poisoned]], [[Unconscious]]
senses: [[Darkvision]] 60Ft, Passive Perception 12, Passive Insight 7, Passive Stealth 12
languages: Understands the Languages you Speak
cr: none
traits: 
  - name: Amorphous Form (Animated Sludge, Entropic Flame, and Living Haze).
    desc: The delerium elemental can move through a space as narrow as 1 inch wide without squeezing.
  - name: Deep Haze (Living Haze Only).
    desc: The delerium elemental can enter a hostile creature's space and stop there. A creature who enters or starts its turn in the same space as the delerium elemental must make a Constitution saving throw. It takes 7 (2d6) necrotic damage on a failed saving throw.    
actions:
  - name: "Multiattack"
    desc: "The delerium elemental makes a number of slam or hurl flame attacks equal to half this spell's level (rounded down)."
  - name: "Slam"
    desc: "_Melee Weapon Attack:_ your spell attack modifier to hit, reach 5 ft., one target. _Hit:_ 1d10 + 4 + the spell's level bludgeoning damage."
  - name: "Hurl Flame (Entropic Flame Only)."
    desc: "_Ranged Weapon Attack:_ your spell attack modifier to hit, range 120 ft., one target. _Hit:_ 1d10 + 2 + the spell's level fire damage. Before or after making this attack, the delerium elemental can teleport up to 10 feet to an unoccupied space it can see."
  - name: "Grasping Tide (Animated Sludge Only)."
    desc: "_Melee Weapon Attack:_ your spell attack modifier to hit, reach 5 ft., one creature. _Hit:_ 2d8 + 4 + the spell's level bludgeoning damage, and the target is grappled (escape DC 16)."
  - name: "Shard Slam (Walking Geode Only)."
    desc: "A creature hit by the delerium elemental's melee attacks must make a Strength saving throw. On a failed saving throw, it is pushed 10 feet away from the delerium elemental."           
```