# Turing Complete (Game) Maze Solver
Sreenivas Eadara

This is a maze solver I wrote for the maze puzzle in Turing Complete.
The strategy involves a trick I remembered about navigating buildings - by keeping your hand on the right-hand wall and walking along it, you can find an exit.
It's a very satisfying puzzle and I enjoyed working on it.

I'm sharing my code because it's poorly optimized (checking for the door could be integrated with checking for an empty space, I only used cond_gt_0 to jump as opposed to an always jump command, unnecessary jump commands, etc) and I hope people (who have already solved the puzzle!) can use it as a stepping stone to make even cooler, faster, better solutions.

Have fun!
