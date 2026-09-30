---
layout: Basic 5e Layout
name: Aberrant Spirit
size: Maduim
type: Aberration
alignment: Unaligned
ac: 17
modifier: 7
hp: 150
hit_dice: 20d10 + 40
speed: 10 ft., Swim 40 ft.
stats: [21, 9, 15, 18, 15, 18]
saves:
- dexterity: 3
- constitution: 6
- intelligence: 8
- wisdom: 6
skillsaves:
- history: 12
- perception: 10
senses: Darkvision 120 ft., Passive Perception 20
languages: Deep Speech, Telepathy 120 ft.
cr: 10
legendary_description: 'Legendary Action Uses: 3 (4 in Lair). Immediately after another creature''s turn, the aboleth can expend a use to take one of the following actions. The aboleth regains all expended uses at the start of each of its turns.'
traits:
- name: Amphibious
  desc: The aboleth can breathe air and water.
- name: Eldritch Restoration
  desc: If destroyed, the aboleth gains a new body in 5d10 days, reviving with all its Hit Points in the Far Realm or another location chosen by the GM.
- name: Legendary Resistance (3/Day, or 4/Day in Lair)
  desc: If the aboleth fails a saving throw, it can choose to succeed instead.
- name: Mucus Cloud
  desc: |-
    While underwater, the aboleth is surrounded by mucus. *Constitution Saving Throw:* DC 14, each creature in a 5-foot Emanation originating from the aboleth at the end of the aboleth's turn. *Failure:* The target is cursed. Until the curse ends, the target's skin becomes slimy, the target can breathe air and water, and it can't regain Hit Points unless it is underwater.

    While the cursed creature is outside a body of water, the creature takes 6 (1d12) Acid damage at the end of every 10 minutes unless moisture is applied to its skin before those minutes have passed.
- name: Probing Telepathy
  desc: If a creature the aboleth can see communicates telepathically with the aboleth, the aboleth learns the creature's greatest desires.
actions:
- name: Multiattack
  desc: The aboleth makes two Tentacle attacks and uses either Consume Memories or Dominate Mind if available.
- name: Tentacle
  desc: '*Melee Attack Roll:* +9, reach 15 ft. *Hit:* 12 (2d6 + 5) Bludgeoning damage. If the target is a Large or smaller creature, it has the Grappled condition (escape DC 14) from one of four tentacles.'
- name: Consume Memories
  desc: '*Intelligence Saving Throw:* DC 16, one creature within 30 feet that is Charmed or Grappled by the aboleth. *Failure:* 10 (3d6) Psychic damage. *Success:* Half damage. *Failure or Success:* The aboleth gains the target''s memories if the target is a Humanoid and is reduced to 0 Hit Points by this action.'
- name: Dominate Mind (2/Day)
  desc: |-
    *Wisdom Saving Throw:* DC 16, one creature the aboleth can see within 30 feet. *Failure:* The target has the Charmed condition until the aboleth dies or is on a different plane of existence from the target. While Charmed, the target acts as an ally to the aboleth and is under its control while within 60 feet of it. In addition, the aboleth and the target can communicate telepathically with each other over any distance.

    The target repeats the save whenever it takes damage as well as after every 24 hours it spends at least 1 mile away from the aboleth, ending the effect on itself on a success.
legendary_actions:
- name: Lash
  desc: The aboleth makes one Tentacle attack.
- name: Psychic Drain
  desc: If the aboleth has at least one creature Charmed or Grappled, it uses Consume Memories and regains 5 (1d10) Hit Points.
statblock: true
atlas-type: statblock
tags:
- dnd5e
- monster
---
# Aberrant Spirit
## Tasha’s Cauldron of Everything (TCE):
```statblock
layout: Basic 5e Layout
image: [[Aberrant Spirit BGR PNG.png]]
name: Aberrant Spirit
size: Medium
type: [[Aberration]]
alignment: Unaligned
ac: 11 + the level of the spell (natural armor)
hp: 40 + 10 for each spell level above 4th
[[speed]]: 30 ft., [[Fly]] 30 ft. (beholderkin only; hover)
stats: [16, 10, 15, 16, 10, 6]
damage_immunities: Psychic
senses: [[Darkvision]] 60Ft, [[Passive Perception]] 10, Passive Insight 10, Passive Stealth 10
languages: Deep Speech, understands the languages you speak
traits:
  - name: Regeneration (Slaad Only).
    desc: The aberration regains 5 hit points at the start of its turn if it has at least 1 [[hit point]].  
  - name: Whispering Aura (Star Spawn Only).
    desc: At the start of each of the aberration's turns, each creature within 5 feet of the aberration must succeed on a Wisdom [[saving throw]] against your spell save DC or take 7 (2d6) psychic damage, provided that the aberration isn't [[incapacitated]].  
actions:
  - name: "Multiattack"
    desc: "The aberration makes a number of attacks equal to half this spell's level (rounded down)."
  - name: "Eye Ray (Beholderkin Only)."
    desc: "_anged Spell Attack:_ your spell attack modifier to hit, range 150 ft., one creature. _Hit:_ 1d8 + 3 + the spell's level psychic damage."    
  - name: "Claws (Slaad Only)."
    desc: "_Melee Weapon Attack:_ your spell attack modifier to hit, reach 5 ft., one target. _Hit:_ 1d10 + 3 + the spell's level slashing damage. If the target is a creature, it can't regain hit points until the start of the aberration's next turn."
  - name: "Psychic Slam (Star Spawn Only)."
    desc: "_Melee Spell Attack:_ your spell attack modifier to hit, reach 5 ft., one creature. _Hit:_ 1d8 + 3 + the spell's level psychic damage."    
```