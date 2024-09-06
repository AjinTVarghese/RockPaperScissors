# Rock Paper Scissors Game

Welcome to the classic game of Rock Paper Scissors! This simple Python script lets you play against the computer until either you or the CPU reaches a score of 3.

## How It Works

1. **Game Initialization:** 
   - Scores for both the player and the CPU start at 0, and ties are also tracked.
   - The possible moves are Rock, Paper, and Scissors.

2. **Gameplay Loop:**
   - The player is prompted to choose Rock, Paper, or Scissors.
   - The computer randomly selects a move from the same options.
   - The game compares the player's choice with the computer's choice to determine the winner for that round.
   - The scores are updated based on the result:
     - If the player wins, their score increases.
     - If the CPU wins, its score increases.
     - If it's a tie, the tie count increases.
   - The game continues until either the player or the CPU reaches a score of 3.

3. **End of Game:**
   - The game ends when either you or the CPU wins 3 rounds, and a final message thanks you for playing.
