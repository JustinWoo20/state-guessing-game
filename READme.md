# 🗺️ U.S. States Game 

This is a Python-based interactive U.S. geography quiz game built with the `turtle` graphics module and `pandas`. 
It challenges users to name all 50 U.S. states by typing in all state names. Correct guesses are displayed over their appropriate 
state to help users keep track of which states they have already guessed. It's a great tool for U.S. kids who are required to take
a geography test in school. 

---
 
## 🎮 How to Play

- The game displays a blank U.S. map.
- You'll be prompted to enter the name of a U.S. state.
- If your guess is correct, the state name appears on the map in its proper location.
- Type `Exit` at any time to quit the game and generate a CSV file of the states you missed.

---

## 🧠 Features

- Keeps track of correct guesses and displays progress.
- Prevents duplicate guesses.
- Exports a list of states not guessed to a file called `States to Learn.csv` for future practice.
- Displays a congratulatory message when all 50 states are guessed correctly.

---

## 🖼️ Requirements

- `images/blank_states_img.gif`: A map of the U.S. with blank state outlines.
- `50_states.csv`: A CSV file containing all U.S. states and their x/y coordinates for positioning text on the map.

---

## 📦 Dependencies

- Python 3.6+
- [pandas](https://pypi.org/project/pandas/)
- [turtle](https://docs.python.org/3/library/turtle.html) (comes with Python)

---

## 🔧 How to Run

1. Clone the repository or download the files.
2. Make sure `50_states.csv` and `images/blank_states_img.gif` are in the correct folders.
3. Run the script:

```bash
python us_states_game.py
```
cd state-guessing-game

---

📁 File Structure

state-guessing-game
```
├── 50_states.csv
├── images/
│   └── blank_states_img.gif
├── us_states_game.py
├── States to Learn.csv # Appears after the first time running
├── requirements.txt
└── README.md
```

## 📘 Acknowledgments

This project is inspired by the 100 Days of Code: Python Bootcamp by Dr. Angela Yu.