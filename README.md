# RacerMinimal
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-blue)](http://makeapullrequest.com) [![License: MIT](https://img.shields.io/badge/License-MIT-blue)](https://github.com/ebukaracer/ebukaracer/blob/ebukaracer-resources/LICENSE.md)

 Simple yet sleek WebGL template for unity.

- [Download RacerMinimal.zip latest](https://github.com/ebukaracer/RacerMinimal/releases/download/v2.1.0/RacerMinimal.zip)

	<p align="left">
		<img src="https://github.com/ebukaracer/ebukaracer/blob/ebukaracer-resources/RacerMinimal-Images/RM1.png" alt="img" width="400"/>
		<img src="https://github.com/ebukaracer/ebukaracer/blob/ebukaracer-resources/RacerMinimal-Images/RM2.gif" alt="gif" width="400"/>
	</p>

## Installation
- Download the latest `.zip` file for this template from the link above
- Extract the contents using any zip program of your choice
- Drag and drop or copy the extracted folder `RacerMinimal` to your unity project's Assets folder: `Assets/RacerMinimal`

*..or  simply clone this repo, copy and paste `RacerMinimal` folder to your unity project's Assets folder: `Assets/RacerMinimal`*

## Usage Guide

![img](https://github.com/ebukaracer/ebukaracer/blob/ebukaracer-resources/RacerMinimal-Images/RM3.png)

If  imported successfully, you should see something similar as in the above image, by navigating to `file > build setting > player setting > resolution and presentation`

### To use this template with its default settings, select `RacerMinimal` from of the listed templates.

*Preview:*

  ![img](https://github.com/ebukaracer/ebukaracer/blob/ebukaracer-resources/RacerMinimal-Images/RM4.png)

### To use this template with custom settings, you can specify a value for the fields:
- `Optimize for pixel art:` Handy if you're targeting pixel art style- set: `either true or false`
- `Hide footer:` Whether or not to hide the buttons below the container- set: `either true or false`
- `Border colour:` Changes the border colour of the container and footer(if not hidden). You can specify `transparent` as a value if you don't need the borders displayed at all otherwise- set: hex-colours such as: `(#xyz, #abc, etc)`, hardcoded colours such as: `(red, blue, etc)`,  or `transparent`

---

## Note for users
> To change background colour navigate to: `Player Settings > Splash Image > Background > Background Color`. Any colour you set there would be applied to this tool, you can observe it during the initial load of your game: 
   ![img](https://github.com/ebukaracer/ebukaracer/blob/ebukaracer-resources/RacerMinimal-Images/RM5.png)

> In case you're hosting your unity WebGL game on [itch.io](itch.io), usually unity defaults a resolution of `960 X 600`, this tends to clip off this template's contents caused by the size of the container which itch website uses to render WebGL games..

*Here's my hacky way of achieving a fitting dimension:*

- Inside unity, set the default Width and Height to `860 X 500`  as seen [above](https://github.com/ebukaracer/RacerMinimal?tab=readme-ov-file#usage-guide).
- On itch website, while editing your game, set the Width and Height values to `960 X 600`:
- 
![img](https://github.com/ebukaracer/ebukaracer/blob/ebukaracer-resources/RacerMinimal-Images/RM6.png)  

## Credits
- See [Unity docs](https://docs.unity3d.com/Manual/webgl-templates.html) on how to customize WebGL Templates.
- Inspired by [BetterMinimal](https://seansleblanc.itch.io/better-minimal-webgl-template) 