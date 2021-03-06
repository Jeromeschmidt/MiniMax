# Juniors Spring Intensive Deliverable README

Dates 3/16-3/25

**Jerome Schmidt**


**MiniMax Game Bot**


## Description
**Minimax bot that plays tic-tac-toe and connect4 against a user. Uses alpha-beta pruning for both games and depth limitation and an evaluation function for connect 4 to make the game more playable.**

## Setup
```bash
# clone the repo
git clone https://github.com/Jeromeschmidt/MiniMax.git
# cd into the cloned directory
cd MiniMax
# run the program
python3 main.py
```

## Example
**Tic-Tac-Toe**

![tic-tak-toe](assets/ttt_minimax.gif)

**Connect 4**

![connect 4](assets/connect4_minimax.gif)


## Phase 1
**Wrote versions of both tic-tac-toe and connect 4 that could be played by 2 players in the terminal.**

## Phase 2
**Built vanilla Minimax bot to play tic-tac-toe and connect 4 against a real user.**

## Phase 3
**Implemented alpha-beta pruning to reduce compute time**

**Since the compute time for connect 4 was significant enough to reason the game was unplayable, added depth limitation and evaluations function to reduce compute time. Depending on the depth allowed, this would lessen the difficulty but that can be adjusted.**

Evaluation Formula: score = ((number of possible streaks of 4)*10 + (number of possible streaks of 3)*5 + (number of possible streaks of 2)*2)

## Challenges I Faced
**Compute time for Connect 4 bot to make a single move could be greater than 1 hour on my laptop. Solved by using depth limitation of Minimax search and an evaluation function to significantly reduce compute time.**

**Student Name:**                
> Jerome Schmidt

**Make School Advisor Name**
> Alan Davis
