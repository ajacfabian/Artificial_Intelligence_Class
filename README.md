Assignment 1
Classwork for Artificial Intelligence class.
Tasked to solve the dirt vacuum problem, an 8 by 8 grid, 20 random cells contain dirt, and one agent.
The agent starts in the bottom left corner, and moves about in the four cardinal directions, up, down, left, and right.
If the agent moves into a cell with dirt, it cleans the dirt and attempts to find more. If all 20 dirt are cleaned, the agent attempts to return to its starting location. It has 1000 actions (movement and vacuuming) to clean the grid.
A score is generated upon completion. -10 points for every movement, -10 for vacuuming dirt, +100 points for vacuuming dirt, -1000 for not ending the program in the starting location. Scores above 0 are possible, but rare.
