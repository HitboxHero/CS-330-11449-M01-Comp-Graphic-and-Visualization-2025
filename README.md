# CS-330-11449-M01-Comp-Graphic-and-Visualization-2025

## About  
This repository is part of my ongoing CS portfolio. It showcases my work in computer graphics and visualization. Included are my final 3D scene project and a design decisions document that reflect my ability to build a fully realized 3D environment, apply lighting and textures, and explain my development process.

## Repository Contents  

### Project 1 – Final 3D Scene: Kitchen Countertop Simulation  
**Summary (What problem did it solve?):**  
For this project, I recreated a real-world granite kitchen countertop scene using OpenGL. The scene features a spoon rest, a melted butter cube, and a woven black mat. I focused on efficient shape design using simple 3D primitives and high-resolution textures. Lighting was a major hurdle—at first, the scene was completely dark. After revisiting my shaders and light source positions, I added a top-down directional light and a side fill light to achieve better visibility and realism.

**What I did particularly well:**  
I kept the code centralized and focused on achieving clean visuals using minimal complexity. I balanced lighting and texture scaling to create a cohesive, realistic look while maintaining readability and simplicity in the code.

**Where could I enhance my code, and how would it help?:**  
Adding helper functions like `CreateSpoon()` or `CreateMat()` could make the code more modular and reusable, especially if the project were to scale or be maintained long-term.

**Which pieces were most challenging, and how did I overcome them?:**  
Lighting was the hardest part. I went through multiple iterations, including rechecking normals, tweaking the fragment and vertex shaders, and adjusting light angles and intensities to make sure the top-down lighting looked natural and revealed the scene properly.

**Tools and resources added to my network:**  
- OpenGL  
- GLSL for vertex and fragment shaders  
- Phong lighting model  
- WASD navigation and camera control  
- Perspective and orthographic camera toggling  

**Skills transferable to other projects:**  
- Shader programming  
- Lighting and texture mapping  
- 3D spatial reasoning  
- Keyboard and mouse input mapping  
- Designing minimal yet meaningful 3D scenes  

**How I made this project maintainable, readable, and adaptable:**  
I wrote clean, centralized code with useful comments. Instead of breaking everything into tiny parts, I kept objects built directly in `RenderScene()` and managed lighting with clearly defined top and fill light sources.

## Additional Reflections  

### How do I approach designing software?  
I usually start by picturing what I want the end result to look like, then work backward to plan which shapes, textures, and logic I need. I prefer a "keep it simple" approach that avoids unnecessary complexity unless it's really needed.

### What new design skills has your work on the project helped you to craft?  
This project helped me better understand spatial layout in 3D, lighting direction, and how textures and colors affect the realism of a scene. I also got better at visual debugging—figuring out why something looks off and adjusting light or material properties to fix it.

### What design process did you follow for your project work?  
I built and tested incrementally. I’d add one object or texture at a time, tweak its position or UV scaling, then rerun and view it. I didn’t go in with a big architecture; I let the design evolve based on what looked best and what was easiest to implement cleanly.

### How could tactics from your design approach be applied in future work?  
Starting simple and focusing on core functionality first helps keep things from becoming overwhelming. Even in larger projects, I’d still break work into visual layers—get shapes and layout right, then texture, then light, then camera.

### How do I approach developing programs?  
I try to get a basic version working quickly, then refine it. I write code in small chunks, test after each, and use clear comments to keep track of what each part does. I also search for errors as soon as things stop behaving as expected instead of waiting.

### What new development strategies did you use while working on your 3D scene?  
I started using keyboard toggles like switching between perspective and orthographic views, which made testing different views much easier. I also cleaned up shader logic and lighting math, which used to scare me, but now makes more sense.

### How did iteration factor into your development?  
I iterated a lot. Textures, lighting, object positions—all of it took trial and error. The first few versions were way too dark or had misaligned textures. Each round of changes helped me get closer to the clean kitchen scene I had in mind.

### How has your approach to developing code evolved throughout the milestones, which led you to the project’s completion?  
I started out kind of intimidated by shader math and 3D concepts. But by the end, I felt more comfortable editing shaders, tweaking light vectors, and fixing camera movement logic. I also learned to simplify—less really is more when the focus is clarity and polish.

### How can computer science help me in reaching my goals?  
It opens doors to remote work and technical careers where I can solve problems and build useful tools. Even visual projects like this one show how CS lets you bring ideas to life through code.

### How do computational graphics and visualizations give you new knowledge and skills that can be applied in your future **educational** pathway?  
They’ve helped me think in 3D and understand rendering and shading in a way that ties into game development, simulation, and user experience design—areas I might explore further in future courses.

### How do computational graphics and visualizations give you new knowledge and skills that can be applied in your future **professional** pathway?  
These skills make me more versatile. Whether I’m working in UI/UX, data visualization, or even AR/VR, knowing how 3D environments and visuals work gives me an edge in building more immersive and user-friendly tech.

### Bonus Project
2D Breakout Clone With Real-Time Physics and Collision

## Collaborators  
For this assignment, I have added my instructor [**omarsnhu**](https://github.com/omarsnhu) as a collaborator so they can review my portfolio work.

## Acknowledgments  
Thanks to my instructor, Professor Omar Aaziz, my classmates, and Southern New Hampshire University (SNHU) for the support and guidance throughout the CS-330 course.

## Contact  
For any questions or suggestions, feel free to open an issue or contact me directly.
