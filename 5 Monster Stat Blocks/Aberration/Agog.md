---
tags:
  - Monster
  - Aberration
  - CR1
  - MoDk
Progress:
  - Game Ready
---
# Monsters of Drakkenheim (MoDk)
___
## Agog
*Medium Aberration*
___
- **[[Armor Class]]** 13
- **[[Hit Point|Hit Points]]** 30 (4d8 + 12)
- **[[Speed]]** 10 ft., Climb 10 ft.
- **[[Initiative]]** -2 (8)
___

|   STR   |  DEX   |   CON   |  INT   |   WIS   |  CHA   |
| :-----: | :----: | :-----: | :----: | :-----: | :----: |
| 15 (+2) | 6 (-2) | 16 (+3) | 3 (-4) | 11 (+0) | 5 (-3) |
___
- **Senses** [[Darkvision]] 60 ft., Passive Perception 10, Passive Insight 10, Passive Stealth 8
- **Languages** Understands Deep Speech but can't speak
- **Challenge** 1 (XP 200; PB +2)
- **[[Proficiency Bonus]]** +2
___
### Traits
***Alien Intellect.*** The agog is immune to any effect that would sense its emotions or read its thoughts, as well as any divination spell that it refuses. Wisdom ([[Insight]]) checks made to ascertain the agog's intentions or sincerity have [[Disadvantage]].  

***Delerium Healing.*** As an [[action]], the agog can touch a delerium [[shard]] to regain 10 (3d6) [[Hit Point|Hit Points]]. Once the agog has used a delerium [[shard]] in this way, the [[shard]] can't be used in this manner again for 24 hours.  

***Fully Contaminated.*** The agog is immune to [[Contamination]] and has [[Advantage]] on [[Saving Throw|saving throws]] against contaminated spells. The agog may cast contaminated spells even though it does not gain [[Contamination]] levels.  

### Actions
***Multiattack.*** The agog makes one Claw attack and one Bite attack.  

***Bite.*** *Melee Attack Roll:*  +4, reach 5 ft. *Hit:* 6 (1d8 + 2) Piercing damage plus 3 (1d6) Acid damage.  

***Claw.*** *Melee Attack Roll:*  +4, reach 5 ft. *Hit:* 7 (2d4 + 2) Slashing damage, and if the target is Medium or smaller, it has the [[Prone|Prone condition]].  

### [[Bonus Action|Bonus Actions]]
***Gobble.*** The agog makes a Bite attack against a [[Prone]] creature.

```statblock
layout: Basic 5e Layout
image: [[Agog BGR PNG.png]]
name: Agog
size: Medium
type: Aberration
ac: 13
hp: 30
hit_dice: 4d8 + 12
speed: 10 ft., Climb 10 ft.
stats: [15, 6, 16, 3, 11, 5]
senses: [[Darkvision]] 60 ft., Passive Perception 10, Passive Insight 10, Passive Stealth 8
languages: Understands Deep Speech but can't speak
cr: 1
traits:
  - name: "Alien Intellect:"
    desc: "The agog is immune to any effect that would sense its emotions or read its thoughts, as well as any divination spell that it refuses. Wisdom ([[Insight]]) checks made to ascertain the agog's intentions or sincerity have [[Disadvantage]]."  
  - name: "Delerium Healing:"
    desc: "As an [[action]], the agog can touch a delerium [[shard]] to regain 10 (3d6) [[Hit Point|Hit Points]]. Once the agog has used a delerium [[shard]] in this way, the [[shard]] can't be used in this manner again for 24 hours."
  - name: "Fully Contaminated:"
    desc: "The agog is immune to [[Contamination]] and has [[Advantage]] on [[Saving Throw|saving throws]] against contaminated spells. The agog may cast contaminated spells even though it does not gain [[Contamination]] levels."    
actions:
  - name: "Multiattack:"
    desc: "The agog makes one Claw attack and one Bite attack."
  - name: "Bite:"
    desc: "*Melee Attack Roll:*  +4, reach 5 ft. *Hit:* 6 (1d8 + 2) Piercing damage plus 3 (1d6) Acid damage."
  - name: "Claw:"
    desc: "*Melee Attack Roll:*  +4, reach 5 ft. *Hit:* 7 (2d4 + 2) Slashing damage, and if the target is Medium or smaller, it has the [[Prone|Prone condition]]."       
bonus_actions:
  - name: "Gobble:"
    desc: "The agog makes a Bite attack against a [[Prone]] creature."
```