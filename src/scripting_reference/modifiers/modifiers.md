# Modifiers
This section refers to the modifiers feature of the asset. Modifiers are extra components the user can add into the maze game object and will automatically be picked up by the Maze component. These modifiers can either change the Maze at a layout level (changing the [Grid](./grid.md) information) or by selecting special cells and generating a special prefab instead of the selected ones.

## Table of Contents
* [IQuadMazeDataModifier](./quad_data_modifier_interface.md)
  * [CellLinkModifier](./cell_link_modifier.md)
* [IQuadMazePrefabModifier](./prefab_modifier_interface.md)
  * [AbsoluteLongestPathModifier](./absolute_longest_path_modifier.md)
  * [RelativeLongestPathModifier](./relative_longest_path_modifier.md)
  * [RandomTileModifier](./entrance_tile_modifier.md)


## Creating your own Prefab Modifiers
* Create a new C# Script in the editor.
* Keep the Monobehaviour inheritance, so that you can later add it to the Maze game object.
* Make the scipt inherit from the IQuadMazePrefabModifier interface or IQuadMazeDataModifier.
* Implement the ApplyPrefabModifier function and other extra logic you might need, keep in mind that this function needs:
  * To read from the Maze Grid the Cells you intend to modify.
  * The prefabs you wish to add in those Cells instead of the default ones.
  * Acess the [uniqueTiles](./../quad_maze_class.md#properties) Dictionary in the [QuadMaze](./../quad_maze_class.md) reference and insert a pair of that Cell and Prefab.
* Finally test the modifier by adding it has a component to the same game object that has the [QuadMaze](./../quad_maze_class.md) component and hitting the Create Maze button.