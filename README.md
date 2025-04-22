# SudoKU Game

A fun, browser-based Sudoku game with user authentication, difficulty levels, hints, and a leaderboard system.

<p align="center">
  <img src="./images/img1a.png" alt="SudoKU Game" width="800" height="400">
</p>


## Features

- 🎮 Interactive Sudoku gameplay with board validation
- 🏆 Leaderboard to track top scores
- 👤 User account system with localStorage
- 🔢 Multiple difficulty levels (Easy, Medium, Hard)
- 💡 Hint system (limited to 5 per game)
- 📱 Responsive design for various screen sizes
- 🎨 Playful, colorful UI

## Demo

You can play the game online at: [Your hosting URL here]

## Pages

The application consists of three main pages:

1. **Login/Register** (`index.html`) - Create an account or login
2. **Game** (`game.html`) - Play Sudoku with various difficulty options
3. **Leaderboard** (`leaderboard.html`) - View top scores filtered by difficulty and time

## How to Play

1. Create an account or play as a guest
2. Select a difficulty level (Easy, Medium, Hard)
3. Click on a cell to select it, then enter a number using the number pad or keyboard
4. Use hints if you get stuck (limited to 5 per game)
5. Complete the puzzle to save your score to the leaderboard

## Setup Instructions

### Local Development

1. Clone this repository:
   ```
   git clone https://github.com/yourusername/sudoku-game.git
   ```

2. Open any of the HTML files in your browser to start playing.

#### GitHub Pages

1. Fork this repository
2. Go to Settings > Pages
3. Select your main branch as the source
4. Your site will be published at `https://yourusername.github.io/sudoku-game/`

## Technical Details

### Data Storage

The game uses `localStorage` to store:
- User accounts
- Current logged-in user
- Game scores and leaderboard data

### File Structure

- `index.html` - Login and registration page
- `game.html` - Main Sudoku game page
- `leaderboard.html` - Scores and rankings page
- Associated CSS and JavaScript (embedded in the HTML files)

## Future Enhancements

- Backend server for persistent data storage
- Timer functionality
- Social sharing features
- More game variants
- Dark mode theme

## License

&copy 2025

## Acknowledgements

- Created by Aditya Yadav.
- Built with HTML, CSS, and JavaScript
- Uses localStorage for data persistence
