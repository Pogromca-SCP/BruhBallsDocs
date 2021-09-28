# Actor
Actors are basic level-building blocks. They are used as props that create level's structure.

## Actor Types
There are many actor types that can be spawned in custom levels, some of them can have their own custom properties. Each actor type has it's unique type identifier that must be used in order to spawn it:
- 0 - `Player Spawn` - This actor's location is used to initially spawn players in level. [Learn more](PlayerSpawn.md)
- 1 - `Block` - Basic cube/block used to build level's structure. Can be used for walls, floor, platforms etc.
- 2 - `Blocker` - Invisible cube that prevents players from bouncing/dashing.
- 3 - `Trigger` - Invisible area that triggers race ending if a player enters it. Use it as a finish line for your race map.
- 4 - `Hot Block` - Block that can hurt/kill players that hit it. [Learn more](HotActor.md)
- 5 - `Checkpoint` - Changes players respawn positions. [Learn more](Checkpoint.md)
- 6 - `Mode Changer` - Changes players gameplay modes. [Learn more](ModeChanger.md)
- 7 - `Red Block` - Basic block in red color. This actor type is only temporary and will be removed/replaced in future update!!!
- 8 - `Orange Block` - Basic block in orange color. This actor type is only temporary and will be removed/replaced in future update!!!

### Properties
- `type` - `Number` - Actor type to spawn. See the list above for all avaiable values. Using any unsupported type id will prevent this actor from spawning.
- `location` - [Vector](Vector.md) - Level location where this actor will be spawned.
- `rotation` - [Rotator](Rotator.md) - Rotation to set for this actor.
- `scale` - [Vector](Vector.md) - Scale to set for this actor.
