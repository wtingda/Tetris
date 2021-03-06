# Tetris
Full featured Tetris game with music and color. Written in Python with pygame. Updated with two player competitive mode!

![Alt text](Screen1.png?raw=true "Screenshot")

## Installation
This game requires Python3 and Pygame to launch. Compatability with Python2 has not been tested.

To install Pygame, type the following terminal command.
```sh
python3 -m pip install pygame --user
```
## Launch
To launch this game, simply type
```sh
Python3 Tetris.py
```
Doing so will launch a Pygame window that runs the game. 

To play 2 player mode, type
```sh
Python3 ctetris.py
```

## Start
In the startup screen displaying `Tetris (press any key to continue)`, follow the prompt and press any key to start the game.

![Alt text](Title.png?raw=true "Title")
## Single Player Controls
Control each falling piece using the `A` or `LEFT` keys to move left and `D` or `RIGHT` keys to move right. Press `S` or `DOWN` to accelerate the fall or `SPACE` to teleport the piece to the bottom. Press 'UP' or `E` to rotate the piece clockwise or `Q` to rotate counter-clockwise. 

![Alt text](Screen2.png?raw=true "Screenshot")

After reaching `game over`, press any key to restart. Press `R` at anytime to switch the music if you don't like the randomly picked one.

Press `P` to enter the `Pause` screen. Then, press any key to return, or hit `esc` to quit game.

## 2-Player Controls
Player 1 (on the left) moves blocks using `A-S-D` as in Single Player. `W` rotates the piece clockwise and `Q` rotates it counter clockwise. `SPACE` teleports the piece to the bottom. 

Player 2 (on the right) loves using the arrow keys `LEFT-RIGHT-DOWN` to move the blocks. `UP` rotates the piece clockwise and the `SLASH` key (aka the `?` key) rotates it counterclockwise. `RIGHT-SHIFT` sends the piece to the bottom. 

![Alt text](Screen3.png?raw=true "2P Screenshot")

## Rules
Move any of the pieces down, trying to fill a row with squares to score. Run out of space and it's `game over`. The pieces are randomly generated but the next piece will be shown on the right. The difficulty goes up as your score increases, speeding up the fall of each piece. Each filled in row adds `1` to `score`.

## 2-Player Rules
In addition to the same rules as in single player, when a player clears a level, the opponent's floor is raised by one and the bottom floor will have a randomly generated row (not entirely filled) of blocks.

## Acknowledgements
The music and fonts in this game were used under the Creative Commons license. 

The arcade classic font is copyright (c) Jakob Fischer,  all rights reserved. For noncommerical use only.

The thin pixel font is copyright (c) Sizenko Alexander, for noncommercial use only.

The Tetrominoes font is copyright (c) Tim Marriot, for personal and noncommercial use.

Tetris triste by Crisopa is licensed under a Attribution-NonCommercial-ShareAlike License.

Tetris (Beware Boy, Videogames Are Evil) by Stealing Orchestra is licensed under a Attribution-NonCommercial-NoDerivatives (aka Music Sharing) 3.0 International License.

<a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/3.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-nd/3.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/3.0/">Creative Commons Attribution-NonCommercial-NoDerivs 3.0 Unported License</a>.


