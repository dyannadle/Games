Echoes of the Past
"Echoes of the Past" is a unique procedural narrative detective game where players explore an abandoned house, uncover fragmented clues, and piece together a mysterious story using the power of an AI interpreter. Each playthrough offers a new house layout and a different set of clues, leading to varied narrative interpretations.

✨ Features
Procedurally Generated House: Every game session creates a new, unique house layout with different rooms and connections.

Dynamic Clue Placement: Story fragments (objects) are placed randomly within the house, ensuring a fresh mystery each time.

Interactive Exploration: Navigate between rooms and examine objects to uncover hidden clues.

AI-Powered Narrative Conclusion: Once enough clues are gathered, an integrated AI model (Gemini 2.0 Flash) analyzes your findings to generate a plausible, concise story interpretation.

Simple Interface: A clean and intuitive text-based interface makes exploration easy.

Game Log: Keep track of your actions and discoveries in a persistent game log.




<img width="916" height="707" alt="image" src="https://github.com/user-attachments/assets/848c9966-f6fc-48c6-be6e-569f5eabb8b2" />

🎮 How to Play
Start Your Investigation: Upon launching the game, you'll find yourself in the Foyer of a mysterious, abandoned house.

Explore Rooms:

Look at the "Exits" section to see available directions (e.g., "Go North," "Go East").

Click on the direction buttons to move to an adjacent room.

Examine Objects:

In the "Objects in Room" section, you'll see items available for interaction.

Click the "Examine" button next to an object to learn more about it.

Some objects will reveal valuable "Clues."

Collect Clues:

Any clues you find will be added to the "Clues Found" section on the right sidebar.

The game log will also notify you when a new clue is discovered.

Conclude the Story:

Once you've collected at least 3 clues, the "Attempt to Conclude Story" button will appear at the bottom of the main content area.

Click this button to open a modal where the AI will analyze your collected clues and generate a narrative interpretation of what might have happened in the house.

🛠️ Technologies Used
HTML5: For the basic structure of the game.

CSS3 (Tailwind CSS): For responsive and modern styling.

JavaScript (ES6+): For all game logic, procedural generation, and interactivity.

Google Gemini API (gemini-2.0-flash): Used for generating the narrative conclusion based on collected clues.

Firebase SDK (Auth & Firestore): (Planned for future use, currently included for environment compatibility but not fully utilized for saving/loading game state in this version.)

🚀 Setup Instructions
To run this game locally:
Open index.html:
Simply open the index.html file in your web browser. You don't need a local server for this basic version, as all assets are loaded via CDNs.

Note: The game is designed to run in an environment that provides __app_id, __firebase_config, and __initial_auth_token global variables (like a Google Canvas environment). If running purely locally without these, Firebase authentication will default to anonymous sign-in, and the game will still function, but persistence features won't be active without a proper Firebase project setup.

💡 Future Enhancements
Game State Persistence: Implement saving and loading of game progress using Firebase Firestore.

Inventory System: Allow players to pick up and use items.

More Complex Puzzles: Introduce multi-step puzzles that require combining clues or items.

Sound Effects & Music: Add ambient sounds and background music to enhance the atmosphere.

Visual Enhancements: Consider adding simple graphics or animations to rooms and objects.

Multiple Endings: Design the AI prompt to encourage more varied conclusions based on specific clue combinations.

"New Game" Option: Add a button to easily restart the game with a fresh house layout.
