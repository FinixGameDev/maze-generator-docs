# Package Contents
### Folder Structure

    └── FinixMazeGenerator/
        ├── Art/
        │   ├── Materials/
        │   │   ├── DefaultMaze.mat
        │   │   ├── Entrance.mat
        │   │   ├── Exit.mat
        │   │   └── Unique.mat
        │   ├── Textures/
        │   │   ├── Grid_01_BaseMap.png
        │   │   ├── Grid_01_Emissive.png
        │   │   ├── Grid_01_Normal.png
        │   │   └── Grid_02_BaseMap.png
        │   ├── quad_maze_parts.fbx
        │   └── StandardTriplanar.shader
        ├── Icons/
        │   └── Maze_Icon.png
        ├── Resources/
        │   └── Prefabs/
        │       ├── Corner.prefab
        │       ├── Corridor.prefab
        │       ├── Crossroads.prefab
        │       ├── Deadend.prefab
        │       ├── Entrance.prefab
        │       ├── Exit.prefab
        │       ├── Intersection.prefab
        │       ├── Pillar.prefab
        │       └── Wall.prefab
        ├── Scenes/
        │   └── SampleScene.unity
        ├── Scripts/
        │   ├── Core/
        │   │   ├── Cells/
        │   │   │   ├── Cell.cs
        │   │   │   └── QuadCell.cs
        │   │   ├── Grids/
        │   │   │   ├── Grid.cs
        │   │   │   └── QuadGrid.cs
        │   │   ├── Algorithms.cs
        │   │   └── Distances.cs
        │   ├── Editor/
        │   │   ├── MazeEditor.cs
        │   │   └── StandardTriplanarInspector.cs
        │   ├── EntranceExitModifier.cs
        │   ├── IMazePrefabModifier.cs
        │   ├── QuadMaze.cs
        │   └── UniqueTileModifier.cs
        ├── FinixMazeGenerator.asmdef
        ├── ThirdPartyNotcice.md
        ├── README.md
        └── Documentation.pdf