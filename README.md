# Workshop #2: MVC

---

## Structure

1. In this workshop, you have to implement a project using the MVC pattern.

2. Remember to use all your previous knowledge about good and bad software, dependency inversion, and so on. This material adds to them, not replaces them.

3. It's acceptable for this workshop to be completed by students working together on one computer.

---

## Task

You have been hired to develop a command-line Connect Four game for a client who wants to offer a simple and engaging experience for users. The application should be easy to use and must implement the Model-View-Controller (MVC) pattern.

You can look at [MVC Sample](https://github.com/artem-korotenko/mvc-tic-tac-toe) here or [play a game here](https://www.cbc.ca/kids/games/play/connect-4)

### Requirements

- Implement the Connect Four game using the MVC architectural pattern.
- The game should be playable via the command line.
- User should be asked about playing PvP vs PvE at the session start (in PvE mode computer should just randomly choose a move)
- Players take turns to drop their discs into one of seven columns.
- Model part should be covered with unit tests in a separate project.
- The game should check for a winner after each move (four of the player's discs in a row horizontally, vertically, or diagonally).
- Handle invalid inputs gracefully (e.g., full columns, out-of-range inputs).
- The game should announce the winner or a draw when appropriate.

### Sample Usage

You are free to select how you want to print a field, for example:

```
1 2 3 4 5 6 7
| | | | | | |
| | | | | | |
| | | | | | |
| | | X | | |
| | | O X | |
| | X X O | |
```

### Grading Policy
1 point - overall MVC implementation

1 point - PvP vs PvE

1 point - Correct model implementation with unit tests (at least 5)

1 point - fully working game loop and logic


Good luck with your implementation!