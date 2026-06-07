# Python Mini Projects

> A collection of terminal-based Python games built to practise core programming concepts — logic design, string manipulation, randomisation, and control flow.

---

## Projects

### 🐍 1. Snake and Ladder
A fully playable 1-player Snake and Ladder game in the terminal. The board follows the classic 100-square layout with snakes and ladders affecting player positions.

**Concepts practised:** dictionaries, random module, game loop design, win condition logic

**How to play:**
```bash
python snake_n_ladder_1.py
```
- Roll the dice each turn (random 1–6)
- Land on a ladder → move up; land on a snake → slide down
- First to reach square 100 wins

---

### 🔤 2. Word Hangman
A word-guessing game where the player uncovers a hidden word one letter at a time before running out of attempts.

**Concepts practised:** file I/O, string manipulation, sets, loop control, user input validation

**How to play:**
```bash
python word_trivia.py
```
- A random word is selected from the word bank (`word5.txt`, `word6.txt`, `word7.txt`)
- Guess one letter at a time
- You have a limited number of incorrect guesses before the game ends

---

## Repository Structure

```
Python-Repo/
│
├── snake_n_ladder_1.py   # Snake and Ladder game
│
├── word_trivia.py        # Word Hangman game
├── word5.txt             # Word bank — 5-letter words
├── word6.txt             # Word bank — 6-letter words
├── word7.txt             # Word bank — 7-letter words
│
├── Prediction_Model.py   # ARIMA/SARIMA time series forecasting (separate project)
├── X.csv                 # Dataset for forecasting project
│
└── README.md             # This file
```

---

## Requirements

No external libraries needed — both games run on the Python standard library.

```bash
python --version   # Python 3.6+ recommended
```

---

## Author

**Ayush Seth**  
B.Sc. (Hons.) Statistics, Hindu College, University of Delhi  
[linkedin.com/in/sethayush](https://linkedin.com/in/sethayush) | sethayush1466@gmail.com
