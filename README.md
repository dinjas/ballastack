BallStack
=========

This code is a outdated, but someone may find it useful for something (although I have no idea what). :-)

It is a simple iPhone game written in 2008, based on the iPhone 2.0 SDK. The app was last compiled against the 4.2 SDK and everything seemed to be working.

**Note:** This game normally connects to a remote server for managing all the ongoing games, players within the games, and the status of the games but...the server is no longer running. Therefore the code currently is only for reference purposes. The server can probably be reverse engineered pretty easily and I may be able to obtain a copy of the server code (it was in python) if you really need it.

Introduction
------------

This game is the product of a project in a game design course I took while in college, in collaboration with Adam McDonald (@raid5) and Peter Beck. It was largely based off the popular OMGPOP [dinglepop](http://www.omgpop.com/) game.

To implement this game, we created our own game engine (collision detection, game objects, network manager, etc) because at the time the iPhone game engine market was fairly limited.

The Code
--------

This project was one of our first experiences with the iPhone SDK and therefore I'm sure the code quality and practices are not up to par.

That said, here are some details:

* ~34 classes
* 5 view controllers
* ~3,500 lines of code (according to [cloc](http://cloc.sourceforge.net/))

The Interface
-------------

Since the main focus of this project was the game engine and multiplayer networking support, the user interface is a bit lacking.

![Game Menu](https://github.com/raid5/ballstack/raw/master/screenshots/ballstack-intro.jpg)
&nbsp;&nbsp;
![Gameplay 1](https://github.com/raid5/ballstack/raw/master/screenshots/ballstack-gameplay.jpg)
&nbsp;&nbsp;
![Gameplay 2](https://github.com/raid5/ballstack/raw/master/screenshots/ballstack-gameplay-2.jpg)
