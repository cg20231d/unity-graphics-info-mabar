# Implementation: Smoke Effect

## Create new particle system

![](/resources/create-particle-system.png)  

## Main Module

### 1. Start Color
Change start color to something darker, could be anything but i use rgba(34, 21, 17, 255).  

![](/resources/implementation/i-start-color.png)

### 2. Start Size
Change start size to 1.5.  

![](/resources/implementation/i-start-size.png)  

### 3. Start Speed
Change start speed to 0.7.  

![](/resources/implementation/i-start-speed.png)  

![](/resources/implementation/i-result-1.gif)  

## Emission Module
### 1. Rate Over Time
Change rate over time to 20.  

![](/resources/implementation/i-rate-over-time.png)

![](/resources/implementation/i-result-2.gif)  

## Shape Module
### 1. Angle and Radius
Change angle to 8 and radius to 0.5.  

![](/resources/implementation/i-angle-radius.png)  

![](/resources/implementation/i-result-3.gif)  

## Size Over Lifetime Module
### 1. Curve
Set size over lifetime curve from 1 to arround 0.5.  

![](/resources/implementation/i-size-over-lifetime.png)

![](/resources/implementation/i-result-4.gif)

## Noise
### 1. Strength
Set strength to 0.15.  

![](/resources/implementation/i-noise-strength.png)

![](/resources/implementation/i-result-5.gif)

## Renderer
### 1. Download image for material
Download smoke image from the link below.  

![](/resources/implementation/i-opengameart.png)  

[OpenGameArt: Smoke-Aura](https://opengameart.org/content/smoke-aura)  

Extract smoke.zip after download.  

### 2. Import image
Drag and drop 0001.png to unity assets.  

![](/resources/implementation/i-0001.png)  

### 3. Create material
Create material and name it smoke-sprites.  

![](/resources/implementation/i-create-material.png)

### 4. Drag 0001 to albedo
Drag 0001 to smoke-sprites albedo.  

![](/resources/implementation/i-standard-material.gif)  

### 5. Change shader type
Change smoke-sprites shader type to sprite/default

![](/resources/implementation/i-sprites-default.png)

### 6. Drag smoke-sprites to material
Drag smoke-sprites to material in renderer module.

![](/resources/implementation/i-sprite-drag.gif)  

## Final Result

![](/resources/implementation/i-result-6.gif)  
