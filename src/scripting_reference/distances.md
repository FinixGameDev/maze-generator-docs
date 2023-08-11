# Distances
class in FinixMakesGames.MazeGenerator.Core 

## Description
Class that represents a data collection of [Cells](./cell.md) in a Maze that forms a path or a set of paths relative to a root Cell and it's distance values

## Constructor
| Type      | Result                                                                                                                                                                      |
| :-------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Distances | Creates a new Distances class with a the provided root Cell component with the distance value set to 0, every other Cell distance value will be relative to this root Cell. |

## Public Methods
| Method                      | Description                                                                                                                                                                        |
| :-------------------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| this[Cell cell] | An override of the [] accessor. When given a Cell it will return it's integer distance to the root cell. If there is no path between these two Cells the value will be null. |
| Cells | Returns a IEnumerable Collection of all cells present in the collection.|
| PathTo | Returns a new Distances Class with ONLY the path between the root Cell and the provided goal Cell
| Max | Returns the Cell furthest away from the root Cell