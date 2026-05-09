# 🏓 Pong Game

A two-player Pong game built in Python using the Turtle graphics module. Both players share the same keyboard — no network required.

![Python](https://img.shields.io/badge/Python-3.x-3670A0?style=flat&logo=python&logoColor=ffdd54)
![Turtle](https://img.shields.io/badge/Library-Turtle-green?style=flat)

---

## 🎮 How to Play

| Player | Move Up | Move Down |
|--------|---------|-----------|
| Left   | `W`     | `S`       |
| Right  | `↑`     | `↓`       |

- The ball speeds up every time it hits a paddle — don't blink.
- First to let the ball past their side gives the other player a point.
- Close the window to quit.

---

## 🚀 Getting Started

**Requirements:** Python 3.x (Turtle is part of the standard library — no installs needed)

```bash
git clone https://github.com/Pranay-Agarwal13/pong-game.git
cd pong-game
python main.py
```

---

## 🗂️ Project Structure

```
pong-game/
├── main.py         # Game loop, screen setup, collision logic
├── ball.py         # Ball movement, bouncing, speed acceleration
├── paddle.py       # Paddle class with keyboard controls
├── scoreboard.py   # Score tracking and display
├── .gitignore
└── README.md
```

---

## 💡 What I Learned

- Structuring a project with OOP — each game element is its own class
- Inheritance with Python's `Turtle` module
- Handling keyboard events and a real-time game loop
- Collision detection using distance calculations

---

## 🔧 Possible Improvements

- [ ] Add a winning score limit (e.g., first to 10)
- [ ] Sound effects on paddle/wall hits
- [ ] Single-player mode with a basic AI opponent
- [ ] Better collision detection for edge cases

---

Built as part of the [100 Days of Code: Python](https://www.udemy.com/course/100-days-of-code/) course — extended with improved code structure and documentation.
