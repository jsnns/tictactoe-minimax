# TicTacToe: Minimax AI Dominance

In essence, we want to maxamize our score "O" while minimizing the score of our opponent "X". The best way of accieving this is with the Minimax function.

The Minimax function attempts to minimize the possible loss of a worst case (maximum loss).
- I.e. what are all the possible moves I can make?
- Will move '1' gain less score, or more?
- Keep going until you finish ALL of the possbile moves...
- Which one looses me the LEAST and harms my opponent the MOST.
- Take "that" move.
Using this knowledge I have created a TicTacToe solving bot that wins *or* draws *100%* of the time.

![Minimax Example](https://www.ocf.berkeley.edu/~yosenl/extras/alphabeta/alphabeta.jpg)
