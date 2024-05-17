# RandomTileModifier
class in FinixMakesGames.MazeGenerator / Inherits from:[MonoBehaviour](https://docs.unity3d.com/ScriptReference/MonoBehaviour.html), [IQuadMazePrefabModifier](./prefab_modifier_interface.md)

## Description
A modifier designed to select candidate Cells and chooses a random one to apply a choosen prefab.


## Properties
| Property   | Description                                                  |
| :--------- | :----------------------------------------------------------- |
| tilePrefab | The tile used for the unique cell.                            |
| tileType   | The format of the tile you want to switch |


## Inhereted Members

### Public Methods
| Method        | Description                                                                                    |
| :------------ | :--------------------------------------------------------------------------------------------- |
| ApplyPrefabModifier | Adds one or multiple <QuadCell,GameObject> pairs to the uniqueTiles property in the given QuadMaze. |
