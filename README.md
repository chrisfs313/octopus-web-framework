This a web framework based on WebGL for 2D Game Development, there's no current oficial documentation but there are somes sample code in: **src/shute-technologies/specs** folder.

## Specs
In order to change which spec is going to be displayed, the developer has to change the file: **index.ts** using the enum in: **src/shute-technologies/specs/enumSpecType.ts** and the available options are:
- SimpleFramework
- SpaceGame

The details of each spec is:

1. **Simple Framework**
The sample code for this is at **src/shute-technologies/specs/types/specTestFramework.ts**, in here are multiple samples of what the framework can do, like:
- Render an image
- Render an animation
- Render a Grid
- Render an 2D effect
- Render a Quad Primitive
- Render a Cirle Primitive

2. **Space Game**
This sample is a whole simple 2D mini-game of side-scroller space shooter, the controls for the are:
- SPACE Key: for shooting the player bullets
- Mouse: for controlling the player movements

The current features of this mini-game are:
- Player with input control
- Player shoots multiple bullets
- Random creation of enemies
- Enemies shoot in random times homing missiles against the player
- Player can destroy an enemy after 2 shoots, there isn't a life bar yet implemented on the enemies.
- Effects when a bullet or missile hit with a spaceship