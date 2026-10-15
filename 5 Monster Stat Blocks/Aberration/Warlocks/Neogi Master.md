---
tags:
  - Monster
  - Aberration
  - MPMM
  - CR4
---
# Mordenkainen Presents: Monster of the Multiverse (MPMM)
___
## Neogi Master
*Medium Aberration (Warlock), Typically Lawful Evil*
___
- **[[Armor Class]]** 15 (natural armor)
- **[[Hit Point|Hit Points]]** 71 (11d8 + 22)
- **[[Speed]]** 30 ft., Climb 30 ft.
- **[[Initiative]]** +3 (13)
___

|  STR   |   DEX   |   CON   |   INT   |   WIS   |   CHA   |
| :----: | :-----: | :-----: | :-----: | :-----: | :-----: |
| 6 (-2) | 16 (+3) | 14 (+2) | 16 (+3) | 12 (+1) | 18 (+4) |
___
- **[[Saving Throw|Saving Throws]]** Wis +3
- **Skills** [[Arcana]] +5, [[Deception]] +6, [[Intimidation]] +6, [[Perception]] +3, [[Persuasion]] +6
- **Senses** Darkvision 120 ft., [[Passive Perception]] 13, Passive Insight 11, Passive Stealth 13
- **Languages** Common, Deep Speech, Undercommon, telepathy 30 ft.
- **Challenge** 4 (XP 1,100; PB +2)
- **[[Proficiency Bonus]]** +2
___
### Traits
***Devil's Sight.*** Magical darkness doesn't impede the neogi's [[darkvision]].  

***Mental Fortitude.*** The neogi has [[advantage]] on [[Saving Throw|saving throws]] against being [[charmed]] or [[frightened]], and magic can't put the neogi to sleep.  

***Spider Climb.*** The neogi can climb difficult surfaces, including upside down on ceilings, without needing to make an [[ability check]].  

### Actions
***Multiattack.*** The neogi makes one Bite attack and one Claw attack, or it makes two Tentacle of Hadar attacks.  

***Bite.*** *Melee Weapon Attack:*  +5 to hit, reach 5 ft., one target. *Hit:* 6 (1d6 + 3) piercing damage plus 14 (4d6) poison damage, and the target must succeed on a DC 12 Constitution [[saving throw]] or become [[poisoned]] for 1 minute. A target can repeat the [[saving throw]] at the end of each of its turns, ending the effect on itself on a success.  

***Claw.*** *Melee Weapon Attack:*  +5 to hit, reach 5 ft., one target. *Hit:* 8 (2d4 + 3) piercing damage.  

***Spellcasting.*** The neogi casts one of the following spells, using Charisma as the spellcasting ability (spell save DC 14):  

At will: *[[guidance]]*, *[[mage hand]]*, *[[minor illusion]]*, *[[prestidigitation]]*  
1/day each: *[[dimension door]]*, *[[hold person]]*, *[[hunger of Hadar]]*  

***Tentacle of Hadar.*** *Ranged Spell Attack:*  +6 to hit, range 120 ft., one target. *Hit:* 14 (3d6 + 4) necrotic damage, and the target can't take reactions until the end of the neogi's next turn, as a spectral tentacle clings to the target.  

### Bonus Actions
***Enslave (Recharges after a Short or [[Long Rest]]).*** The neogi targets one creature it can see within 30 feet of it. The target must succeed on a DC 14 Wisdom [[saving throw]] or be magically [[charmed]] by the neogi for 1 day, or until the neogi dies or is more than 1 mile from the target. The [[charmed]] target obeys the neogi's commands and can't take reactions, and the neogi and the target can communicate telepathically with each other at a distance of up to 1 mile. Whenever the [[charmed]] target takes damage, it can repeat the [[saving throw]], ending the effect on itself on a success.

```statblock
layout: Basic 5e Layout
image: [[Neogi Master BGR PNG.png]]
name: Neogi Master
size: Medium
type: Aberration
subtype: Warlock
alignment: Typically Lawful Evil
ac: 15 (natural armor)
hp: 71
hit_dice: 11d8 + 22
speed: 30 ft., Climb 30 ft.
stats: [6, 16, 14, 16, 12, 18] 
saves: 
  - WIS: +3
skillsaves:
  - Arcana: +5
  - Deception: +6
  - Intimidation: +6
  - Perception: +3
  - Persuasion: +6        
senses: Darkvision 120 ft., [[Passive Perception]] 13, Passive Insight 11, Passive Stealth 13
languages: Common, Deep Speech, Undercommon, telepathy 30 ft.
cr: 4
spellsNotes: "***Spellcasting.*** The neogi casts one of the following spells, using Charisma as the spellcasting ability (spell save DC 14):"
spells: 
  - "At will: *[[guidance]]*, *[[mage hand]]*, *[[minor illusion]]*, *[[prestidigitation]]*"
  - "1/day each: *[[dimension door]]*, *[[hold person]]*, *[[hunger of Hadar]]*"  
traits:
  - name: Devil's Sight.
    desc: Magical darkness doesn't impede the neogi's [[darkvision]].    
actions:
  - name: "Multiattack"
    desc: "The doppelganger makes two Slam attacks and uses Unsettling Visage if available."
  - name: "Slam"
    desc: "_Melee [[Attack Roll]]:_ +6 (with [[Advantage]] during the first round of each combat), reach 5 ft. _Hit:_ 11 (2d6 + 4) Bludgeoning damage."
  - name: "Unsettling Visage (Recharge 6)"
  - desc: "_Wisdom [[Saving Throw]]:_ DC 12, each creature in a 15-foot [[Emanation]] originating from the doppelganger that can see the doppelganger. _Failure:_ The target has the [[Frightened]] condition and repeats the save at the end of each of its turns, ending the effect on itself on a success. After 1 minute, it succeeds automatically."   
bonus_actions:
  - name: "Shape-Shift"
    desc: "The [[doppelganger]] shape-shifts into a Medium or Small [[Humanoid]], or it returns to its true form. Its game statistics, other than its size, are the same in each form. Any equipment it is wearing or carrying isn't transformed."
reactions:
  - name: 
    desc: 
legendary_actions:
  - name: 
    desc:   
mythic_description: 
mythic_actions:
  - name: 
    desc:
lair_actions:
  - name: 
    desc:
regional_effects:
  - name: 
    desc:
```