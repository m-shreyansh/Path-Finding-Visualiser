# PATH FINDING VISUALISER

Path Finding Visualiser is a 2-D maze generation and optimal path-finder that has been developed using PyGame (a Python set of modules).

It uses the heuristic A-Star algorithm to determine paths between 2 nodes in a Two-Dimenstional Grid with some obstacles in between (which is dependent on the interactive user where he/she wants to place them). Based on a heuristic function, different possible paths are traversed and once the final node is reached; using backtracking the shortest path is found and visualised. The project aims at understanding how the A-Star algorithm actually functions and can be visually interpreted. 

## Requirements
Installing Pygame.

Try any one of the following two commands:

pip install pygame

python -m pip install pygame

After installing Pygame, simply run the command to run the Project:
python main.py

## Running of the project

Initially, on a 2-D Grid you can choose two different position, starting and ending position, by right clicking on the 2-D grid. The starting position is marked by yellow and ending position is marked by a blue node.

Once it has been done, you can now start placing obstacles interactively by right clicking on the cells you want to. The obstacles are represented by black colour.

Once you're done with placing obstacles, press the Space Bar on your Keyboard to let the project function and determine paths heurestically from starting to ending node. The visualisation of the whole process can be seen using a red stream that flows from the starting node that tries to reach the ending node. The functioning A-Star algorithm is visualised through this manner.

Once the final node is reached, a stream of purple colour backtracks to find the optimal path free of obstacles from starting to ending node.

## STARTING, ENDING AND OBSTACLE POSITIONING EXAMPLE
![Initial](https://user-images.githubusercontent.com/72565175/126190690-dfdb0e71-435e-49de-9483-f442fa35c255.png)

## A-STAR ALGORITHM PATH FINDING VISUALISATION USING RED STREAM
![In_between](https://user-images.githubusercontent.com/72565175/126190766-88c804b0-8e26-46ae-805c-1b0949606d2c.png)

## FINAL PATH DETERMINATION USING PURPLE STREAM
![Final](https://user-images.githubusercontent.com/72565175/126190756-92c7af89-8238-4e8e-bb6d-bfa07d8543e2.png)


