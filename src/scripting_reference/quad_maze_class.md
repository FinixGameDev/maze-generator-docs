# QuadMaze
class in FinixMakesGames.MazeGenerator / Inherits from:[Maze](./maze_class.md)

## Description
A Unity component capable of creating rectangular mazes.

## Properties
| Property            | Description                                                                                                                                                                                                          |
| :------------------ | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| seed                | A string value used to determine the layout of a maze, leaving it empty will generate a random seed                                                                                                                  |
| cellSize            | The number of units that a single cell will ocupy in a scene.                                                                                                                                                        |
| rows                | The number of Cells created along the local z-axis.                                                                                                                                                                  |
| collumns            | The number of Cells created along the local x-axis.                                                                                                                                                                  |
| generationType      | An Enum used to determine whether the maze will be created with prefab tiles, or with simple walls and pillars                                                                                                       |
| algorithm           | The algorithm used to create the Maze layout                                                                                                                                                                         |
| ---                 | ---                                                                                                                                                                                                                  |
| corridorObjects     | A list of prefabs used in when generating the prefab with tiles, will select a random tile from this list every time it encounters a Cell with a corridor layout.                                                    |
| cornerObjects       | A list of prefabs used in when generating the prefab with tiles, will select a random tile from this list every time it encounters a Cell with a corner layout.                                                      |
| intersectionObjects | A list of prefabs used in when generating the prefab with tiles, will select a random tile from this list every time it encounters a Cell with a intersection/t-section layout.                                      |
| crossroadObjects    | A list of prefabs used in when generating the prefab with tiles, will select a random tile from this list every time it encounters a Cell with a crossroad/4-way layout.                                             |
| deadEndObjects      | A list of prefabs used in when generating the prefab with tiles, will select a random tile from this list every time it encounters a Cell with deadend.                                                              |
| ---                 | --- These can be set to empty if the maze is being generated with the walls and pillars                                                                                                                              |
| wallPrefab          | A prefab used as the walls when generating the maze with the walls and pillars method. Note: this prefab will be stretched to fit the cellSize.                                                                      |
| pilarPrefab         | A prefab used as the pillar when generating the maze with the walls and pillars method.                                                                                                                              |
| ---                 | ---These can be set to empty if the maze is being generated with the tile prefabs                                                                                                                                    |
| generateOnStart     | If set to true, it will generate a new maze every time the scene loads on the Start() frame.                                                                                                                         |
| ---                 | ---                                                                                                                                                                                                                  |
| grid                | A [QuadGrid](./quad_grid.md) class with the maze layout information                                                                                                                                                  |
| uniqueTiles         | A dictionary of Cells and Prefabs used for [Modifiers](./modifiers/modifiers.md) and the prefab tiles method. When detecting a cell contained in the dictionary it will spawn the corresponding prefab instead of a random one. |

## Public Methods
| Method     | Description                                     |
| :--------- | :---------------------------------------------- |
| CreateMaze | Generates the maze                              |
| ResetMaze  | Destroys every child object of this maze object |