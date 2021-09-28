# Actor
Actors are basic level-building blocks. You can think about them as props that are used to create level's structure.

## Actor Types
There are many actor types that can be spawned in custom levels. Each actor type has it's unique type identifier:
- 0 - 

### Properties
- `type` - `Number` - Actor type to spawn. See the list above for all avaiable values. Using any unsupported type id will prevent this actor from spawning.
- `location` - [Vector](Vector.md) - Level location where this actor will be spawned.
- `rotation` - [Rotator](Rotator.md) - Rotation to set for this actor.
- `scale` - [Vector](Vector.md) - Scale to set for this actor.
