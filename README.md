# Chess Royale ♔

A sophisticated, browser-based Chess engine featuring a custom UI and multiple levels of AI difficulty. **Chess Royale** combines classical strategy with a modern, "Royale" aesthetic.

## 🚀 Features
* **Four AI Difficulty Levels:**
    * **Novice:** Random move selection for beginners.
    * **Knight:** Heuristic-based evaluation with slight randomized "noise."
    * **Master:** Minimax algorithm with Alpha-Beta pruning and Piece-Square Tables (PST).
    * **Grand Master:** Powered by the **Stockfish 10.0.2** engine via Web Workers.
* **Responsive Design:** Fully playable on desktop and mobile browsers.
* **Move History & Undo:** Track your match in algebraic notation and revert moves to test different strategies.
* **Board Customization:** Toggle board orientation (Flip Board) for black-side practice.
* **Visual Polish:** Animated piece movements, capture "burst" effects, and a custom "Cinzel" typography theme.

## 🛠️ Technical Stack
* **Frontend:** HTML5, CSS3 (CSS Variables, Flexbox, Grid, Animations).
* **Logic:** Vanilla JavaScript (ES6+).
* **Engine:** Stockfish.js (Integrated via CDN).
* **Fonts:** Google Fonts (Cinzel & Crimson Pro).

## 📥 Installation & Usage
1. Clone the repository:
   ```bash
   git clone [https://github.com/YOUR_USERNAME/Chess-Royale.git](https://github.com/YOUR_USERNAME/Chess-Royale.git)
   
