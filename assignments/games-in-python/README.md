
# 📘 Assignment: Games in Python

## 🎯 Objective

Build a simple Hangman-style game in Python to practice string handling, loops, conditionals, and user interaction.

## 📝 Tasks

### 🛠️ Game Setup and Word Selection

#### Description
Create a list of target words and write logic to randomly select one for each new game.

#### Requirements
Completed program should:

- Define a list of possible words to guess
- Choose one word at random each time the game starts
- Keep the selected word hidden from the player

### 🛠️ Guessing and Progress Display

#### Description
Implement the main guessing loop that allows the player to guess letters, shows progress, and tracks guesses.

#### Requirements
Completed program should:

- Accept one letter guess at a time from the player
- Reveal correctly guessed letters in the word using placeholders for unknown letters
- Track and show letters that have already been guessed
- Reduce remaining attempts for wrong guesses

### 🛠️ Win/Lose Conditions

#### Description
Add game-ending logic that detects whether the player has correctly guessed the word or used all attempts.

#### Requirements
Completed program should:

- End the game when the word is fully guessed
- End the game when the player runs out of attempts
- Display a win message when the player guesses the word
- Display a lose message and reveal the word when time runs out
