# Graphics Module

## Overview
This module manages the rendering of the 3D environment, projectiles, and targets in Cannonfire. It includes advanced features like lighting, textures, and special effects.

## Key Functions
- `renderObject(Object)`: Renders objects in the 3D environment.
- `applyTextures(Object, Texture)`: Applies textures to the objects.
- `configureLighting()`: Sets up the lighting in the game.

## Rendering Engine
We use Unity's built-in rendering engine for high-quality graphics. This includes support for advanced lighting and shadow effects.

### Requirements and Expectations
- Develop high-quality 3D models for the environment, projectiles, and targets.
- Implement dynamic lighting and shadow effects to enhance realism.
- Ensure that graphics rendering is optimized for performance, especially on lower-end systems.

## Example Usage
```cpp
Object target;
renderObject(target);
applyTextures(target, "targetTexture.png");
configureLighting();
