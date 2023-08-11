# QuadGrid
class in FinixMakesGames.MazeGenerator.Core / Inherits from:[Grid](./grid.md)

## Description
A class that represents a rectangular Maze in it's raw data form without any graphics.

## Constructor
| Type     | Result                                                                                                                     |
| :------- | :------------------------------------------------------------------------------------------------------------------------- |
| QuadGrid | Creates a new grid with the given row and collumn components, creates a new collection of cells and assings it's neighbors. |

## Properties
| Property  | Description                                                                                         |
| :-------- | :-------------------------------------------------------------------------------------------------- |
| cells     | A double Array of [QuadCell](./quad_cell.md) that stores all Cells present in this grid   .         |
| distances | A class [Distances](./distances.md) variable that can store a collection of paths. Null by default. |

## Inhereted Members
## Public Methods
| Method     | Description                                                      |
| :--------- | :--------------------------------------------------------------- |
| RandomCell | Returns a random Cell from the Grid.                             |
| Size       | Returns the number of total Cells present in this Grid.          |
| DeadEnds   | Returns a list of Cells that have only one link to another cell. |
| ToString   | Represents the maze in form of a string. Usefull for debugging.  |