# Simple Wind Shader

A simple 2D shader for the godot engine that give sprites like grass or plants a wiggle/wind effect.
This shader is a ported version of the [3D version](https://github.com/Maujoe/godot-simple-wind-shader)

## How to use

There is a demo scene in the demo folder where you can test all features and play with the settings.

If you don't need the demo just ignore the demo folder and connect your mesh with the wind_shader_2d.shader file that can be found in the shaders folder.

## Documentation:

### Shader settings avaiable from Editor/GDscript.
- float speed - The speed of the wind movement.
- float minStrength - The minimal strength of the wind movement.
- float maxStrength - The maximal strength of the wind movement.
- float strengthScale - Scalefactor for the wind strength.
- float interval - The time between minimal and maximal strength changes.
- float detail - The detail (number of waves) of the wind movement.
- float distortion - The strength of geometry distortion.
- float heightOffset - The height where the wind begins to move. By default 0.0.

## License

All parts of this project that are not copyrighted or licensed by someone else are released free under the MIT License - see the LICENSE.md file for details.
