---
species_select: "[[AArakocra]]"
class_selector: "[[Alienist Apothecary]]"
background_selector: "[[Amnesiac]]"
---
```meta-bind
INPUT[suggester(optionQuery("Rules/Species"), useLinks(partial), title(Species)):species_select]
```

```meta-bind
INPUT[suggester(optionQuery("Rules/Classes"), useLinks(partial), title(Class)):class_selector]
```


```meta-bind
INPUT[suggester(optionQuery("Rules/Backgrounds"), useLinks(partial), title(Class)):background_selector]
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
    templateFile: Templates/Copy Multiple Properties Template.md
    folderPath: /
    fileName: Character Maker Test
    openNote: true
    openIfAlreadyExists: false

```
