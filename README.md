# Kolossus-Sky-Shader
Use this for your own engine if you would like. the shader originates from here with some minor tweaks: https://www.shadertoy.com/view/llffzM


# Getting the shader working in your own engine:
Render the shader to a fullscreen quad and assign the following data to the shader:
1. a vec2 of the resolution you are rendering to: uniform vec2 iResolution;
2. a vec3 of the direction the sun is pointing: uniform vec3 SunVec3;
3. kinda simple, just the view matrix: uniform mat4 ViewMatrix;
4. (SORTA Optional) the shader assumes the FOV of the camera is 80. changing this is simple, make it a uniform float instead
