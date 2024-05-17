# Save Your Maze to An Image

Now that you have created your mazes you might want a map of that maze. If your maze is generated at runtime and you want to use just a texture, you can just use the [ToTexture](./../scripting_reference/quad_maze_class.md#public-methods) method to get a Texture2D of the maze.

However, sometimes you might want to generate your maze on the project and use the map texture as a file image like a PNG or JPEG. For this you have the **Maze Printer** component. Simply attach the Maze Printer Script to the Maze Game Object and after the Maze is created press print script.

>Warning: Currently this feature is still a work in progress so you might encounter some bugs if you change scenes. Also currently the ToTexture method just prints the maze in black and white but you can change the colors in the script.