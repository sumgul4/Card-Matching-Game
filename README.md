# Card-Matching-Game
 A C program for a card matching game where the user plays against the computer with varying difficulty levels.

## YTU - Introduction to Computer Science - Term Project
- Easy level: 4x4 board, computer remembers 2 cards.
- Medium level: 6x6 board, computer remembers 6 cards.
- Hard level: 8x8 board, computer remembers 16 cards.
If a player matches a pair, they get another turn.
The player who matches more than half the cards wins the game.
  
### Prerequisites

- An IDE or compiler capable of compiling C language (e.g., Dev-C++)

### How to Play

1. When the program starts, you will be asked to choose a difficulty level.
   - For easy level, press 1
   - For medium level, press 2
   - For hard level, press 3
   - For game information, press 4
     
2. After selecting the level, the game board will be created and the cards will be randomly distributed.

3. The user takes turns to flip two cards by entering the row and column coordinates. If the cards match, the user scores a point and gets another turn. If the cards do not match, it's the computer's turn.

4. The computer will then flip two cards and try to find matching pairs. The computer has a memory capacity and can remember previously flipped cards.

5. The game continues until all cards are matched or one player matches more than half of the total cards.
