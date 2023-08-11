# Getting Started
Now that you've installed this package, on the Assets folder you can go to Finix's Maze Generator ▶︎ Scenes ▶︎ Sample Scene and mess around with the maze already pre-built in the scene.

## Table of Contents
- [Getting Started](#getting-started)
  - [Table of Contents](#table-of-contents)
  - [Using the package](#using-the-package)
    - [Adding a Maze into a scene](#adding-a-maze-into-a-scene)
    - [Customizing your Maze](#customizing-your-maze)
    - [Adding Modifiers](#adding-modifiers)


## Using the package
### Adding a Maze into a scene
* To add a maze in another scene go to the tool bar on top of the Editor and selecting Tools ▶︎ Maze Generator ▶︎ Quad Maze.
* Alternitavely you can go to the Hierarchy window and create a new Empty Object and on the inspector window of that object add a new Quad Maze Component, by using this method you need to manually assign what prefabs you want for the different maze parts and Generation methods. When all of that is set-up click the Generate Maze button.

### Customizing your Maze
Upon inspecting the Quad Maze component on the Inspector window you might notice a bunch of parameters to tweak and change. To see more information about each one check the documentation refering to the [QuadMaze](../scripting_reference/quad_maze_class.md) class.

You're main concern now should be setting up your desired prefabs. To do so first we need to talk about the two generation types:
* Walls Type: Generates only the walls and pillars of the maze, to use it simply set the Generation Type parameter to Walls Type and add a prefab to the Wall Prefab Slot and the Pillar Prefab in the bottom.
* Prefab Type: This one is a more involved process of generating a maze and requires some steps in order to work properly, however once your done, you can have more customization by adding a list of tiles that will be randomly selected per [Cell](../scripting_reference/cell.md) and [Modifiers](../scripting_reference/modifiers.md) that can help further with the variety and gameplay balance of the maze. To learn more about this Genaration Type check this next page on how to [Setup Your Own Prefabs](./prefabs.md).

By doing this you can now admire your very own procedurally generated maze and change it's layout with a few clicks of a button. You can leave it static and manually adjust it to your liking or toggle the Generate On Start checkbox to generate a new map layout each time the scene loads.

### Adding Modifiers
Modifiers are Components that can 