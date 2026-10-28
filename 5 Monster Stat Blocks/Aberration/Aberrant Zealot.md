---
tags:
  - Monster
  - Aberration
  - CR8
  - PaBTSO
Progress:
  - Game Ready
---
# Phandelver and Below: Shattered Obelisk (PaBTSO)
___
## Aberrant Zealot
*Medium Aberration, typically Chaotic Evil*
___
- **[[Armor Class]]** 16 (*[[Studded Leather Armor]]*)
- **[[Hit Point|Hit Points]]** 93 (17d8 + 17)
- **[[Speed]]** 30 ft.
- **[[Initiative]]** +4 (14)
___

|   STR   |   DEX   |   CON   |   INT   |  WIS   |   CHA   |
| :-----: | :-----: | :-----: | :-----: | :----: | :-----: |
| 15 (+2) | 18 (+4) | 12 (+1) | 13 (+1) | 8 (-1) | 19 (+4) |
___
- **[[Saving Throw|Saving Throws]]** Dex +7, Cha +7
- **Skills** [[Perception]] +5
- **Damage Resistances** Psychic
- **Immunities** [[Blinded]], [[Charmed]], [[Frightened]], [[Grappled]], [[Restrained]]
- **Gear** *[[Shortsword]]*
- **Senses** [[Darkvision]] 60 ft., [[Truesight]] 10 ft., [[Passive Perception]] 15, Passive Insight 9, Passive Stealth 14
- **Languages** Common, Deep Speech
- **Challenge** 8 (XP 3,900; PB +3)
- **[[Proficiency Bonus]]** +3
___
### Traits
***Aberrant Form.*** The zealot exudes the chaos of the Far Realm. Any non-Aberration creature that starts its turn within 5 feet of the zealot must succeed on a DC 15 Wisdom [[saving throw]] or take 7 (2d6) psychic damage.  

***Weirdly Pliable.*** The zealot, along with any equipment it is wearing or carrying, is unnaturally flexible. The zealot can move through any space as narrow as 1 inch without squeezing.  

### Actions
***Multiattack.*** The zealot makes one Psychic Rend attack and two Shortsword attacks.  

***Psychic Rend.*** *Melee  or Ranged Spell Attack:*  +7 to hit, reach 15 ft. or range 120 ft., one target. *Hit:* 14 (3d6 + 4) psychic damage, and the target must succeed on a DC 15 Wisdom [[saving throw]] or have the [[stunned]] [[condition]] until the start of the zealot's next turn.  

***Shortsword.*** *Melee Weapon Attack:*  +7 to hit, reach 15 ft., one target. *Hit:* 7 (1d6 + 4) piercing damage plus 7 (2d6) psychic damage.  

***Spellcasting (Psionics).*** The zealot casts one of the following spells, requiring no components and using Charisma as the spellcasting ability (spell save DC 15):  

At will: *[[Detect Thoughts]]*, *[[Minor Illusion]]*  
1/day each: *[[Arcane Gate]]*, *[[Hunger of Hadar]]*  

### [[Bonus Action|Bonus Actions]]
***Void Warp (Recharge 5–6).*** The zealot teleports, along with any equipment it is wearing or carrying, to an unoccupied space it can see within 120 feet of itself, leaving a churning void in the space it left. Immediately after it teleports, each creature within 30 feet of the void other than the zealot must make a DC 15 Strength [[saving throw]]. On a failed save, a creature takes 18 (4d8) force damage and is pulled to the unoccupied space closest to the void. On a successful save, the creature takes half as much damage only. The void then disappears.

```statblock
layout: Basic 5e Layout
image: [[Aberrant Zealot BGR PNG.png]]
name: Aberrant Zealot
size: Medium
type: Aberration
alignment: typically Chaotic Evil
ac: 16 (*[[studded leather armor]]*)
hp: 93
hit_dice: 17d8 + 17
speed: 30 ft.
stats: [15, 18, 12, 13, 8, 19]
saves: 
  - DEX: +7
  - CHA: +7  
skillsaves:
  - Perception: +5
damage_resistances: Psychic
condition_immunities: [[Blinded]], [[Charmed]], [[Frightened]], [[Grappled]], [[Restrained]]
senses: [[Darkvision]] 60 ft., [[Truesight]] 10 ft., [[Passive Perception]] 15, Passive Insight 9, Passive Stealth 14
languages: Common, Deep Speech
cr: 8
spellsNotes: "***Spellcasting (Psionics).*** The zealot casts one of the following spells, requiring no components and using Charisma as the spellcasting ability (spell save DC 15):"
spells:
  - "At will: *[[detect thoughts]]*, *[[minor illusion]]*"
  - "1/day each: *[[arcane gate]]*, *[[hunger of Hadar]]*"  
traits:
  - name: "Aberrant Form:"
    desc: "The zealot exudes the chaos of the Far Realm. Any non-Aberration creature that starts its turn within 5 feet of the zealot must succeed on a DC 15 Wisdom [[saving throw]] or take 7 (2d6) psychic damage."  
  - name: "Weirdly Pliable:"
    desc: "The zealot, along with any equipment it is wearing or carrying, is unnaturally flexible. The zealot can move through any space as narrow as 1 inch without squeezing."  
actions:
  - name: "Multiattack:"
    desc: "The zealot makes one Psychic Rend attack and two Shortsword attacks."
  - name: "Psychic Rend:"
    desc: "*Melee  or Ranged Spell Attack:*  +7 to hit, reach 15 ft. or range 120 ft., one target. *Hit:* 14 (3d6 + 4) psychic damage, and the target must succeed on a DC 15 Wisdom [[saving throw]] or have the [[stunned]] [[condition]] until the start of the zealot's next turn."
  - name: "Shortsword:"  
    desc: "*Melee Weapon Attack:*  +7 to hit, reach 15 ft., one target. *Hit:* 7 (1d6 + 4) piercing damage plus 7 (2d6) psychic damage."     
bonus_actions:
  - name: "Void Warp (Recharge 5–6):"
    desc: "The zealot teleports, along with any equipment it is wearing or carrying, to an unoccupied space it can see within 120 feet of itself, leaving a churning void in the space it left. Immediately after it teleports, each creature within 30 feet of the void other than the zealot must make a DC 15 Strength [[saving throw]]. On a failed save, a creature takes 18 (4d8) force damage and is pulled to the unoccupied space closest to the void. On a successful save, the creature takes half as much damage only. The void then disappears."
```