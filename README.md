# 🎰 Slot Machine Game (Node.js)

A simple **command-line slot machine game** built with **JavaScript (Node.js)**.  
The user deposits money, chooses the number of lines to bet on, places a bet, and spins the reels.  
The game randomly selects symbols for each reel and calculates winnings based on the bet.

---

## 🚀 Features
- Deposit money and manage balance 💰
- Choose number of lines to play (1-3)
- Place bets per line
- Randomized reels with symbol frequency
- Symbol values determine winnings
- Runs fully in the terminal (using `prompt-sync`)

---

## 🛠️ Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/shivansh-77/slot-machine-game.git
   cd slot-machine-game
2. Install dependencies:
   npm install
3. ▶️ Usage
   Run the game with:
   node project.js
4. 🎮 Game Rules

Symbols and counts (how often they appear in the reels):

A → appears 2 times

B → appears 4 times

C → appears 6 times

D → appears 8 times

Symbol values (used to calculate winnings):

A → 5x

B → 4x

C → 3x

D → 2x

Winning condition:
If all symbols in a line match, you win bet * symbol_value.
Example: If you bet 10 on a line and it shows C | C | C, you win 10 * 3 = 30.

You can bet on 1, 2, or 3 lines.

1 line = middle row

2 lines = top and bottom rows

3 lines = all rows

5. 📦 Dependencies

prompt-sync
 – for user input in the terminal
