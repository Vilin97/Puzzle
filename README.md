# Puzzle
The Puzzle is as follows.
You and your friend are put in prison by an evil mathematician. The mathematician will flip a coin n times, for a very large n, and tell you 
the results of odd flips, and your friend -- the results of even flips. You will have to name an even number i, and your friend -- an odd number j.
If the flip i is the same as flip j, you escape the prison. If not, you stay in prison forever.
You and your friend are allowed to talk beforehand to devise strategy. What strategy should you follow, and with what probability can you escape?

This code explores all possible strategies (find_good_strategies() function) by trying all possible (symmetric) strategies. The best probability 
is claimed to be 0.75. That's the goal.
On six coin flips the highest probability is 0.6875 = 44/64. What about 8? 
