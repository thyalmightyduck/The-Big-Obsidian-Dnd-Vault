# Construct Spirt 
## Player’s Handbook (2024):
```statblock
layout: Basic 5e Layout
image: [[Construct Spirit BGR PNG.png]]
name: Construct Spirit
size: Medium
type: [[Construct]] 
alignment: Neutral
ac: 13 + the spell's level
hp: 40 + 15 for each spell level above 4
speed: 30ft
stats: [18, 10, 18, 14, 11, 5]
damage_resistances: Poison
condition_immunities: [[Charmed]], [[Exhaustion]], [[Frightened]], [[Paralyzed]], [[Poisoned]]
senses: [[Darkvision]] 60Ft, Passive Perception 10, Passive Insight 10, Passive Stealth 10
languages: Understands the languages you know
traits:
  - name: Heated Body (Metal Only).
    desc: A creature that hits the spirit with a melee attack or that starts its turn in a grapple with the spirit takes 1d10 Fire damage.
  - name: Stony Lethargy (Stone Only).
    desc: When a creature starts its turn within 10 feet of the spirit, the spirit can target it with magical energy if the spirit can see it. _Wisdom Saving Throw:_ DC equals your spell save DC, the target. _Failure:_ Until the start of its next turn, the target can't make [[Opportunity Attacks]], and its [[Speed]] is halved.    
actions:
  - name: "Multiattack"
    desc: "The spirit makes a number of Slam attacks equal to half this spell's level (round down)."
  - name: "Slam."
    desc: "_Melee Attack Roll:_ Bonus equals your spell attack modifier, reach 5 ft. _Hit:_ 1d8 + 4 + the spell's level Bludgeoning damage."  
reactions:
  - name: Berserk Lashing (Clay Only).
    desc: _Trigger:_ The spirit takes damage from a creature. _Response:_ The spirit makes a Slam attack against that creature if possible, or the spirit moves up to half its [[Speed]] toward that creature without provoking [[Opportunity Attacks]].   
```