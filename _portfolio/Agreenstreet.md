---
layout: post
title: Green street
feature-img: "img/green_street_tmodes.png"
thumbnail-path: "img/street_profile_landing.gif"
short-description: Green street, have fun while planning!

---
Green street is a web application which should serve as a tool for street planning and education, regardless of whether it is going to be used by
professionals or other people involved in transportation and/or urban planning process. **The application is made with Rails and Angular 1, and
it is still in development.** I have chosen this project because it suits perfectly for three goals that I set myself, to make something to help the society, to learn more about two frameworks I would like to work with in the future, and to show my dedication and ability to start and finish non-trivial projects.   

Users can make their own proposals for street profiles by simply dragging, dropping or sorting elements which represents common transport modes or other facilities
that makes a street. The idea is not new but I wanted to make some kind of "localization" for Scandinavian market, with more suitable elements and to
add some extra functionality. The application is gonna a be free for all users.

Back-end of the application, as mentioned above, is coded in Rails. For user authentication Devise gem is used. Users can create their profiles, which will give them possibility to save their work. Rails communicates with Angular, as expected, through an API. All routing is happening in Angular with UI-router.

There are several important elements in the front-end, such as main street profile, buildings and street elements which can be dragged and dropped. All of these are custom Angular directives with isolated scopes and they communicate through couple of services. For enable dragging, dropping and sorting jQuery-UI is used with customized elements to suit the purpose of the project.

Trying to get two frameworks to work together taught me many things that I wasn't aware before. I spent a lot of time to understand how these two frameworks works, and to learn about other important concepts, for instance, what is rails assets pipeline or how Angular digest cycle works. I wrote some part of the code several times from the beginning while my understanding of the technologies was gradually improved and I am still changing it and adding some new features.    
