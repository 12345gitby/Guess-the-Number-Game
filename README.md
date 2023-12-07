# Guess-the-Number-Game

Welcome to the "Guess The Number Game" project! This Java-based console game involves a guesser who randomly selects a number within a defined range, three players who make their guesses, and an umpire who determines the winner based on matching numbers.
Getting Started
To run the game locally on your machine, follow these steps:
1.Clone the Repository:
git clone https://github.com/12345gitby/guess-the-number.git
cd guess-the-number
2. Compile the Code:
javac GuessTheNumberGame.java
3.Run the Game:
java GuessTheNumberGame
How to Play :
1.The guesser will randomly select a number within a predefined range.
2.Three players will each guess a number within the same range and submit their guesses to the umpire.
3.The umpire will check each player's guess against the guesser's number.
4.If a player's guess matches the guesser's number, that player wins the game.
Configuration
Adjust the game parameters by modifying the following variables in the GuessTheNumberGame.java file:
// Define the range of possible numbers
int minRange = 1;
int maxRange = 100;

// Number of players
int numberOfPlayers = 3;
Sample Output:
The game will display messages indicating the progress and outcome of each round. Here's an example:

Guesser has selected a number between 1 and 100.

Player 1, make your guess: 42
Player 2, make your guess: 75
Player 3, make your guess: 20

Guesser's number: 58

Player 1, your guess is incorrect.
Player 2, your guess is incorrect.
Player 3, your guess is incorrect.

No winners this round. Better luck next time!

Contributions:
Feel free to contribute to this project by opening issues or submitting pull requests. If you have ideas for improvements, bug fixes, or new features, we welcome your input.

