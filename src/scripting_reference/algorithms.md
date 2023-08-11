# Algorithms
class in FinixMakesGames.MazeGenerator.Core / Implemented in FinixMakesGames.MazeGenerator.Core

## Description
A static class that holds a collections of methods that picks up a new [Grid](./grid.md) class and generates it's maze layout.

## Static Methods
| Method               | Description                                                                                                                                                                                                       |
| :------------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BinaryTree           | Applies the [Binary Tree](https://en.wikipedia.org/wiki/Maze_generation_algorithm#Simple_algorithms) algorithm to a Grid (Only available to [QuadGrid](./quad_grid.md)).                                          |
| Sidewinder           | Applies the [Sidewinder](https://en.wikipedia.org/wiki/Maze_generation_algorithm#Simple_algorithms) algorithm to a Grid (Only available to [QuadGrid](./quad_grid.md)).                                           |
| AldousBroder         | Applies the [Aldous-Broder](https://en.wikipedia.org/wiki/Maze_generation_algorithm#Aldous-Broder_algorithm) algorithm to any type of [Grid](./grid.md).                                                          |
| Wilson               | Applies [Wilson's](https://en.wikipedia.org/wiki/Maze_generation_algorithm#Wilson's_algorithm) algorithm to any type of [Grid](./grid.md).                                                                        |
| HuntAndKill          | Applies the [Hunt-And-Kill](https://weblog.jamisbuck.org/2011/1/24/maze-generation-hunt-and-kill-algorithm) algorithm to a Grid (Only available to [QuadGrid](./quad_grid.md)).                                   |
| RecursiveBacktracker | Applies the [Recursive Backtracker](https://en.wikipedia.org/wiki/Maze_generation_algorithm#Randomized_depth-first_search) algorithm (Also known has a Randomized Depth-First Search) to any type of [Grid](./grid.md). |



