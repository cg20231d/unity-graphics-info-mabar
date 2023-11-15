
# Main

## Create Particle System

Right click on the panel -> Select `effects` -> Select `Particle System`  

![](/resources/create-particle-system.png)  

Result:  

![](/resources/create-particle-system.gif)  

## Attributes
Attributes of main module

![](/resources/main.png)

### 1. Duration
Duration is simply how long the particle system is going to emit particles. Here is an example of Duration = 5.  

![](/resources/duration-and-lifetime.gif)  

Notice that the particle system stops emitting at playback time = 5, but the particles emitted still present.  

### 2. Looping
Check the box to play the particle system in loop.  

### 3. Prewarm
By default, particle system starts emitting particles when we press the play button.  

![](/resources/duration-and-lifetime.gif)  

However, for a certain case, this is not what we want. Suppose we are making a game scene and there is a fire stage with ashes all over the scene to give a dramatic effects. Wouldn't it be weird if the ashes starts appearing only the moment we got there?  

This is when prewarm takes place. With prewarm we can play the particle system as if it already looped once when we press the start button.  

![](/resources/prewarm.gif)

### 4. Start Delay
Giving a delay before the first particle emmittion. For example, when we want to create an explosion effect consisting of multiple particle such as explosion, smoke, and burn mark. Logically, the burn mark should appear only after the explosion.  

![](/resources/start-delay.gif)  

source: [Explosion Particle](https://youtu.be/mJ3k_DLxRU0?si=PZP9IOYKlcmy-72U&t=510)

### 5. Start Lifetime
When a particle is emmitted, it basically starts a countdown before it vanish. Start lifetime determine how long should a particle exists.  

Here is an example of Duration = 5 and Start lifetime = 5.  

![](/resources/duration-and-lifetime.gif)  

The very last particle emmitted would disappear at playback time ≈ 10

### 6. Start Speed
Define the movement speed of particles.  

Start speed = 5  

![](/resources/duration-and-lifetime.gif)  

Start speed = 10  

![](/resources/speed20.gif)  

### 7. 3D Rotation, Start Rotation, Flip Rotation

sek mbuh

### 8. Start Color
The default color of particles is white. However, you can change it using Start Color attribute in RGBA value.  

Default white particle

![](/resources/duration-and-lifetime.gif)  

Red particle

![](/resources/red.gif)  

### The rest

![](/resources/the-rest.png)  

We are not going to cover these attributes since we consider it may overcomplicate today's presentation and we are not going to use them today anyway. If you are interested in more advanced particle system please checkout the links below.  

[]()
