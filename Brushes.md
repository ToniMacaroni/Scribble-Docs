---
title: Brushes
layout: default
has_children: false
nav_order: 0
---
## Creating brushes
Brushes are stored in the 'UserData/Scribble/CustomBrushes.ini' file.⋅⋅
A valid brush looks like this:
```
[Primary]
Color = #e63535
TextureName = standard
Size = 30
Glow = 0.5
```

The section name marks your brush name.

Properties:
- Color: The color of a brush as a hexadecimal string
- Texture: 'standard' is like no texture. Following values are possible
	* standard
	* pogchamp
	* brush
	* .png brushes that are in the Texture directory of Scribble ('UserData/Scribble/Textures'). The name of the texture is the filename without the extension (brush.png => brush)
- Effect: The name of the effect.. Following values are possible
	* standard
	* animated (trail is moving in one direction)
	* dotbpm (a dot that moves with the bpm of the song you are currently playing)
- Size: The size of the brush
- Glow: How much does the drawn line glow. This value is between 0 and 1
- TextureMode: 'Stretch' or 'Tile' the texture
- Tiling: How many times the texture repeats

## Textures
You can use custom textures by putting .png files into the 'UserData/Scribble/Textures' directory.
You can then select them In-Game on any brush you want