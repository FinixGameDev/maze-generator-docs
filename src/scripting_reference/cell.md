# Cell
class in FinixMakesGames.MazeGenerator.Core 

## Description
An Abstract Class that represents the basic unit of a maze. Similar to a node in a graph, the Cell is meant to represent a point in a maze [Grid](./grid.md) and it stores how that point connects to other neighbouring points/Cells.

## Properties
| Property | Description                            |
| :------- | :------------------------------------- |
| links    | Array of all Cells linked to this Cell |

## Public Methods
|Method|Description|
|:---|:---|
|Link| Links this Cell to another Cell, making a path between them.
|UnLink| Removes a link from a choosen Cell to this one.
|IsLinked| Check if a Cell is linked to this one.
|Neighbors| Returns a list of all neighboring cells whether they're linked or not.
|CellDistances| Returns a [Distances](./distances.md) class with all paths and their relative distance to this Cell.