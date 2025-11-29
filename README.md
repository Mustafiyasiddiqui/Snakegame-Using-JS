# 🐍 Snake Game

A simple, responsive, and aesthetic **Snake Game** built using **HTML, CSS, and JavaScript**. This project includes full game logic, a timer, scoring system, high‑score persistence, and clean UI modals for start and end screens.

---

## 🚀 Features

* **Full Snake Movement Logic** (grid-based)
* **Start Modal** to begin the game
* **Game Over Modal** with restart option
* **Live Score Counter**
* **Persistent High Score** (saved in LocalStorage)
* **Game Timer** (tracks gameplay duration)
* **Responsive UI** for all screen sizes
* **Bright, Aesthetic Color Palette** (no dark or eye‑straining backgrounds)

---

## 📁 Project Structure

```
/snakegame
│── index.html
│── style.css
│── script.js
│── README.md
```

---

## 🕹️ How to Play

1. Open the game in any modern browser.
2. Press **Start Game** on the modal.
3. Use **Arrow Keys (↑, ↓, ←, →)** to move the snake.
4. Eat food to increase your score.
5. Avoid hitting the walls.
6. Try to beat your **high score**!

---

## ⚙️ How It Works

### 🧠 Game Logic

* The board is a dynamic CSS grid.
* Snake is updated every game tick with position arrays.
* Collision detection checks:

  * Wall hit
* Random food generation system.

### 🪟 Modals

* **Start Modal**: Shown before game begins.
* **End Modal**: Displays restart button.

### 🏆 Scoring

* Score increments by +10 per food.
* High score saved using `localStorage`.

### ⏱️ Timer

* Runs from game start to game over.
* Displays minutes + seconds.

---

## 🧪 Running Locally

1. Clone the repo:

```
git clone https://github.com/Mustafiyasiddiqui/Snakegame-Using-JS/tree/main
```

2. Open project folder:

```
cd snakegame
```

3. Open `index.html` in your browser.

---

## 📝 Recent Changes

* Implemented core game loop
* Added scoring, high score, and timer logic
* Added start and end game modals
* Updated UI with aesthetic bright color palette

---

## 🤝 Contributing

Feel free to fork the repo, open issues, and submit PRs.

---

## 📄 License

This project is open-source. Use it freely.

---

Enjoy the game & keep improving it! 🎮🐍
