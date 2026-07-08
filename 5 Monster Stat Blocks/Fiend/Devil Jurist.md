# Devil Jurist Statblock
```statblock
layout: Basic 5e Layout
image: [[Devil Jurist BGR PNG.png]]
name: Devil Jurist
size: Medium
type: [[Fiend]]
subtype: Devil, Artillery
alignment: Typically Lawful Evil
ac: 16 (Studded Leather)
hp: 156
hit_dice: 24d8+48
speed: 30 ft., Fly 40 ft.
stats: [11, 18, 15, 16, 14, 19]
saves: 
  - INT: +7
  - WIS: +6
  - CHA: +8  
skillsaves:
  - [[Arcana]]: +7
  - [[Deception]]: +8
  - [[Perception]]: +6
  - [[Persuasion]]: +8      
damage_resistances: Bludgeoning, Piercin, And Slashing From Mundane Attacks
damage_immunities: Fire
condition_immunities: [[Charmed]]
senses: [[Darkvision]] 120Ft, Passive Perception 16, Passive Insight 12, Passive Stealth 14
languages: [[Common]] And Infernal
cr: 10
traits:
  - name: Hellfire.
    desc: Fire damage dealt by the jurist ignores damage resistance.
  - name: True Name.
    desc: If a creature the jurist can hear within 60 feet of them speaks the jurist's true name aloud, the jurist loses their damage resistances, damage immunities, and Devilish Charm reaction for 24 hours.    
actions:
  - name: "Multiattack"
    desc: "The jurist makes two Fire and Brimstone attacks."  
  - name: "Fire and Brimstone."
    desc: "_Melee or Ranged Spell Attack:_ +8 to hit, reach 5 ft. or range 120 ft., one target. _Hit:_ 17 (3d8 + 4) fire damage, and the target must succeed on a DC 16 Constitution saving throw or gain one festering wound. A creature takes 4 (1d8) fire damage at the start of each of their turns for each festering wound they have. A creature who receives supernatural healing loses all festering wounds."
  - name: "Inferno (Recharge 5–6)."
    desc:  "The jurist makes one Fire and Brimstone attack against each enemy they can see within 60 feet of them."
bonus_actions:
  - name: "Ashes to Ashes."
    desc: "The jurist chooses a creature they can see within 120 feet of them who has one or more festering wounds. One of the target's wounds ignites and they take 9 (2d8) fire damage."
reactions:
  - name: "Devilish Charm (1/Day)."
    desc: "When the jurist is targeted by an attack, power, spell, or other supernatural effect by a creature they can see within 60 feet of them, the creature must make a DC 16 Charisma saving throw. On a failed save, the creature is [[charmed]] by the jurist until the start of the creature's next turn, and the jurist chooses a new target the jurist can see for the triggering effect. The new target must be within the triggering effect's range."
```