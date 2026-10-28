# Cubey's Make-A-Rama
2026 Scratch Project by Brett Linhardt

A lightweight, 2D, tile-based level editor engineered in Scratch and packaged via TurboWarp into HTML.
Play it in your browser [here](https://blinhardt8-lab.github.io/cubeys-make-a-rama/)!:

## Key Features
* **Frame Independency**: Instead of being capped at 30FPS (native Scratch refresh rate), custom delta time scripts allow movement to be calculated consistently across any monitor.
* **Level Serialization/Deserialization**: Saving a level converts its tilemap data into a long, serialized string, that can be converted back into tile data through a custom level deserializer.
* **Lightweight Collision Physics**: Only adjacent tiles' hitboxes are rendered, while the rest of the level is drawn using pen to avoid lag.

## Controls
1-9: Select Block
E: Erase
R: Rotate
* F: Flip (Symmetrical blocks have a unique variant when flipped!)
* Q: Paint (Press multiple times to cycle through eight colors)
* Q + E: Default color
* Arrow Keys: Switch Rooms (+-1 = horizontal, +-10 = vertical)
* M: Switch Music (toggle)
* N: Reset Level

* P: Save Level
* L: Load Level
* Space: Playtest/Edit
* Z: Debug Mode (hitboxes)

## Credits
Player movement and item pickup code courtesy of griffpatch: [https://www.youtube.com/playlist?list=PLy4zsTUHwGJIATydhFeZa5pspLZR7yE__].
All other scripting by Brett Linhardt.
All music and art by Brett Linhardt.
Sound effects courtesy of Scratch (MIT)'s default sound library.
