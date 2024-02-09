# Leslie_Konlack
~Algorithm and design
Assignment 2
Question 5d~

Magic Square Generation README
Overview
In this project, I compared the two algorithms for generating magic squares: My designed exhaustive search method and the Siamese method. A magic square is a grid where the sum of every row, column, and diagonal is the same.

Exhaustive Search Algorithm
My exhaustive search tries every possible number combination in the square, checking if each forms a magic square. It's straightforward but slow, suitable only for small squares (up to 3x3 in my tests).

Siamese Algorithm
The Siamese method is a clever, fast approach for odd-sized squares. It starts with 1 at the bottom middle, then moves diagonally down-right for each new number. If this spot is taken or out of bounds, it goes one up instead. This pattern guarantees a magic square for any odd-sized grid.

Experiment
I tested both algorithms to find their limits. The exhaustive search worked up to a 3x3 square, taking about 0.07 seconds. It was the larger value of n to find a magic square of order n in less than 1minute. The Siamese method handled a 1997x1997 square in 0.964664 seconds of my computer’s time, the larger value of n to find a magic square of order n in less than 1minute. This huge difference has showed me the efficiency of using smart, rule-based algorithms for specific problems.

Conclusion
While my exhaustive search is simple, it's not practical for large squares. The Siamese method, however, is perfect for creating large, odd-sized magic squares quickly. This experiment highlighted to me the importance of choosing the right algorithm for the task.
