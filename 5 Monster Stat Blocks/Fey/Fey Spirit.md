---
tags:
  - Monster
  - Fey
  - PHB24
  - Summon
ArmorClass: 12
HitPoints: "30"
Speed:
  - Walking 30ft
  - Fly 30ft
ConditionImmunities:
  - Charmed
Languages:
  - Sylvan
---
# Fey Spirit
## Player’s Handbook 2024 (PHB24):
```statblock
layout: Basic 5e Layout
image: [[Fey Spirt BGR PNG.png]]
name: Fey Spirit
size: Small
type: [[Fey]]
alignment: Neutral
ac: 12 + the spell's level
hp: 30 + 10 for each spell level above 3
speed: 30 ft., Fly 30 ft.
stats: [13, 16, 14, 14, 11, 16]
condition_immunities: [[Charmed]]
senses: [[Darkvision]] 60Ft, Passive Perception 10, Passive Insight 10, Passive Stealth 13
languages: Sylvan, understands the languages you know  
actions:
  - name: "Multiattack."
    desc: "The spirit makes a number of Fey Blade attacks equal to half this spell's level (round down)."
  - name: "Fey Blade."
    desc: "_Melee Attack Roll:_ Bonus equals your spell attack modifier, reach 5 ft. _Hit:_ 9 (2d6+3) + the spell's level Force damage."    
bonus_actions:
  - name: "Fey Step."
    desc: "The spirit magically teleports up to 30 feet to an unoccupied space it can see. Then one of the following effects occurs, based on the spirit's chosen mood:"
  - name: "Fuming."
    desc: "The spirit has [[Advantage]] on the next attack roll it makes before the end of this turn." 
  - name: "Mirthful."
    desc: "_Wisdom Saving Throw:_ DC equals your spell save DC, one creature the spirit can see within 10 feet of itself. _Failure:_ The target is [[Charmed]] by you and the spirit for 1 minute or until the target takes any damage."   
  - name: "Tricksy."
    desc: "The spirit fills a 10-foot [[Cube]] within 5 feet of it with magical Darkness, which lasts until the end of its next turn."    
```