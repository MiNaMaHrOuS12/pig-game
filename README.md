# 🐷 Pig Game

A classic two-player dice game built with vanilla JavaScript, HTML, and CSS. The goal is to be the first player to reach 100 points!

## 🎮 How to Play

1. **Roll Dice**: Click the "🎲 Roll dice" button to roll a die
   - If you roll a 2-6: The number is added to your current score
   - If you roll a 1: You lose all your current score and your turn ends

2. **Hold**: Click the "📥 Hold" button to add your current score to your total score and pass the turn to the other player

3. **Win**: The first player to reach 100 points wins the game!

4. **New Game**: Click the "🔄 New game" button to start a fresh game

## 🎯 Game Rules

- Players take turns rolling a single die
- On each turn, a player can roll the die multiple times
- If a player rolls a 1, they lose all points accumulated in that turn and the turn switches
- If a player chooses to "Hold", their current score is added to their total score and the turn switches
- The first player to reach 100 points wins the game

## 🚀 Getting Started

1. Open `index.html` in your web browser
2. Start playing!

No installation or build process required - just open the HTML file and enjoy!

## 📁 Project Structure

```
starter/
├── index.html      # Main HTML file
├── script.js       # Game logic and functionality
├── style.css       # Styling for the game
├── dice-1.png      # Dice face images
├── dice-2.png
├── dice-3.png
├── dice-4.png
├── dice-5.png
├── dice-6.png
└── README.md       # This file
```

## 🛠️ Technologies Used

- **HTML5**: Structure and markup
- **CSS3**: Styling and layout
- **Vanilla JavaScript**: Game logic and DOM manipulation

## 🎨 Features

- Two-player gameplay
- Real-time score tracking
- Visual dice display
- Active player highlighting
- Winner announcement
- Reset functionality

## 📝 Code Overview

The game uses:
- DOM manipulation to update scores and UI
- Event listeners for button interactions
- State management for game variables (scores, current score, active player, game status)
- Conditional logic to handle game rules

## 🎓 Learning Objectives

This project demonstrates:
- DOM selection and manipulation
- Event handling
- State management
- Conditional logic
- Game development concepts

---

Enjoy playing the Pig Game! 🎲

