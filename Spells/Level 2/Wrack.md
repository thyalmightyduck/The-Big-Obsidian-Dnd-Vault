---
tags:
  - spells
school: Necromancy
spell_level: Level 2
casting_time: Action
range: 30 ft.
componenets: Vocal
---
#### Wrack
*Level 2 Necromancy*
___
- **Casting Time:** Action
- **Range:** 30 feet
- **Components:** V, S, M (a frayed piece of cord)
- **Duration:** Concentration, up to 1 minute
---
Choose a creature that you can see within range. The target must succeed on a Constitution saving throw or be afflicted with excruciating muscle spasms for the duration. On a failed save, the target's Speed is halved and it has Disadvantage on attack rolls. The target repeats the save at the end of each of its turns, ending the spell on a success.

**Classes:** Cleric

#### Acid Burn
School: `INPUT[inlineSelect(defaultValue(School Of Magic), option(Abjuration), option(Biomancy), option(Conjuration), option(Divination), option(Enchantment), option(Evocation), option(Illusion), option(Necromancy), option(Psionic), option(Transmutation), option(null,School Of Magic)):school]` Level: `INPUT[inlineSelect(option(Cantrip), option(Level 1), option(Level 2), option(Level 3), option(Level 4), option(Level 5), option(Level 6), option(Level 7), option(Level 8), option(Level 9)):spell_level]`
___
- Casting Time: `INPUT[inlineSelect(option(Action), option(Bonus Action), option(Reaction), option(24 Hours), option(12 Hours), option(8 Hours), option(1 Hour), option(10 Min), option(1 Min)):casting_time]`
- Range: `INPUT[inlineSelect(option(Self), option(Touch), option(Sight), option(10 ft.), option(15 ft.), option(20 ft.), option(30 ft.), option(40 ft.), option(50 ft.), option(60 ft.), option(90 ft.), option(100 ft.), option(120 ft.), option(150 ft.), option(180 ft.), option(200 ft.), option(300 ft.), option(500 ft.), option(600 ft.), option(1000 ft.), option(1 Mile), option(5 Miles), option(10 Miles), option(500 Miles), option(unlimited), option(Special)):range]`
- Components: `INPUT[inlineSelect(option(Vocal), option(Semantic), option(Material)):componenets]`,  `INPUT[text]`
- **Duration:** Instantaneous
---
You magically produce a spray of acidic formula in a 15-foot cone in front of you. All creatures in the cone must succeed on a Dexterity saving throw or take 1d6 acid damage.

This spell's damage increases by 1d6 when you reach 5th level (2d6), 11th level (3d6), and 17th level (4d6).

**Classes:** [[Apothecary]]
