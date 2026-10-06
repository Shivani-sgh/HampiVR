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

<img width="400" height="400" alt="Screenshot 2026-08-25 204930" src="https://github.com/user-attachments/assets/500ba877-4aec-421b-a611-2b61e39636da" />


### 2. Terrain Preparation

The heightmap-based terrain was prepared and adjusted before importing it into the Unity environment.

- Processed and adjusted the terrain in **Blender**.
- Checked the terrain shape and elevation.
- Prepared the surface for texturing and environment placement.


<img width="400" height="400" alt="Screenshot 2026-08-26 174022" src="https://github.com/user-attachments/assets/9585fa5b-34c9-47a9-b834-92f0a90daa75" />
<img width="400" height="400" alt="Screenshot 2026-08-26 143833" src="https://github.com/user-attachments/assets/40daa4ea-500b-46f7-9e25-48fa2051bfdf" />


### 3. Terrain Texturing

Terrain textures were applied to create a more natural ground environment.

- Applied soil/ground textures.
- Adjusted the terrain surface to support the placement of heritage structures and environmental assets.

<img width="400" height="400" alt="Screenshot 2026-08-31 225712" src="https://github.com/user-attachments/assets/9446e967-370e-4b92-a1b2-d05d55d19e82" />


### 4. Heritage Environment

The main heritage environment was assembled around the **Vittala Temple and Stone Chariot** area.

- Added the Stone Chariot model.
- Added temple structures and entrance elements.
- Created the courtyard area.
- Added rocks and trees around the terrain.
- Added a boundary around the main temple area.
  

<img width="400" height="400" alt="Screenshot 2026-10-06 161450" src="https://github.com/user-attachments/assets/5172592f-0645-4d4d-a704-39217d233c49" />
<img width="400" height="400" alt="Screenshot 2026-10-06 161554" src="https://github.com/user-attachments/assets/8df98835-db61-4140-82a2-ab5569cfc06d" />


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

<img width="353" height="491" alt="Screenshot 2026-10-06 162155" src="https://github.com/user-attachments/assets/5b5cc8aa-0d43-43e3-8799-cdc127683c0a" />


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
