---
tags:
  - Monster
  - Aberration
  - CR4
  - GHMG24
---
# Grim Hallow: Monster Grimoire 2024 (GHMG24)
___
## Anguisher
*Medium Aberration, Chaotic Evil*
___
- **[[Armor Class]]** 13
- **[[Hit Point|Hit Points]]** 65 (10d8 + 20)
- **[[Speed]]** 30 ft.
- **[[Initiative]]** +3 (13)
___

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|8 (-1)|16 (+3)|15 (+2)|8 (-1)|10 (+0)|17 (+3)|
___
- **[[Saving Throw|Saving Throws]]** Dex +7
- **Skills** [[Insight]] +2, [[Perception]] +2, [[Stealth]] +5
- **Damage Resistances** Psychic
- **Immunities** [[Exhaustion]], [[Frightened]], [[Grappled]], [[Paralyzed]], [[Petrified]], [[Prone]], [[Restrained]], [[Unconscious]]
- **Senses** [[Darkvision]] 60 ft., [[Passive Perception]] 12, Passive Insight 12, Passive Stealth 13
- **Languages** Understands all languages but can't speak, telepathy 60 ft.
- **Challenge** 4 (XP 1,100; PB +2)
- **[[Proficiency Bonus]]** +2
___
### Traits
***Amorphous.*** The anguisher can move through a space as narrow as 1 inch without without expending extra movement to do so.  
***Continued Suffering.*** A creature with an Intelligence score of 4 or higher that dies from the anguisher's attacks spawns a new anguisher in 3 days. Any effect that prevents the target's body from becoming Undead also prevents the emergence of the new anguisher.  

***Frightening Advantage.*** The anguisher has [[Advantage]] on [[attack rolls]] against creatures that have the [[Frightened|Frightened condition]]. Against such targets, the anguisher scores a [[Critical Hit]] on a roll of 18 to 20 on the d20.  

### Actions
***Multiattack.*** The anguisher makes two Anguish attacks.  

***Anguish.*** *Melee  or Ranged Spell Attack Roll:*  +5 to hit, reach 5 ft. or range 60 ft. *Hit:* 13 (3d6 + 3) Psychic damage, and the target has the [[Frightened|Frightened condition]] until the end of its next turn. The target must use its [[Reaction]] to move up to its [[Speed]] away from the anguisher by the safest route. Movement used during this [[Reaction]] can't be used during the target's next turn.  

***Harrow (Recharge 6).*** *Wisdom [[Saving Throw]]:* DC 13, each creature of the anguisher's choice within 60 feet that is aware of the anguisher. *Failure:* 17 (5d6) Psychic damage, and the target has the [[Frightened|Frightened condition]]. At the end of each of its turns, the target repeats the save, ending the effect on itself on a success. After 1 minute, it succeeds automatically.  

***Invisibility.*** The anguisher casts *[[Invisibility]]* on itself, requiring no spell components and using Charisma as the spellcasting ability.

```statblock
layout: Basic 5e Layout
image: [[Anguisher BGR PNG.png]]
name: Anguisher
size: Medium
type: Aberration
alignment: Chaotic Evil
ac: 13
hp: 65
hit_dice: 10d8 + 20
speed: 30 ft.
stats: [8, 16, 15, 8, 10, 17]
saves: 
  - DEX: +7
skillsaves:
  - Insight: +2
  - Perception: +2
  - Stealth: +5   
damage_resistances: Psychic
condition_immunities: [[Exhaustion]], [[Frightened]], [[Grappled]], [[Paralyzed]], [[Petrified]], [[Prone]], [[Restrained]], [[Unconscious]]
senses: [[Darkvision]] 60 ft., [[Passive Perception]] 12, Passive Insight 12, Passive Stealth 13
languages: v
cr: 4
traits:
  - name: "Amorphous:"
    desc: "The anguisher can move through a space as narrow as 1 inch without without expending extra movement to do so."
  - name: "Continued Suffering:"
    desc: "A creature with an Intelligence score of 4 or higher that dies from the anguisher's attacks spawns a new anguisher in 3 days. Any effect that prevents the target's body from becoming Undead also prevents the emergence of the new anguisher."
  - name: "Frightening Advantage:"
    desc: "The anguisher has [[Advantage]] on [[attack rolls]] against creatures that have the [[Frightened|Frightened condition]]. Against such targets, the anguisher scores a [[Critical Hit]] on a roll of 18 to 20 on the d20."      
actions:
  - name: "Multiattack:"
    desc: "The anguisher makes two Anguish attacks."
  - name: "Anguish:"
    desc: "*Melee  or Ranged Spell Attack Roll:*  +5 to hit, reach 5 ft. or range 60 ft. *Hit:* 13 (3d6 + 3) Psychic damage, and the target has the [[Frightened|Frightened condition]] until the end of its next turn. The target must use its [[Reaction]] to move up to its [[Speed]] away from the anguisher by the safest route. Movement used during this [[Reaction]] can't be used during the target's next turn."
  - name: "Harrow (Recharge 6):"
    desc: "*Wisdom [[Saving Throw]]:* DC 13, each creature of the anguisher's choice within 60 feet that is aware of the anguisher. *Failure:* 17 (5d6) Psychic damage, and the target has the [[Frightened|Frightened condition]]. At the end of each of its turns, the target repeats the save, ending the effect on itself on a success. After 1 minute, it succeeds automatically."
  - name: "Invisibility:"
    desc: "The anguisher casts *[[Invisibility]]* on itself, requiring no spell components and using Charisma as the spellcasting ability."  
```