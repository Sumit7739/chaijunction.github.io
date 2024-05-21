# tiktactoe.github.io

**Undefeatable Tic Tac Toe - A JavaScript Challenge**

This project implements a Tic Tac Toe game with an unbeatable AI opponent built using JavaScript.

**Features:**

- **Undefeatable AI:** The AI leverages the Minimax algorithm to analyze every possible move sequence and guarantee a win or a draw, making it impossible to defeat.
- **Interactive Gameplay:** Players can choose their symbol (X or O) and take turns placing moves on the 3x3 grid.
- **Clear Board Representation:** The current game state is displayed visually, making it easy to follow the game's progress.

**How to Play:**

1. Visit the following link to play the game in your web browser: https://sumit7739.github.io/tiktactoe.github.io/ 
2. Clone this repository.
3. Open the index.html file in your web browser.
4. Choose your symbol (X or O) from the prompt.
5. Click on an empty square on the board to make your move.
6. The AI will calculate its best move and place its symbol automatically.
7. The game continues until either a player wins, the board is full (resulting in a draw), or an error occurs.

**Technologies Used:**

- JavaScript (HTML, CSS for the user interface)
- Minimax Algorithm (for AI decision-making)

**Running the Project:**

1. Ensure you have a code editor or IDE set up for JavaScript development.
2. Open the `index.html` file in your preferred editor or browser.

**Undefeatable AI with Minimax**

The core of this project lies in the Minimax algorithm, a powerful technique for two-player zero-sum games like Tic Tac Toe. It works by:

1. **Evaluating Potential Outcomes:** The AI considers all possible moves it can make and simulates the game's progression after each move.
2. **Assigning Scores:** Each simulated outcome is assigned a score based on how favorable it is for the AI (winning being the best outcome).
3. **Maximizing Min Scores:** The AI chooses the move that leads to the highest **minimum** score across all possible continuations. This ensures it blocks any potential win by the player and strives for its own victory.

**Challenges and Improvements:**

- **Difficulty Levels:** Explore implementing difficulty levels for the AI by limiting the search depth of the Minimax algorithm, making it more challenging to defeat at lower difficulty settings.
- **Enhanced User Interface:** Consider creating a more visually appealing and interactive user interface with graphical elements, animations, and sound effects.
- **Error Handling:** Implement robust error handling to gracefully handle invalid moves or unexpected scenarios.

**Disclaimer:**

While the AI in this project aims to be unbeatable, there's always the possibility of bugs or unforeseen circumstances. If you manage to find a way to win against the AI, please share your insights as it can help improve the algorithm's effectiveness!

This README file provides a detailed overview of your project, explaining its functionality, technology stack, and the underlying Minimax algorithm. It also suggests potential enhancements and acknowledges the ongoing challenge of creating a truly unbeatable AI.