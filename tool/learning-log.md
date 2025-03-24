# Tool Learning Log

## Tool: **Godot**

## Project: **Open World Game**

---

### 9/30/2024: (Getting the gist of Godot)
* For my freedom Project I want to create a game using the tool of Godot
* Starting with the [website](https://docs.godotengine.org/en/stable/getting_started/introduction/introduction_to_godot.html), I read the introduction
* Godot has this community tutorial and resources for additional help and support --> [website](https://docs.godotengine.org/en/stable/community/tutorials.html#doc-community-tutorials)
* Godot also has this screen which makes it organized and a lot like GitHub and Photoshop
* Godot has a component called Nodes
* Nodes are used to store things in the "tree"
* The tree is called a "scene tree" where it stores all the scenes in one place
* There is also a thing called signals that are used to change the code inside the tree. This is very useful and also flexible for some quick changes.

### 10/14/2024:
* This week I want to start looking at tutorials and I found two videos to take notes on
* Tutorial [one](https://www.youtube.com/watch?v=QKgTZWbwD1U&t=10s)
* I learned more about how Godot engine develops games
* Godot has a feature where you can alternate shapes to different sizes called Collision shapes
* Collision shapes are an amazing feature because you can adjust size by using your mouse
* There's also a thing called a Gizmo and it is there to make the shape adjustable for all sizes
* Mesh Instance is when you can make any shape 3d and also realistic with lighting
* The second [tutorial](https://www.youtube.com/watch?v=ntYjl_obUDo&list=PL9FzW-m48fn1iR6WL4mjXtGi8P4TaPIAp) shows me in a slower pace of what the first scene of Godot should look like
* Godot doesn't necessarily need code for a beginning scene, Godot can be used by dragging the mouse and creating new components.
* Godot feels a lot like HTML and CSS but more interactive instead of typing code
* Godot does have the option to write restrictions towards the game but at the moment I would be focusing on how the platform works

### 10/21/2024:
* This week I am just going to go through this [document](https://docs.godotengine.org/en/stable/getting_started/introduction/learning_new_features.html)
* This is called a user manual and it highlights the engine concepts
* There's a way to search up concepts as well using `F1` or searching up `Help`
* [This](https://docs.godotengine.org/en/stable/classes/index.html#doc-class-reference) is all the classes page
* This reference also tells you the class role and what goes through what  
For example: PhysicsBody2D --> Collision2D --> Node2D 
* There is also a community page where when people need help you can always ask for help
* I also wanted to look at this [portion](https://docs.godotengine.org/en/stable/getting_started/introduction/first_look_at_the_editor.html) of the website where it displays all games
* This portion also shows the 3d versions, docks, symbols, folders, bottom panels, etc. 

### 10/28/2024:
* This week I am going to try out Godot by downloading or using this [website](https://godotengine.org/download/windows/)
* I also find this [website](https://docs.godotengine.org/en/stable/getting_started/first_3d_game/index.html)
* After downloading it, I went back to the [tutorial](https://www.youtube.com/watch?v=QKgTZWbwD1U&t=10s) and tried to follow it
* After getting to follow along with the tutorial, I found that Godot is really fun to use since you can interact with the objects and it seems so neat to use it
* We can be able to use code to program the movement of the user or the character
* The mesh component is useful for making solid shapes and adjusting the volume
* I have gotten to make this using the video:
* For the sun positioning I was confused about how to do the angling on the sunlight

![image](https://github.com/shellyw8542/apcsa-freedom-project/blob/main/Screenshot%202024-10-27%20182159.png)

* I circled the component that helped me and I found out that there are icons to make things more organized

![image](https://github.com/shellyw8542/apcsa-freedom-project/blob/main/Screenshot%202024-10-27%20182845.png)

* I enjoy using the platform, there are a lot of components on top of the icon
* I believe that the more I use this tool, I will get better at the workflow

### 11/4/2024 : BLOG 1

### 11/11/2024: 
* This week I plan to look at a document, watch a video, and try it
* For the document on the official website I wanted to look at this [page](https://docs.godotengine.org/en/stable/getting_started/first_3d_game/02.player_input.html)
* This document is all about player scenes and inputting actions
* I already went through the player scenes last week but I don't mind having a recap of it
* Character bodies are complementary to the area and rigid bodies used in the 2D game tutorial. Like rigid bodies, they can move and collide with the environment, but instead of being controlled by the physics engine, you dictate their movement.
* Following the document
* It leads me to this:
![image](https://github.com/shellyw8542/apcsa-freedom-project/blob/main/Sphere.png)
* I finished creating my character and now it is time for me to do input actions
* I've realized that you do not need code to move the character by using the input map feature
* This is what I've gotten so far
![image](https://github.com/shellyw8542/apcsa-freedom-project/blob/main/Godot_Input_Map.png)
* For the next week, I will be continuing to follow the manual on the next document to help with my mini-game

### 11/18 - 11/25
* For this week I wanted to look at the troubleshooting [document](https://docs.godotengine.org/en/stable/tutorials/troubleshooting.html)
* I believe that the troubleshooting portion would be a helpful tool for me since there will be a lot of bugs in the future but it is good to learn now
* There can be a lot of issues that can be relatable like "The editor or project takes a very long time to start" OR " The project works when run from the editor, but fails to load some files when running from an exported copy"
* In the documentation, there can be a lot of issues that are in the program, but they mostly relate to the laptop, computer, CPU, or any physical thing to operate the platform
* I believe that most of this isn't an issue for me, but I'll reexamine it just in case I need it.
* I've also realized that the [3D](https://docs.godotengine.org/en/stable/tutorials/3d/index.html) page looks a lot like having all you need to know in one page
* Godot feels organized and fun to deal with, so I hope it gets better and better when I start working on my project. 
* For this week I wanted to look at the next portion of the 3D game [portion](https://docs.godotengine.org/en/stable/getting_started/first_3d_game/03.player_movement_code.html)
* In this part, this is more towards the coding instead of the interactive part
* The component `target_velocity` is a 3D vector that combines speed and direction
* The `_physics_process()` allows me to update the node every frame, but it is more for physic-related code. (kinematic or rigid body)
* This page is longer than I expected so I will continue to work on this next week.

### 12/9/2024
* This week, I will continue my portion of making a [3D player movement](https://docs.godotengine.org/en/stable/getting_started/first_3D_game/03.player_movement_code.html).
* While tinkering I found that there can be different angles that you can use to help support the angling of the camera so there are more points of view using the `Camera3D` component
* At first when I was following the document, I was struggling with the component `main` and getting the file of `main.tscn`
  
![image](https://github.com/shellyw8542/apcsa-freedom-project/blob/main/Screenshot%202024-12-08%20233834.png)
* I chose to use Node3D as a substitute and link it to the components in the tutorial.
* I've also found a cool feature that I can do to preview the camera's angle from the main scene
* It's interactive and when you click on it you cause the scene to exclude or include the camera
* The camera also has some cool features because it can help adjust the `view` component in Godot

![image](https://github.com/shellyw8542/apcsa-freedom-project/blob/main/Screenshot%202024-12-08%20234120.png)
![image](https://github.com/shellyw8542/apcsa-freedom-project/blob/main/Screenshot%202024-12-08%20234154.png)
### 12/16/2024 : BLOG 2

### 1/3/2025!!!
* During this break I wanted to go over some more documents
* I will be doing the [mob scene](https://docs.godotengine.org/en/stable/getting_started/first_3d_game/04.mob_scene.html)
* My struggle was how to get the file of mob.glb since I didn't know where the Filesystem was on
* After following the document, I've seen the orange dots to help adjust the sizes and also help be interactive
![image](https://github.com/shellyw8542/apcsa-freedom-project/blob/main/Screenshot%202025-01-02%20002353.png)
* The new component to note was the VisibleOnScreenNotifier3D, which is a pink box that will signal once the box completely leaves the screen
* This is what my node looks like:
![image](https://github.com/shellyw8542/apcsa-freedom-project/blob/main/Screenshot%202025-01-02%20002541.png)
* I've used the script feature to help code
* By using VisibleOnScreenNotifier3D component you can signal the node to add a point in I will be trying this out more in the next week

![image](https://github.com/shellyw8542/apcsa-freedom-project/blob/main/Screenshot%202025-01-02%20003535.png)

### 1/13/2025
* This week, I will be working on the coding portion of the mob scene
* Viewing the last week [documentation](https://docs.godotengine.org/en/stable/getting_started/first_3d_game/04.mob_scene.html)
* I've realized that Godot uses `#` for comments and when there's an error in the code it has red on it
![image](https://github.com/shellyw8542/apcsa-freedom-project/blob/main/Screenshot%202025-01-12%20213714.png)
* In this image, the red means the error and the white means the comments
* I found it very neat and visually clear if you made a mistake in the coding.
* For the comments it's a bit more convenient as well since you can just use # instead of what I normally use on Java
* Based on the code, and also my understanding of the document `start_position ` is a spawn point towards the player and you use the `look_at_from_position()` for randomizing the angles depending on the Y-axis
* Using the `randi_range() concept,` random values are given to input for the minimum and maximum speed.
* `queue_free()` method is when a function is gone on the instance when it is being called. 

### 3/3/2025
* This week's learning log, I will be doing my plan and layout of the map for my open-world game
* I will also be trying to get Angela into a Godot collaboration linked to our Github page so it would be better for both of us
* First I will make a wireframe of the layout of our project with Angela
![image](https://github.com/shellyw8542/apcsa-freedom-project/blob/main/wireframefp.png)
* Next I will be following this [video](https://www.youtube.com/watch?v=fZ-CJIYPFMI)
* I worked and I finally got to make a new repository with help from William and the tutorial that he recommended me follow
* Seems that I have to download GitHub and link the file to Godot
* Then I helped Angela download the GitHub Desktop and file it to Godot
* Lastly Angela will help with the design for the enemies model using our project

### 3/10/2025

* For this week, I will be following my MVP plan and scripting the player's movement
* I will be following this [tutorial](https://www.youtube.com/watch?v=UpF7wm0186Q&ab_channel=GDQuest) for the movement
* I will also be following this [tutorial](https://www.youtube.com/watch?v=s9ueeDIeJc8&ab_channel=ExploreGameDev) and this [website](https://www.kenney.nl/assets?search=characters&sort=update) to help get my model for my project
* Something weird about my project was the tutorial told me that I should be able to just drag and drop the file down directly on the website and file, however, it didn't work for me
* I asked Angela if she could help me with the issue because I thought that it was a computer issue but it still didn't work
* Then I figured it out 
* I had to go manually to the Godot file in my computer and add the file into the Godot folder, then I dragged the character that I wanted into the map
* Then I continued to follow the tutorial until when the tutorial stopped and just landed (3:03)
* I coded it so that the player movements are wasd and the jump velocity and speed are set.
![image](https://github.com/shellyw8542/apcsa-freedom-project/blob/main/Screenshot%202025-03-08%20232601.png)

### 3/17/2025 : BLOG 4

### 3/24/2025
* For this week, I will be continuing to follow the tutorial from last week (finishing things up)
* Also checking up with Angela with the enemy.
* I followed what the tutorial says on how I should code the character and how to align it with the camera
* However, I found some mistakes with the code but I cannot figure out why (which will lead me to next week)
* Then I worked on the spring arm and this is what I've worked on:
  ![image](https://github.com/shellyw8542/apcsa-freedom-project/blob/main/Screenshot%202025-03-23%20203609.png)
* For next week I hope to address my issue while working on the map
### 4/1/2025
* For this week, I will be addressing my issue and importing my map
* I also found this cool [video](https://www.youtube.com/watch?v=OdWa6r1yI4U) on how to make a shooting gun in under 2 minutes





<!-- 
* Links you used today (websites, videos, etc)
* Things you tried, progress you made, etc
* Challenges, a-ha moments, etc
* Questions you still have
* What you're going to try next
-->
