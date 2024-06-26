![](https://staticdelivery.nexusmods.com/mods/3667/images/headers/2620_1702626696.jpg)

| [Description](#description) | [Keybinds](#default-keybinds) | [Installing](#installing) | [Contact Author](#contact-author) | [Other Info](#config-and-other-info) | [Config](#config) | [Source](#source) | [Screenshots](#screenshots) |
|---|---|---|---|---|---|---|---|

## Description
Adds a craftable and functional spyglass that doubles as a weapon. Use it to bash your enemies or to see their cowardly faces up close... but from a safe distance! The spyglass has 3 zoom levels that you can cycle through. Uses custom mesh, textures, and logic. Configurable and includes gamepad support.

The spyglass can be crafted and upgraded at a workbench.
<br>
Recipe is: 2x Obsidian, 2x Bronze, 1x Crystal.

Alternatively, you can spawn the item with the console command `spawn AdvizeSpyglass`.

## Default Keybinds

Keyboard and Mouse:
```
Right Mouse Click will increase zoom level by 1.
Left Shift + Right Mouse Click will decrease zoom level by 1.
An optional keybind may be set to fully zoom out.
```

Gamepad:
```
Left Trigger/L2 will increase zoom level by 1.
Left Bumper/L1 + Left Trigger/L2 will decrease zoom level by 1.
When not zoomed, holding left bumper/L1 before pressing left trigger/L2 will allow you to block with the spyglass.
```
All configurable keybinds support keyboard combinations (e.g. Left Ctrl + F8).

## Installing

### Manual Install

Extract the Advize_Spyglass.dll file into your BepinEx/plugins folder.
Directory structure should look like this:
```
BepInEx ->
    plugins ->
        Advize_Spyglass.dll
```
#### In multiplayer environments:
This mod uses a version handshake to ensure all other connected clients have the mod. Install the mod on the server (if dedicated) as well as on all connected clients.

## Contact Author
You can reach me on NexusMods to provide bug reports or feedback https://www.nexusmods.com/valheim/mods/2620

For further mod or mod dev support, I can be found at the following Discord server:

[![](https://i.imgur.com/HZMpQip.png)](https://discord.gg/89bBsvK5KC)

## Config and Other Info:
The mod is configurable. A config file will be generated after first loading the mod and can be found in ﻿﻿BepInEx/config/advize.Spyglass.cfg

The config can be edited out of game with a text editor, or modified in game using the Configuration Manager mod.

Note: In multiplayer environments, configuration settings will sync between connected clients using ServerSync. Install the mod on the server (if dedicated) to ensure its configuration file remains authoritative.

Localization Support: A file named Advize_Spyglass.json will be generated in the config\Spyglass directory after the game is first launched while [General]EnableLocalization is set to true. In it you will find the ability to change the item name and description text. I will be improving upon this later.

## Config
### Default Config File:
```
Please see Nexus mod page for the default configuration.
```
## Source
Github Repo: [Advize_ValheimMods](https://github.com/AdvizeGH/Advize_ValheimMods)

## Screenshots

Spyglass 3D Model

![](https://staticdelivery.nexusmods.com/mods/3667/images/2620/2620-1701939910-152087581.png)

Spyglass Item Tooltip & Recipe

![](https://staticdelivery.nexusmods.com/mods/3667/images/2620/2620-1702022583-1103677912.png)

Zoom Level Comparison With Vignette Postprocessing Effect

![](https://staticdelivery.nexusmods.com/mods/3667/images/2620/2620-1702626736-2080813564.png)

Zoom Level Comparison Without Vignette Postprocessing Effect

![](https://staticdelivery.nexusmods.com/mods/3667/images/2620/2620-1701939876-2048130099.png)

No Zoom

![](https://staticdelivery.nexusmods.com/mods/3667/images/2620/2620-1702628267-1640800431.png)

1st Zoom Level

![](https://staticdelivery.nexusmods.com/mods/3667/images/2620/2620-1702628267-1182166968.png)

2nd Zoom Level

![](https://staticdelivery.nexusmods.com/mods/3667/images/2620/2620-1702628272-2128657286.png)

3rd Zoom Level

![](https://staticdelivery.nexusmods.com/mods/3667/images/2620/2620-1702628272-978895214.png)

Config Options

![](https://staticdelivery.nexusmods.com/mods/3667/images/2620/2620-1702627168-1402528900.png)