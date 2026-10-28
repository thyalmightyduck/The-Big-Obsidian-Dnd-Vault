---
Progress: Game Ready
---
# Tome of Beasts 1 2023 Edition (ToB123)
___
## Oculo Swarm
*Large swarm of Tiny Aberrations, Neutral Evil*
___
- **[[Armor Class]]** 15
- **[[Hit Point|Hit Points]]** 82 (11d10 + 22)
- **[[Speed]]** 5 ft., Fly 40 ft. (hover)
- **[[Initiative]]** +5 (15)
___

|   STR   |   DEX   |   CON   |  INT   |   WIS   |   CHA   |
| :-----: | :-----: | :-----: | :----: | :-----: | :-----: |
| 10 (+0) | 20 (+5) | 14 (+2) | 8 (-1) | 15 (+2) | 17 (+3) |
___
- **Skills** [[Insight]] +6, [[Perception]] +6, [[Stealth]] +7
- **Damage [[Resistance|Resistances]]** Bludgeoning, Piercing, Slashing
- **Immunities** [[Charmed]], [[Frightened]], [[Grappled]], [[Paralyzed]], [[Petrified]], [[Prone]], [[Restrained]], [[Stunned]]
- **Senses** [[Darkvision]] 60 ft., [[Passive Perception]] 16, Passive Insight 16,  Passive Stealth 17
- **Languages** Understands Common but can't speak
- **Challenge** 4 (XP 1,100; PB +2)
- **[[Proficiency Bonus]]** +2
___
### Traits
***Hundreds of Eyes.*** The oculo swarm has [[advantage]] on Wisdom ([[Perception]]) checks that rely on sight and on [[Saving Throw|saving throws]] against being [[blinded]]. In addition, if the swarm isn't [[blinded]], creatures attacking it can't benefit from traits and features that rely on a creature's allies distracting or surrounding the swarm, such as the Pack Tactics trait or Sneak Attack class feature.  

***Swarm.*** The swarm can occupy another creature's space and vice versa, and the swarm can move through any opening large enough for a Tiny eyeball. The swarm can't regain hp or gain temporary hp.  

### Actions
***Multiattack.*** The oculo swarm makes two Extract Eye attacks. If both attacks hit one creature, the target must succeed on a DC 13 Strength [[saving throw]] or the swarm removes one of its eyes. While missing half or fewer of its total number of eyes, the target has [[disadvantage]] on [[attack rolls]] and Wisdom ([[Perception]]) checks that rely on sight. While missing more than half its total number of eyes, the target is [[blinded]] until its sight is restored. If the target's eye is recovered from the defeated swarm, it can be reattached with a successful DC 12 Wisdom ([[Medicine]]) check, provided the eye is reattached within 1 hour of the target losing the eye.  

***Extract Eye.*** *Melee Weapon Attack:*  +7 to hit, reach 0 ft., one creature in the swarm's space. *Hit:* 18 (4d8) piercing damage, or 9 (2d8) piercing damage if the swarm has half of its hp or fewer.  

***Disorienting Gaze (Recharge 5–6).*** The swarm's many eyes suddenly turn in different directions. Each creature within 10 feet of the oculo swarm must make a DC 13 Charisma [[saving throw]]. On a failure, a creature takes 21 (6d6) psychic damage and is disoriented until the end of its next turn. On a success, a creature takes half the damage and isn't disoriented. A disoriented creature is [[incapacitated]] and moves in a random direction when it moves.

```statblock
layout: Basic 5e Layout
image: [[Oculo Swarm BGR PNG.png]]
name: Oculo Swarm
size: Large swarm
type: Tiny Aberrations
alignment: Neutral Evil
ac: 15
hp: 82
hit_dice: 11d10 + 22
speed: 5 ft., Fly 40 ft. (hover)
stats: [10, 20, 14, 8, 15, 17]
skillsaves:
  - [[Insight]]: +6
  - [[Perception]]: +6
  - [[Stealth]]: +7    
damage_resistances: Bludgeoning, Piercing, Slashing
condition_immunities: [[Charmed]], [[Frightened]], [[Grappled]], [[Paralyzed]], [[Petrified]], [[Prone]], [[Restrained]], [[Stunned]]
senses: [[Darkvision]] 60 ft., [[Passive Perception]] 16, Passive Insight 16,  Passive Stealth 17
languages: Understands Common but can't speak
cr: 4
traits:
  - name: Hundreds of Eyes.
    desc: The oculo swarm has [[advantage]] on Wisdom ([[Perception]]) checks that rely on sight and on [[Saving Throw|saving throws]] against being [[blinded]]. In addition, if the swarm isn't [[blinded]], creatures attacking it can't benefit from traits and features that rely on a creature's allies distracting or surrounding the swarm, such as the Pack Tactics trait or Sneak Attack class feature.  
  - name: Swarm.
    desc: The swarm can occupy another creature's space and vice versa, and the swarm can move through any opening large enough for a Tiny eyeball. The swarm can't regain hp or gain temporary hp.      
actions:
  - name: "Multiattack."
    desc: "The oculo swarm makes two Extract Eye attacks. If both attacks hit one creature, the target must succeed on a DC 13 Strength [[saving throw]] or the swarm removes one of its eyes. While missing half or fewer of its total number of eyes, the target has [[disadvantage]] on [[attack rolls]] and Wisdom ([[Perception]]) checks that rely on sight. While missing more than half its total number of eyes, the target is [[blinded]] until its sight is restored. If the target's eye is recovered from the defeated swarm, it can be reattached with a successful DC 12 Wisdom ([[Medicine]]) check, provided the eye is reattached within 1 hour of the target losing the eye.  "
  - name: "Extract Eye."
    desc: "*Melee Weapon Attack:*  +7 to hit, reach 0 ft., one creature in the swarm's space. *Hit:* 18 (4d8) piercing damage, or 9 (2d8) piercing damage if the swarm has half of its hp or fewer."
  - name: "Disorienting Gaze (Recharge 5–6)."
    desc: "The swarm's many eyes suddenly turn in different directions. Each creature within 10 feet of the oculo swarm must make a DC 13 Charisma [[saving throw]]. On a failure, a creature takes 21 (6d6) psychic damage and is disoriented until the end of its next turn. On a success, a creature takes half the damage and isn't disoriented. A disoriented creature is [[incapacitated]] and moves in a random direction when it moves."  
```