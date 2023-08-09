# Getting Started
[Finix's Maze Generator](../README.md) is fully self contained and does not depend on any external assets. If you do not need the sample scenes, standard prefabs or the triplanar shader, feel free to exclude the art and resources folder when importing the package.

Keep in mind that for a walls and pillars instatiation the walls will be stretched to fit the maze size, as such the UVs will also be stretched, it is reccomended to use the included standard triplanar shader for the walls or other similar implementation.

## Installation
* Open the Unity Editor on version 2020.3.20 or above.
* On the tool bar go to Window ▶︎ PackageManager. 
* On the top left of the Package Manager window select the "Packages: In Project" dropdown menu and switch to "My Assets".
* Select the Finix's Maze Generator Package.
* On the bottom right click on the Download button.
* When the package finishes downloading on the bottom right of the Package Manager window click Import.

## Using the package
### Adding a Maze into a scene
* Now that you've installed this package, on the Assets folder you can go to Finix's Maze Generator ▶︎ Scenes ▶︎ Sample Scene and mess around with the maze already pre-built in the scene.
* To add a maze in another scene go to the tool bar on top of the Editor and selecting Tools ▶︎ Maze Generator ▶︎ Quad Maze.
* Alternitavely you can go to the Hierarchy window and create a new Empty Object and on the inspector window of that object add a new Quad Maze Component, by using this method you need to manually assign what prefabs you want for the different maze parts and instatiation methods. When all of that is set-up click the Generate Maze button.

### Customizing your Maze
Upon inspecting the Quad Maze component on the Inspector window you might notice a bunch of parameters to tweak and change. These include: