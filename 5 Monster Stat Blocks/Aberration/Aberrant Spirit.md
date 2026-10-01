---
layout: Basic 5e Layout
name: Aberrant Spirit
size: Medium
type: Aberration
alignment: Unaligned
ac: 11 + the level of the spell (natural armor)
hp: 11 + the level of the spell (natural armor)
speed: 30 ft., [[Fly]] 30 ft. (beholderkin only; hover)
stats:
  - 16
  - 10
  - 15
  - 16
  - 10
  - 6
senses: Darkvision 60Ft, Passive Perception 10, Passive Insight 10, Passive Stealth 10
traits:
  - name: Regeneration (Slaad Only).
    desc: The aberration regains 5 hit points at the start of its turn if it has at least 1 hit point.
  - name: Whispering Aura (Star Spawn Only).
    desc: t the start of each of the aberration's turns, each creature within 5 feet of the aberration must succeed on a Wisdom saving throw against your spell save DC or take 7 (2d6) psychic damage, provided that the aberration isn't incapacitated.
actions:
  - name: Multiattack
    desc: The aberration makes a number of attacks equal to half this spells level (rounded down).
  - name: Eye Ray (Beholderkin Only).
    desc: "*Melee Attack Roll:* +9, reach 15 ft. *Hit:* 12 (2d6 + 5) Bludgeoning damage. If the target is a Large or smaller creature, it has the Grappled condition (escape DC 14) from one of four tentacles."
  - name: Claws (Slaad Only)
    desc: "*Melee Weapon Attack:* your spell attack modifierto hit, reach 5 ft., one target. *Hit:* 1d10 + 3 + the spells level slashing damage. If the target is a creature, it cant regain hit points until the start of the aberrations next turn."
  - name: Psychic Slam (Star Spawn Only)
    desc: "*Melee Spell Attack:* your spell attack modifier to hit, reach 5ft., one creature. *Hit:* 1d8 + 3 _ the spells level psychic damage"
picture:
  - - Aberrant Spirit BGR PNG.png
statblock: true
atlas-type: statblock
tags:
  - monster
  - TCE
image: atlas-vtt/assets/Aberrant_Spirit_1790816522884_xo9e16.webp
---

# Aberrant Spirit
## Tasha’s Cauldron of Everything (TCE):
```statblock
layout: Basic 5e Layout
image: [[Aberrant Spirit BGR PNG.png]]
name: Aberrant Spirit
size: Medium
type: [[Aberration]]
alignment: Unaligned
ac: 11 + the level of the spell (natural armor)
hp: 40 + 10 for each spell level above 4th
[[speed]]: 30 ft., [[Fly]] 30 ft. (beholderkin only; hover)
stats: [16, 10, 15, 16, 10, 6]
damage_immunities: Psychic
senses: [[Darkvision]] 60Ft, [[Passive Perception]] 10, Passive Insight 10, Passive Stealth 10
languages: Deep Speech, understands the languages you speak
traits:
  - name: Regeneration (Slaad Only).
    desc: The aberration regains 5 hit points at the start of its turn if it has at least 1 [[hit point]].  
  - name: Whispering Aura (Star Spawn Only).
    desc: At the start of each of the aberration's turns, each creature within 5 feet of the aberration must succeed on a Wisdom [[saving throw]] against your spell save DC or take 7 (2d6) psychic damage, provided that the aberration isn't [[incapacitated]].  
actions:
  - name: "Multiattack"
    desc: "The aberration makes a number of attacks equal to half this spell's level (rounded down)."
  - name: "Eye Ray (Beholderkin Only)."
    desc: "_anged Spell Attack:_ your spell attack modifier to hit, range 150 ft., one creature. _Hit:_ 1d8 + 3 + the spell's level psychic damage."    
  - name: "Claws (Slaad Only)."
    desc: "_Melee Weapon Attack:_ your spell attack modifier to hit, reach 5 ft., one target. _Hit:_ 1d10 + 3 + the spell's level slashing damage. If the target is a creature, it can't regain hit points until the start of the aberration's next turn."
  - name: "Psychic Slam (Star Spawn Only)."
    desc: "_Melee Spell Attack:_ your spell attack modifier to hit, reach 5 ft., one creature. _Hit:_ 1d8 + 3 + the spell's level psychic damage."    
```