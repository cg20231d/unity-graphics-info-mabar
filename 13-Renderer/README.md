# Trails

The Renderer module’s settings determine how a particle’s image or Mesh is transformed, shaded and overdrawn by other particles.

## Properties

![image](https://github.com/cg20231d/unity-graphics-info-mabar/assets/58579201/6e093d44-a968-429f-8839-244c9feadd36)

### Render Mode

How Unity produces the rendered image from the graphic image (or Mesh).

We can change how the renderer look, instead of Billboard, let's try to change it to Mesh by clicking `Render Mode` then choose `Mesh`.

![image](https://github.com/cg20231d/unity-graphics-info-mabar/assets/58579201/2762af2f-28b3-4b79-98a3-99f573929731)

Then we can change the shape of the mesh by clicking `Meshes`.

![image](https://github.com/cg20231d/unity-graphics-info-mabar/assets/58579201/8a49bee1-98af-47a6-a591-c073ef52da61)

If we chose Sphere, the particles should look like this:

![image](https://github.com/cg20231d/unity-graphics-info-mabar/assets/58579201/a304fe9a-3cf1-4abe-a68a-f7570d58bbe2)

### Material

The material Unity uses to render the particles.

We can use a sprite (image file) for our particles. First, drag the image you want to use to `Assets`.

![image](https://github.com/cg20231d/unity-graphics-info-mabar/assets/58579201/9951bdfc-19a5-48b3-b85f-5759f293b4cc)

Then create a new material, for example let's name it `Smoke Sprite`.

![image](https://github.com/cg20231d/unity-graphics-info-mabar/assets/58579201/338714f1-9503-4902-ae74-3251baf14ba9)

Click on the `Smoke Sprite`, then change the `Shader` to `Sprites/Default`.

![image](https://github.com/cg20231d/unity-graphics-info-mabar/assets/58579201/039d8099-7653-41f4-9694-355aba3ccdf9)

Then it should look like this :



## Further Read

[Renderer Module](https://docs.unity3d.com/Manual/PartSysRendererModule.html)