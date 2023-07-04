# Tic-Tac-Toe-
Tic Tac Toe game with AI. Choose to play against a computer or another player. Enjoy strategic gameplay, place X's or O's, and aim to win by getting three in a row. Simple, classic fun for all ages!
The code provided is a Python implementation of the classic game Tic Tac Toe, also known as Noughts and Crosses. The program allows you to play the game against either a computer AI or another human player.

The code defines several functions to handle different aspects of the game:

1. `insertLetter(letter, pos)`: This function inserts a given letter ('X' or 'O') into a specific position on the game board.

2. `spaceIsFree(pos)`: Checks if a given position on the board is empty (contains a space).

3. `printBoard(board)`: Prints the current state of the Tic Tac Toe board.

4. `isWinner(bo, le)`: Checks if a given player ('X' or 'O') has won the game.

5. `playerMove()`: Allows the human player to make a move by choosing a position on the board.

6. `compMove()`: Represents the computer's move. It includes some basic AI logic to make strategic moves.

7. `selectRandom(li)`: Helper function that selects a random element from a given list.

8. `isBoardFull(board)`: Checks if the board is full, indicating a tie when there are no more empty spaces.

9. `main()`: The main game loop that coordinates the game flow, including player and computer moves, checking for a win or tie, and printing the board.

10. The final part of the code is a continuous loop that prompts the player to play again after the game is finished.

Before starting the game, the program will ask the user to select the player mode: '1' for Human vs. Computer and '2' for Human vs. Human. The user can continue playing as many games as they wish, and the board will be reset after each game.

Overall, the code provides a simple but functional implementation of Tic Tac Toe, with the option to play against the computer or another human player.
