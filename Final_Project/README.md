<h1>Adv Coding 1 | Final Project</h1>
<hr>

<h1>Video Link: https://youtu.be/vLLhusq7HOw</h1>
Note: For some reason, the sound isn't very good in the recording.. If you run the code in mimic, you'll notice that the sound is much louder
<hr>

<h1>Code on Mimic: https://mimicproject.com/code/28dd13c0-b3e1-2797-c63e-5625292c1640</h1><hr>
<br>

<h3>Project Description</h3>
<br>

For my final project, I decided to integrate three.js and sound to create a fun composition. The final outcome is a space filled with cubes of many shapes and sizes scattered around and rotating. The way to navigate this space is through the mouse, as it can be used to zoom in/out and even interact with the solid cubes. The interaction with the cubes is a simple one that basically changes the cube colors on mouse hover. This was achieved using raycasting and long hours of trying to figure out how to make it work! Furthermore, this change of color also triggers an audio sound that gives the illusion of touching a physical object without the use of a physics library. 
<br><br>
I originally intended to create a time-based animation that transitions from one three.js scene to another. However, due to my limited coding knowledge, I couldn’t do that and as such, I created an alternative solution! Using a simple rotation command and mouse control, I made a bunch of cubes within cubes that mimic 2D graphics and waves. This was achieved by creating geometry that has a wireframe rather than a solid material, and then animating it without clearing the canvas. Thus, creating the illusion of patterns and morph geometry. This was inspired by Whitney designs and the lessons we had on 2D graphics and generating circles without the predefined circle or arc function! In fact, my code does not have a single sphere geometry, the wireframe waves are simply hundreds of overlapping planes rotating in space. Furthermore, I added another layer of depth by playing around with the camera position so that the geometry fades when the user zooms out. This reduces the number of lines visible in the scene, thus reducing the noise and simultaneously, generating different rotations and shapes with every mouse movement, which overall, creates the feel of a time-based animation. Lastly, I added sound using the Maximilian.js library to bring the geometry to life by adding and multiplying different uploaded samples and generated oscillators. 
<br><br>
Overall, I really enjoyed working on this project, even though I had many failed attempts along the way. I think one of the biggest challenges I had was combining different elements from different weeks. For instance, I originally intended to create a geometry that allows the user to transition between different fragment shaders. I proceeded to create multiple very colorful shaders, but then found myself unable to proceed with idea, because I could not stop my program from crashing upon loading multiple shaders. Another failed attempt was trying to make the looped solid cubes morph and twist into different geometries. I was able to create one morphing cube! However, it was glitching and the loop would not do what I wanted it to do and so I couldn’t use it. There were many attempts like this in the past two weeks, however, I did enjoy the process. To be honest, there’s nothing as exciting as the moment a code that you’ve been working on for hours finally works and the program runs smoothly. As a final note, I am looking forward to exploring more with the material that I’ve gained this semester, especially GLSL and shaders!


<br>
<h3>Photo Documentation</h3>
<br>

![Photo_Documentation2](https://user-images.githubusercontent.com/92052904/144649889-3f5fc052-2a81-4995-b34b-f029e5c649de.jpg)

![Photo_Documentation3](https://user-images.githubusercontent.com/92052904/144649908-b72ed711-c4ab-4392-8617-f6f8dcb8cf13.jpg)

![Photo_Documentation4](https://user-images.githubusercontent.com/92052904/144649914-90937663-8ec0-4829-a20a-223bf8d37811.jpg)

![Photo_Documentation5](https://user-images.githubusercontent.com/92052904/144649916-3a3edc39-59cd-41db-a420-5175eff25971.jpg)

![Photo_Documentation6](https://user-images.githubusercontent.com/92052904/144649920-19a532b7-fe82-4396-aa00-8d26bff15142.jpg)

![Photo_Documentation7](https://user-images.githubusercontent.com/92052904/144649925-27511bd7-df24-40e8-b8c4-3d5426935eea.jpg)

![Photo_Documentation8](https://user-images.githubusercontent.com/92052904/144649929-78214e51-8762-4acd-999d-b55bde798ce4.jpg)

![Photo_Documentation9](https://user-images.githubusercontent.com/92052904/144649932-a756e776-05df-4ea6-a789-0efa16e99266.jpg)
