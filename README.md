# Tic Tac Toe

## Description
A simple React Tic-Tac-Toe game designed to reinforce state management and event handling. Players take turns marking the board, with the game determining the winner or a draw. This project helps practice managing component state, handling user interactions, and rendering dynamic UI updates.

### Component, reusable pieces of UI
Game Component: Handles the game logic, history tracking, and winner determination.

Board Component: Displays the 3x3 grid and manages individual squares.

Square Component: Represents each square and allows users to make moves.

### Props, allow components to receive data from their parent
The Game component passes the current board state to the Board component as a prop.

The Board component passes individual square values to the Square components.

### State, data that React tracks and updates when changed
Which player’s turn it is (X or O)

The game board (current squares array)

Move history for undo functionality

## Table of Contents
- [App Demo](#app-demo)
- [Installation](#installation)
- [Contributing](#contributing)
- [Questions](#questions)

## App Demo
![image](https://github.com/user-attachments/assets/d9e8a4fa-9fe4-49c5-b4dc-d81fb5057dd1)


## Installation
To run locally, follow these steps:

1. Clone the repository using the following command:
    ```bash
    git clone https://github.com/FelixW01/tic-tac-toe.git
    ```

2. Navigate to the project directory:
    ```bash
    cd tic-tac-toe
    ```
3. Install Root dependencies:
    ```bash
    npm install
    ```
    
5. Install dependencies:
    ```bash
    npm run build
    ```

5. Run application:
    ```bash
    npm run dev
    ```


## Contributing
Felix Willem
## Questions
If you have any questions please contact me via github: FelixW01 or Email: felixwillem01@yahoo.com.
