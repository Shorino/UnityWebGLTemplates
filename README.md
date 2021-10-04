# UnityWebGLTemplates

## Description
This is a modified version of unity default minimal webgl template, 
it was made in Unity 2020.3.11f. I copy the default minimal template 
from here: C:/Program Files/Unity/Hub/Editor/2020.3.11f1/Editor/Data/PlaybackEngines/WebGLSupport/BuildTools/WebGLTemplates/

## Sauce
Unity Docs: https://docs.unity3d.com/Manual/webgl-templates.html

## Features
1. Removed unity default template's border, everything fit nicely inside browser's viewport
2. Allow fixed aspect ratio based on canvas resolution and auto scale canvas to fit inside browser's viewport

## Usage
1. Copy WebGLTemplates folder and paste it into Assets folder
2. Under Build Settings -> Player Settings -> Resolution and Presentation, select "ModifiedMinimal" in order to use this template
3. To enable fixed aspect ratio based on canvas resolution, input 1 inside "Fixed Aspect Ratio" parameter