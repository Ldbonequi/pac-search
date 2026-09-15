To run code:
-cd into  project directory

-run any of the following commands to test each search function:
  Q1 (DFS):
    python pacman.py -l tinyMaze -p SearchAgent
    python pacman.py -l mediumMaze -p SearchAgent
    python pacman.py -l bigMaze -z .5 -p SearchAgent
  Q2 (BFS):
    python pacman.py -l mediumMaze -p SearchAgent -a fn=bfs
    python pacman.py -l bigMaze -p SearchAgent -a fn=bfs -z .5
    python eightpuzzle.py
  Q4 (A*):
    python pacman.py -l bigMaze -z .5 -p SearchAgent -a fn=astar,heuristic=manhattanHeuristic

-To run the autograder: 
  python autograder.py
OR:
  open DEMO.ipynb notebook file where it has been run already and can be re-ran in a cell
