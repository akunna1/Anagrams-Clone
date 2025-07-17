# Game Pigeon's 🐦 Anagrams Clone 

A Python-based clone of the popular Game Pigeon's Anagrams game. The game challenges players to create valid English words from a random set of 6 or 7 letters within a 1-minute timer. It uses a public dictionary API to validate word entries and keeps track of the score based on word lengths..

---

## Features

* Generates random letters for gameplay
* Validates words using the free Dictionary API (`dictionaryapi.dev`)
* Enforces rules: only uses given letters, minimum word length of 3
* Prevents duplicate entries
* 1-minute timed gameplay session
* Calculates total score based on word lengths
* Option to play multiple rounds

---

## Technologies & Libraries

* Python 3
* `requests` for API calls to validate words
* `random` and `string` for letter generation
* `time` for countdown timer
* Works in terminal/console or Jupyter notebook environments

---

## How to Play 🎲

1. Run the Python script.
2. Enter the number of letters to play with (6 or 7).
3. Use the displayed letters to form as many valid English words as possible within 1 minute.
4. Submit words one by one; duplicates and invalid words are rejected.
5. View your total score at the end of the round.
6. Option to play again or exit.

---

## Example Gameplay

```
Welcome to Anagrams!

Enter the number of letters (6 or 7): 7
Letters:  fekrvzy
You have 1 minute to make words using these letters.
Enter a word (press enter to exit): rev
Enter a word (press enter to exit): very
Enter a word (press enter to exit): very
You already entered that word.

Time's up!
You made 2 words:
rev
very
Your total score is: 7
Do you want to play again? (yes/no): no
```

---

## Usage

Simply run the script in your terminal or Python environment:

```bash
python anagrams_clone.py
```

---

## Notes

* Requires internet connection to validate words via the dictionary API.
* Designed for command line interaction; can be adapted for GUIs or web apps.
