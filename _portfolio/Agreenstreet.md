---
layout: post
title: Green street
feature-img: ""
thumbnail-path: "img/"
short-description: Green street, have fun while planning!

---
Green street is a web application which should serve as a tool for street planning, regardless of whether it is going to be used by
professionals or other people involved in transportation and/or urban planning process. The application is made with Rails and Angular 1, and
it is still in development. I chose this project because it suits perfectly for three goals that I set myself, to make something to help the society, to learn more than basic concepts of two frameworks I would like to work with in the future, and to show my dedication and ability to start and finish non-trivial projects on my own.   

Users can make their own proposals for street profiles by simply dragging, dropping and sorting elements which represents common transport modes or other facilities
that makes a street. The idea is not new but I wanted to make some kind of "localization" for Scandinavian market, with more suitable elements and to
add some extra functionality. The application is gonna a be free for all users.

Back-end of the application, as mentioned above, is coded in Rails. For user authentication is utilized Devise gem, where users can create their profiles which will give them possibility to save their street profiles. Rails communicates with Angular, as expected, through an API. Besides application layout, only index page is used in Rails and all routing is happening in Angular with UI-router.

There are several important elements in the front-end, such as main street profile, buildings and street elements which can be dragged and dropped. All of these are custom Angular directives with isolated scopes and they communicate through couple of services. For enable dragging, dropping and sorting jQuery-UI is utilized with customized elements to suit the purpose of the project.

Trying to get two frameworks to work together taught me many things that I wasn't aware before. I spent a lot of time to understand how these two frameworks functioning, what influence performance of the application, and to learn about other important concepts such as rails assets pipeline or how Angular digest cycle works, for instance.
I wrote some part of the code several times from the beginning while my understanding of the technologies was gradually improved and I am still changing it and adding some new things.    
