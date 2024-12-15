# Entry 2
##### 12/13/2024
### Context
I am writing this blog entry to explain my learning process with Godot. I aim to showcase and explain the documentation I’ve read, learned, and experimented with by using trial and error.
### Experimenting with the tools of Godot
At first, I wanted to follow the documentation to help create my "first 3D game." My first step in the manual was to set up the player scene and actions. To do this, I followed the [manual](https://docs.godotengine.org/en/stable/getting_started/first_3d_game/02.player_input.html), take notes, and apply it to Godot itself. Although I went to do player scenes in blog 1, I didn't mind recapping what happened and adding to the player's actions. Taking notes, I wrote that, Character bodies are complementary to the area and rigid bodies used in the 2D game tutorial. Like rigid bodies, they can move and collide with the environment, but instead of being controlled by the physics engine, you dictate their movement. Characters are objects that can move in command of the user and that they can collide with the surface and things that surround the character.  
By doing some tinkering, I've gotten up to this part of the scene:  
![image](https://github.com/shellyw8542/apcsa-freedom-project/blob/main/Sphere.png)  

This is the formatting of my character and now my next goal is to try to input actions and movement. While trying to work with the interactive platform, I realized that you did not need to know how to code with the movement just yet, but rather you can use this portion of the platform called the "Input Map" which when you press a key bind, the character moves on whatever the coder writes. 
This leads to what I have here:  
![image](https://github.com/shellyw8542/apcsa-freedom-project/blob/main/Godot_Input_Map.png)  

After that, I was curious about the Godot page, so I wanted to look at the troubleshooting [document](https://docs.godotengine.org/en/stable/tutorials/troubleshooting.html). I felt that taking a moment to look at the troubleshooting document would help me develop and overcome problems that I might face when working with this platform. I've noticed that the common issues on the page are mostly linked to one another, some examples being: "The editor or project takes a very long time to start" OR " The project works when run from the editor, but fails to load some files when running from an exported copy." In the document, some issues could be due to the physical laptop, computer, CPU, or any physical thing to operate the platform. I've also realized that the [3D](https://docs.godotengine.org/en/stable/tutorials/3d/index.html) page looks a lot like having all you need to know in one page, which made me appreciate Godot's organization and accessibility for the convenience of my project. I also wanted to start doing the other part of the 3D game [portion](https://docs.godotengine.org/en/stable/getting_started/first_3d_game/03.player_movement_code.html), which is to code instead of doing the interacting part. Learning the component `target_velocity` is a 3D vector that combines speed and direction, and the component `_physics_process()` allows me to update the node every frame, but it is more for physic-related code(kinematic or rigid body). When making the 3D player movement and following the documentation, I found that there can be a different angle that you can use to help support the angling of the camera, there are more points of view using the `Camera3D` component. I was struggling with the component `main` component and the `main.tscn` file. This is what appeared on my screen:

![image](https://github.com/shellyw8542/apcsa-freedom-project/blob/main/Screenshot%202024-12-08%20233834.png)  
To work around this, I used `Node3D` as a substitute and linked it to the components in the tutorial. I also discovered a neat feature that allows you to preview the camera’s angle directly from the main scene. This interactive feature lets you include or exclude the camera by clicking on it. The camera itself has some useful settings to adjust the view component in Godot. Following the documentation eventually led me here:
![image](https://github.com/shellyw8542/apcsa-freedom-project/blob/main/Screenshot%202024-12-08%20234154.png)  

### EDP and Next Steps
I am currently in the "Research the Problem" stage of the Engineering Design Process. At this stage, I research, learn, and experiment with the tool to become familiar with the platform and take notes for my freedom project. My next steps are to continue "Researching the Problem" and start "Brainstorming Possible Solutions" by considering the concepts I’ve learned and applying them to my project. During this blog, I’ve honed the skills of "How to Read" and "How to Learn" by studying the documentation, understanding the concepts and their purposes, and experimenting with them to see the results.

[Previous](entry01.md) | [Next](entry03.md)

[Home](../README.md)
