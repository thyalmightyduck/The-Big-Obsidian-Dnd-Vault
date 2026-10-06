---
school:
spell_select_cantrips:
species_select:
class_selector:
spell_level: Level 3
casting_time: 8 Hours
range: 15 ft.
componenets:
  - "-"
exampleProperty: []
progress_value: 0
---
School: `INPUT[inlineSelect(defaultValue(School Of Magic), option(Abjuration), option(Biomancy), option(Conjuration), option(Divination), option(Enchantment), option(Evocation), option(Illusion), option(Necromancy), option(Psionic), option(Transmutation), option(null,School Of Magic)):school]`

Level: `INPUT[inlineSelect(option(Cantrip), option(Level 1), option(Level 2), option(Level 3), option(Level 4), option(Level 5), option(Level 6), option(Level 7), option(Level 8), option(Level 9)):spell_level]`

Casting Time: `INPUT[inlineSelect(option(Action), option(Bonus Action), option(Reaction), option(24 Hours), option(12 Hours), option(8 Hours), option(1 Hour), option(10 Min), option(1 Min)):casting_time]`

Range: `INPUT[inlineSelect(option(Self), option(Touch), option(Sight), option(10 ft.), option(15 ft.), option(20 ft.), option(30 ft.), option(40 ft.), option(50 ft.), option(60 ft.), option(90 ft.), option(100 ft.), option(120 ft.), option(150 ft.), option(180 ft.), option(200 ft.), option(300 ft.), option(500 ft.), option(600 ft.), option(1000 ft.), option(1 Mile), option(5 Miles), option(10 Miles), option(500 Miles), option(unlimited), option(Special)):range]`

Components: `INPUT[multiSelect(option(-), option(Vocal), option(Semantic), option(Material)):componenets]`, `INPUT[inlineSelect(option(-), option(Vocal), option(Semantic), option(Material)):componenets]`, `INPUT[inlineSelect(option(-), option(Vocal), option(Semantic), option(Material)):componenets]` `INPUT[text(defaultValue(Material Componenets Here))]`

# Durations
- Instantaneous

```meta-bind
INPUT[suggester(optionQuery("Rules/Species"), useLinks(partial), title(Species)):species_select]
```
```meta-bind
INPUT[suggester(optionQuery("Rules/Classes"), useLinks(partial), title(Class)):class_selector]
```
```meta-bind
INPUT[listSuggester(optionQuery("Rules/Spells/Cantrips"), useLinks(partial), title(Cantrips)):spell_select_cantrips]
```

```meta-bind
INPUT[multiSelect(option(-), option(Vocal), option(Semantic), option(Material)):componenets]
```


`= this.species_select`

```meta-bind-button
label: 📄 Create Note & Copy Property
icon: plus-circle
style: primary
class: ""
cssStyle: ""
backgroundImage: ""
tooltip: ""
id: ""
hidden: false
actions:
  - type: templaterCreateNote
    templateFile: Templates/Template Test.md
    folderPath: /
    fileName: Character Maker Test
    openNote: true
    openIfAlreadyExists: false

```
