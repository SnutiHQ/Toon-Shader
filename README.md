# Toon-Shader
A Character concentric Toon Shader for Unity using Shader Graph.
This shader use a C# helper script on the object to supply lighting data to the material.

![](Example1.gif)

### Awesomeness & Features
- Supports multiple light sources and types
- Adjustable shading bands
- Beautiful gloss and Fresnel effects
- Shade detection with Raycasting ("faked" shadows)

### Drawbacks
- Not ideal for enviroment shading
- One material per character
- Doesn't receive shadows directly
- Lights are relative to the character rather than the actual mesh surface position. This difference is usually not noticable, apart from when you are standing on top of a light source.

## How to use
1. Apply the "Toon Helper" script to your character
2. Create a material with the Toon Shader, and set this as the `Material` on the "Toon helper".
3. On the material set "Shading Gradient" to one of the gradients in this repo, or make your own.
4. Play around
