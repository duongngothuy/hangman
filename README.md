# Hangman Game

This project implements the classic word-guessing game Hangman using Python.

## Methodology

The project follows these main steps:

1. **Game Setup:**
   - Initializing the game state and selecting a random word.
   - Setting up the display for the hangman figure and word progress.

2. **Game Logic:**
   - Handling user input for letter guesses.
   - Updating the word display based on correct guesses.
   - Managing incorrect guesses and updating the hangman figure

3. **Game State Management:**
   - Keeping track of guessed letters and remaining attempts.
   - Checking for win or lose conditions.

4. **Display:**
   - Rendering the current state of the hangman figure.
   - Showing the partially guessed word and used letters.

## Results

The result is an interactive Hangman game where players can:

- Guess letters to reveal the hidden word.
- See the hangman figure progress with each incorrect guess.
- Win by guessing the entire word or lose if the hangman is completed.

## Usage

To run the code and reproduce the results, follow these steps:

1. Ensure you have Python installed on your system.
2. Clone the repository:
   `git clone https://github.com/duongngothuy/hangman.git`

3. Navigate to the project directory:
   `cd hangman`
4. Run the game:
   `python hangman.py`
5. Play the game:
- Enter letters to guess the word.
- Try to guess the word before the hangman is fully drawn.

## Future Work

- Implement difficulty levels with varying word lengths.
- Add a graphical user interface using a library like Pygame or Tkinter.
- Include categories for words (e.g., animals, countries, foods).
- Implement a hint system to help players with difficult words.

## References

- Python documentation: https://docs.python.org/3/
