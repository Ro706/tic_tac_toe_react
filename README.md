# Tic-Tac-Toe Game

This is a simple Tic-Tac-Toe game built using React. The game allows two players to take turns placing "X" and "O" on a 3x3 grid. The game automatically detects the winner, or if the game ends in a draw. Players can also reset the game to start over.

## Features

- Two-player gameplay with alternating turns.
- Displays the current status of the game (next player or winner).
- History of moves, allowing players to jump back to any previous state.
- "Reset Game" button to clear the board and start a new game.

## Getting Started

Follow the instructions below to set up and run the project locally.

### Prerequisites

Make sure you have the following installed on your system:

- [Node.js](https://nodejs.org/) (v14 or higher)
- [npm](https://www.npmjs.com/) (comes with Node.js)

### Installation

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/Ro706/tic_tac_toe_react/
   ```

2. Navigate to the project directory:

   ```bash
   cd tic_tac_toe_react
   ```

3. Install the project dependencies:

   ```bash
   npm install
   ```

### Running the Project

Once the dependencies are installed, you can run the project locally using:

```bash
npm start
```

This will start a development server, and the app will be available at [http://localhost:3000](http://localhost:3000) in your browser.

### How to Play

- The game board consists of a 3x3 grid.
- Click on any square to place your mark (X or O).
- The game will alternate between "X" and "O" after each move.
- The current player's turn will be displayed at the top of the board.
- The game will detect a winner and display the result.
- If no player wins, the game will continue until all squares are filled (draw).
- You can reset the game at any time using the **Reset Game** button.
- You can also go back to any previous move using the move history list.

### Project Structure

- `Game.js`: The main game logic including state management for players, move history, and game reset.
- `Board.js`: Renders the game board and handles user interactions.
- `Square.js`: Represents individual squares on the board.
- `App.css`: Contains styles for the game layout.

### Customization

You can customize the styles in `App.css` to give the game a different look. For example, you could change the color scheme, size of the board, or animations.

### Screenshot

![Tic-Tac-Toe Screenshot](path/to/screenshot.png)

### Technologies Used

- **React**: A JavaScript library for building user interfaces.
- **CSS**: Used for styling the game components.

### Future Enhancements

Some potential improvements that can be made to the game:

- Add an AI opponent for single-player mode.
- Improve the UI design for a more polished look.
- Add sound effects for clicks and winning scenarios.
- Implement a timer for each move.

### License

This project is open-source and available under the [MIT License](LICENSE).
