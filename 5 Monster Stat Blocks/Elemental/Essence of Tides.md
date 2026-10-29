---
Progress:
  - In Progress
tags:
  - Monster
  - Elemental
  - CR5
  - FM
---
# Flea, Mortals! (FM)
___
## Essence of Tides
*Medium Elemental (Water, Skirmisher); Any Alignment*
___
- **[[Armor Class]]** 15 (natural armor)
- **[[Hit Point|Hit Points]]** 84 (13d8 + 26)
- **[[Speed]]** 15 ft., Swim 50 ft.
- **[[Initiative]]** +4 (14)
___

|   STR   |   DEX   |   CON   |  INT   |   WIS   |   CHA   |
| :-----: | :-----: | :-----: | :----: | :-----: | :-----: |
| 12 (+1) | 18 (+4) | 14 (+2) | 9 (-1) | 16 (+3) | 10 (+0) |
___
- **Skills** [[Acrobatics]] +7, [[Medicine]] +6
- **Damage Resistances** Acid, Fire, Poison
- **Immunities** [[Grappled]], [[Poisoned]], [[Restrained]]
- **Senses** [[Darkvision]] 60 ft., [[Passive Perception]] 13, Passive Insight 13, Passive Stealth 14
- **Languages** Aquan, Common
- **Challenge** 5 (XP 1,800; PB +3)
- **[[Proficiency Bonus]]** +3
___
### Traits
***Water Glide.*** While within 5 feet of a liquid or solid surface, the essence gains a flying speed equal to their swimming speed. While flying, the essence doesn't provoke [[Opportunity Attack|opportunity attacks]].  

### [[Action|Actions]]
***Multiattack.*** The essence makes two Water Wing attacks and one Lightning Tail Whip attack.  

***Water Wing.*** *Melee Weapon Attack:*  +7 to hit, reach 5 ft., one target. *Hit:* 7 (1d6 + 4) bludgeoning damage. If the same creature is hit twice with this attack on a turn, they are [[Vulnerability|vulnerable]] to lightning damage until the end of the essence's turn.  

***Lightning Tail Whip.*** *Melee Spell Attack:*  +6 to hit, reach 15 ft., one target. *Hit:* 7 (2d6) lightning damage, and the target is pushed up to 10 feet away from the essence.  

### [[Bonus Action|Bonus Actions]]
***Convocation of Water (1/Day).*** The essence imbues the power of water in themself or another Elemental they can see within 30 feet, granting one of the following effects of that Elemental's choice:  
- **Scalding Steam.** The Elemental spouts blistering steam. Each non-Elemental creature within 15 feet of them must make a DC 15 Constitution [[saving throw]]. On a failed save, a target takes 18 (4d8) fire damage and is [[blinded]] until the end of their next turn. On a successful save, a target takes half as much damage and isn't [[blinded]].
- **Waters of Vitality.** The Elemental regains 25 [[Hit Point|hit points]] and can end one of the following conditions affecting them: [[blinded]], [[charmed]], [[Dazed (FM)|dazed]], [[deafened]], [[paralyzed]], [[poisoned]], or [[stunned]].

```statblock
layout: Basic 5e Layout
image: [[Blank Elemental Portrait BGR PNG.png]]
name: Essence of Tides
size: Medium
type: Elemental
subtype: (Water, Skirmisher)
alignment: Any Alignment
ac: 15 (natural armor)
hp: 84
hit_dice: 2d6
speed: 13d8 + 26
stats: [12, 18, 14, 19, 16, 10]
skillsaves:
  - Acrobatics: +7
  - Medicine: +6  
damage_resistances: Acid, Fire, Poison
condition_immunities: [[Grappled]], [[Poisoned]], [[Restrained]]
senses: [[Darkvision]] 60 ft., [[Passive Perception]] 13, Passive Insight 13, Passive Stealth 14
languages: Aquan, Common
cr: 5
traits:
  - name: "Water Glide:"
    desc: "While within 5 feet of a liquid or solid surface, the essence gains a flying speed equal to their swimming speed. While flying, the essence doesn't provoke [[Opportunity Attack|opportunity attacks]]."  
actions:
  - name: "Multiattack:"
    desc: "The essence makes two Water Wing attacks and one Lightning Tail Whip attack."
  - name: "Water Wing:"
    desc: "*Melee Weapon Attack:*  +7 to hit, reach 5 ft., one target. *Hit:* 7 (1d6 + 4) bludgeoning damage. If the same creature is hit twice with this attack on a turn, they are [[Vulnerability|vulnerable]] to lightning damage until the end of the essence's turn."
  - name: "Lightning Tail Whip:"
    desc: "*Melee Spell Attack:*  +6 to hit, reach 15 ft., one target. *Hit:* 7 (2d6) lightning damage, and the target is pushed up to 10 feet away from the essence."       
bonus_actions:
  - name: "Convocation of Water (1/Day):"
    desc: "The essence imbues the power of water in themself or another Elemental they can see within 30 feet, granting one of the following effects of that Elemental's choice:<P>- **Scalding Steam.** The Elemental spouts blistering steam. Each non-Elemental creature within 15 feet of them must make a DC 15 Constitution [[saving throw]]. On a failed save, a target takes 18 (4d8) fire damage and is [[blinded]] until the end of their next turn. On a successful save, a target takes half as much damage and isn't [[blinded]].<P>- **Waters of Vitality.** The Elemental regains 25 [[Hit Point|hit points]] and can end one of the following conditions affecting them: [[blinded]], [[charmed]], [[Dazed (FM)|dazed]], [[deafened]], [[paralyzed]], [[poisoned]], or [[stunned]]." 
```