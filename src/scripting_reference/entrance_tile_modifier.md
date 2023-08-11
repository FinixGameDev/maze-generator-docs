# UniqueTileModifier
class in FinixMakesGames.MazeGenerator / Inherits from:[MonoBehaviour](https://docs.unity3d.com/ScriptReference/MonoBehaviour.html), [IMazePrefabModifier](./prefab_modifier_interface.md)

## Description
A modifier designed to select candidate Cells and chooses a random one to apply a choosen prefab.


## Properties
| Property   | Description                                                  |
| :--------- | :----------------------------------------------------------- |
| tilePrefab | The tile used for the unique cell.                            |
| tileLinks  | How many links/paths the entrance prefab is supposed to have. |


## Inhereted Members

## Public Methods
| Method        | Description                                                                                    |
| :------------ | :--------------------------------------------------------------------------------------------- |
| ApplyModifier | Adds one or multiple <Cell,GameObject> pairs to the uniqueTiles property in the given QuadMaze. |
