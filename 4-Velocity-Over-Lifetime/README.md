# Velocity Over Lifetime

## Properties
Properties of velocity over lifetime module  

![](/resources/velocity-over-lifetime.png)  

First, lets set `Start Time` on main module to 0.  

### 1. Linear
X = 5:  
![](/resources/x.gif)  

Y = 5:  
![](/resources/y.gif)  

Z = 5:  
![](/resources/z.gif)

However, this speed is constant and it is not what we want to discuss, with velocity over lifetime we can manipulate particle speed based on their lifetime countdown.

Now, use the dropdown to switch to curve mode.  

![](/resources/curves-mode.png)  

Adjust Z speed to 10 with the little box on top left to make the speed change more noticeable.    

![](/resources/z-curve.png)  

Then drag down the left side of the curve down to 0, and this is what we got.  

![](/resources/velocity-10-overtime.gif)

The particle clustered at the start, because the starting speed is 0, but gradually getting faster over lifetime.  

### 2. Orbital
Orbital is the orbital velocity of particle, which will rotate them around the center of the particle system. The customization is esentially the same with linear which is using X, Y, and Z.

Here is an example of Orbital Z = 10 with Linear Z = 10.  

![](/resources/orbital-z.gif)  

### 3. Radial 
Apply radial velocity to the particle, resulting them to project out of the center of particle.  

Linear Z = 10, Orbital Z = 10, Radial = 1.  

![](/resources/radial.gif)  

### Further Read
[Velocity Over Lifetime Module](https://docs.unity3d.com/Manual/PartSysVelOverLifeModule.html)
