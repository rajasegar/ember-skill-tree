# How to edit skill tree?
1. Open `skill-tree.pum`
2. Add relevant items under the appropriate headings

# Run PlantUML from the command line
Use PlantUML's command line syntax to include it in your own scripts or documentation tools:

First, create a text file with PlantUML commands, like this example
```plantuml
@startmindmap
...
**[#Aqua] File Layout
***[#Aquamarine] Classic
***[#Aquamarine] Pods
***[#Aquamarine] MU
***[#Aquamarine] Octane
...
@endmindmap
```

Then, run (or have your software call) PlantUML, using `skill-tree.pum` as input. The output is an image, which either appears in the other software, or is written to an image file on disk.

For example:

```sh
java -jar plantuml.jar skill-tree.pum
```

This outputs your sequence diagram to a file called `skill-tree.png`.

# More Info
- http://plantuml.com/mindmap-diagram


