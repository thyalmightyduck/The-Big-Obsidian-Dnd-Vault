# Statblock

```statblock
layout: Basic 5e Layout
image: [[Giaint Insect Monster BGR PNG.png]]
name: Giant Insect Monster
size: Large
type: [[Beast]]
alignment: Unaligned
ac: 11 + the spell's level
hp: 30 + 10 for each spell level above 4
speed: 40 ft., Climb 40 ft., Fly 40 ft. (Wasp only) 
stats: [17, 13, 15, 4, 14, 3]
senses: [[Darkvision]] 60Ft, Passive Perception 12, Passive Insight 12, Passive Stealth 11
languages: Understands the languages you know
traits:
  - name: Spider Climb.
    desc: The insect can climb difficult surfaces, including along ceilings, without needing to make an ability check.  
actions:
  - name: "Multiattack"
    desc: "The insect makes a number of attacks equal to half this spell's level (round down)."
  - name: "Poison Jab."
    desc: "_Melee Attack Roll:_ Bonus equals your spell attack modifier, reach 10 ft. _Hit:_ 1d6 + 3 + the spell's level Piercing damage plus 1d4 Poison damage."
  - name: "Web Bolt (Spider Only)."
    desc: "_Ranged Attack Roll:_ Bonus equals your spell attack modifier, range 60 ft. _Hit:_ 1d10 + 3 + the spell's level Bludgeoning damage, and the target's [Speed](https://5e.tools/variantrules.html#speed_xphb) is reduced to 0 until the start of the insect's next turn."        
bonus_actions:
  - name: "Venomous Spew (Centipede Only)."
    desc: "_Constitution Saving Throw:_ Your spell save DC, one creature the insect can see within 10 feet. _Failure:_ The target has the [Poisoned] condition until the start of the insect's next turn."  
```