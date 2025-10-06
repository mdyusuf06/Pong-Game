# 🏓 Pong Game in Python (Turtle Graphics)

A fun, classic **Pong game** implemented in Python using the `turtle` graphics library.  
This simple arcade-style project is perfect for beginners learning **object-oriented programming** and **game loops** in Python.

---

## 🎮 Features

- Two-player controls (Left: **W/S**, Right: **↑/↓**)  
- Real-time ball movement with bounce physics  
- Score tracking and display for both players  
- Auto-reset when the ball goes out of bounds  
- Smooth gameplay using `tracer()` and `update()` for frame control  

---

## 🧩 File Structure

📁 Pong-Game/
│
├── main.py # Main game loop and screen setup
├── ball.py # Ball movement and collision logic
├── paddle.py # Paddle control (missing here but used in main.py)
└── scoreboard.py # Scoreboard display and scoring system


> ⚠️ **Note:** Make sure you have a `paddle.py` file that defines the `Paddle` class.  
> It should handle paddle creation and movement using Turtle.

---

## 🕹️ How to Play

1. **Clone this repository:**
   ```bash
   git clone https://github.com/<your-username>/Pong-Game.git
   cd Pong-Game

2. Run the game:
    python main.py

3. Controls:

Right Paddle:
⬆️ → Move Up
⬇️ → Move Down

Left Paddle:
W → Move Up
S → Move Down

4. Try to bounce the ball past your opponent to score points!

🖥️ Requirements:
Python 3.7 or higher
No external libraries required (only the built-in turtle module)

📸 Demo:
(Optional — add a screenshot or GIF of the game here)

🧠 Concepts Used:
Object-Oriented Programming (Classes & Inheritance)
Game loops using while
Collision detection
Coordinate movement
Screen updates and event listening

Author:
Mohammed Yusuf
