# Bricks_Breaker_Turtle

Here we will be coding an amazing game which I am pretty sure all of you must have played, it is the Brick Breaker game. We will use the Python turtle module for building the game.

# Getting Started - Setup Turtle:

# macOS/Linux
If you are a macOS User or Linux user, run the following command to create a new virtual environment:
"python3 -m venv turtle_env"
Once the environment is created, let's activate it:
"source turtle_env/bin/activate"

# Windows
If you are a Windows user then, you need to install virtualenv module to set up a virtual environment. It is pretty simple using pip in Python. To install virtualenv module, run:
"pip install virtualenv"
Then create a new environment:
"virtualenv turtle_env"
Then activate the virtual environment:
"cd turtle/env/Scripts" then "ACTIVATE"

Once the virtual environment setup is done. We need to install the turtle module to start using it for game development.Run the following command to install the turtle module:
"pip install turtle"

# Code for Brick Breaker Game

In this game, we have the following main components:
1. Paddle (The horizontal bar at the bottom on which the ball bounces to go back and hit the bricks)
2. Ball
3. Bricks
4. Showing the Score
5. Showing the Lives

And on top of these components, we have to handle the following:
1. Collision between the ball and the paddle
2. Movement of the paddle
3. Collision of the Ball and the Bricks
4. Ball bouncing off the boundaries of the game window
5. End of the game if no bricks or life left 
6. Increment the score
7. Decrement of Lives
