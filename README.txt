Treasure Hunt in the Enchanted Forest

Description:
This assignment involves navigating through an Enchanted Forest to find a hidden treasure. The forest is represented as an 8x8 grid with various elements such as safe grids, obstacles, animals, and endpoints. The objective is to reach the treasure located at the southeast corner while avoiding dangers and overcoming obstacles.

Implemented Algorithms:
Two algorithms have been implemented to find the optimal path through the forest:
1. Uniform Cost Search (UCS): This algorithm explores paths in order of increasing cost, guaranteeing the shortest path to the goal.
2. A* Search: A heuristic-based algorithm that combines the cost of reaching a node with an estimate of the remaining cost to the goal. The heuristic used here is the Manhattan distance between the current position and the goal.

Running the Program:
Running the program is very simple....just run the cell and you are good to go.

Libraries Used:
Only random library is used and PriorityQueue is used.

Optimization Details:
PriorityQueue has been used in order to dequeue the path with minimal cost everytime.

Dynamics and Error Handling:
Proper error handling has been imlemented and proper checks have been added.

Randomization:
The grid is being generated randomly in the following steps:

The random grid generation in the code works by creating an 8x8 grid (although the size can be different) representing the Enchanted Forest. Here's how it works:

Initialization: The ForestGrid class initializes with a default size of 8. However, this size can be adjusted if needed.

Grid Generation: Upon calling the generate_grid method, it creates the forest grid by iterating over each cell in the grid.

Cell Type Selection: For each cell, a random selection is made to determine its type. The cell can be one of the following:

0: Representing a safe grid (60% chance).
-1: Representing an obstacle (40% chance).
5: Representing an endpoint (5% chance).
4: Representing a wild animal (random chance).
Start and Goal Assignment: After generating the grid, the starting point is set to the northwest corner (2), and the goal is set to the southeast corner (3).

Output: Finally, the generated grid is returned as a list of lists representing the forest grid.

Overall, this approach ensures the creation of a dynamically changing Enchanted Forest with random obstacles, endpoints, and animals, providing a unique and challenging adventure for the adventurer to navigate through.

Group Collaboration Details:
We have worked with collaboration and done both questions collectively.