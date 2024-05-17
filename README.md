# Connect-4
AI connect game, where a user can play connect 4, 5, ect against the computer. 

In short this was a final project, where we used multiple AI methods to allow the computer to make future moves, whether that was against a user, itself or a different algorithms.

The two algorithms we used where A* and Alpha-Beta Pruning. Both search algorithms use a cost based search, where the "cheapest" path would be the best. With a couple of differences the main thing that A* uses a heuristic or an ideal of what it takes to win and a probability of a move being the way to win. Alpha-Beta uses a min max method of seeing which path was best. Where it sees ahead and gets rid of the “branches” where winning is not possible.

I also used a random player which would place tiles in random locations. From the results, winning against these algorithms was impossible.

