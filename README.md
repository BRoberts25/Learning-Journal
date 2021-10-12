# Learning-Journal

## 28/09/2021

Start of Programming Module.

My goal within this module is not to be a "master coder", instead just to feel comfortable with the Unity Engine and using C# programming
The aim is to simply be able to think of an idea for a game and be able to confidently make a working prototype of the core mechanics if I ever needed to pitch or deicde to make my own projects.

I think this will be a really important module for me as a game design student as I am not entirely confident in using Unity as an engine as well as code so hopefully this will give me the confidence I need to bettering my Game Design knowledge in general

## 05/10/2021

Today I watched a tutorial by Brackeys on how to control a character in a 3D space with full 3rd Person camera tracking.

It was a fairly simple and a very well made tutorial. The camera was controlled by Cinemachine which is a camera based package for Unity which improves upon the Unity camera system.

The outcome was rather good and I was really proud of myself for being able to complete it, I actually took in quite a bit of information as well, and starting to understand floats and public gameObjects etc which before went straight over my head.

My aim for future weeks is to continue using the same Unity Project and build upon what I already have. That way I feel like this will help me understand how multiple lines of code interact with one another and also may help with my debugging process and build up my confidence on that as well.

I am creating a Youtube Playlist for videos and tutorials for assiting me with the code I wish to learn for the future weeks

Below is a (very) rough outline of what I want to accomplish each week within lecture time:

Week 3: Add a pickup system (possibly with UI score count)
Week 4: Add Instantiate shoot mechanic
Week 5: Add particles to the gun (camera shake + juice)
Week 6: Add targets to shoot
Week 7: Add First Person toggle

*These above plans are planned for in lecture time (2 hours each) however to get things completed and stay on track I plan to do independent work*

## 12/10/2021

In todays lecutre I spent each hour doing doing different things. The first hour of the lecutre was spent playing around with the Unity Particle System and seeing how to implement different shapes and textures and getting a better understanding on how it all works. It will be certainly something I look at outside of lectures to get more familiar with as it is quite a vast system to get to grips with.

The second hour I spent watching First Person Controllers within Unity for my charatcer. The process was very similar as last weeks Third Person camera but did not require the Cinemachine add-on. It made use of the Horizontal and Veritcal movement with GetAxis for movement look. The MouseLook script worked great and even used Clamping to ensure that the player could not upside down past -90 degrees and 90. However I encounted a problem with the script I had created, fortunatley I know the issue I just need to find out how to fix it. As this is the same project as last weeks journal with the Third Person Camera it, it is not quite compatible with both movement scripts and controllers so they are contradicting one another/ taking priority when I do not want them to. 

An easy fix, in theory would be to add a toggle as stated in my To-Do List, that way I can switch between third and first person at ease with seemless and smooth movement and camera transition. However to get around this issue now, I will move the first person assets/scripts out of the current project and reinstate them once other features have been added, if it is still possible down the line. 

Next week I want to look further into adding projectiles with Raycasts into the project.
