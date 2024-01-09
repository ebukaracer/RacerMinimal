# RacerMinimal
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-blue.svg)](http://makeapullrequest.com) [![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://github.com/ebukaracer/ebukaracer/blob/ebukaracer-resources/LICENSE.md)

- Simple yet sleek WebGL template for unity.
	
	![WebGL template 1.png](https://github.com/ebukaracer/ebukaracer/blob/ebukaracer-resources/RacerMinimal-Images/WebGL%20template.png)


## Installation
- Download the .zip file for this template: [here](https://github.com/ebukaracer/RacerMinimal/releases/download/v1.0.0/RacerMinimal.zip)
- Extract the content using a zip program
- Drag and drop or copy the extracted content to your project's assets' directory: `Assets/RacerMinimal`

## Usage Guide

![Screenshot (455).png](https://github.com/ebukaracer/ebukaracer/blob/ebukaracer-resources/RacerMinimal-Images/Screenshot%20(455).png)

*If  imported successfully, you should see something similar as in the above image, by navigating to `file` -> `build setting` ->` player setting` -> `resolution and presentation`*

### To use this template with its default settings, select `RacerMinimal` from of the listed templates.

*Preview of it running in localhost:*

  ![Screenshot (452).png](https://github.com/ebukaracer/ebukaracer/blob/ebukaracer-resources/RacerMinimal-Images/Screenshot%20(452).png)

### To use this template with custom settings, you can specify a value for the fields:
- `Optimize for pixel art:` Handy if you're targeting pixel art style; value: `either true or false`
- `Hide footer:` Whether or not to hide the buttons below the container; value: `either true or false`
- `Border colour:` Changes the border colour of the container and footer(if not hidden). You can specify `transparent` as a value if you don't need the borders displayed at all; value: `hex-colours(#xyz, #abc, etc), hardcoded colours(red, blue, etc)`, `transparent`

## Side notes
*In case you're hosting your unity WebGL game on [itch.io](itch.io), usually unity defaults a resolution of `960 X 600`, this tends to clip off this template's contents caused by the size of the container which itch website uses to render WebGL games.*

*You can follow my ways to achieve a fitting dimension:*

- Inside unity, set the default Width and Height to `860 X 500`  as seen above.
- On itch website, while editing your game, set the Width and Height values to `960 X 600`:
- 
![Screenshot (457).png](https://github.com/ebukaracer/ebukaracer/blob/ebukaracer-resources/RacerMinimal-Images/Screenshot%20(457).png)  

## Credits
- See [Unity docs](https://docs.unity3d.com/Manual/webgl-templates.html) on how to customise WebGL Templates.
- Got inspired by [Better-Minimal](https://seansleblanc.itch.io/better-minimal-webgl-template) 

*Drop a ⭐ if found useful.*