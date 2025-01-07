# Fermi-Pico-Bagel
```markdown
# 🔢 Fermi Pico Bagel Game

Welcome to the Fermi Pico Bagel Game! This is a fun number guessing game where you try to guess a secret 3-digit number with unique digits, and get clues based on your guesses.

## 📝 How to Play

1. **Objective:** Guess the secret 3-digit number.
2. **Clues:**
   - **Fermi:** A digit in the guess is in the correct position.
   - **Pico:** A digit in the guess is correct but in the wrong position.
   - **Bagel:** None of the digits in the guess are correct.

### 🎮 Example

- Secret Number: `123`
- Player Guess: `135`
  - Clues: Fermi (1 is in the correct position), Pico (3 is in the number but the wrong position), Bagel (no 5 in the number)

## 🚀 Getting Started

### Prerequisites

- Python 3.x

### Installation

1. **Clone the repository:**
   ```sh
   git clone https://github.com/your-username/fermi-pico-bagel-game.git
   ```
2. **Navigate to the project directory:**
   ```sh
   cd fermi-pico-bagel-game
   ```

### Running the Game

```sh
python game.py
```

## 🛠️ Code Overview

### `generate_secret_number()`

Generates a random 3-digit number with unique digits.

### `get_clues(guess, secret_number)`

Provides clues based on the player's guess.

### `is_valid_guess(guess)`

Checks if the player's guess is valid.

### `play_game()`

Main function to run the game.

## 💡 Ideas for Enhancements

1. **Hints:** Introduce hints if the player is struggling.
2. **Difficulty Levels:** Adjust the length of the secret number for varying difficulty.
3. **User Interface:** Implement a GUI using `tkinter` or `pygame`.
