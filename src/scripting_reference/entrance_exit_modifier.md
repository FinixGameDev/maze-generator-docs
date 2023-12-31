# EntranceExitModifier
class in FinixMakesGames.MazeGenerator / Inherits from:[MonoBehaviour](https://docs.unity3d.com/ScriptReference/MonoBehaviour.html), [IMazePrefabModifier](./prefab_modifier_interface.md)

## Description
A modifier designed to add a pair of prefab tiles. This modifier will always pick the pair most further apart possible.

## Properties
| Property       | Description                                                  |
| :------------- | :----------------------------------------------------------- |
| entrancePrefab | The tile used for the entrance cell.                          |
| entranceLinks  | How many links/paths the entrance prefab is supposed to have. |
| exitPrefab     | The tile used for the exit cell.                              |
| exitLinks      | How many links/paths the exit prefab is supposed to have.     |


## Inhereted Members

## Public Methods
| Method        | Description                                                                                    |
| :------------ | :--------------------------------------------------------------------------------------------- |
| ApplyModifier | Adds one or multiple <Cell,GameObject> pairs to the uniqueTiles property in the given QuadMaze. |
