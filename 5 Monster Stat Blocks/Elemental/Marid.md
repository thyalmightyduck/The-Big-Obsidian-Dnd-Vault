---
tags:
  - Monster
  - Elemental
  - MM25
ArmorClass: 17
HitPoints: "229"
Speed:
  - Walking 30ft
  - Fly 60ft
  - Swim 90ft
Saves:
  - DEX
  - CHA
DMGResistances:
  - Acid
  - Cold
  - Lightning
Languages:
  - Primordial (Aquan)
---
# Marid
## Monster Manual 2025 (MM25):
```statblock
layout: Basic 5e Layout
image: [[Marid BGR PNG.png]]
name: Marid
size: Large
type: [[Elemental]]
subtype: (Genie)
alignment: Chaotic Neutral
ac: 17
hp: 229
hit_dice: 17d10+136
speed: 30 ft., Fly 60 ft., Swim 90 ft.
stats: [22, 12, 26, 18, 17, 18]
saves: 
  - DEX: +5
  - CHA: +8
damage_resistances: Acid, Cold, Lightning
senses: Blindsight 30 ft., Darkvision 120 ft., Passive Perception 13, Passive Insight, Passive Stealth 11
languages: Primordial (Aquan)
cr: 11
spells:
  - The marid casts one of the following spells, requiring no Material components and using Charisma as the spellcasting ability (spell save DC 16):
  - At Will: [[Create or Destroy Water]], [[Detect Evil and Good]], [[Detect Magic]], [[Purify Food and Drink]]
  - 1/day each: [[Control Water]], [[Gaseous Form]], [[Invisibility]], [[Plane Shift]], [[Tongues]]  
traits:
  - name: Amphibious.
    desc: The marid can breathe air and water.
  - name: Elemental Restoration.
    desc: If the marid dies outside the Elemental Plane of Water, its body dissolves into brine, and it gains a new body in 1d4 days, reviving with all its [[Hit Points]] somewhere on the Plane of Water.    
  - name: Wishes.
    desc: The marid has a 30 percent chance of knowing the [[Wish]] spell. If the marid knows it, the marid can cast it only on behalf of a non-genie creature who communicates a wish in a way the marid can understand. If the marid casts the spell for the creature, the marid suffers none of the spell's stress. Once the marid has cast it three times, the marid can't do so again for 365 days.  
actions:
  - name: "Multiattack"
    desc: "The marid makes three Aquatic Lash attacks." 
  - name: "Aquatic Lash."
    desc: "_Melee Attack Roll:_ +10, reach 15 ft. _Hit:_ 15 (2d8 + 6) Slashing damage plus 9 (2d8) Cold damage."
  - name: "Water Jet."
    desc: "_Dexterity Saving Throw:_ DC 18, each creature in a 60-foot-long, 10-foot-wide [[Line]]. _Failure:_ 31 (9d6) Cold damage. If the target is a Huge or smaller creature, it is pushed up to 20 feet straight away from the marid and has the [[Prone]] condition. _Success:_ Half damage only."    
bonus_actions:
  - name: "Misty Veil (Recharge 5–6)."
    desc: "The marid casts [[Fog Cloud]], using the same spellcasting ability as Spellcasting."
```