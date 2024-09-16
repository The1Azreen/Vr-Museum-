# VR Museum

A Virtual Reality Museum built with Unity for the HTC Vive, allowing users to explore exhibits in a fully immersive environment.

## Table of Contents

- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [HTC Vive Setup](#htc-vive-setup)
- [Controls](#controls)
- [Usage](#usage)
- [Customization](#customization)
- [Credits](#credits)

---

## Features

- **Interactive Exhibits**: Explore 3D models, art, and historical artifacts.
- **Teleportation System**: Smooth movement with teleportation to avoid motion sickness.
- **Hand Interaction**: Pick up, inspect, and interact with objects using HTC Vive controllers.
- **Audio Guide**: Listen to audio explanations of exhibits.
- **Customizable Layout**: Add and arrange exhibits using the Unity editor.

---

## Requirements

- **Hardware**: 
  - HTC Vive (or any SteamVR-compatible VR headset)
  - VR-ready PC
- **Software**:
  - Unity 2020.3 (or later) 
  - SteamVR plugin for Unity

---

## Installation

1. **Download the Unity Package**:
    - Download the `Azreen.unitypackage` file from the GitHub repository: [Azreen.unitypackage](https://github.com/your-repo/vr-museum/Azreen.unitypackage).

2. **Import the Package into Unity**:
    - Open Unity and create a new project or use an existing one.
    - Go to `Assets > Import Package > Custom Package` in the Unity menu.
    - Select the `Azreen.unitypackage` file you downloaded and click **Import**.
    - Ensure all the necessary assets are selected in the import dialog.

3. **Install Dependencies**:
    - Make sure the **SteamVR plugin** is installed via the Unity Asset Store or Unity Package Manager.

---

## HTC Vive Setup

1. **Install SteamVR**:
    - Download and install **Steam** and **SteamVR** from [here](https://store.steampowered.com/steamvr).
2. **Connect HTC Vive**:
    - Follow the HTC Vive setup guide to connect the headset and controllers to your PC.
3. **Enable VR in Unity**:
    - In Unity, go to `Edit > Project Settings > XR Plug-in Management`.
    - Check the box for **OpenVR** (if using SteamVR).

---

## Controls

| **Action**                | **Vive Controller Input**         |
|---------------------------|-----------------------------------|
| Teleport                   | Point with the **right hand** controller and press the **trackpad** |
| Pick up/Interact with objects | Press the **trigger** on either hand |
| Rotate object              | Hold the object and move the **trackpad** to rotate |
| Open Menu                  | Press the **menu button** on the left controller |

---

## Usage

1. **Start the Scene**:
   - In Unity, open the `MainMuseumScene` from the **Assets/Scenes** folder.
2. **Play Mode**:
   - Press the `Play` button in Unity to launch the VR experience.
   - Make sure your HTC Vive is connected and SteamVR is running.
3. **Explore the Museum**:
   - Use the Vive controllers to teleport between exhibits, pick up objects, and interact with the environment.

---

## Customization

1. **Add New Exhibits**:
    - Place your 3D models in the `Assets/Exhibits` folder.
    - Drag and drop new objects into the scene and assign interaction scripts as needed.
2. **Change Audio Guides**:
    - Audio files can be replaced or added to the `Assets/Audio` folder.
    - Attach the audio clips to the respective exhibit objects via the Unity editor.
3. **Modify Layout**:
    - Use the Unity editor to rearrange exhibits and change room layouts.

---

## Credits

- Project by **Your Name/Team**.
- Special thanks to the Unity and SteamVR community for tutorials and support.
