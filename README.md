# deep_sea_adeventure_ai
Simplistic Computer player for the board game Deep Sea Adventure.

Rule based AI which randomly selects rules to follow.
  - The AI will either pick up the first 2, 3 or 4 it lands on and always turns back next turn.
  - If the first piece it took was a 2, it will attempt to pick up more pieces to total 4 i.e. 1 more 2, or 2 more 1s.
  - If the first piece took was a 3 or 4 there is a 50% chance it will pick up the first 1 it lands on on its way back.

Currently only runs in a jupyter notebook.

Initialise a computer player with 
`player1 = randomRuleAI()`.
On a computer's turn, roll the dice, move the computer's token and run `player1.play(x)` where x is the number of the tile the computer lands on`. The computer will then tell you if it is "Going back" or "Picking up"
