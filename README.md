# Practice Lab: Tic Tac Toe

## Overview
Build a **command-line Tic Tac Toe game** in **Python**. Players take turns placing marks on a **3×3 board**, the game detects **wins or draws**, and the program offers a simple **menu** with replay.  

> **Deliverable:** a runnable CLI program plus a short README.

---

## Learning Goals
- Practice **imperative programming** with loops and conditionals.  
- Apply **modular design** by separating responsibilities into files.  
- Use **basic OOP** with small objects and attributes. (Properties, Fields, Getters & Setters, Inheritance, Polymorphism, Interfaces, etc)
- Strengthen **error handling** for invalid input.  
- Create a **clear CLI user experience**.

---

## Functional Requirements

### Gameplay
- 3×3 board shown after every move.  
- Player 1 = `X`, Player 2 = `O`.  
- Reject invalid input: out of range, wrong type, or already occupied cell.  
- Detect wins (rows, columns, diagonals) and draws.  
- Replay option after a game ends.  

### CLI Menu
1) New Game  
2) How to Play  
3) Exit  

Prompt players for names/aliases. Show a clean ASCII board (numbers 1–9 or row/col).  

### Optional Features
- Single-player vs. simple computer bot.  
- Session scoreboard (wins/losses/draws).  
- Move history or custom symbols.  

---

## Example CLI Output
```
=========================
      TIC TAC TOE
=========================
1) New Game
2) How to Play
3) Exit
> 1

Enter Player 1 name (X): jose
Enter Player 2 name (O): ana

Current board:
 1 | 2 | 3
---+---+---
 4 | 5 | 6
---+---+---
 7 | 8 | 9

jose (X), choose a cell [1-9]: 5
ana (O), choose a cell [1-9]: 5
Cell already taken. Try again.
ana (O), choose a cell [1-9]: 1

... (play continues)

Winner: jose (X)!
Play again? (y/n): y
```

---

## Deliverables
1. A runnable CLI program.  
2. A short README explaining:
   - How to run the program  
   - Input format (e.g., cell numbers 1–9)  
   - Any optional features you added  
