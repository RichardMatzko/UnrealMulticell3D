# UnrealMulticell3D

Software: UnrealMulticell3D (UM3D)

Author: Richard Matzko

License: CC-BY

WARNING: Please be aware that using this incomplete software is at your own risk. The cells will not stop proliferating by themselves, you must close the application or press the reset button in a timely fashion. This version was focused towards performance optimization.

If you can demonstrate improved performance for this work and set of functions please contact me and let me know how you achieved it.

Installation
------------
This software was developed in Windows 10/11. Projects may be cross compatible with other operating systems. This has not been confirmed.

This project utilized (UE4) Unreal Engine version 4.26.2 and should be opened using the UE4 editor.

On Windows, follow these steps:

1. Download UM3D_Vers_SimplestCell2.zip
1. Install Epic Games Launcher https://store.epicgames.com/en-US/download
2. Register and log in.
3. Go to Unreal Engine (UE) -> Library in Epic Games Launcher
4. Install UE version 4.26.2
5. Your documents folder should have a folder called "Unreal Projects". If not create it and extract the UM3D_Vers_SimplestCell folder from UM3D_Vers_SimplestCell2.zip into Documents/Unreal Projects.
6. Navigate back to your Unreal Engine Library in Epic Games Launcher.
7. Double click the project: UM3D_Vers_SimplestCell
8. When building the project for the first time, the editor appears to reinstate 600 megabytes worth of deleted starter content to the project.
9. The project may say that modules are missing and you will need to build the project the first time which should take only a few minutes.

About
-----
This is a simplified version of MultiCellRM for performance testing. It removes many features and demonstrates performance of cells in terms of proliferation (growth and cell division). The full version (unreleased) possesses a Cell Editor and more parameters.

Key functions present in this version:
-> Cell Spawn Transforms
-> Cell Growth
-> Cell Division
-> Color Oscllation

Note: Some variables might not be in use in this versions and might be artifacts.

For more information please see the GitHub page for publication links to be used for attribution.
https://github.com/RichardMatzko/UM3D_Vers_SimplestCell

Basic Controls:
--------------
Navigation: Mouse, Left Click and WASD keyboard
R: Toggles the camera on/off

On Screen Controls:
------------------
Reset: Resets and stops the Simulation
Start: Starts the Simulation
Count: Counts the current number of cells

Advanced details:
---------------
The physics constraint mode is set to a monolayer (xy plane), which can be adjusted in the "SimplestCell" blueprint.

Behaviours can be modified through blueprinting or even custom C++ functions, and parameter adjustment of existing functions.