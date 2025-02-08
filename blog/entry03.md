# Entry 3
##### 2/10/2025

### Context
I am writing this blog to explain more about my learning process on Godot and show what I did during the break. 
### Learning more about 3D components / Mob scene
During the break, I wanted to learn more about the coding part and also the mob scene by following the [documents](https://docs.godotengine.org/en/stable/getting_started/first_3d_game/04.mob_scene.html). My first struggle was the how to get the file of mob.glb since I wasn't sure where the Filesystem was and if it was on. However, after more looking in-depth with the Godot client I found it and continued to follow the document, I've seen the orange dots and it helps adjust the sizes and also helps be interactive.  
As seen in the picture below:  
![image](https://github.com/shellyw8542/apcsa-freedom-project/blob/main/Screenshot%202025-01-02%20002353.png)  

There is also another element that is introduced in the document: `VisibleOnScreenNotifier3D`. `VisibleOnScreenNotifier3D` is a pink box that will signal once the box completely leaves the screen.  
Showing what my node looks like:  
![image](https://github.com/shellyw8542/apcsa-freedom-project/blob/main/Screenshot%202025-01-02%20002541.png)  
By using the VisibleOnScreenNotifier3D component you can signal the node to add a point, but this is how the VisibleOnScreenNotifier3D looks like:    
![image](https://github.com/shellyw8542/apcsa-freedom-project/blob/main/Screenshot%202025-01-02%20002541.png)

### Coding portion of the mob scene 
Going more in-depth with the coding portion of the same [mob-scene document](https://docs.godotengine.org/en/stable/getting_started/first_3d_game/04.mob_scene.html). I've realized that in Godot, comments are used with `#` and whenever there is an error in the code, it will highlight the line with red.
![image](https://github.com/shellyw8542/apcsa-freedom-project/blob/main/Screenshot%202025-01-12%20213714.png)  
This image shows the red lines and the transparent lines. Red means error and transparent/gray means that it is usually a comment. Overall I found it  neat and visually clear if and whenever I make a mistake in the coding. For the comments, it's a bit more convenient as well since I can use `#` instead of what I normally use on Java `//`  

Based on the code, and also my understanding of the document `start_position ` is a spawn point towards the player and you use the `look_at_from_position()` for randomizing the angles depending on the Y-axis. Another component to keep in mind is the `randi_range() concept,` random values are given to input for the minimum and maximum speed. Lastly, the `queue_free()` method is when a function is gone on the instance when it is being called. 

That was mostly what I wanted to do over the break and it helped me understand some more components on the starting position and also the coding portion in Godot since I've tinkered and also followed some documentation. 
### EDP and Next Steps

[Previous](entry02.md) | [Next](entry04.md)

[Home](../README.md)
