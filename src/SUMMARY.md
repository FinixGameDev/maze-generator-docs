# Summary

[Finix's Maze Generator Documentation](README.md)

-----------
# User Guide
-----------
- [Installation](./guide/installation.md)
- [Getting Started](./guide/getting_started.md)
  - [Setting Up Prefabs](./guide/prefabs.md)
- [Save your maze to an Image](./guide/maze_printer.md)
- [Package Contents](./guide/package_contents.md)
  
----------
# Scripting Reference
-----------
- [Base Namespace](./scripting_reference/maze_generator_scripting_intro.md)
  - [Maze](./scripting_reference/maze_class.md) 
    - [QuadMaze](./scripting_reference/quad_maze_class.md) 
  - [Modifiers](./scripting_reference/modifiers/modifiers.md)
    - [IQuadMazeDataModifier](./scripting_reference/modifiers/quad_data_modifier_interface.md)
      - [CellLinkModifier](./scripting_reference/modifiers/cell_link_modifier.md)
    - [IQuadMazePrefabModifier](./scripting_reference/modifiers/prefab_modifier_interface.md)
      - [AbsoluteLongestPathModifier](./scripting_reference/modifiers/absolute_longest_path_modifier.md)
      - [RelativeLongestPathModifier](./scripting_reference/modifiers/relative_longest_path_modifier.md)
      - [RandomTileModifier](./scripting_reference/modifiers/entrance_tile_modifier.md)
- [Core Namespace](./scripting_reference/core.md)
  - [MazeCell](./scripting_reference/cell.md)
    - [QuadCell](./scripting_reference/quad_cell.md)
  - [MazeGrid](./scripting_reference/grid.md)
    - [QuadGrid](./scripting_reference/quad_grid.md)
  - [Algorithms](./scripting_reference/algorithms.md)
  - [Distances](./scripting_reference/distances.md)
- [Editor Namespace](./scripting_reference/editor/editor.md)
  - [MazeEditor](./scripting_reference/editor/maze_editor.md)
  - [MazePrinterEditor](./scripting_reference/editor/maze_print_editor.md)



