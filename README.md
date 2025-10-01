This repository contains a small tutorial for running the Intro Game made with Python and Pygame.

Requirements

Python 3 installed on your computer

Pygame library installed

Download or copy the repository

Navigate to the game folder

run this command in your terminal or CMD direct file and whrite: pgzrun intro.py
<img width="1110" height="537" alt="image" src="https://github.com/user-attachments/assets/b2d9a54f-857a-45ba-a445-be79eddc0aee" />

<img width="1580" height="1026" alt="image" src="https://github.com/user-attachments/assets/4260514b-cf68-4468-a343-e90f461eddae" />

the game will run in a small window

<img width="1614" height="999" alt="image" src="https://github.com/user-attachments/assets/27ffd2d9-bdcb-4ba2-9181-0c359ac9bfaf" />



code game created:

import random

TITLE = "intro"
WIDTH = 600
HEIGHT = 400

square = Rect((100, 100), (50, 50))
score = 0

def draw():
    screen.clear()
    screen.fill((200, 200, 200))
    screen.draw.filled_rect(square, "red")
    screen.draw.text(f"Pontos: {score}", (10, 10), fontsize=40, color="black")

def on_mouse_down(pos):
    global score
    if square.collidepoint(pos):
        score += 1

        square.x = random.randint(0, WIDTH - square.width)
        square.y = random.randint(0, HEIGHT - square.height)[intro.py](https://github.com/user-attachments/files/22628903/intro.py)



Game in .zip available


Enjoy the game!
Click on the red square to score points. Close the window to exit


About the Code

The square moves to a random position each time you click it.

Your score increases with each successful click.

Game size: 600x400 pixels.



