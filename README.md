# Tic-Tac-Toe

<h2>✨ Features </h2>

<ul>
<li>Two-player local game (X vs O)

<li>Clean terminal UI with a numbered board for easy moves

<li>Input validation and win/tie detection

<li>Optional: play-again prompt

<li>Lightweight: pure Python, no external libraries required
</ul>

<h2>🕹️ Gameplay / Controls </h2>
<ul>
<li>The board is numbered 0–8:
  
```
 0 | 1 | 2
---+---+---
 3 | 4 | 5
---+---+---
 6 | 7 | 8
 ```
  
<li>On your turn, type the number of the cell you want to occupy and press Enter.
<li>Invalid inputs (non-numeric, out-of-range, or occupied) will prompt you to try again.
<li>The game announces a win (three-in-a-row) or a tie, then asks whether to play again.
</ul>

🧠 Example interaction
Welcome to Tic-Tac-Toe!
Player X goes first.
```
 0 | 1 | 2
---+---+---
 3 | 4 | 5
---+---+---
 6 | 7 | 8

Player X, choose a cell (1-9): 4

 0 | 1 | 2
---+---+---
 3 | X | 5
---+---+---
 6 | 7 | 8

Player O, choose a cell (1-9): 3
 0 | 1 | 2
---+---+---
 O | X | 5
---+---+---
 6 | 7 | 8
...

Thanks for playing!
```

<h2>🙋 Contributions </h2>

Pull requests welcome! Keep changes small and tested. For feature requests, open an issue with steps to reproduce and expected behavior.

