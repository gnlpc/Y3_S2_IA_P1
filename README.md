# IA_P1 FOCUS

This is a recreation of the [Focus Game](https://boardgamegeek.com/boardgame/789/focus), a 2 player board game.

In this project we aimed to implement the game, as well as an artificial intelligence agent to play against the user or agains another AI agent. 

When the game is initiated the user can choose between playing against another player playing against the computer, which has 3 dificulty levels (easy, medium and hard) or computer vs computer, where a dumb AI will play against a smart AI.

## Algorithms implemented

In order to create the AI agent we implement two different algorithms to play the game.

* The first one and for the easy AI, is a random algorithm, that chooses a random piece of the player randomly, and then chooses a random position to move that piece to, from a list of possible moves.

* To implement the medium and hard levels of dificulty we implemented minimax (with depth 3 and depth 8 respectively).


## Runnin the game  

It is recommend to run the game in a linux distribituion (if ran in windows, WSL usage is recommended)

In order to run our game, you need to have the following libraries installed:
pygame

To install pygame, you can use the following command:
```bash
pip install pygame
```

To run the game, you can use the following command:
```bash
python3 main.py
```

The game will start and you will be given instructions on the menu. 

In the menu you can choose to play the game, see the rules or exit the game. You should select the wanted option on the menu. 
After this you should input your options by writing on the terminal the option you want.


## Conclu

# Contributors:
    - Gonçalo Costa 
    - João Correia 
    - Ricardo Vieira 