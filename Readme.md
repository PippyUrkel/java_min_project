 # Java GameBoy Project

 Welcome to the Java GameBoy Project! This is a collection of classic arcade-style games, built using Java and organized in an Eclipse environment. The project is inspired by retro gaming consoles and provides a fun way to explore Java programming through games.

 ## Games Included

 This project includes the following four games, each designed to be modular and easy to run individually:

 1. **Flappy Bird** - Control a bird as it navigates through pipes. Tap to keep the bird airborne and avoid hitting obstacles.
 2. **Match Card Game** - A simple memory game where you flip cards to find matching pairs within a set number of moves.
 3. **Snake Game** - Guide a growing snake to eat food and avoid colliding with walls or its own tail.
 4. **Tetris** - Rotate and place falling shapes to form complete rows and score points.

 Each game is a self-contained module, housed in its own folder within the Eclipse workspace, making it easy to work with or modify them individually.

 ## Project Setup

 ### Prerequisites

 - **Java Development Kit (JDK)** - Version 8 or higher is recommended.
 - **Eclipse IDE** - This project is structured for Eclipse, but it can be run on any IDE that supports Java projects.

 ### Cloning the Repository

 1. Clone the repository using the command:
   ```bash
   git clone https://github.com/your-username/JavaGameBoyProject.git
   ```
 2. Open Eclipse and import the project:
   - Go to **File > Open Projects from File System...**
   - Browse to the location where you cloned the repository and select the folder.
 3. Eclipse will automatically recognize the project structure and import it.

 ## Project Structure

 The project is organized into separate folders for each game, making it easy to navigate:

 ```
 /JavaGameBoyProject
 │
 ├── FlappyBird
 │   └── src
 │       └── main
 │           └── App.java   # Main class to run the Flappy Bird game
 │
 ├── MatchCardGame
 │   └── src
 │       └── main
 │           └── Main.java  # Main class to run the Match Card Game
 │
 ├── SnakeGame
 │   └── src
 │       └── main
 │           └── App.java   # Main class to run the Snake Game
 │
 ├── Tetris
 │   └── src
 │       └── main
 │           └── Main.java  # Main class to run the Tetris Game
 ```

 Each folder contains the game's assets and core files, ensuring each game runs independently without dependencies on the other games.

 ## Running Each Game

 To run any game, follow these steps:

 1. Open **Eclipse** and navigate to the specific game folder in the Project Explorer.
 2. Locate the main class file for each game (`App.java` or `Main.java`) in the `src/main` package.
 3. Right-click on `App.java` or `Main.java` and select **Run As > Java Application**.

 Repeat these steps for any game you want to run. This modular setup allows you to run each game independently.

 ## Game Instructions

 1. **Flappy Bird** - **Controls**: Tap the spacebar to keep the bird flying. **Objective**: Avoid hitting the pipes and survive as long as possible to get a high score.
 2. **Match Card Game** - **Controls**: Click on cards to flip them and reveal the hidden image. **Objective**: Match all pairs of cards within the allowed number of moves to win.
 3. **Snake Game** - **Controls**: Use the arrow keys to guide the snake. **Objective**: Eat the food to grow longer, but avoid crashing into walls or the snake's own body.
 4. **Tetris** - **Controls**: Use the arrow keys to move shapes left or right, up arrow to rotate, and down arrow to speed up. **Objective**: Fit the falling shapes together to complete and clear lines, aiming for a high score.

 ## Customization

 Each game has been structured for ease of customization, making it easy to:
 - Modify graphics and animations in the `resources` folder.
 - Adjust game settings like speed, difficulty, or grid size within each game’s code.
 - Extend gameplay by adding new features (e.g., new levels for Snake, or additional challenges in Tetris).

 ## Troubleshooting

 - **Error: Java version compatibility** - Ensure the installed JDK is compatible with your Java IDE. This project is optimized for JDK 8 or higher.
 - **Project import issues in Eclipse** - If you encounter issues importing the project, try reloading Eclipse or use the **Refresh** option on the project.

 ## License

 This project is **unlicensed**, meaning it is freely available for public use, modification, and distribution without restrictions.

 Feel free to fork this project, make changes, and create your own versions!
