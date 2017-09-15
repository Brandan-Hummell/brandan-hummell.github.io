---
layout: post
title: BlocJams
feature-img: "img/bloc_jams_bg.jpg"
thumbnail-path: "img/Bloc_Jams_Thumbnail.PNG"
short-description: Javascript Music Player

---
## My First Major JS Project

BlocJams displays a collection of music and allows you to play through that music with an user-friendly interface. Everything is sorted by artist and album in order to keep the music organized and easy to find. While Bloc provided most of the image assets and style guidelines, it was my job to code the functionality and piece everything together.

## A Music Player Built Three Ways

The task at hand was to make a music player that organizes songs by album and artist. I first built the site using DOM scripting in order to understand the underlying logic behind JS libraries and frameworks that manipulate the DOM. I then incorporated the jQuery library and refactored the site. While I am glad I learned DOM scripting, I was very relieved to learn jQuery, which is a much simpler and semantic way to interact with the DOM. Finally, I refactored the site once again using AngularJS. This process took quite a bit of time since the Angular framework introduced a ton of new jargon and concepts. Once I got past the initial learning curve though, Angular was the easiest and fastest way of the three to create a site like BlocJams.

## The Site Includes:

1. A landing page with a navigation bar
2. A collection page with a list of albums
3. An album page that lists and plays the individual songs from the specific album
4. A player bar that can skip tracks, adjust volume, display any relevant song information, and seek a specific point in a song

{:.center}
![]({{ site.baseurl }}/img/bloc_jams_player_bar.png)

## Final Thoughts

The buzz library was a great tool that makes playing songs with JS a relatively easy process. I would use the buzz library again to work with sound files.

One thing I would change if I revisit the project is how BlocJams stores song and album information. Not only is it inefficient, because there is not central data base involved, but I can't actually add songs to the library in its current state.

Something that took me by surprise was the vast difference between jQuery and AngularJS. jQuery felt much more akin to DOM scripting, albeit more semantic and consolidated. Angular was a whole other beast entirely. True to the definition of a framework, Angular wants to be used in a very specific manner. The file structure, the usage and implementation of controllers, services, directives, and filters, and even the integration within HTML was all so very foreign after completing the project in DOM dcripting and jQuery beforehand.

I gained a ton of insight into the inner workings of a web page. I learning about everything from event handlers to the nuances between CSS display properties. Most of this knowledge with be applicable at large to many - if not all - of my future web development projects.
