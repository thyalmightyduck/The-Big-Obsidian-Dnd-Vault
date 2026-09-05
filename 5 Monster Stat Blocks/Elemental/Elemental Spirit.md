---
tags:
  - Monster
  - Elemental
  - PHB24
  - Summon
ArmorClass: 11
HitPoints: "50"
Speed:
  - Walking 40ft
  - Burrow 40ft (Earth Only)
  - Fly 40ft (Hover Air Only)
  - Swim 40ft (Water Only)
DMGResistances:
  - Lightning
  - Thunder
  - Piercing
  - Slashing
  - Acid
DMGImmunities:
  - Poison
  - Fire
ConditionImmunities:
  - Exhaustion
  - Paralyzed
  - Petrified
  - Poisoned
Languages:
  - Primordial
---
# Elemental Spirit
## Players Handbook 2024 (PHB24):
```statblock
layout: Basic 5e Layout
image: [[Elemental Spirit BGR PNG.png]]
name: Elemental Spirit
size: Medium
type: [[Elemental]]
alignment: Neutral
ac: 11 + spells level
hp: 50 + 10 for each spell level above 4
speed: 40 ft., Burrow 40 ft. (Earth Only), Fly 40 ft. (Hover Air Only), Swim 40 ft. (Water Only)
stats: [18, 15, 17, 4, 10, 16]
damage_resistances: Lightning and Thunder (Air Only), Piercing and Slashing (Earth Only), Acid (Water Only)
damage_immunities: Poison, Fire (Fire Only)
condition_immunities: [[Exhaustion]], [[Paralyzed]], [[Petrified]], [[Poisoned]]
senses: [[Darkvision]] 60Ft, Passive Perception 10, Passive Insight 10, Passive Stealth 12
languages: Primordial, understands the languages you know
traits:
  - name: Amorphous Form (Air, Fire, and Water Only).
    desc: The spirit can move through a space as narrow as 1 inch wide without it counting as [[Difficult Terrain]].  
actions:
  - name: "Multiattack."
    desc: "The spirit makes a number of Slam attacks equal to half this spell's level (round down)."
  - name: "Slam."
    desc: "_Melee Attack Roll:_ Bonus equals your spell attack modifier, reach 5 ft. _Hit:_ 1d10 + 4 + the spell's level Bludgeoning (Earth only), Cold (Water only), Lightning (Air only), or Fire (Fire only) damage."     
```