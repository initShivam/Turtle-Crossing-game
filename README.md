# 🐢 Turtle Crossing Game

A fun and simple arcade-style game built with Python's Turtle module! Your goal is to help the turtle safely cross the road while avoiding fast-moving cars. Each time you make it across, the game speeds up and your level increases.

## 🚀 Features

* Turtle player controlled by the **Up Arrow** key
* Randomly spawning cars that move across the screen
* Increasing difficulty with each level
* "Game Over" message on collision

## 📁 Project Structure
turtle_crossing_game/
│
├── main.py              # Main game loop and setup
├── player.py            # Player class logic
├── car_manager.py       # Car generation and movement logic
├── scoreboard.py        # Score tracking and display
└── README.md            # Project documentation

## 🕹️ How to Play

1. Run `main.py`.
2. Use the **Up Arrow** key to move the turtle forward.
3. Avoid cars!
4. Reach the top to level up and increase the game's speed.
5. The game ends when a car hits the turtle.

## 🛠️ Requirements

* Python 3.x
* Standard Library only (`turtle` and `time` are built-in)

No external packages are required!

## ▶️ Running the Game

```bash
python main.py
```

## 📌 Notes

* This is a beginner-friendly project for learning object-oriented programming and the basics of game loops in Python.
* Make sure all the class files (`player.py`, `car_manager.py`, `scoreboard.py`) are in the same directory as `main.py`.
