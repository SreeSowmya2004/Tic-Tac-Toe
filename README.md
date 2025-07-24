# ✨ Tic-Tac-Toe Game (Python Console Version) 🎮

A simple and fun **Tic-Tac-Toe** game built in Python. This is a **two-player** game played in the terminal with intuitive controls and basic input validation. Ideal for beginners learning Python fundamentals!

---

## 📷 Preview

```
 X | O | X
-----------
 O | X |  
-----------
 X |   | O

Player O's turn.
```

---

## 🛠️ Features

- 🔁 Turn-based gameplay
- ❌ Detects wins and draws
- 🚫 Input validation (prevents overwriting moves)
- 💡 Beginner-friendly and well-commented code

---

## 🧠 How It Works

- The board is a 3x3 grid (`list of lists`)
- Players enter row & column numbers (`0-2`)
- After each move:
  - ✔️ Check win condition (rows, columns, diagonals)
  - ⚠️ If the board is full and no winner → it's a draw

---

## 🗂️ Project Structure

```
tic-tac-toe-python/
│
├── tic_tac_toe.py      # 🧠 Main game script
├── README.md           # 📄 This file
├── report.md           # 📊 Project documentation
└── requirements.txt    # 📦 (Empty unless GUI added)
```

---

## ▶️ How to Run

```bash
git clone https://github.com/yourusername/tic-tac-toe-python.git
cd tic-tac-toe-python
python tic_tac_toe.py
```

📝 Requires **Python 3.x**

---

## 🌱 Future Improvements

- 🖼️ Add a GUI (Tkinter or Pygame)
- 🤖 Add an AI opponent (Minimax algorithm)
- 🌐 Build a web version (Flask or Django)
- 🏆 Track scores and game history

---

