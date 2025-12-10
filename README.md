# 🎲 Dicee Game

A simple and fun two-player dice game built with **JavaScript**. Refresh the page to roll the dice and see who wins!

## ✨ Features

* **Random Dice Logic:** Generates random numbers between 1 and 6 for both players every time the page loads.
* **Dynamic DOM Manipulation:** The dice images and the main heading update instantly based on the result.
* **Winner Declaration:** The game automatically compares the two dice and declares "Player 1 Wins!", "Player 2 Wins!", or "Draw!".
* **Custom Styling:** Features a dark theme with playful Google Fonts (*Lobster* and *Indie Flower*).

## 🕹️ How to Play

1.  **Start the Game:** Open `index.html` in your web browser.
2.  **Roll the Dice:** Simply **refresh the page** (F5 or Command+R).
3.  **See the Result:**
    * If Player 1 has a higher number, the title shows **"🚩 Player 1 Wins!"**.
    * If Player 2 has a higher number, the title shows **"Player 2 Wins! 🚩"**.
    * If numbers are equal, it shows **"Draw!"**.

## 🛠️ Technologies Used

* **HTML5:** Structure of the game board and player labels.
* **CSS3:** Flexbox/centering layout and custom typography.
* **JavaScript (ES6):** Logic for random number generation and DOM updates.

## 📂 Project Structure

```text
├── images/             # Dice assets (dice1.png - dice6.png)
├── index.html          # Main HTML file
├── index.js            # Game logic script
└── styles.css          # Styling sheet
