# Ray Tracer

This Ray Tracer is designed to demonstrate how ray tracing works at a basic level. 
Starting from the direction of simulated light, to different refraction and reflection rates by material, different shapes and objects, external cameras, glass, and aperture level focusing. 
Created under the guidance of Carson Cheng, my excellent high school teacher of Computer Science 30/31 AP.
![ImageDemo](https://github.com/user-attachments/assets/a0161376-1300-4d75-82bc-86ba6bd9dc48)
*A demo image 1600 x 900 of RTRandomFinal, my final iteration of this Ray Tracer*

## Beginning Process
Starting from simple 2D shapes to just appear on our swing panels, a relatively basic start, we add features one by one to reach our end goal of a Ray Tracer. Initially, much of the process consisted of hard coding in features we would like to be automatic, like the colours, shape, area, dimensions, location, etc. The goal in the beginning parts is simply to open a path for the future.

![image](https://github.com/user-attachments/assets/ddca3181-49d8-45e4-9ee1-f18fb6f63c76)

*The Red Square*

## Into 3D

The difficulty only picks up when rendering 3D shapes. As compared to 2D, there are many more aspects to consider:
- Coordinates in 3D
- Ray tracing past an object
- Ray normals on an object and angle of reflection
- Degree of refraction and reflection
- Antialiasing
- etc.
It's important to note that while some of these could have been considered in 2D, it would be far less consequential to the 2D results by nature.
Implementing these features took considerable amount of time. Fortunately, I had my instructors guidance when necessary. Overall, this part of the process is where I learned the most about how ray tracing worked, and why it was so computationally expensive. It gave me a deeper profundity for the field of Computer Graphics.

![image](https://github.com/user-attachments/assets/3e3f712e-f7d5-4d85-8cf6-43c2a7763fbd)

*First 3D Image*

## Finishing Touches

Although the bulk of the ray tracer has passed, it could not be complete without some fundamental features. After all, there is more to vision then just light bouncing around until it hits our retina. Important features here consisted of:
- Ray Diffusion
- Lambertian reflection
- Glass
- Moveable Camera
- Focus levels

![image](https://github.com/user-attachments/assets/29365609-c2c2-4dd9-810d-22eb45500709)

*New Features*

Usually, ray tracing is used to provide a higher sense of realism in the graphics. If there was not such an advantage to it, it's unlikely it would be used often. Pre-loaded creations would be much more sensible. It's because with ray-tracing we approach reality at a level different from manual creations. We can simulate the environment to a great degree, and perhaps fully immerse the user into the graphic. These features are at minimum necessary for such a level of ray tracing.


## Concluding Thoughts

This project was very enjoyable, and I recommend anyone to just dig right into it. At first I was taken aback by the scale of this. I didn't think implementing a Ray Tracer from scratch was such a simple thing. But given enough time and passion, it was more than feasible. I'm sure you can too. The more you learn, the more you want to learn. And that just makes this all the more fun.
