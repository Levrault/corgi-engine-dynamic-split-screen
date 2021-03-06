# Dynamic split screen script for two players coop games
## Setup
To use this extension, you will need an unity project with the corgi engine installed.  If you don't have the corgi engine, you can get it from [unity asset store](https://assetstore.unity.com/packages/templates/systems/corgi-engine-2d-2-5d-platformer-26617). 

## Demo

You can import this project and test the script by yourself. Just be sure to add the corgi engine in the project.

![demo.gif](demo.gif)

## How to use 

Feel free to use the prefabs of the demo. But If you don't want to, here how to set your unity scene project to work with the extension

1. Copy *SplitScreen.cs* and *SplitScreenManager.cs* into your Assets/Scripts folder.
2. Add two new cameras with the current main camera. 
3. Edit the Viewport Rect of the camera component to make the camera half the size of the screen. *e.g. w:0.5 h:1*
4. Edit the X value to 0.5 from the right camera
5. Add *SplitScreen.cs* to the left/right camera 
6. Edit the Z's Camera Offset settings to -10.
7. Create an empty object at the root of the hierarchy and name it **SplitScreenManager** (or whatever you want) 
8. Add *SplitScreenManager.cs* to the **SplitScreenManager** object
9. Params **SplitScreenManager** variables by following the editor instructions
10. Voilà

## Credits

Corgi Engine is a product of [reunono](https://github.com/reunono) (more mountains)