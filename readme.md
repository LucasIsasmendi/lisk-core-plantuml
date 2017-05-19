## Conventions

## Run
### [CLI](http://plantuml.com/command-line)
* run all folders and generate png output:

`java -jar ~/java/plantuml.jar -r "plantUML/*/**" -o png`

* run all folders and generate svg output:

`java -jar ~/java/plantuml.jar -r "plantUML/*/**" -o svg -tsvg`

You can also provide a configuration file which will be included before each diagram:
`java -jar ~/java/plantuml.jar -config plantUML/config.txt -r "plantUML/*/**" -o svg -tsvg`

* colors: [link](http://plantuml.com/skinparam)

### Folders
- **activity** [activity diagram](http://plantuml.com/activity-diagram-beta)
- **class** [class diagram](http://plantuml.com/class-diagram)

subfolders with single entities (classes) and relations between them (relationships)

- **deployment** [deployment diagram](http://plantuml.com/deployment-diagram)
- **sequence** [sequence]()
- **state** [state]()
- **use-case** [use-case]()

## Tools
### Atom
[PlantUML Viewer package](https://atom.io/packages/plantuml-viewer)
`ctrl-alt-p`

## Analysis
* Calls (total|files)
logger(309|24)
logic(88|14)
schema(65|18)

network(41|9)
ed(33|9)
config(56|10)
modules(15|10)

bus(14|8)
balancesSequence(13|9)
genesisblock(7|7)
sequence(4|3)
nonce(3|3)

dbSequence(5|1)
public(1|1)
build(1|1)
lastCommit(1|1)
api(0)
connect(0)
ready(0)
listen(0)
