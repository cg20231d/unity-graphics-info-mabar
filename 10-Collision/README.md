# Collision

This module controls how particles collide with GameObjects in a Scene.

Before we start, let's make a cube (you can set it wide and thin like in the picture below), then put the particle right below it and facing upward.

![image](https://github.com/cg20231d/unity-graphics-info-mabar/assets/58579201/c86a5d06-d5fe-4290-a4c8-ec78687b63a1)

After you enabled the Collision, you can change the type to `World` so the particles can collide with the cube.

## Properties

![image](https://github.com/cg20231d/unity-graphics-info-mabar/assets/58579201/e35791c1-e37f-40c9-9d45-ced580d45c07)

### Dampen

The fraction of a particle’s speed that it loses after a collision. Higher values decrease the particle's speed after collision. If you set the dampen to 1, the particle will stop moving after collision.

### Bounce

The fraction of a particle’s speed that rebounds from a surface after a collision.

### Lifetime Loss

The fraction of a particle’s total lifetime that it loses after a collision.

## Further Read

[Collision Module](https://docs.unity3d.com/Manual/PartSysCollisionModule.html)