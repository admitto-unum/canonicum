# Description

TODO: give description here.


## Design Documenation

Design documentation will be created using [C4builder](https://adrianvlupu.github.io/C4-Builder/#/?id=overview).  This documenation
tool supports Markdown documents and [C4 Models](https://c4model.com/) using [C4-PlantUML](https://github.com/plantuml-stdlib/C4-PlantUML#supported-diagram-types).   This tool is integrated with [VSCode](https://code.visualstudio.com/) with _PlantUML v2.17.3_ plugn.

The C4Builder tool generates a Web site locally for view using at (http://localhost:3000) while developing documentation.

When editing design documentation the C4Builder can be run to automatically regenerate the site content with

```bash
    c4builder site --watch
```

To run the Web site locally

```bash
    c4builder site
```
