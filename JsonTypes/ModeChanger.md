# Mode Changer
## Inherits from [Actor](Actor.md)
This invisible area changes gameplay mode for player that enters it.

## Game Modes
All players can play the game in one of the different modes. Each game mode has it's unique identifier:
- 0 - `3D Fast Rolling` - This is players default game mode. It's also used in case of invalid game mode identifier. In this game mode player controls the camera and dashing is enabled.
- 1 - `2D Platforming` - In this mode player can roll only horizontally in certain direction.
- 2 - `Top Down` - In this mode player's camera watches from above and jumping is disabled.

### Properties
- `gamemode` - `Number` - This identifier will be used to decide which game mode will be applied by this actor. This property is set to 0 by default. See the list above.
- `gameplay-rotation` - `Number` - Defines rotation angle used by applied game mode. This property is ignored in `3D Fast Rolling` mode.
