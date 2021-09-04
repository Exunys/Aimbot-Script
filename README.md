# Aimbot Script

### About

This script works on all games (unless the character is not in workspace)
Feel free to edit any of the global settings inside the script.
Editable settings :
- Aimbot Enabled / Disabled
- Aim Body Part
- Sensitivity / Aim Speed

This script also has FOV customization, circle color, circle filled, circle thickness, circle radius (fov or size), circle position and how many sides does the circle have (set to 64 for a circle, anything below 3 won't work)

### Settings (For the script with the FOV Circle)

```lua
--// Aimbot

_G.AimbotEnabled = true -- Determines whether or not the Aimbot script will lock onto players.
_G.TeamCheck = false -- If set to true then the script would only lock your aim at enemy team members.
_G.AimPart = "Head" -- What body part of the closest enemy the aimbot script would lock at.
_G.Sensitivity = 0 -- How many seconds it takes for the aimbot script to officially lock onto the target's aimpart.

--// FOV Circle

_G.CircleSides = 64 -- How many sides the FOV circle would have.
_G.CircleColor = Color3.fromRGB(255, 255, 255) -- (RGB) Color that the FOV circle would appear as.
_G.CircleTransparency = 0.7 -- Transparency of the circle.
_G.CircleRadius = 80 -- The radius of the circle / FOV.
_G.CircleFilled = false -- Determines whether or not the circle area will be filled.
_G.CircleVisible = true -- Determines whether or not the circle will be visible.
_G.CircleThickness = 0 -- The thickness of the circle.
```

## Script (With FOV Circle)

Load the script by using the code below or by copying it from [here](https://github.com/Exunys/Aimbot-Script/blob/main/Aimbot%20Script.lua).
```lua
loadstring(game:HttpGet("https://pastebin.com/raw/ygp8Enye"))()
```

## Script (Without FOV Circle)

Load the script by using the code below or by copying it from [here](https://github.com/Exunys/Aimbot-Script/blob/main/Aimbot%20Script%20(Without%20FOV).lua).
```lua
loadstring(game:HttpGet("https://pastebin.com/raw/CwQcEnEd"))()
```

## Contact information

- Discord : [Exunys](https://discord.com/users/611111398818316309)
- ROBLOX : [Exunys](https://www.roblox.com/users/330279990/profile)
