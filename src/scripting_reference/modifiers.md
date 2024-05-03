# Modifiers
This section refers to the modifiers feature of the asset. Modifiers are extra components the user can add into the maze game object and will automatically be picked up by the Maze component. These modifiers can either change the Maze at a layout level (changing the [Grid](./grid.md) information) or by selecting special cell and generating a special prefab instead of the selected ones.

Currently this tool only has a feature for prefabs modifiers and comes with 2 pre-built modifiers to test the feature. To learn more about making your own modifiers check the [IMazePrefabModifier](./prefab_modifier_interface.md) interface.

## Table of Contents
* [IMazePrefabModifier](./prefab_modifier_interface.md)
  * [AbsoluteLongestPathModifier](./absolute_longest_path_modifier.md)
  * [UniqueTileModifier](./entrance_tile_modifier.md)