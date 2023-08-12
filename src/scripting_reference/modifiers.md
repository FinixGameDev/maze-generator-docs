# Modifiers
This section refers to the modifiers feature of the asset. Modifiers are extra components the user can add into the maze game object and will automatically be picked up by the Maze component. These modifiers can either change the Maze at a layout level (changing the [Grid](./grid.md) information) or by selecting special cell and generating a special prefab instead of the selected ones.

Currently this tool only has a feature for prefabs modifiers and comes with 2 pre-built modifiers to test the feature. To learn more about making your own modifiers check the [IMazePrefabModifier](./prefab_modifier_interface.md) interface.

>Warning: Currently modifiers can be very CPU intensive, as such, it's not recomended to use modifiers in mazes that have a cell count above 400.

## Table of Contents
* [IMazePrefabModifier](./prefab_modifier_interface.md)
  * [EntraceExitModifier](./entrance_exit_modifier.md)
  * [UniqueTileModifier](./entrance_tile_modifier.md)