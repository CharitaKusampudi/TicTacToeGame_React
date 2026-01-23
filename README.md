## Tic Tac Toe Game – React
  
This is a classic Tic Tac Toe game built using ReactJS that allows two players to play against each other on the same device.
The application supports custom player names, real-time turn switching, winner and draw detection, and game reset functionality.
The application is deployed on Netlify for easy access and sharing.

## ✨ Features

- Two-player gameplay (X and O)

- Players can edit, save, and display their own names before starting the game

- Active player highlighting during gameplay

- Displays a move history showing every action taken by the players

- Draw detection when all cells are filled

- Game reset to start a new match

- Clean and user-friendly UI

- Responsive design for different screen sizes

## 🛠 Tech Stack

- **Frontend**: ReactJS (Vite), JavaScript (ES6+), HTML5, CSS3,
- **State Management**: React Hooks (useState, useEffect)
- **Build Tool**: Vite
- **Hosting:** Netlify

## 🚀 Live Demo
👉 Live URL:
https://tic-tac-toesreactgame.netlify.app/

## 📦 Getting Started

Follow the steps below to run the project locally.

1.  **Clone the Repository**: First, clone the repository to your local machine using the following command:  
git clone https://github.com/CharitaKusampudi/TicTacToeGame_React.git

2.  **Install Dependencies:** Navigate to the project directory and install the necessary dependencies using npm or yarn:
```
cd TicTacToeGame_React
  
npm install
```
3.  **Run the Application**: Once dependencies are installed, start the app using the following command:

```
npm run dev
```

The application will be available at:http://localhost:5173

### 🧱 App Structure
**/src**: Contains all the source files for the application.  
**/components**: Contains reusable React components used throughout the app, including:  
- **GameBoard**: Renders the Tic Tac Toe grid and handles user interactions when a player selects a cell.  

- **Player**: Allows players to edit, save, and display their custom names. Also highlights the active player during gameplay.  

- **GameOver**: Displays the game result (winner or draw) and provides an option to restart the game.  

**/App.jsx**: The main application component where:  

- Core game logic is managed

- Player turns are controlled

- Components are integrated and rendered

**/main.jsx**: The entry point of the application that renders the React app into the DOM.  

**index.css**: Contains global styles applied across the application.

**🌍 Hosting on Netlify**

To deploy the project on Netlify:
- Push the code to a GitHub repository
- Log in to Netlify using GitHub
- Click New site from Git
- Select the repository
- Configure build settings:
- Build Command: npm run build
- Publish Directory: dist
- Deploy the site
- Netlify will generate a public URL that can be shared.
