# Othello.game
This Java program implements a basic version of the board game Othello.

## Board Setup:
The program creates an 8x8 game board for Othello.
At the beginning of the game, it initializes the board with two black and two white pieces arranged diagonally.
## Printing the Board:
There's a method called print() that displays the current state of the board.
It prints out the board with numbers representing empty spaces (0), black pieces (1), and white pieces (2).
## Moving Pieces:
The move() method allows players to make moves on the board.
Players specify the coordinates (x, y) where they want to place their piece.
The method checks if the move is valid and flips opponent pieces according to the rules of Othello.
## Validating Moves:
The program checks if the specified move is valid by scanning in eight directions around the chosen position.
If there are opponent pieces adjacent to the chosen position and the move results in flipping those pieces, it's considered a valid move.
## Main Method:
The main() method is where the game starts.
It initializes the game board and sets up a loop where players take turns making moves.
The loop continues until a specified number of moves have been made.
## Player Turns:
Players alternate turns making moves.
Player 1 is represented by black pieces (1), and Player 2 is represented by white pieces (2).
## Input Handling:
The program uses a Scanner object to read input from the console.
Players input the number of moves they want to make and the coordinates for each move.
Overall, this program provides a simple implementation of Othello where players can make moves and see the board's state after each move. It follows the basic rules of Othello and allows for two players to play against each other.
