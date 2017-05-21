---
layout: post
title: Pong
feature-img: "img/pong_just_the_ball.png"
thumbnail-path: "img/pong_main_page.png"
short-description: The grandfather of all games!

---
Pong is one of the first computer games ever created (if not the first one). Goal of this project was to recreate this legendary game with pure ("vanilla") JavaScript and HTML 5 canvas element.  

I consider myself a gamer and to have knowledge to create even the simplest game was very exciting for me.  As mentioned above, besides HTML canvas element everything was made with vanilla JavaScript, which was good for practicing programming skills. Before I started with development I developed scenarios that can occur while somebody playing the game, which is mostly related to movement of the ball. Moving paddles to hit the ball is quite straight forward.   

The biggest challenge was to animate the ball which bouncing from walls and paddles, and can be shoot with different angles and speeds. Actually the main problem was to prevent “tunneling” when the ball touch walls or paddles. The fact that the ball uses certain number of pixels for movements and that distance between the ball and next point of impact divided with this number should be a whole number. Although the application is not complex, this was the most interesting part. It had fun writing an algorithm to solve this problem.  
