# QuadCell
class in FinixMakesGames.MazeGenerator.Core / Inherits from:[Cell](./cell.md)
## Description
Class that represents the basic unit of a  [QuadGrid](./quad_grid.md) and by extension a [QuadMaze](./quad_maze_class.md).

## Constructor
| Type     | Result                                                                                            |
| :------- | :------------------------------------------------------------------------------------------------ |
| QuadCell | Creates a new cell with the given row and collumn components, sets the neighbouring cells to null |

## Properties
| Property                 | Description                                                                      |
| :----------------------- | :------------------------------------------------------------------------------- |
| row                      | The position of the Cell within the [QuadGrid](./grid.md) on the horizontal axis |
| collumn                  | The position of the Cell within the [QuadGrid](./grid.md) on the vertical axis   |
| north, east, west, south | References to each of the four neighbouring Cells relative to this one.          |

## Inherited Members
## Properties
| Property | Description                            |
| :------- | :------------------------------------- |
| links    | Array of all Cells linked to this Cell |

## Public Methods
| Method        | Description                                                                                          |
| :------------ | :--------------------------------------------------------------------------------------------------- |
| Link          | Links this Cell to another Cell, making a path between them.                                         |
| UnLink        | Removes a link from a choosen Cell to this one.                                                      |
| IsLinked      | Check if a Cell is linked to this one.                                                               |
| Neighbors     | Returns a list of all neighboring cells whether they're linked or not.                               |
| CellDistances | Returns a [Distances](./distances.md) class with all paths and their relative distance to this Cell. |