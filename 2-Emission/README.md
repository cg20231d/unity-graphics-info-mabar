# Emission

## Properties
Properties of emission module

![](/resources/emission.png)

### 1. Rate Over Time
How many particle should the system emits per second.  

For example if we set Rate Over Time = 50 with Duration = 1 its gonna look like this:  

![](/resources/rateovertime.gif)

### 2. Bursts
Beside having rate over time, we can have extra burst of particle to custom more effect. Click `+` to add new burst.  

#### Burst properties 
![](/resources/burst-properties.png)  

- Burst time: starting time of the burst
- Burst count: particle count in a single burst
- Burst cycle: how many times should the burst repeat
- Burst interval: burst interval
- Burst Probability: 0 to 1 to randomize burst chance, for now leave it at 1

Here is an example of burst:  
- Duration = 5
- Rate over time = 10
- Burst time = 3
- Burst count = 50
- Burst cycle = 2
- Burst interval = 2
- Burst Probability = 1

![](/resources/burst.gif)

Burst has nothing to do with particles count in rate over time, we can even have a burst with rate over time = 0.

![](/resources/burst2.gif)

### Further Read
Read more about emission module with the link below.

[Emission Module](https://docs.unity3d.com/Manual/PartSysEmissionModule.html)
