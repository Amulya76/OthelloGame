This project is a Java-based implementation of the Othello (Reversi) board game that supports multiplayer gameplay using a client–server architecture, a graphical user interface (GUI) built with Java Swing, and a basic AI opponent for single-player mode.
The system demonstrates core concepts in:
Computer Networking (TCP sockets)
Multithreading
Object-Oriented Programming (OOP)
GUI development
Game logic and rule enforcement
Introductory Artificial Intelligence (heuristic-based decision making)
🧠 Key Features

✔ Client–Server multiplayer (Client vs Client)

✔ Single-player mode (Client vs AI)

✔ Java Swing GUI

✔ Turn-based gameplay with validation

✔ Real-time board updates

✔ Modular and extensible codebase

| File Name               | Description                                            |
| ----------------------- | ------------------------------------------------------ |
| `OthelloServer.java`    | Starts the server and accepts client connections       |
| `PlayerHandler.java`    | Handles communication with each client (multithreaded) |
| `GameSession.java`      | Controls turn order, move validation, and game flow    |
| `OthelloBoard.java`     | Implements Othello rules and board logic               |
| `OthelloClient.java`    | Terminal-based client                                  |
| `OthelloClientGUI.java` | GUI-based client using Java Swing                      |
| `OthelloGameVsAI.java`  | Single-player mode with AI opponent                    |

🎮 Gameplay Modes
1️⃣ Client vs Client (Multiplayer)

Two clients connect to a central server

Server assigns player colors (Black / White)

GameSession ensures turn-based synchronization

2️⃣ Client vs AI (Single Player)

Player competes against a basic AI

AI selects moves using a greedy heuristic:

Chooses the move that flips the maximum opponent pieces

Prioritizes valid legal moves only

⚙️ System Requirements

Java JDK 8 or higher

Windows / macOS / Linux

Any Java IDE (VS Code, IntelliJ, Eclipse)

📈 Learning Outcomes

Through this project, the following skills were developed:

Java socket programming

Multithreaded server design

GUI development using Swing

Game state management

Modular OOP design

Introductory AI logic

Professional project documentation

🚀 Future Enhancements

Implement Minimax with Alpha-Beta pruning

Add evaluation functions (corners, mobility, stability)

Replace char[][] board with bitboard representation

Add game statistics and replay support

Improve AI with reinforcement learning

Deploy as an online multiplayer game

Amulya Pallikonda
Master’s Student – Computer Science
University of Hartford
