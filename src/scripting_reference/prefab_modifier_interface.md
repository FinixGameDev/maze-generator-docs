# IMazePrefabModifier
interface in FinixMakesGames.MazeGenerator

## Description
An interface used to create Maze [Modifiers](./modifiers.md).

## Public Methods
| Method        | Description                                                                                    |
| :------------ | :--------------------------------------------------------------------------------------------- |
| ApplyModifier | Adds one or multiple <Cell,GameObject> pairs to the uniqueTiles property in the given QuadMaze. |

## Creating your own Prefab Modifiers
* Create a new C# Script in the editor.
* Keep the Monobehaviour inheritance, so that you can later add it to the Maze game object.
* Make the scipt inherit from the IMazePrefabModifier interface.
* Implement the ApplyModifier function and other extra logic you might need, keep in mind that this function needs:
  * To read from the Maze Grid the Cells you intend to modify.
  * The prefabs you wish to add in those Cells instead of the default ones.
  * Acess the [uniqueTiles](./quad_maze_class.md#properties) Dictionary in the [QuadMaze](./quad_maze_class.md) reference and insert a pair of that Cell and Prefab.
* Finally test the modifier by adding it has a component to the same game object that has the [QuadMaze](./quad_maze_class.md) component and hitting the Create Maze button.
