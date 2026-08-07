# Mini Game Hub

Mini Game Hub is a lightweight, browser-based collection of classic mini games built with plain HTML, CSS, and JavaScript. The project delivers a polished single-page experience with a modern UI, theme switching, responsive layout, and simple sound effects.

## Project Overview

This project was created as a fun and educational web application that combines multiple simple games in one place. Instead of using a framework or external libraries, it focuses on core web technologies to keep the project easy to understand, modify, and run.

The app currently includes four interactive games:
- Rock Paper Scissors
- Tic Tac Toe
- Memory Card Game
- Snake

## Features

### 🎮 Multi-game experience
The hub provides a central menu where users can switch between games without leaving the page.

### 🌗 Dark and light theme toggle
The interface includes a theme switcher that lets users toggle between light and dark mode. The selected theme is saved in the browser using local storage so it persists across refreshes.

### 📱 Responsive design
The layout adapts to different screen sizes, making it usable on desktops, tablets, and mobile devices.

### 🔊 Simple sound feedback
The app uses the Web Audio API to produce basic tones for some game interactions such as wins and scoring events.

### ✨ Clean UI
The project uses gradients, glassmorphism-style effects, rounded buttons, and smooth transitions to create an attractive interface.

## Games Included

### 1. Rock Paper Scissors
A simple single-player game where the player chooses Rock, Paper, or Scissors and competes against the computer.

How it works:
- The player selects one option.
- The computer randomly chooses one option.
- The result is determined by classic rules.
- The player score increases when the player wins.

### 2. Tic Tac Toe
A two-player-style game against the computer.

How it works:
- The player starts as X.
- The computer automatically plays as O.
- The game checks for a win condition after each move.
- The board resets when the player selects the restart option.

### 3. Memory Game
A matching-card game where players try to find pairs of matching symbols.

How it works:
- Cards are shuffled at the start.
- The player clicks two cards at a time.
- Matching cards stay revealed.
- Non-matching cards flip back after a short delay.

### 4. Snake Game
A classic snake game where the player controls a growing snake and tries to eat food.

How it works:
- The snake moves continuously across the canvas.
- The player uses arrow keys to change direction.
- Eating food increases the score and lengthens the snake.
- The snake moves forward continuously in a loop.

## Project Structure

The project is intentionally simple and is centered around a single file:

- index.html – Contains the full structure, styles, game logic, and interactivity.

## Technologies Used

- HTML5 for structure
- CSS3 for styling and layout
- JavaScript for game logic and DOM manipulation
- Web Audio API for sound effects
- Local Storage for theme persistence

## How to Run the Project

No installation or package manager is required.

1. Open the project folder.
2. Double-click the index.html file, or open it in your browser.
3. Start playing the games from the main menu.

You can also run it using a simple local server if you prefer, but it is not necessary for this project.

## File Details

### index.html
This single file contains:
- The main menu UI
- Screen switching logic
- Styling for all games
- Game implementation for each mini-game
- Theme toggle behavior
- Basic audio response

## Customization Ideas

You can extend the project in many ways, including:
- Adding more games such as quiz, hangman, or puzzle games
- Improving the Snake game with collision detection and game-over logic
- Adding score history or high-score tracking
- Adding animations and particle effects
- Supporting sound toggle controls
- Creating a more advanced game selection screen

## Future Improvements

Possible upcoming enhancements:
- Better game-over screens
- Score persistence across sessions
- Sound on/off settings
- Difficulty levels
- Leaderboards
- A more polished visual design

## Why This Project Is Useful

Mini Game Hub is a great example of:
- Front-end web development fundamentals
- DOM manipulation in JavaScript
- Event handling and UI state management
- Responsive design implementation
- Building interactive features without frameworks

## License

This project is open for personal and educational use. If you plan to share or extend it, feel free to do so with attribution.
