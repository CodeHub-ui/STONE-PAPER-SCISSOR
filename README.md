# Stone-Paper-Scissor Game in C

## Overview
This project implements a simple Stone-Paper-Scissor game using the C programming language. The game allows a single player to compete against the computer, where the computer's choice is randomized.

## Features
- Player vs. Computer gameplay.
- Randomized computer moves.
- Clear and interactive user interface in the terminal.
- Input validation to handle incorrect user inputs.
- Displays game outcomes: Win, Lose, or Draw.

## Rules of the Game
1. The player and the computer each choose one of the three options: Stone, Paper, or Scissor.
2. The rules for determining the winner are as follows:
   - Stone beats Scissor.
   - Scissor beats Paper.
   - Paper beats Stone.
   - If both choose the same, it is a Draw.

## Getting Started
### Prerequisites
To run this program, you need:
- A C compiler (e.g., GCC)
- A terminal or IDE for running the program

### Installation
1. Clone or download the repository containing the program.
2. Save the file as `stone_paper_scissor.c`.

### Compilation
Use the following command to compile the program:
```bash
gcc -o stone_paper_scissor stone_paper_scissor.c
```

### Running the Program
Run the compiled program using:
```bash
./stone_paper_scissor
```

## How to Play
1. Upon running the program, you will be prompted to enter your choice:
   - 1 for Stone
   - 2 for Paper
   - 3 for Scissor
2. The computer will randomly select its choice.
3. The program will display both choices and the result of the round (Win, Lose, or Draw).
4. The game can continue for multiple rounds until the player decides to quit.

## Code Structure
- **main()**: Contains the game loop and controls the overall flow of the program.
- **randomChoice()**: Generates a random choice for the computer.
- **determineWinner()**: Determines the result of each round based on player and computer choices.
- **displayChoices()**: Displays the choices made by the player and the computer.
- **validateInput()**: Ensures the player enters a valid choice.

## Example Output
```
Welcome to Stone-Paper-Scissor Game!
Choose an option:
1. Stone
2. Paper
3. Scissor
Enter your choice: 1
You chose: Stone
Computer chose: Scissor
You Win!
Do you want to play again? (y/n): n
Thank you for playing!
```

## Customization
- Modify the game loop to track scores across multiple rounds.
- Add additional choices or rules to extend the game.

## Contributing
Feel free to fork this repository and submit pull requests for enhancements or bug fixes.

## License
This project is open-source and available under the MIT License.

## Acknowledgments
- Thanks to the open-source community for inspiration and tools.

