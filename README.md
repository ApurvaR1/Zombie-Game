Shoot at Sight

Overview:
"Shoot at Sight" is a dynamic Python game developed using the Pygame and Tkinter modules, aimed at showcasing the implementation of the Singleton and Bridge design patterns. This game challenges players to survive against waves of approaching zombies with limited lives, emphasizing strategic movement and precise shooting.

Installation:
To run "Shoot at Sight", ensure you have Python installed on your machine. Clone this repository and navigate into the game directory:
git clone https://github.com/ApurvaR1/shootatsight.git
cd shootatsight

Install the required dependencies:
pip install -r requirements.txt

Running the Game:
Execute the game with the following command:
python3 game.py

Upon starting the game, enter your name for the leaderboard and navigate through the game using keyboard keys and mouse clicks to aim and shoot at zombies.

Game Mechanics:
Lives: Players start with 5 lives, represented by pumpkins on the top left corner.
Movement: Use A (backward), D (forward), W (left), and S (right) for movement. The Enter key and mouse movement are used for aiming and shooting.
Scoring: Killing a zombie awards one point. The game tracks the top 5 scores.

Design Patterns Implemented:
Singleton Design Pattern
Ensures that only a single instance of the game logic class exists throughout the game's lifecycle, controlling access to game states and player information.

Bridge Design Pattern
Decouples game abstraction (game logic and player interaction) from its implementation (graphics and input handling), allowing for flexibility and ease of maintenance.

Acknowledgments:
Pygame Community
Tkinter Documentation
Python's Math and Datetime Modules for game functionality enhancements
