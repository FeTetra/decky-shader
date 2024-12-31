# Decky Shader
## An (ideally) ReShade compatible plugin for the Decky plugin loader
<sub><sup>Note: This is *not* a complete project<sup><sub>

## Todo:
1. Implement shader injection
2. Implement user interface
3. Rework for compatability with ReShade
4. Presets?
5. Per-game profiles?

## Some other notes
Ideally I'd like for this to be ReShade compatible, as in ReShade shaders should work with this. There is currently no existing port of ReShade to Linux platforms, but seeing as I would only have to worry about OpenGL and Vulkan on Linux, it should be a bit less annoying.

This would however, imply I should create a solid and abstracted backend. This would make it way easier to create a GUI wrapper outside of just the Decky plugin interface. For now though, this will remain within this project until I choose to separate it.

