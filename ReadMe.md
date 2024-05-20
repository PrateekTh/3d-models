# 3D Modelling

This repository contains some of my 3D Models, made on **Blender**. The focus is on creating efficient topology, and use techniques that will enable low-end systems (and web browsers) to render them easily.

- ### Tomodachi

  A low-poly 3D model (scene) of "Friend" from 20th Century Boys, a really great manga by Urasawa. The steps involved were:

  - Gathering references
  - Modelling, with good, and low topology
  - UV Unwrapping, and marking proper seams
  - Texture painting (manual) (Folder contains the texture file)
  - Manual Rigging from scratch and weight painting

<img src="https://github.com/PrateekTh/3d-models/assets/57175545/d7b10a04-1fd5-4a6a-bda4-942eb5ec97b6" height ="400">

<img src="https://github.com/PrateekTh/3d-models/assets/57175545/70b64712-3084-4aa0-a037-5d8a7145433e" height ="400">


#### Renders : 
The base mesh uses a basic emission shader material, with the texture as the colormap.
The world background contains a procedural texture made using blender's shading nodes.

<img src="https://github.com/PrateekTh/3d-models/assets/57175545/22aa0fb2-40df-499d-bcad-7ec2808efe42" height ="250">
<img src="https://github.com/PrateekTh/3d-models/assets/57175545/4bb0f4bb-9133-4688-9939-2ec4138b410d" height ="250">


- ### Jojolion

  A low-poly model of character - Josuke Higashikata from JJBA part 8 - JOJOLION.

  - Gathering references
  - Modelling, with good, and low topology
  - Vertex-based coloring (using multiple materials)
  - Manual Rigging from scratch
 
  #### Renders :
  The base mesh contains the individual materials, associated to various faces.
  The background is a custom procedural texture made using shading nodes, along with a text with a volumetric shader, and a translucent BSDF surface.
  <img src="https://github.com/PrateekTh/3d-models/assets/57175545/282eaa8f-a0f5-4ee9-b520-7b1650b7dfc7" height ="400">

  With Custom Handpainted Textures: (Texture file in folder)
  <img src="https://github.com/PrateekTh/3d-models/assets/57175545/1dd150b0-2963-4569-a52d-f3dacf162a17" height ="400">

- ### Lighthouse scene
  A lighthouse (under construction)
  ![lh](https://github.com/PrateekTh/3d-models/assets/57175545/9fe95d92-5632-491b-9367-e89732148a9f)
  
- ### Little Ghost
  
  <img src="https://github.com/PrateekTh/3d-models/assets/57175545/cda19e47-08cb-47a8-8c16-362e6b4a0a31" height ="400">
  
  Added a little ghost character. The standard ideal process was followed, and I tried to speed-make it, to practice the complete workflow.

  Now I think I should've given him headphones as well.
  
  <img src="https://github.com/PrateekTh/3d-models/assets/57175545/8414c66d-1b1a-42d4-9458-50ab79beb3bf" height ="200">

 - ### Simple Brutalist Scene
  <img src="https://github.com/PrateekTh/3d-models/assets/57175545/a7b67762-e72c-4d1f-9de1-99535227fde5" height ="400">
  
  Working on assets to build a brutalist architecture based scene, with stripped out monuments (Possibly in an isolated, post-apocalyptic type setting). I was inspired to work on this after listening to [this album](https://youtu.be/LwGkPZcsmH0?si=eTsYbCJFw7qw3FHC). Will make a unity scene out of them soon!
I will eventually use these to create scenes/animations, and test out shaders I create in the shaders repository. This is the primary reason behind a low poly approach, since performance is the objective in this case.
