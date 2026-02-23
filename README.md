# tic-tac-toe
 A simple and interactive Tic Tac Toe game built using HTML, CSS, and JavaScript.
This project demonstrates core JavaScript concepts like DOM manipulation, event handling, and game logic implementation.

📌 Features

✅ Two-player game (X vs O)

✅ Turn-based logic

✅ Winner detection

✅ Draw detection

✅ Reset game functionality

✅ Responsive UI design

✅ Clean and user-friendly interface
interface

🛠️ Technologies Used

HTML5 – Structure of the game board

CSS3 – Styling and layout (Grid/Flexbox)

JavaScript (ES6) – Game logic and DOM manipulation


🎯 How It Works

The game board consists of 9 clickable boxes.

Players take turns placing "X" and "O".

JavaScript tracks the current player.

After every move:

The system checks for winning patterns.

If matched → Winner is declared.

If all boxes are filled → Game is declared as Draw.

Reset button restarts the game.
Winning Patterns Used
const winningPatterns = [
  [0,1,2],
  [3,4,5],
  [6,7,8],
  [0,3,6],
  [1,4,7],
  [2,5,8],
  [0,4,8],
  [2,4,6]
];

The game checks if any of these combinations contain the same symbol ("X" or "O").
🎉

🚀 Future Improvements

Add AI opponent (single-player mode)

Add scoreboard tracking

Add sound effects

Improve UI animations

Add difficulty levels




