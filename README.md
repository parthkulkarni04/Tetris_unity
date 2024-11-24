## Tetris
#### Problem statement - 
Develop a simple Tetris game using C# and a game framework such as Unity. The
game should include the following features:
1. Randomly generated Tetriminos (tetrominoes).
2. The ability to move and rotate Tetriminos.
3. The game field (grid) should be able to detect filled rows and clear them.
4. The game should end when the Tetriminos reach the top of the grid.
5. A scoring system that tracks the number of cleared lines.

## Demo
![demo]

[demo]: screenshots/demo.gif


## Features
### Stage / Infinity Mode
The game can start with two different modes. Infinity mode is a classic one, but in the Stage mode, you need to find and clear gems (the orange blocks) to clear the stage and go to the next level.

### Score
When a line is cleared, the score increases based on the number of lines cleared at once. 

### Preview next piece
You can see the next piece of a tetromino upper-right side of the screen.

### Ghost Piece
A tetromino will land if it is allowed to drop into the bottom field. As you moves the falling piece, the ghost piece moves below it.

### Hard/Soft Drop
If you push the space bar, a Tetromino drops instantly to where the Ghost Piece is. It can't be moved or rotated afterwards. It causes the Score to go up. If you need more sensitive control, you can push the down arrow button to drop softly.

### Background Music and Sound effect
Implement the classic BGM as well as the sound effects for Tetris arcade version.

