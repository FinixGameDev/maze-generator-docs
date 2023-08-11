# Setting Up Your Own Prefabs

So, you want to add your own prefabs to the maze? Here's a step-by-step guide:

## Table of Contents
- [Setting Up Your Own Prefabs](#setting-up-your-own-prefabs)
  - [Table of Contents](#table-of-contents)


* ## Step 1: Get modular maze parts
  
  In order to generate a prefab maze, first you need to have to have at least one pre-built prefab for each scenario. 
  
  So either pick up your chosen 3D modelling software or buy a modular maze pack from the asset store. In this example I'll be using PolySquid's [Sewer Maze](https://assetstore.unity.com/packages/3d/environments/sewer-maze-77049) pack to make a prefab Quad Maze.

  By scenario, we're talking about how many paths a [Cell](../scripting_reference/cell.md) can have to its neighbouring cells and each unique pattern it creates. In the case of a Quad Maze there are 5 unique scenarios possible:


* ## Step 2: Converting the Meshes to prefab
    ### Important Note:
    