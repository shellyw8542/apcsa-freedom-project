# Entry 3
##### 2/10/2025

### Context
I am writing this blog to explain more about my learning process in Godot and show what I did during the break.
### Learning more about 3D components / Mob scene
During the break, I wanted to learn more about the coding part and the mob scene by following the [document](https://docs.godotengine.org/en/stable/getting_started/first_3d_game/04.mob_scene.html). My first struggle was how to get the file mob.glb since I wasn't sure where the Filesystem was or if it was on. However, after looking more in-depth at the Godot client, I found it and continued following the document. I've seen the orange dots, and they help adjust the sizes while also being interactive.
As seen in the picture below:  
![image](https://github.com/shellyw8542/apcsa-freedom-project/blob/main/Screenshot%202025-01-02%20002353.png)  

Another element introduced in the document is `VisibleOnScreenNotifier3D`. `VisibleOnScreenNotifier3D` is a pink box that signals once the box completely leaves the screen.
Showing what my node looks like:  
![image](https://github.com/shellyw8542/apcsa-freedom-project/blob/main/Screenshot%202025-01-02%20002541.png)  
By using the `VisibleOnScreenNotifier3D` you can signal the node to add a point. This is what the `VisibleOnScreenNotifier3D` looks like:  
![image](https://github.com/shellyw8542/apcsa-freedom-project/blob/main/Screenshot%202025-01-02%20002541.png)

### Coding portion of the mob scene 
After going more in-depth with the coding portion of the same mob scene document, I realized that in Godot, comments are used with`#`, and whenever there is an error in the code, the line is highlighted in red.
![image](https://github.com/shellyw8542/apcsa-freedom-project/blob/main/Screenshot%202025-01-12%20213714.png)  
This image shows the red lines and the transparent lines. Red means an error and transparent/gray means that it is usually a comment. Overall, I found it neat and visually clear whenever I made a mistake in the code. For the comments, it's a bit more convenient as well since I can use `#` instead of what I normally use in Java, `//`  

Based on the code and my understanding of the document, `start_position` is a spawn point towards the player, and you use `look_at_from_position()` to randomize the angles depending on the Y-axis. Another component to keep in mind is the `randi_range() concept,` random values are given as input for the minimum and maximum speed. Lastly, the `queue_free()` method removes an instance when it is called.

That was mostly what I wanted to do over the break. It helped me understand more about the starting position and the coding portion in Godot since I've tinkered with and followed some documentation.

### EDP and Next Steps
I am currently in the "Research the Problem" and some of the "Brainstorm Possible Solutions" stages. At this stage, I continue to tinker, read, and take into consideration whether I need to put the things that I've learned from the documents into the overall project. My next steps are to continue with the "Brainstorm Possible Solutions" stage while also starting to "Plan the Most Promising Solution," which is to start planning my MVP. During this blog, I've learned to use the skills of "Consideration" and "How to Learn." I've used the skill of consideration by learning all my components in the documents and taking notes on what I should put in my project to determine if the component is important. I've used the skill of "How to Learn" to teach myself tips and tricks on how to make mobs, code their spawning in an area, and set their direction, as well as how they can have a limitation before disappearing.

[Previous](entry02.md) | [Next](entry04.md)

[Home](../README.md)
