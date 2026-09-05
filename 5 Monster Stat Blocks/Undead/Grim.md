---
tags:
  - Monster
  - Undead
  - TCM24
  - Summon
ArmorClass: 13
HitPoints: "5"
Speed:
  - Walking 40ft
DMGImmunities:
  - Necrotic
ConditionImmunities:
  - Frightened
  - Grappled
  - Petrified
  - Poisoned
  - Prone
  - Restrainded
---
# Grim
## The Crooked Moon 2024 (TCM24):
```statblock
layout: Basic 5e Layout
image: [[Grim BGR PNG.png]]
name: Grim
size: Medium
type: [[Undead]]
alignment: Neutral
ac: 13 plus your Wisdom modifier
hp: 5 plus five times your Ranger level (the grim has a number of Hit Dice [d8s] equal to your Ranger level)
speed: 40 ft.
stats: [16, 16, 14, 14, 10, 10]
damage_immunities: Necrotic
condition_immunities: [[Frightened]], [[Grappled]], [[Petrified]], [[Poisoned]], [[Prone]], [[Restrained]]
senses: [[Darkvision]] 60Ft, Passive Perception 10, Passive Insight 10, Passive Stealth 13
languages: Understands the languages you know
traits:
  - name: Incorporeal Movement.
    desc: The grim can move through other creatures and objects as if they were [[Difficult Terrain]]. The grim takes 1d10 Force damage if it ends its turn inside an object.  
  - name: Shared Fate.
    desc: Add your [[Proficiency Bonus]] to any ability check or saving throw the grim makes. 
actions:
  - name: "Ominous Rend."
    desc: "_Melee Attack Roll:_ Bonus equals your spell attack modifier, reach 5 ft. _Hit:_ 1d6 + 3 plus your Wisdom modifier Necrotic damage, and if the target is a creature, it has the [[Frightened]] condition until the start of your next turn." 
reactions:
  - name: Baleful Howl.
    desc: _Trigger:_ A creature moves out of the grim's reach. _Response—__Wisdom Saving Throw:_ Your spell save DC, the triggering creature. _Failure:_ The target's [[Speed]] is 0 until the end of the turn.   
```