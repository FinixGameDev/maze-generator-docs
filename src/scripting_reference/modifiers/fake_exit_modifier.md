# FakeExistModifier
class in FinixMakesGames.MazeGenerator / Inherits from:[MonoBehaviour](https://docs.unity3d.com/ScriptReference/MonoBehaviour.html), [IQuadMazeDataModifier](./quad_data_modifier_interface.md)

## Description
Creates a true entrance and exit as well as a select number of fake exits.


## Properties
| Property       | Description                                             |
| :------------- | :------------------------------------------------------ |
| cutPaths       | Remove the connection to the valid path                 |
| longestExit    | Always choose the longest candidate cell as the true exit |
| entrancePrefab | Reference to the entrance prefab to spawn               |
| exitPrefab     | Reference to the exit prefab to spawn                   |
| fakeExitPrefab | Reference to the exit prefab to spawn                   |
| fakeExitCount  | Number of fake exits to spawn                        |



## Inhereted Members

### Public Methods
| Method        | Description                                                                                    |
| :------------ | :--------------------------------------------------------------------------------------------- |
| ApplyDataModifier | Modifies the Cell links and consequently the Grid layout|
| ApplyPrefabModifier | Adds one or multiple <QuadCell,GameObject> pairs to the uniqueTiles property in the given QuadMaze. |
