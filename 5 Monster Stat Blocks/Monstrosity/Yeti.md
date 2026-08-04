# Yeti
## Monster Manual (2025):
```statblock
layout: Basic 5e Layout
image: [[Yeti BGR PNG.png]]
name: Yeti
size: Large
type: [[Monstrosity]]
alignment: Chaotic Evil
ac: 12
hp: 51
hit_dice: 6d10+18
speed: 40 ft., Climb 40 ft.
stats: [18, 13, 16, 8, 12, 7] 
skillsaves:
  - Perception: +5
  - Stealth: +5  
damage_immunities: Cold
senses: [[Darkvision]] 60Ft, Passive Perception 15, Passive Insight 11, Passive Stealth 15
languages: Yeti
cr: 3
traits:
  - name: Fear of Fire.
    desc: If the yeti takes Fire damage, it has [[Disadvantage]] on attack rolls and ability checks until the end of its next turn.  
actions:
  - name: "Multiattack"
    desc: "The yeti can use its Chilling Gaze and makes two attacks, using Claw or Ice Throw in any combination."
  - name: "Claw."    
    desc: "_Melee Attack Roll:_ +6, reach 5 ft. _Hit:_ 7 (1d6 + 4) Slashing damage plus 3 (1d6) Cold damage."  
  - name: "Ice Throw."  
    desc: "_Ranged Attack Roll:_ +6, range 30/120 ft. _Hit:_ 6 (1d4 + 4) Bludgeoning damage plus 2 (1d4) Cold damage."
  - name: "Chilling Gaze."
    desc: "_Constitution Saving Throw:_ DC 13, one creature the yeti can see within 30 feet. _Failure:_ 5 (2d4) Cold damage, and the target has the [[Paralyzed]] condition until the start of the yeti's next turn unless the target has [[Immunity]] to Cold damage. _Success:_ The target is immune to the Chilling Gaze of all yetis (but not abominable yetis) for 1 hour."  
```