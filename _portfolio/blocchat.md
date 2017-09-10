---
layout: post
title: Bloc Chat
feature-img: "https://github.com/Brandan-Hummell/brandan-hummell.github.io.git/img/bloc_chat_feature.png"
thumbnail-path: "https://github.com/Brandan-Hummell/brandan-hummell.github.io.git/img/bloc_chat_thumbnail.png"
short-description: An AngularJS Chatroom Application

---
## Designing an AngularJS Based Chatroom

This application allows users to across messages across saved chat rooms in real time. Bloc chat utilizes Google's Firebase as a data base to store/retrieve messages from unique char rooms. The user name, as set by a modal when the user first visits, is saved as a cookie on the user's computer. While Bloc set user story goals, I was completely in charge of developing the style and code required for this application.


## Query, Save, Update Data in Real Time

The task to build a chat room required the ability to save and manipulate data from the user's end. Firebase and AngularFire are lightweight solutions that put the strain of data storage on Google's servers. While I have worked with SQL databases to retrieve data in my previous marketing jobs, this was the first time I've used any sort of database in a programming project. Whenever the user creates a chat room or writes a message, the data is saved to the Firebase data base and the data is requeried to update the page accordingly. 


## Bloc Chat Lets Users:

1. Set their username (cookie based)
2. Create and name unique chat rooms that save any previous messages
3. Switch between any existing chat rooms
4. Send messages real time


## Final Thoughts

Firebase worked really well as a database solution for this application. I do not know how well it would scale if hundreds of users were using Bloc Chat at the same time... but the project gave me an important experience with creating a small scale data base and manipulating it with code.

The cookie based user name system, while it works, is inherently flawed. Given more time, I would want to add a user-name/password based system to the Firebase database, so there can be some more consistency. This would also allow different levels of permissions for the user base. 

The modal for creating rooms was surprisingly hard to implement. The poorly written documentation that explained the requirements to use a modal was confounding and non-intuitive. I specifically struggled with the idea of an instance controller, though I was able to figure it all out with a lot of trial & error (and a few hints from my mentor).

