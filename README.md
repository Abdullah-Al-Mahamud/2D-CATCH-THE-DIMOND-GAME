💎 GemCollection

GemRush is a fast-paced arcade-style OpenGL game where your goal is to catch falling gems using a basket. The game tests your reflexes and precision as the gems drop faster with every successful catch.

📜 Table of Contents
Overview

Features

Requirements

Installation

Running the Game

Gameplay Instructions

Controls
Objective
Game Over Conditions
Scoring
Game Screen Layout

Tips & Tricks

License

📖 Overview
In GemRush, sparkling gems fall from the top of the screen, and you control a basket at the bottom to catch them. The more gems you catch, the faster they fall. If you miss a gem, the game ends, and you can restart or quit via the on-screen buttons.

✨ Features
🎯 Smooth real-time gameplay at 60 FPS
💎 Rotating and sparkling gem visuals
🛑 Pause, restart, and quit buttons built into the UI
📈 Progressive difficulty — gems fall faster as your score increases
🎨 Custom OpenGL rendering with perspective and shape details
🖥 Requirements
Python 3.x
PyOpenGL
PyOpenGL_accelerate (optional for better performance)
⚙ Installation
# Clone this repository
git clone https://github.com/yourusername/gemrush.git
cd gemrush

# Install dependencies
pip install PyOpenGL PyOpenGL_accelerate
▶ Running the Game
python gemrush.py
🎮 Gameplay Instructions
🎛 Controls
Action	Key/Mouse
Move basket left	← (Left Arrow)
Move basket right	→ (Right Arrow)
Pause/Resume	Spacebar
Restart game (UI button)	Left-click on blue circle at top left
Quit game (UI button)	Left-click on red X at top right
Pause/Resume (UI button)	Left-click on orange button at top center
🎯 Objective
Catch falling gems with your basket before they hit the ground.
Each successful catch increases your score and makes the gems fall faster.
💀 Game Over Conditions
You miss a gem (it falls past the basket).
The basket turns red when the game ends.
You can restart via the blue restart button or quit via the red exit button.
🏆 Scoring
+1 point for every gem caught.
Gems fall faster with each point scored.
🖼 Game Screen Layout
 -------------------------------------------------
|  🔄 (Restart)   ⏸ (Pause/Resume)   ❌ (Exit)    |
|                                                  |
|         Falling gems appear here                 |
|                                                  |
|                                                  |
|                      Basket                      |
 -------------------------------------------------
💡 Tips & Tricks
Anticipate gem movement — they drop faster over time.
Use pause to regain focus during intense gameplay.
Keep your basket centered when waiting for the next gem.
📜 License
This project is licensed under the MIT License.

About
No description, website, or topics provided.
Resources
 Readme
License
 MIT license
 Activity
Stars
 1 star
Watchers
 0 watching
Forks
 0 forks
Report repository
Releases
No releases published
Packages
No packages published
Languages
Python
100.0%
Footer
