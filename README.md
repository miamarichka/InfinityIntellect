# InfinityIntellect
This is a JavaScript implementation of the popular game 2048. Are you ready to put your JavaScript skills to the test? Let's get started!

This project was created with Parcel. To learn about it more, 
please, check the docs (https://parceljs.org/).

## Demo
You can find a live demo of the game [https://miamarichka.github.io/game_2048/](DEMO LINK). Give it a try!

## Instructions
To run the game on your computer, follow these instructions:

1. Replace <your_account> with your Github username in the following link: Github Repository.
2. Clone the repository to your local PC.
3. Navigate to the project directory.
4. Run the following command to install the required dependencies:
Copy code
npm install
5. Once the installation is complete, you can use the following commands to run the game:
Run npm start.


## Here's what you need to know:

- The game field is a 4x4 grid.
- Each cell can either be empty or contain a number that is a power of 2 (2, 4, 8, ... 2^n).
- The player can move the cells using the keyboard arrow keys.
- All the numbers move in the selected direction until all empty cells are filled.
- If two cells with the same number collide, they merge into a cell with the doubled number.
- The merged cell cannot be merged again during the same move.
- A move is considered valid if at least one cell changes after the move.
- After each move, either a 2 or a 4 appears randomly in an empty cell. The probability of a 4 appearing is 10%.
- When the value 2048 is displayed in any cell, a win message will be shown.
- If there are no more available moves, a game over message will be displayed.
- The "Start" button will change to "Restart" after the first move.
- The score will increase with each move. The score will be incremented by the sum of all merged cells.

## Good luck! Have fun playing and implementing the 2048 game.
