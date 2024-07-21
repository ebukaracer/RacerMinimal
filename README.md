# RacerMinimal
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-blue.svg)](http://makeapullrequest.com) [![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://github.com/ebukaracer/ebukaracer/blob/ebukaracer-resources/LICENSE.md)

- Simple yet sleek WebGL template for unity.
	
	![WebGL template 1.png](https://github.com/ebukaracer/ebukaracer/blob/ebukaracer-resources/RacerMinimal-Images/WebGL%20template.png)


## Installation
- Download the latest .zip file for this template: [here](https://github.com/ebukaracer/RacerMinimal/releases)
- Extract the content using any zip program of choice
- Drag and drop or copy the extracted folder `RacerMinimal` to your unity project's Assets folder: `Assets/RacerMinimal`

You can simply clone this repo, copy and paste `RacerMinimal` folder to your unity project's Assets folder: `Assets/RacerMinimal`

## Usage Guide

![Screenshot (455).png](https://github.com/ebukaracer/ebukaracer/blob/ebukaracer-resources/RacerMinimal-Images/Screenshot%20(455).png)

If  imported successfully, you should see something similar as in the above image, by navigating to `file -> build setting -> player setting -> resolution and presentation`

### To use this template with its default settings, select `RacerMinimal` from of the listed templates.

*Preview of it running on localhost:*

  ![Screenshot (558).png](https://github.com/ebukaracer/ebukaracer/blob/ebukaracer-resources/RacerMinimal-Images/Screenshot%20(558).png)

### To use this template with custom settings, you can specify a value for the fields:
- `Optimize for pixel art:` Handy if you're targeting pixel art style- set: `either true or false`
- `Hide footer:` Whether or not to hide the buttons below the container- set: `either true or false`
- `Border colour:` Changes the border colour of the container and footer(if not hidden). You can specify `transparent` as a value if you don't need the borders displayed at all otherwise- set: `hex-colours such as:(#xyz, #abc, etc), hardcoded colours such as:(red, blue, etc)`,  or `transparent`

---

## Notes
> To change background colour navigate to: `Player Settings -> Splash Image -> Background -> Background Color`. Any colour you set there would be applied to this tool, you can observe it during the initial load of your game.  
   ![Screenshot (458).png](https://github.com/ebukaracer/ebukaracer/blob/ebukaracer-resources/RacerMinimal-Images/Screenshot%20(458).png)

> In case you're hosting your unity WebGL game on [itch.io](itch.io), usually unity defaults a resolution of `960 X 600`, this tends to clip off this template's contents caused by the size of the container which itch website uses to render WebGL games:

*Here's my hacky way of achieving a fitting dimension:*

- Inside unity, set the default Width and Height to `860 X 500`  as seen [above](https://github.com/ebukaracer/RacerMinimal?tab=readme-ov-file#usage-guide).
- On itch website, while editing your game, set the Width and Height values to `960 X 600`:
- 
![Screenshot (457).png](https://github.com/ebukaracer/ebukaracer/blob/ebukaracer-resources/RacerMinimal-Images/Screenshot%20(457).png)  

## Credits
- See [Unity docs](https://docs.unity3d.com/Manual/webgl-templates.html) on how to customise WebGL Templates.
- Got inspired by [Better-Minimal](https://seansleblanc.itch.io/better-minimal-webgl-template) 

*Drop a ⭐ if found useful.*