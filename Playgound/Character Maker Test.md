---
species_select: "[[Bugbear]]"
class_selector: "[[The Lantern Warlock]]"
background_selector: "[[Athlete]]"
Name: Name
---
```meta-bind
INPUT[suggester(optionQuery("Species"), useLinks(partial), title(Species)):species_select]
```

```meta-bind
INPUT[suggester(optionQuery("Rules/Classes"), useLinks(partial), title(Class)):class_selector]
```

```meta-bind
INPUT[suggester(optionQuery("Rules/Backgrounds"), useLinks(partial), title(background)):background_selector]
```

```meta-bind
INPUT[text(defaultValue(Name Here)):Name]
```


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
    fileName: "= this.CharacterName"
    openNote: true
    openIfAlreadyExists: false

```

