---
layout: page
title: Variations of tic-tac-toe
permalink: /modules/tic-tac-toe/variations
---

### Game of Fifteen
In the **Game of Fifteen**, two players take turns choosing numbers according to the following rules.

1. Each player takes turns choosing a number greater than $$0$$ and less than $$10$$.
2. Once a number has been chosen, it cannot be chosen again.
3. The first player to collect three numbers that add up to $$15$$ wins.
4. If all the numbers have been chosen and no player has won, then the game is a draw.

The Game of Fifteen turns out to be very related to tic-tac-toe, as we will see in Problem 1.

### Game of Thirty-four
Similar to the Game of Fifteen, we can make the **Game of Thirty-four**, whose rules are very similar.

1. Each player takes turns choosing a number greater than $$0$$ and less than $$17$$.
2. Once a number has been chosen, it cannot be chosen again.
3. The first player to collect four numbers that add up to $$34$$ wins.
4. If all the numbers have been chosen and no player has won, then the game is a draw.

### The $$m,n,k$$-game
A more general variation of tic-tac-toe is the $$m,n,k$$-game.
The rules are identical, except it is played on an $$m\times n$$ grid rather than a $$3\times 3$$ grid, and the goal is to get $$k$$ in a row.

## Problems
### Problem 1 
The Game of Fifteen turns out to be identical to Tic-tac-toe, though it is not immediately apparent.
To see why this is, consider the following $$3\times 3$$ grid of numbers

$$
\begin{array}{|c|c|c|}\hline
 8 & 1 & 6 \\\hline
 3 & 5 & 7 \\\hline
 4 & 9 & 2 \\\hline
\end{array}
$$

* **Part A** Show that each row, each column and each diagonal of the above grid adds up to $$15$$.
Squares with this property are called **magic squares**.
* **Part B** List (up to reordering) all the possible triples $$(a,b,c)$$ of integers between $$1$$ and $$9$$ which don't repeat digits and which sum up to $$15$$.  Show that each occurs as either a row, column, or diagonal in the matrix above.
* **Part C** Use the results of Problem 1 and Problem 2 to explain why the Game of Fifteen is the same as Tic-tac-toe.

### Problem 2
Consider the table below, which is an example of a $$4\times 4$$ magic square.

$$
\begin{array}{|c|c|c|c|}\hline
 2 & 16 & 13 &  3\\\hline
11 &  5	&  8 & 10\\\hline
 7 &  9 & 12 &  6\\\hline
14 &  4 &  1 & 15\\\hline
\end{array}
$$

* **Part A** Show that each row, each column and each diagonal of the above grid adds up to $$34$$.
* **Part B** Find some examples of four entries in the matrix above which sum to $$34$$ but are not rows, columns, or diagonals.
* **Part C** Explain why even though we have a similar situation as in Problem 1, it is **not** true that the Game of Thirty-four is the same as the $$4,4,4$$-game.



