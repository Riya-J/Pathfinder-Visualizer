## Pathfinder-Visualizer

#### The aim of this project is to approximate the shortest path in real-life situations, like- in maps, games where there can be many hindrances. A star algorithm is used for the same. 

## A star algorithm

#### A * algorithm is a searching algorithm that searches for the shortest path between the initial and the final state. It is used in various applications, such as maps.
A* algorithm has 3 parameters:

g : the cost of moving from the initial cell to the current cell. Basically, it is the sum of all the cells that have been visited since leaving the first cell.
h : also known as the heuristic value, it is the estimated cost of moving from the current cell to the final cell. The actual cost cannot be calculated until the final cell is reached. Hence, h is the estimated cost. We must make sure that there is never an overestimation of the cost.

f : it is the sum of g and h. So, f = g + h

The way that the algorithm makes its decisions is by taking the f-value into account. The algorithm selects the smallest f-valued cell and moves to that cell. This process continues until the algorithm reaches its goal cell.

