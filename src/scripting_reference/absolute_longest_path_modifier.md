# AbsoluteLongestPathModifier
class in FinixMakesGames.MazeGenerator / Inherits from:[MonoBehaviour](https://docs.unity3d.com/ScriptReference/MonoBehaviour.html), [IMazePrefabModifier](./prefab_modifier_interface.md)

## Description
A modifier designed to add a pair of prefab tiles. This modifier will always pick the pair most further apart possible.

>Warning: Because this modifier searches for the absolute longest path in a maze it can be very CPU intensive, as such, it's not recomended to use it in mazes that have a cell count above 400 (e.g. A 40x40 maze can require Dijkstra's algorithm to run aproximately 16 000 times). 

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
