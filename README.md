## 8-Puzzle AI Solver – A* Algorithm

This project is a web-based implementation of the classic 8-Puzzle Problem using the A* (A-Star) Search Algorithm. The solver finds the optimal sequence of moves from the initial configuration to the goal state.

The application is built with HTML, CSS, and JavaScript, making it lightweight and easy to run directly in any modern web browser.
---

## 🚀 Features

* Interactive **8-puzzle board**
* Solve using **A\* search algorithm with heuristics**
* Step-by-step solution path visualization
* Simple and clean **UI/UX** design
* Runs **directly in the browser** (no installation required)

---

## 🧠 About the Algorithm

The **A\*** algorithm is an informed search technique widely used in AI and pathfinding.

* **Heuristic Function (h):** Estimates the cost from the current state to the goal.
* **Cost Function (g):** Tracks the cost of moves so far.
* **Evaluation Function (f):** `f(n) = g(n) + h(n)` is used to choose the most promising path.

In this project, common heuristics like **Manhattan Distance** or **Misplaced Tiles** can be used.

---

## 🖥️ Tech Stack

* **HTML5** – Structure
* **CSS3** – Styling and animations
* **JavaScript (ES6)** – Logic and algorithm implementation

---

## 📂 Project Structure

```
├── epzzle.html
└── README.md       # Documentation
```

---

## ⚡ How to Run

1. Clone this repository:

   ```bash
   git clone https://github.com/<your-username>/<repo-name>.git
   ```
2. Open the project folder.
3. Run `epzzle.html` in your browser.
4. Interact with the puzzle and let the solver do the magic!

---

## 📈 Future Enhancements

* Add more search algorithms (BFS, DFS, IDA\*)
* Allow user to select heuristics dynamically
* Improve puzzle animations and UI themes
* Support for N-Puzzle (e.g., 15-puzzle)

---

## 🤝 Contribution

Contributions, issues, and feature requests are welcome!
Feel free to fork this repo and submit a pull request.

---

## 📜 License

This project is licensed under the **MIT License** – free to use, modify, and distribute.

