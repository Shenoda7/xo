# Tic-Tac-Toe Game (React)

A simple two-player Tic-Tac-Toe game built with React. Players can rename themselves, take turns placing their symbols, and restart the game once it's over.

## Features

- Rename players before or during the game
- Automatic turn handling
- Detects winner or draw
- Game log history
- "Rematch!" button to reset the game

## How to Play

1. **Edit player names** (optional)
2. Players take turns clicking a cell to place their symbol.
3. The game ends when:
    - A player gets **3 in a row** (horizontally, vertically, or diagonally)
    - **All cells are filled** (draw)
4. Click **Rematch!** to play again.

## Technologies Used

- React (with Hooks)
- JavaScript (ES6+)
- Vite (for fast build and dev server)
- CSS for basic styling

## Folder Structure
    src/
    │
    ├── components/
    │   ├── GameBoard.jsx
    │   ├── Log.jsx
    │   └── Player.jsx
    │
    ├── GameOver.jsx
    ├── App.jsx
    ├── main.jsx
    ├── winning-combinations.js
    └── index.css
    └── index.jsx

## Getting Started

### Prerequisites

- Node.js and npm installed

### Installation

```bash
# Clone the repository
git clone https://github.com/Shenoda7/tic-tac-toe-react.git

# Navigate into the project directory
cd tic-tac-toe-react

# Install dependencies
npm install

# Start the development server
npm run dev

