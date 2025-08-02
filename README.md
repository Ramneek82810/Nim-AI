# 🧠 Nim AI

An intelligent agent that plays the classic mathematical game **Nim** using game theory and the **Minimax algorithm**. This AI can play optimally against human players or simulate games against itself — fully implemented in Python.

---

## 📌 Overview

Nim is a mathematical game of strategy where players take turns removing objects from heaps. The player forced to take the last object **loses** (or wins, depending on the variation).

This project implements:
- Full game logic
- A **Minimax-based AI agent**
- Human vs AI and AI vs AI play modes

---

## 🧠 Tech Stack

| Component     | Technology |
|---------------|------------|
| Programming   | Python     |
| AI Algorithm  | Minimax with recursion |
| Game Type     | Deterministic Turn-Based Game |
| Interface     | Console (Text-based) |

---

## 📁 Project Structure

```
Nim-AI/
├── nim.py          # Game logic (heap state, available actions, move application)
├── play.py         # Game loop for playing against the AI
├── README.md       # Documentation
```

---

## 🧠 How the AI Works

- The AI uses the **Minimax algorithm** to simulate all possible game states.
- For each state, it calculates the best move assuming the opponent also plays optimally.
- The result: an unbeatable AI in most Nim configurations.

---

## ▶️Getting Started

### ✅ Prerequisites
- Python 3.x

### 🛠 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Ramneek82810/Nim-AI.git
   cd Nim-AI
   ```

2. Run the game:
   ```bash
   python play.py
   ```

---

## 🎮 How to Play

- You can play as a human against the AI.
- During your turn, input which pile to remove from and how many objects to remove.
- The AI will make optimal moves in its turn.

---

## 💡 Game Rules

- Start with several piles containing objects.
- On your turn, choose **one pile** and remove **one or more** objects.
- The player forced to take the last object **loses**.

---

## 🧪 Sample Output

```plaintext
Initial piles: [1, 3, 5, 7]
Your Turn:
Choose pile: 2
Choose how many to remove: 3

AI Turn:
AI chose pile 3 and removed 4 objects
```

---

## 📈 Future Improvements

- Add difficulty levels (easy, hard)
- Create a graphical (GUI) interface using Pygame or Tkinter
- Add support for multiple Nim variations

---


