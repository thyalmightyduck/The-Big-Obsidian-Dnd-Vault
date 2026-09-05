---
tags:
  - Monster
  - Undead
  - Summon
  - PHB24
ArmorClass: 11
HitPoints: 20-30
Speed:
  - Walking 30ft
  - Fly 40ft (Hover Ghosts Only)
DMGImmunities:
  - Necrotic
  - Poison
ConditionImmunities:
  - Exhaustion
  - Frightened
  - Paralyzed
  - Poisoned
Languages:
  - Common
---
# Undead Spirit
## Player’s Handbook 2024 (PHB24): 
```statblock
layout: Basic 5e Layout
image: [[Undead Spirit BGR PNG.png]]
name: Undead Spirit
size: Meduim
type: Undead
alignment: Neutral
ac: 11+ Spells Level
hp: 30 (Ghostly and Putrid only) or 20 (Skeletal only) + 10 for each spell level above 3
speed: 30Ft., Fly 40Ft., (hover; Ghostly Only)
stats: [12, 16, 25, 14, 10, 9] 
damage_immunities: Necrotic, Poison
condition_immunities: [[Exhaustion]], [[Frightened]], [[Paralyzed]], [[Poisoned]]
senses: [[Darkvision]] 60Ft, [[Passive Perception]] 10, Passive Insight 10, Passive Stealth 13
languages: Common
traits:
  - name: "Festering Aura (Putrid Only)."
    desc: "_Constitution Saving Throw:_ DC equals your spell save DC, any creature (other than you) that starts its turn within a 5-foot [[Emanation]] originating from the spirit. _Failure:_ The creature has the [[Poisoned]] condition until the start of its next turn."  
  - name: Incorporeal Passage (Ghostly Only).
    desc: The spirit can move through other creatures and objects as if they were [[Difficult Terrain]]. If it ends its turn inside an object, it is shunted to the nearest unoccupied space and takes 1d10 Force damage for every 5 feet traveled.  
actions:
  - name: "Multiattack"
    desc: "The spirit makes a number of attacks equal to half this spell's level (round down)."
  - name: "Deathly Touch (Ghostly Only)."
    desc: "_Melee Attack Roll:_ Bonus equals your spell attack modifier, reach 5 ft. _Hit:_ 1d8 + 3 + the spell's level Necrotic damage, and the target has the [[Frightened]] condition until the end of its next turn."  
  - name: Grave Bolt (Skeletal Only).
    desc: _Ranged Attack Roll:_ Bonus equals your spell attack modifier, range 150 ft. _Hit:_ 2d4 + 3 + the spell's level Necrotic damage.
  - name: Rotting Claw (Putrid Only).
    desc: _Melee Attack Roll:_ Bonus equals your spell attack modifier, reach 5 ft. _Hit:_ 1d6 + 3 + the spell's level Slashing damage. If the target has the [[Poisoned]] condition, it has the [[Paralyzed]] condition until the end of its next turn.    
```