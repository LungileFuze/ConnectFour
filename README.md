# Connect Four - Blazor Implementation

## Overview
This is a **Connect Four** game built using **Blazor**, as part of an evaluation of the framework for game development. The game follows the classic Connect Four rules where two players take turns placing game pieces, aiming to connect four in a row to win.

## Game Rules
1. The game is played on a **7-column x 6-row** grid.
2. Two players take turns dropping a game piece (checker) into one of the columns.
3. The game piece falls to the lowest available row in the selected column.
4. The first player to align **four** game pieces **horizontally, vertically, or diagonally** wins the game.
5. If the grid is completely filled without a winner, the game ends in a **draw**.

## Features
- **Turn-based gameplay** for two players.
- **Blazor UI rendering** for a dynamic web-based experience.
- **Game logic validation** to check for winning conditions.
- **Real-time updates** using Blazor's interactive components.

## Technologies Used
- **Blazor (WebAssembly or Server)**
- **C#** for game logic
- **HTML & CSS** for UI styling
- **.NET** for backend logic (if applicable)

## Getting Started
### Prerequisites
- .NET SDK (Latest version recommended)
- A compatible browser (Chrome, Edge, Firefox, etc.)

### Installation & Running the Game
1. **Clone the repository:**
   ```sh
   git clone https://github.com/yourusername/connect-four-blazor.git
   cd connect-four-blazor
   ```
2. **Build and run the project:**
   ```sh
   dotnet run
   ```
3. Open your browser and navigate to:
   ```
   https://localhost:5001
   ```

## How to Play
1. Click on a column to drop your game piece.
2. The game alternates turns between Player 1 and Player 2.
3. The game automatically detects a win or a draw and displays the result.
4. Refresh the page to restart the game (or implement a reset button).

## Future Improvements
- Add **AI opponent** for single-player mode.
- Implement **online multiplayer** functionality.
- Improve UI/UX with animations and sound effects.
- Add **game restart** and **score tracking** features.

## Contributing
Contributions are welcome! Feel free to submit **issues**, **feature requests**, or **pull requests** to improve the project.

## License
This project is open-source and available under the **MIT License**.

