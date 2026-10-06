# HampiVR

A Unity-based virtual exploration experience of the **Vittala Temple and Stone Chariot area of Hampi**, created to digitally explore and present the heritage environment.

## Tech Stack

- Unity 2022.3.62f3
- C#
- Unity Terrain
- XR Interaction Toolkit
- Blender
- Heightmap / Elevation Data
- 3D Heritage Models
- Terrain & Texture Assets

## Implementation

### 1. Terrain & Heightmap

The terrain was created using elevation data for the Hampi region.

- Generated a grayscale heightmap using **Tangram Heightmapper**.
- Used the heightmap to represent the elevation and natural contours of the site.
- Exported the heightmap and used it as the basis for the Unity terrain.
- Adjusted the terrain scale and elevation to fit the heritage environment.

![Hampi Heightmap](screenshots/heightmap.png)

### 2. Terrain Preparation

The heightmap-based terrain was prepared and adjusted before importing it into the Unity environment.

- Processed and adjusted the terrain in **Blender**.
- Checked the terrain shape and elevation.
- Prepared the surface for texturing and environment placement.

![Terrain Preparation](screenshots/terrain-blender.png)

### 3. Terrain Texturing

Terrain textures were applied to create a more natural ground environment.

- Applied soil/ground textures.
- Adjusted the terrain surface to support the placement of heritage structures and environmental assets.

![Textured Terrain](screenshots/textured-terrain.png)

### 4. Heritage Environment

The main heritage environment was assembled around the **Vittala Temple and Stone Chariot** area.

- Added the Stone Chariot model.
- Added temple structures and entrance elements.
- Created the courtyard area.
- Added rocks and trees around the terrain.
- Added a boundary around the main temple area.

![Hampi Heritage Environment](screenshots/hampi-environment.png)

![Hampi Scene Overview](screenshots/hampi-overview.png)

### 5. Unity Scene Setup

The final environment was organized in Unity with separate objects for the terrain, heritage structures and environmental elements.

Main scene components include:

- Hampi Terrain
- Courtyard
- Stone Chariot
- Temple structures
- Temple Boundary
- Rocks
- Trees
- Main entrance elements
- Lighting and environment

![Unity Scene Hierarchy](screenshots/unity-hierarchy.png)

### 6. Exploration Setup

The scene includes a player exploration setup using Unity's XR components.

- Configured XR Origin.
- Added camera and player components.
- Set up the scene for interactive exploration and navigation.

## Project Structure

```text
HampiVR/
├── Assets/
│   ├── Hampi/
│   ├── Hampi Stone/
│   ├── Hampi Stone 1/
│   ├── Material/
│   ├── Scenes/
│   ├── scenes 1/
│   ├── scenes 2/
│   └── XRI/
├── Packages/
├── ProjectSettings/
├── .gitignore
└── README.md
