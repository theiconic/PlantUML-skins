# C4 Modelling skin

This skin is an extension of [RicardoNiepel/C4-PlantUML](https://github.com/RicardoNiepel/C4-PlantUML),
which is part of the standard library. We are sourcing the standard library
version and applying our own styling enhancements and additonal
syntax on top.

## Usage
You will need to import either the `C4_Container.iuml` (for Context- or Container-level models)
or the `C4_Component.iuml` (for Component-level models) file. In most cases you
will want to create a Container-level model.
```
@startuml
!includeurl https://raw.githubusercontent.com/TheIconic/PlantUML-skins/master/src/C4/C4_Container.iuml

'...define your model...

@enduml
```

### Video walk-throughs
1) [Plugin Setup and Skin Overview](https://www.loom.com/share/3d265167522144ca85dd1076e8494d66)
2) [Re-modelling existing Draw.io diagram in PlantUML](https://www.loom.com/share/be99494bc5c0488881f92b516f3200f3)
3) [Advanced Layouting](https://www.loom.com/share/16add14f80b0472a94d790b7fec55c47)

## Syntax & Examples
See [samples](samples) folder for examples and syntax.

In particular, you can use the [Container_Level.puml](samples/Container_Level.puml)
file as a starting point for your models and find available elements
in the [Kitchensink](samples/Kitchensink.puml).

You can also consult [the repository of the original skin](https://github.com/RicardoNiepel/C4-PlantUML)
for syntax documentation and more examples.
This, of course, doesn't include the syntax extension provided by this skin.

## AWS Containers
The [AWS container definitions](C4_AWS.iuml) in currently deemed experimental
and may be removed in the future. Please **do not use them**, yet - or your models
may break in the future.
