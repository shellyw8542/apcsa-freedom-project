# Entry 5
##### 4/28/25

#### Context
For this blog entry, I will be writing about my struggles and how I completed my MVP
#### Working on the MVP
I've been working on my MVP and looking through a lot of tutorials like the [map](https://www.youtube.com/watch?v=JxbnStn-BIY&ab_channel=LegionGames), followed by this [platform](https://www.kenney.nl/assets/platformer-kit), the [shooter](https://www.youtube.com/watch?v=OdWa6r1yI4U&ab_channel=GameStick) function, to help continue with my game. However, my partner advised me to redo the whole thing because I messed up on the project formatting and importing the files into different documents. So my partner and I had to redo the whole project during our spring break, as we found it at the last minute. Our friend Dong helped us with the formatting and recommended this [tutorial](https://www.youtube.com/watch?v=-juhGgA076E&ab_channel=DevLogLogan) so that targets can follow you by creating a `mesh` component and a `navigation agent` to correlate with the feature `Navmesh`.  
Which would make the code look like this:   

Which then, after a bit of coding, we made it so that there's an enemy component that can follow you. We wanted to, at first, create a gun and shooting feature, but then we wanted to have an animated melee attack. Hence, we followed this [tutorial](https://www.youtube.com/watch?v=qMBJaVL-vKc&ab_channel=DevLogLogan). I had to create the animation using the `animationplayer`, and you can change the time and the position for the animation. Then we made some code that makes it so that when you left-click, you can swipe across the screen, making it so that it is a melee attack.   
This is what the code looks like:  
![image](https://github.com/shellyw8542/apcsa-freedom-project/blob/main/Screenshot%202025-04-27%20012747.png)
Now I need to work on the attacking portion to finish my part of the MVP, while Angela works on the visuals for the map. So in onder to work on the hp portion I will be following this [tutorial](https://www.youtube.com/watch?v=VZ6GGl_f0hs&ab_channel=GameStick) where it can create the hp bar and that when you go up towards the enemy it changes so that the player loses 10 hp and that I also want to make it so that the enemy can have a set amount of hp and die. After following the tutorial, the hardest thing for me was to make it so that the enemy could attack you. But I embedded the code into the enemy and also towards the player so that when the enemy gets hit by the radius `area` of the melee attack, it gets "hit," which makes it so that they lose 10 hp. Then, after the enemy gets hit 10 times, it dies. This is how the code looks for the enemy when it gets killed:  

And this is the [demo](https://acoolhappy.itch.io/freedom-project?authuser=1) of the MVP. This demo didn't catch the HP scaling because GitHub didn't update when we created this demo. But this is how the HP looks:  

#### EDP and Next Steps
I am currently in "Test and evaluate the prototype," where I created my MVP standards. As long as my project and code work fine, I can work on the visuals and improve the game now. My next steps in the Engineering Design Process are to "Improve as needed." As I've gotten some feedback to make more enemies and maybe a boss to end the game with something cooler, we should also work on the visuals. During this blog, I've used the skills of "Debugging", "Time management", and "How to learn". I've used debugging and learned how to learn throughout all the tutorials, and what I have learned to apply it to my project. While coding, I had numerous codes to compile and a lot of bugs in the code that I had to manually fix. One major thing that messed up my project was how much of a clutter and disorganized the files were in our project. In which we had to use some debugging to help fix those bugs and issues, as well as time management. I've used the skill of time management for the last minute change and how to finish the MVP within a limited amount of days.   

[Previous](entry04.md) | [Next](entry06.md)
 
[Home](../README.md)
