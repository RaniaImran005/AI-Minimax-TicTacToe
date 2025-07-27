# AI-Minimax-TicTacToe
The Minimax algorithm with alpha-beta pruning for AI decision-making is used in the AI Tic-Tac-Toe project. The game is made to let players battle  against AI opponents. Raylib library is used in the implementation of the user interface. The AI uses a search methodology to guarantee the best moves at every  turn, making it impossible to defeat.

Scope of the Project
The project's main characteristics are as follows:
I. Play Tic-Tac-Toe on a 3x3 grid with AI and human opponents.
II. Alpha-beta pruning improves the Minimax method, which the AI opponent use to cut down on pointless computations and accelerate decision-making.
III. Graphical Interface: Using Raylib, the game's graphical user interface (GUI) has a clean, gridbased layout and recognizable X and O marks.
IV. Side Panel Display: A side panel shows real-time information about the status of the game, including the outcome (win, lose, or draw).
V. Dynamic Messaging: Humorous and motivational messages are displayed based on the player's and AI’s performance, adding a unique, playful character to the game.

Selected Data Structures
The following data structures will be employed in the project:
I. 2D Array: A 3x3 2D character array (char board[3][3]) to represent the Tic-Tac-Toe board. Each cell contains either 'X', 'O', or an empty space ' ' to represent the state of the game at any point.
II. Minimax Tree: The game makes use of a recursive decision tree (Minimax) to evaluate all possible game states, with alpha-beta pruning to eliminate unnecessary branches and optimize performance.
