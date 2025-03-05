# 🎮 2048 Pro – Full Implementation of the Classic Puzzle Game

**Live Preview:** [🔗 View Game](https://your-demo-link.com)

---

## Project Overview

2048 Pro is a fully-featured implementation of the classic 2048 puzzle game built with HTML, SCSS, and JavaScript. This project faithfully recreates every element and rule of the original game, including dynamic tile generation, merging of identical numbers, score tracking, and win/lose conditions. Developed with a focus on clean and maintainable code, 2048 Pro demonstrates modern approaches to styling, animations, and responsive design.

---

## Key Features

- **🧩 Complete Game Logic:**  
  Implements all core mechanics, such as moving tiles in four directions, merging identical tiles, and generating new tiles after each move.

- **📱 Responsive Design:**  
  Optimized for various devices—from mobile phones to desktops—using CSS Grid and media queries for a seamless user experience.

- **🎨 User-Friendly Interface:**  
  Features a clean, minimalist design with intuitive controls. Supports both keyboard and touch input for easy interaction.

- **💡 Dynamic Score Tracking and Notifications:**  
  Automatically updates the score and displays messages for win or game over scenarios, enhancing player engagement.

---

## Technologies Used

- **HTML5:**  
  Provides semantic markup for structuring the game board and user interface.

- **SCSS:**  
  Leverages the power of a CSS preprocessor to create modular, maintainable styles with smooth animation effects.

- **JavaScript:**  
  Implements the entire game logic, handles event processing, manages state updates, and controls UI interactions.

- **Responsive Design Techniques:**  
  Utilizes adaptive design principles to deliver an optimal experience across all devices.

---

## Implementation Details

 Each cell is a dynamic element that changes state based on player actions. When a move is made, tiles slide in the chosen direction, merge when two tiles of the same value meet, and then update the score accordingly. A new tile is generated in a random empty cell after every move, keeping the game challenging.

The JavaScript code is responsible for:
- ⌨️ Handling keyboard and touch events to capture player moves.
- ⚙️ Managing the game state and enforcing the rule that each tile can merge only once per move.
- 🔄 Dynamically updating the game board and score display after each action.

---

📖 How to Run the Project Locally
1️⃣ Prerequisites
Before running the project, ensure you have the following installed:

Git – Download & Install Git
Node.js (v16 or later) – Download Node.js
To check if Node.js and npm are installed, run:

node -v # Should return a version number (v16 or later recommended)
npm -v # Should return a version number
2️⃣ Clone the Repository
Run the following command in your terminal:

git clone https://github.com/your-username/2048-project.git
Navigate into the project folder:

cd crazybaby-landing-page
3️⃣ Install Dependencies
Run the following command to install required packages:

npm install
4️⃣ Run the Project
Start a local development server:

npm run dev
#The site should now be accessible at http://localhost:3000/ (or another port specified in the console).






