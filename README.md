# snake-game-python-edition

Hi! Gabriel again, with my snake game project. Let me walk you through it!

disclaimer: this game uses python integrated GUI: Turtle to generate a screen where the game functions, so you're probably need an Python Interpreter such as PyCharm to get to play the game.

This game functions just like those snake games from your old Nokia phone, remember? So you use the arrow keys to guide the snake head to the food that'll spawn randomly on the screen, each 
food that you grab will make the snake increase in size more and more. You can keep your score of howmany foods you manage to grap until you collide with your own tail or the walls. The game
also keep track of your highest score.

Some captures of the game:

![image](https://github.com/GabrielTAlberton/snake-game-python-edition/assets/144245356/c3d91f85-8e39-401a-a4aa-201296e13d54)


![image](https://github.com/GabrielTAlberton/snake-game-python-edition/assets/144245356/d333b44d-78cf-4fe3-970f-0721f65c1bb0)


This was the most challenging code games that i made, and i have to admit that i needed some little help when it comes to figure out how to increase the snake in size each time you grab a food.
So, let me try to explain how this all works:

First.  This game is powered by the Turtle library that usually comes integrated in Python, for educational porpuses. This library let you create, inittialy, a turtle that walk around drawing
        where it walks, but it has many resources to create a lot of things and change the shape of the turtle, background image etc.

Second. First we create the screen and setup a window name, window size, background color and activate the tracer, that is a screen function that, with the help of other functions, keeps on 
        refreshing the screen to give you the idea that the snake is moving.

Third.  Now we create the snake body, the head first, with a square shape. And than we make it walk using the .goto function to walk forward to the wherever the direction it's facing. Not only
        that, but a way to detect the collision with the walls, wich will result in game over.

Fourth. We create randomly (x,y) chain spawn food, that the snake need to chase to be able to grown. And have a method to detect if the snake head collided with the food and consume it.

fifth.  Make a way to, each time a food is cosumed, a new part on the snake body is created behind its head. Also, we need to create a collision detection of the head with its own body, wich 
        will also result in game over.

last.   We will create a score board that you keep track of how many foods were eaten in the current gameplay, and also keep track of the highest scoring game.

Well, that's it. I'm learning how to write a documentation of my code and i'm far from decent, but i'll learn more and more each day. Feel free to give me any feedbacks!
