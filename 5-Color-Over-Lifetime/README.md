# Color Over Lifetime

## Properties
Properties of color over lifetime module  

![](/resources/color-over-lifetime.png)

First, make sure `Start Color` on main module is white rgba(255, 255, 255, 255).  

![](/resources/white.gif)

### 1. Color
Click color to open color gradient editor.  

![](/resources/gradient-editor.png)  

Bottom left arrow is to set initial color and bottom right arrow is to set end color.  

Change initial color to red and end color to blue.  

![](/resources/color-gradient.png)  

This is what it looks like.  

![](/resources/red-blue.gif)  

### How it works?
Color over lifetime works by blending `Start Color` from main module with `Color` from color over lifetime module. That's why we need to set `Start Color` to white. This is what we got for the same configuration but `Start Color` is green.  

![](/resources/blended.gif)  

### Further Read
[Color Over Lifetime Module](https://docs.unity3d.com/Manual/PartSysColorOverLifeModule.html)  
