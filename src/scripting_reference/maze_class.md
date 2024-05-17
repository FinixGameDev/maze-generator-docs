# Maze
class in FinixMakesGames.MazeGenerator / Inherits from:[MonoBehaviour](https://docs.unity3d.com/ScriptReference/MonoBehaviour.html)

## Description
An abstract class meant to store common data between the different types of mazes.

## Enums
| Enum           | Description                                                                                            |
| :------------- | :----------------------------------------------------------------------------------------------------- |
| GenerationType | An enum used in the Inspector window to select the generation method used when creating a maze         |
| AlgorithmType  | An enum used in the Inspector window to select the algorithm used when creating the layout of the maze |

## Methods

## Public Methods
| Method        | Description                                                                                          |
| :------------ | :--------------------------------------------------------------------------------------------------- |
| ToTexture     | Returns a [Texture2D](https://docs.unity3d.com/ScriptReference/Texture2D.html) of the Maze map.                                                             |