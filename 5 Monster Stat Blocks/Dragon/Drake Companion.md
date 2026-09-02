---
tags:
  - Monster
  - Dragon
  - Summon
  - FTD
ArmorClass: 14
HitPoints: "5"
Speed:
  - Walking 40ft
Saves:
  - DEX
  - WIS
Languages:
  - Draconic
---
# Drake Companion
## Fizban’s Treasury of Dragons (FTD):
```statblock
layout: Basic 5e Layout
image: [[Drake Companion BGR PNG.png]]
name: Drake Companion
size: Small
type: [[Dragon]] 
ac: 14 + PB (Natural Armor)
hp: 5 + five times your ranger level (the drake has a number of Hit Dice [d10s] equal to your ranger level)
speed: 40 ft.
stats: [16, 12, 15, 8, 14, 8]
saves: 
  - DEX: +1 + PB
  - WIS: +2 + PB 
damage_immunities: determined by the drake's draconic essence trait
senses: [[Darkvision]] 60Ft, Passive Perception 12, Passive Insight 12, Passive Stealth 11
languages: Draconic
traits:
  - name: Draconic Essence.
    desc: When you summon the drake, choose a damage type. acid, cold, fire, lightning, or poison. The chosen type determines the drake's damage immunity and the damage of its Infused Strikes trait.  
actions:
  - name: "Bite."
    desc: "_Melee Weapon Attack:_ +3 plus PB to hit, reach 5 ft., one target. _Hit:_ 3 (1d6) plus PB piercing damage."   
reactions:
  - name: Infused Strikes.
    desc: When another creature within 30 feet of the drake that it can see hits a target with a weapon attack, the drake infuses the strike with its essence, causing the target to take an extra 3 (1d6) damage of the type determined by its Draconic Essence.
  
```