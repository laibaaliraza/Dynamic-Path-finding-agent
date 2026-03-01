Dynamic Pathfinding Agent:
This is a python project for visualizing A* and Greedy search algorithms on a grid You can create your own grid put obstacles and see how agent find path from start to goal It also has dynamic obstacles that can appear while agent moving so agent replans path if needed

Features:
Create custom grid of any size
Place obstacles manually by clicking on cells
Generate random maps with obstacle density
Choose algorithm A* or Greedy
Choose heuristic Manhattan or Euclidean
Step by step agent movement with visualization
Dynamic obstacles mode for more challenging environment
Shows metrics nodes visited path cost and execution time

How to Use:
Run the main.py file
Enter number of rows and columns and click Create Grid
Click cells to toggle obstacles manually
Or enter % of obstacles and click Random Map to generate map automatically
Select algorithm A* or Greedy and heuristic Manhattan or Euclidean
Check Dynamic Mode if you want random obstacles while agent moving
Click Run Search to see the agent move step by step
Click Reset to clear the grid and start again

Colors in Grid:
Start cell : Beige
Goal cell : Peru
Empty cell : Orchid
Obstacle : Teal
Frontier / neighbor : Black
Visited cell : Lavender
Path : Green
Dynamic obstacle : Purple
Cleared cell : Pink

Note:
The agent moves step by step so sometimes it looks slow but it is for visualization
If path gets blocked by dynamic obstacle agent automatically replans
The grid colors are chosen to be clear and easy to see
Works with python 3.x and tkinter installed

Requirements:
Python 3.x
Tkinter usually comes with python

Future Improvements:
Add diagonal movements
Add more algorithms like Dijkstra
Make movement speed adjustable
