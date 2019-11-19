# Toon-Shader
A Character concentric Toon Shader for Unity using Shader Graph.
This shader use a C# helper script on the object to supply lighting data to the material.

We've made a tutorial about this shader on YouTube, check it out:
[![Watch tutorial on YouTube](https://img.youtube.com/vi/0CzdmJVkGKk/0.jpg)](https://www.youtube.com/watch?v=0CzdmJVkGKk)

If you see any mistakes or improvements to be made to this setup, please fork this, make pull requests or open issues.
Everything is made with the MIT lisence and you are welcome to use this in your own private and commercial projects.

### Aweomeness & Features
- Supports multiple light sources and types
- Adjustable shading bands
- Beautiful gloss and Fresnel effects
- Shade detection with Raycasting ("faked" shadows)

### Creaveats & Drawbacks
- Not ideal for enviroment shading
- One material per character
- Doesn't recieve shaodws directly
- Lights are relative to the character rather than the actual mesh surface position. This difference is usually not noticable, apart from when you are standing on top of a light source.

## How to use
1. Apply the "Toon Helper" script to your character
2. Create a material with the Toon Shader, and set this as the `Material` on the "Toon helper".
3. On the material set "Shading Gradient" to one of the gradients in this repo, or make your own.
4. Play around
