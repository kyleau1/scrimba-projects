# Scrimba Projects Portfolio

This repository contains web development projects I built while learning **React** through Scrimba tutorials.

DISCLAIMER: These projects run in an "index.html" as the code is in react native.

---

## **Project 1: ChefClaude**

**Description:**  
ChefClaude is an AI-powered cooking assistant that helps users create recipes based on the ingredients they have on hand. Simply enter your ingredients, and the app generates recipe ideas tailored to what you’ve got.

**Features:**  
- User inputs a list of ingredients  
- AI generates custom recipe suggestions  
- Clean, user-friendly React interface  

**Tech Stack:**  
- React (frontend)  
- HuggingFace AI (for recipe generation)

**How to Use:**  
1. Enter your available ingredients in the input field.  
2. Click "Generate Recipe."  
3. Get a customized recipe created by AI!  

---

## **Project 2: Tenzies**

**Description:**  
Tenzies is a digital dice game where the goal is to roll until all 10 dice show the same number. Players can click individual dice to “hold” them at their current value between rolls, creating a fun mix of strategy and luck.

**Features:**  
- Roll 10 dice with a single button click  
- Click dice to hold/unhold them between rolls  
- Game automatically detects when all dice match (game won)  
- Confetti animation celebrates when the game is won  
- Button changes to “New Game” to start over  
- Accessibility: New Game button automatically receives keyboard focus  

**Tech Stack:**  
- React (frontend)  
- nanoid (for unique dice IDs)  
- react-confetti (for win celebration animation)  

**How to Play:**  
1. Click the Roll button to roll all dice.  
2. Click individual dice to hold them at their current value.  
3. Keep rolling until all dice show the same number.  
4. When the game is won, confetti drops and the button changes to New Game.  
5. Click New Game to reset the dice and play again.

---

## **Project 3: Assembly Endgame (Hangman)**

**Description:**  
Assembly Endgame is a coding-themed twist on Hangman. Instead of hanging a man, wrong guesses eliminate coding languages from the “universe” until only **Assembly** remains. It’s a fun way to test your word-guessing skills while celebrating programming humor.  

**Features:**  
- Guess the word one letter at a time  
- Wrong guesses remove languages from left to right  
- Game ends when you guess the word, or only Assembly remains  
- Confetti celebrates when you win  
- Keys indicate feedback: green for correct, red for wrong, greyed out after guessing  
- Click **New Game** to start over 
- The full word is revealed if you lose  

**How to Play:**  
1. Start guessing letters  
2. Wrong guesses remove languages one by one  
3. Correct guesses reveal letters in the word  
4. If all attempts are used, the full word is revealed  
5. Goal: Guess the word before the universe loses all languages


