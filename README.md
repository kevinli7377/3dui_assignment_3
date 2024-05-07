# Go Fish!

Name: Kevin Li 

UNI: kl3285

Date of Submission: March 29, 2024

Computer platform: macOS (Sonoma 14.1.1), Macbook Pro 14-in. (2021), Apple M1 Max, 32 GB RAM

Unity version: 2022.3.18f1

Mobile platform: Samsung One UI 6.0, Android 14, Samsung Galaxy S23 Ultra

## Project Overview and Folder Structure

Project titles: "HW3" and "HW3 Part2"
    There are two project folders as part of this submission: HW3, HW3 Part 2.
    The former contains the files and project build for Part 1. The latter contains files for Part 2. 

Project directory overview: This directory contains two directories.

"HW3": Contains all files for Part 1.
- "Assets/Scene/MainScene" contains the scene for the project.
- "Assets/Prefabs" contains all prefabs used in the project.
- "Assets/Scripts" contains all created scripts for the project.
-  "Assets/Sprites" contains all sprites used in the project.
-  "Assets/Materials" contains all materials used in the project.

"HW3 Part2": Contains all files for Part 2.
- "Assets/Scene/MainScene" contains the scene for project Part 2.
- "Assets/Resources" contains "HW3_scene.csv" which is the scene used in the video submission.
- "Assets/Resources/Prefabs" contains all prefabs used in the project, especially during load scene. 
NOTE: The models (meshes) are the same as Part 1 but differ in their scripts and attached components.
- "Assets/Resources" contains the .csv files used during scene loading called by the LoadScene script.
- "Assets/Materials" contains all materials used in the project.
        

## Special Instructions: 
Since two separate projects were created for Part 1 and Part 2, please open and 
    build using "HW3" for Part 1 and "HW3 Part2" for Part 2 on a mobile device and Oculus Quest 2 respectively.

## Demo Video
Unlisted Video URL: https://youtu.be/EH53pfIGL5Y

Missing features: None. All required features were implemented. 

## Identified Bugs
Explanation of bugs: 
Part 1: 

- AR Plane from AR Foundation was used to create the mobile application for Part 1. The plane manager is greatly affected by the environment and can often generate multiple overlapping planes that affect the placement of AR objects. This can be mititgated by using the application in a well-lit environment with clean simple flooring. 

Part 2: 
- None.
    
## References

Asset attributions:
- Meta XR All-in-One SDK: https://assetstore.unity.com/packages/tools/integration/meta-xr-all-in-one-sdk-269657
- Low Poly Pack - Environment Lite: https://assetstore.unity.com/packages/3d/props/exterior/low-poly-pack-environment-lite-102039
- Cola Can: https://assetstore.unity.com/packages/3d/cola-can-96659
- Stylized Low Poly Rocks: https://assetstore.unity.com/packages/3d/environments/landscapes/stylized-low-poly-rocks-271334
- Boats - PolyPack: https://assetstore.unity.com/packages/3d/vehicles/sea/boats-polypack-189866
- Fish - PolyPack: https://assetstore.unity.com/packages/3d/characters/animals/fish/fish-polypack-202232

