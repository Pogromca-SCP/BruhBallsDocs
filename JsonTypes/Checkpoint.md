# Checkpoint
## Inherits from [Actor](Actor.md)
This invisible area changes respawn location for player that enters it. To prevent earlier checkpoints from overriding new respawns, each checkpoint has it's own priority level. Checkpoint will activate only when player's current spawn point has lower or equal priority level. Players start the game with priority level -1.

### Properties
- `respawn-location` - [Vector](Vector.md) - Defines relative location from this actor's position, where player will be respawned. By default player will be respawned at this actor's location.
- `priority-level` - `Number` - Priority level for this checkpoint (only integers are used). This property is set to 0 by default.
