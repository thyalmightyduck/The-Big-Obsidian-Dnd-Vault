# Draconic Spirit
## Player’s Handbook (2024)
```statblock
layout: Basic 5e Layout
image: [[Draconic Spirit BGRP NG.png]]
name: Draconic Spirit
size: Large
type: [[Dragon]]
alignment: Neutral
ac: 14 + the spell's level
hp: 50 + 10 for each spell level above 5
speed: 30 ft., Fly 60 ft., Swim 30 ft.
stats: [19, 14, 17, 10, 14, 14] 
damage_resistances: Acid, Cold, Fire, Lightning, Poison
condition_immunities: [[Charmed]], [[Frightened]], [[Poisoned]]
senses: [[Blindsight]] 30 ft., [[Darkvision]] 60 ft., Passive Perception 12, Passive Insight 12, Passive Stealth 12
languages: Draconic, understands the languages you know
traits:
  - name: Shared Resistances.
    desc: When you summon the spirit, choose one of its Resistances. You have [[Resistance]] to the chosen damage type until the spell ends.  
actions:
  - name: "Multiattack."
    desc: "The spirit makes a number of Rend attacks equal to half the spell's level (round down), and it uses Breath Weapon."
  - name: "Rend."
    desc: "_Melee Attack:_ Bonus equals your spell attack modifier, reach 10 feet. _Hit:_ 7 (1d6+4) + the spell's level Piercing damage."   
  - name: "Breath Weapon."
    desc: "_Dexterity Saving Throw:_ DC equals your spell save DC, each creature in a 30-foot [[Cone]]. _Failure:_ 6 (2d6) damage of a type this spirit has [[Resistance]] to (your choice when you cast the spell). _Success:_ Half damage."  
```