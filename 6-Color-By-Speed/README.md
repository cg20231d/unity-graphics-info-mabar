# Color by Speed

## Properties
Properties of color by Speed module  

![](/resources/color-by-speed.png)  

Before we start: 
- Make sure `Start Color` on main module is white rgba(255, 255, 255, 255).  
- `Start Speed` on main module is 0
- Velocity over lifetime is activated with Z curve 0 to 10

### 1. Color
Click color to open color gradient editor.  

![](/resources/gradient-editor.png)  

Bottom left arrow is to set initial color and bottom right arrow is to set end color.  

Change initial color to green and end color to blue.  

![](/resources/color-gradient-2.png).    

#### Speed range
Since velocity over lifetime is 0 - 10 then set speed range from 0 - 10.  

Result:  

![](/resources/green-blue.gif)  

Notice that particle is green upon spawning and gradually turning to blue while their speed getting faster.  

### Further Read
[Color by Speed Module](https://docs.unity3d.com/Manual/PartSysColorBySpeedModule.html)  
