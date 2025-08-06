# ♟ Chess Engine with AI (Python + Pygame)

This is a **fully playable chess engine with AI opponent**, built in Python using the `pygame` library. It supports all major chess rules including **castling**, **en passant**, **pawn promotion**, **checkmate**, and **stalemate**. The AI uses **Negamax with Alpha-Beta pruning** for efficient move search.

## 🧠 Features

* ✔️ Player vs Player (hotseat)
* 🤖 Player vs AI (minimax + alpha-beta)
* ⟲ Undo Moves
* ♚ Castling (both sides)
* ♟ En Passant capture
* ♛ Automatic pawn promotion to Queen
* 🔄 Restart game
* 📦 Clean object-oriented structure with `ChessEngine.py` and `SmartMoveFinder.py`

## 🗆 Project Structure

```
Chess-Engine/
├── ChessMain.py           # Pygame GUI and main game loop
├── ChessEngine.py         # Game state and move rules
├── SmartMoveFinder.py     # AI using Negamax + Alpha-Beta
├── images/                # Piece images (png format)
│   ├── wp.png, bK.png ... # White/Black pieces
├── README.md
└── requirements.txt       # (Optional) pip dependencies
```

## 🎡 Controls

| Action            | Key / Mouse      |
| ----------------- | ---------------- |
| Select/Move Piece | Left Mouse Click |
| Undo Move         | `Z` key          |
| Restart Game      | `R` key          |
| Quit Game         | Close window     |

## 🧠 AI Logic

The AI uses:

* **Negamax Search**
* **Alpha-Beta Pruning**
* **Basic material evaluation**
* Configurable search depth (`DEPTH` in `SmartMoveFinder.py`)

Evaluation is based on standard material values:

* Queen = 10
* Rook = 5
* Bishop/Knight = 3
* Pawn = 1

## 📸  Some Screenshots

**Starting Position**
<img width="1470" height="956" alt="Screenshot 2025-08-06 at 7 03 54 PM" src="https://github.com/user-attachments/assets/307d280c-6394-483e-a5e5-81fca76570ec" />

**Stalemate Situation**
<img width="1470" height="956" alt="Screenshot 2025-08-06 at 7 09 43 PM" src="https://github.com/user-attachments/assets/2aba2f4a-69e2-4572-9065-29b88bb77ddd" />


**After Game is Over**
<img width="1470" height="956" alt="Screenshot 2025-08-06 at 7 08 11 PM" src="https://github.com/user-attachments/assets/5158bf76-3f56-442c-af92-b1e5329b95c7" />



## 🚀 Getting Started

### 1. Clone the Repo

```bash
git clone https://github.com/iiabhi/ChessAI.git
cd ChessAI
```

### 2. Set up a Virtual Environment (recommended)

```bash
python3 -m venv venv
source venv/bin/activate
```

### 3. Install Dependencies

```bash
pip install pygame
```

### 4. Run the Game

```bash
python ChessMain.py
```

## 🧑‍💻 Author

**Abhishek Kumar**
GitHub: [@iiabhi](https://github.com/iiabhi)

