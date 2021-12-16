# BruhBallsDocs
This repository contains technical details about data, formats, etc. used by "Balls'o Bruh".

## Custom JSON Types
In addition to the standard JSON types, the game also uses it's own custom JSON types. All custom types are JSON objects with additional properties. Some custom types may inherit from other types, the derived type has all properties of the base type, but may interpret them differently. Missing properties are interpreted as null, 0 etc.

## Loading Custom Levels
The game can load custom levels directly from `.json` files in `{GameDirectory}/CustomContent/Levels/` directory. [Click here to learn more about custom level structure](JsonTypes/Level.md).
