# GDT-110 Rendering Engine
This is my project for the GDT-110 Rendering Engine assignment. Here are the links to the required submissions:

- Link to the GitHub repository: https://github.com/Jimothy2007/GDT-110-RenderingEngine
- Link to the research report Word document: https://1drv.ms/w/c/1bae3a119f73a11b/IQBe2uw9kTyOSJNqLcd4saEBAUPOU_XL4cgj-lU9EjnkDas?e=e6FU8U
- Link to the video explaining the project:

How to run the project:
- Clone the GitHub repository to GitHub desktop by clicking add -> clone repository.
- Go to the Unity hub and click add -> add project from disk then select the folder that the GitHub repository is in.
- Open the Unity project and then you can press play to run the project.

What was made for the project?

For this project, I chose to add post-processing effects to a scene. Unity has a built in way to do this using Global Volume and applying the effects to the camera. I also had to add 5 "primitive" objects to the scene and add textures to each of them. I added a plane with a grass texture, a cube with a dirt texture, a sphere with a crystal texture, a cylinder with a rock texture, and a capsule with a wood texture. Each object also has LOD group components attached to them which swaps out meshes for lower detailed meshes to save on performance.
