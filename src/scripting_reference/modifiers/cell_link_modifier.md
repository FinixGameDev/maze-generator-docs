# CellLinkModifier
class in FinixMakesGames.MazeGenerator / Inherits from:[MonoBehaviour](https://docs.unity3d.com/ScriptReference/MonoBehaviour.html), [IQuadMazeDataModifier](./quad_data_modifier_interface.md)

## Description
Allows the user to manually set the paths of a selected Cell.


## Properties
| Property       | Description                                             |
| :------------- | :------------------------------------------------------ |
| _cellPosition  | The position of the Cell in the Grid                    |
| _unLinkIfFalse | If true removes the path of the directions set to false |
| _north         | Makes a link to the north path                          |
| _south         | Makes a link to the south path                          |
| _west          | Makes a link to the west path                           |
| _east          | Makes a link to the east path                           |



## Inhereted Members

### Public Methods
| Method        | Description                                                                                    |
| :------------ | :--------------------------------------------------------------------------------------------- |
| ApplyPrefabModifier | Adds one or multiple <QuadCell,GameObject> pairs to the uniqueTiles property in the given QuadMaze. |