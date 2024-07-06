# Chess Game App

This is a simple console-based chess game application developed in Java.

## Features

- Complete chess rules: All the moves for each type of piece (pawn, rook, knight, bishop, queen, king) are implemented, including en passant, castling, and promotion.
- Check and Checkmate: The application checks for check and checkmate situations.
- Captured pieces: The application keeps track of all the pieces the player has captured.
- Board printing: The board is printed in the console after each move.

## Technologies Used

- Java
- Maven

## How to Run

1. Clone the repository to your local machine.
2. Navigate to the project directory.
3. Run `mvn clean install` to build the project.
4. Run `java -cp target/chess-java-1.0-SNAPSHOT.jar application.Main` to start the game.

## How to Play

The game is played in the console. Each player enters their move in the format `e2` `e4`, where `e2` is the starting piece position and `e4` is the end position.

