# Lights

Add real-time lights to a percentage of your particles.

## Properties

![image](https://github.com/cg20231d/unity-graphics-info-mabar/assets/58579201/ee8142e9-93a5-4b64-83ef-e17e56ccc23d)

First, let's create a `Point Light`.

![image](https://github.com/cg20231d/unity-graphics-info-mabar/assets/58579201/8f84df18-96d8-4928-8edb-fa9a14f85f7c)

You can change the color of the `Point Light`.

![image](https://github.com/cg20231d/unity-graphics-info-mabar/assets/58579201/6a7a68a8-c6e6-4549-bdaa-4bd16257503a)

Drag the `Point Light` to the `Light` property.

![image](https://github.com/cg20231d/unity-graphics-info-mabar/assets/58579201/e66728d4-97f3-4fb8-97b6-f6dc9a3babbf)

You can create an Object just to show how the lights module works. For example, I use the cube from the Collision module and change the color to black.

![image](https://github.com/cg20231d/unity-graphics-info-mabar/assets/58579201/4439f801-f766-4d7c-9968-5fc64f4c14fc)

### Ratio

A value between 0 and 1 describing the proportion of particles that will receive a light.

### Random Distribution

Choose whether lights are assigned randomly or periodically. When set to true, every particle has a random chance of receiving a light based on the Ratio. Higher values increase the probability of a particle having a light. When set to false, the Ratio controls how often a newly created particle receives a light (for example, every Nth particle will receive a light).

### Use Particle Color

When set to True, the final color of the Light will be modulated by the color of the particle it is attached to. If set to False, the Light color is used without any modification.

## Further Read

[Lights Module](https://docs.unity3d.com/Manual/PartSysLightsModule.html)