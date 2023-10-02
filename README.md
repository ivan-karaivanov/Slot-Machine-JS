# Slot Machine Application

Slot Machine Application is a simple command-line game where you can try your luck and have fun playing a slot machine. Below, you'll find a brief guide on how to play this game and an overview of the source code.

## How to Play

Playing the Slot Machine is easy and involves the following steps:

1. **Deposit Money**: To get started, deposit some money into the game. You will use this balance to place bets.

2. **Choose Number of Lines**: Determine the number of lines you want to bet on (1 to 3). The more lines you choose, the higher the chance of winning, but also the higher the cost.

3. **Place Your Bet**: Enter the bet amount for each line you are playing. Make sure it's within your available balance.

4. **Spin the Reels**: Watch the reels spin and see if the symbols align to win a prize.

5. **Check for Winnings**: After the spin, the game will check if you've won on any of the lines. If you do, you'll receive your winnings.

6. **Play Again**: You can choose to play again to continue your slot machine adventure.

## Source Code Overview

The source code provided is a JavaScript implementation of a simple slot machine game. Here are some key components of the code:

- It uses the `prompt-sync` module to interact with the player through the command line.

- The slot machine consists of 3 rows and 3 columns of symbols.

- Symbols have different values and counts. The more a symbol appears, the higher the chance of it landing on the reels.

- The game logic includes functions for depositing money, choosing the number of lines, placing bets, spinning the reels, checking for winnings, and playing again.

- The game continues until you choose to stop or run out of money.

## How to Run

To play the game, you need to have Node.js installed on your computer. Here's how to run it:

1. Open your terminal or command prompt.

2. Navigate to the directory where your source code is located.

3. Run the following command to start the game:

   ```bash
   node project.js
   ```

4. Follow the on-screen instructions to play the game as described above.
