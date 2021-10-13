# Escape the stone

## Goal
the goal of this project is to focuse on syntax analysis

This is my final project (Project 9) for the nand2tetris course! It's a Escape the stone game written in the Jack language.

nand2tetris is one of the most rewarding computer science courses I've taken. The course challenges us to build a full application (in this case, Escape the stone) using a high level language (the Jack language) compiled using a compiler we wrote ourselves, with an operating system we write ourselves, running on a hardware platform (the Hack machine) we designed ourselves, powered by a CPU we wired together ourselves. There is nothing left to "magic" and everything is built by the students down to the transistors!

## Game instructions:

The game is over when the stone falls on the boy.

The boy wins when he reaches the top floor.

Use the arrow keys <kbd>←</kbd><kbd>↑</kbd><kbd>↓</kbd><kbd>→</kbd> to move the boy around the grid:

* press <kbd>→</kbd> to move the boy one step right.
* press <kbd>←</kbd> to move the boy one step left.
* press <kbd>↑</kbd> to bounce the boy over the stone in the next row to the right.
* press <kbd>↓</kbd> to bounce the boy over the stone in the next row to the left.

If there are stones near the boy that the difference from the stone on which he stands is greater or equal to two, he will not be able to jump.

If there are stones near the boy that the difference from the stone on which he stands is greater or equal to one, he will not be able to move right or left.

If the boy is at a certain height and he moves right or left to a height that is less than the stone he is standing on, he falls down in the direction he is moving


## How to load the game

Download the [nand2tetris software suite](https://www.nand2tetris.org/software) and run the script `tools/VMEmulator.sh` (on Unix machines) or `tools/VMEmulator.bat` (on Windows machines).

In the VMEmulator Java Applet, click on the folder icon to open a project, and then navigate to the `jack-game-boy-and-stones` directory.

Click on the `jack-game-boy-and-stones` folder and then click "Load Program" to load it.

Click "Yes" when it says "No implementation was found for some functions which are called in the VM code".

Set the "Animate" dropdown option to "No animation".

Finally, click on the fast forward button to run the game!

I pre-compiled the `.vm` files for you in the in the `jack-game-boy-and-stones` directory so you can run the game without compiling. If you would like to compile the `.vm` files yourself, then use your [nand2tetris software suite](https://www.nand2tetris.org/software) to run the JackCompiler to compile all the `.jack` files in the `jack-game-boy-and-stones` folder into `.vm` files.

*Enjoy the game!*