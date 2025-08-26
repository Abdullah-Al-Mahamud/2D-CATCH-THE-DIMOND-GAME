💎 GemRush

GemRush is a fast-paced arcade-style OpenGL game where your goal is to catch falling gems using a basket. The game tests your reflexes and precision as the gems drop faster with every successful catch.

📜 Table of Contents
  1. Overview
  2. Features
  3. Requirements
  4. Installation
  5. Running the Program
  6. Usage Instructions
     . Controls
     . Objective
     . Program Flow
  7. Tips & Tricks
  8. License

📖 Overview
This project visualizes how lines are drawn using the Midpoint Line Algorithm, an efficient rasterization method in computer graphics. It also includes zone conversion to handle all octants and a C_T_Dimond class that checks for collisions between diamond-shaped objects.

The program renders points in real time with OpenGL, helping learners understand the fundamentals of low-level drawing and geometric transformations.

✨ Features

. 🎯 Midpoint Line Drawing Algorithm implemented in Python

. 🔄 Zone-based transformations for handling all slope cases

. 💎 Custom C_T_Dimond class with built-in collision detection

. 🎨 OpenGL rendering with point plotting (GL_POINTS)

. ⚡ Step-by-step pixel drawing visualization

🖥 Requirements

  . Python 3.x

  . PyOpenGL

  . PyOpenGL_accelerate (optional for better performance)

🎮 Usage Instructions

🎛 Controls

| Action                  | Key |
| ----------------------- | --- |
| Close window            | ESC |
| Redraw lines            | R   |
| Trigger collision check | C   |

🎯 Objective

 . Visualize how the Midpoint Line Algorithm plots pixels on the screen.

 . Understand how zone conversion ensures correct rendering in all slopes.

 . Experiment with simple 2D object collision detection.

💀 Program Flow

 . Lines are drawn step by step using the Midpoint Algorithm.

 . Zone detection ensures lines render correctly in all octants.

 . Collision detection checks if two diamond objects overlap.

🖼 Screen Layout
 -------------------------------------------------
|                Coordinate Grid                 |
|                                                 |
|        Lines plotted using Midpoint Algo        |
|                                                 |
|   Objects (Diamonds) with collision check       |
 -------------------------------------------------

💡 Tips & Tricks

 . Experiment with different line start/end coordinates to test all slopes.

 . Use collision detection by creating multiple diamond objects.

 . Increase point size in OpenGL to better visualize plotted pixels.

📜 License
This project is licensed under the MIT License.
