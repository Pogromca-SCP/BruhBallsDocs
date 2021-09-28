# BruhBallsDocs
This repository contains technical details about data, formats, etc. used by "Balls'o Bruh".

### Custom Json Types
In addition to the standard Json types, the game also uses its own custom Json types. All custom types are Json objects with additional properties. Some custom types may inherit from other types, the derived type has all properties of the base type, but may interpret them differently.

### Loading Custom Levels
The game can load custom levels directly from `.json` files in `{GameDirectory}/CustomContent/Levels/` directory. [Click here to learm more about custom level structure](Json/Level.md).
