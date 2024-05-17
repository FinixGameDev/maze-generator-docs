# RelativeLongestPathModifier
class in FinixMakesGames.MazeGenerator / Inherits from:[MonoBehaviour](https://docs.unity3d.com/ScriptReference/MonoBehaviour.html), [IQuadMazePrefabModifier](./prefab_modifier_interface.md)

## Description
A modifier designed to add a prefab tile that's furthest away from a chosen cell.

## Properties
| Property          | Description                                                                     |
| :---------------- | :------------------------------------------------------------------------------ |
| startTilePosition | The position of the tile that the modifier will use to choose the furthest cell |
| endPrefab        | The tile used for the exit cell.                                                |
| endLinks         | How many links/paths the exit prefab is supposed to have.                       |


## Inhereted Members

### Public Methods
| Method              | Description                                                                                         |
| :------------------ | :-------------------------------------------------------------------------------------------------- |
| ApplyPrefabModifier | Adds one or multiple <QuadCell,GameObject> pairs to the uniqueTiles property in the given QuadMaze. |
