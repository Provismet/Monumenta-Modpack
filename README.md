# Provi's Monumenta Modpack

Another unofficial modpack for the CTM-MMO Minecraft server, [Monumenta](www.playmonumenta.com).

## License
This **modpack** (custom menu layouts, configuration files, etc) is licensed as MIT, feel free to disect and reuse parts of it.  
The contents of this modpack (mods, resourcepacks, music, logos, etc) are not covered by the modpack's license and instead have separate licenses to respect.

## Contents
- Performance improvement mods.
- Monumenta Official Resource Pack v4.3.0 (check the official discord for the latest release).
- Monumenta General Music Pack v2.0.0 (check the official discord for the latest release).
  - Contains open world, dungeon, boss, and town music.
- Monumenta Custom Music Pack v1.2.0 (check the official discord for the latest release).
  - Allows you to set custom music to play in Monumenta.
- General gameplay enhancement mods.
  - Tooltip Scroll
  - Shulkerbox Tooltips
  - Xaero's Minimap/Worldmap (Fair-Play)
- Monumenta specific gameplay enhancement mods.
  - Unofficial Monumenta Mod
  - Monumenta Item List
  - Dynamic Fullbright (yes this was actually made specifically for Monumenta)

## Installation
### Vanilla Launcher
- [Modrinth Modpack Installer](https://github.com/Provismet/Modrinth-Modpack-Installer) (zero setup required)
  - I made this one, so just tell me if it breaks somehow.
  - It will set up a folder with all the mods and configs from the `.mrpack` file, then you can just tell Minecraft to launch an installation from that folder.
- There are also several command line tools you can try that have the ability to set up the modpack for you.
- Manual Installation (lots of setup required)
  1. The `.mrpack` file is just a zip folder with a fancy extension. Rename the file to change the filetype to `.zip`.
  2. Unzip the folder.
    - If you have 7zip, you can use that to open the `.mrpack` directly and skip step 1.
  3. The "overrides" folder contains configs, resourcepacks, etc in the exact format they need to be for a standard Minecraft profile.
    - Either use this folder as the profile/installation folder or copy its contents into your chosen folder.
  4. `modrinth.index.json` is a json file containing URLs to every mod to download.
    - These URLs are direct download links, so just click all of them and let your web browser do the rest.
  5. Move all the downloaded mods into your mods folder.
  6. Create a Minecraft profile pointing at the location of the folder you set up (the same folder you dumped the contents of override into).
  7. Play, let Minecraft and the mods generate all remaining files.

### 3rd Party Launchers
The instructions will be different per 3rd party launcher, but any launcher that supports Modrinth modpacks should be able to set everything up:
- Prism Launcher
- ATLauncher
- MultiMC

## Complete Mod List
- [**AppleSkin**](https://modrinth.com/mod/appleskin) - Food/hunger-related HUD improvements
- [**AttributeFix**](https://modrinth.com/mod/attributefix) - Removes arbitrary limits on Minecraft's attribute system. Fixes MANY mods!
- [**Audio Extension for FancyMenu**](https://modrinth.com/mod/audio-extension-for-fancymenu) - Add audio elements to FancyMenu layouts.
- [**Auudio**](https://modrinth.com/mod/auudio) - Library mod to easily play background sound in menus and worlds.
- [**Better Advancements**](https://modrinth.com/mod/better-advancements) - Better Advancements tries to improve the UI and UX for the advancements system in minecraft 1.12+ in a modded environment
- [**Borderless Mining**](https://modrinth.com/mod/borderless-mining) - Changes Fullscreen to use a borderless window.
- [**CIT Resewn (fork from NickNackGus)**](https://github.com/SHsuperCM/CITResewn/pull/262) - Re-implements MCPatcher's CIT (custom item textures from optifine resource packs)
- [**Cloth Config API**](https://modrinth.com/mod/cloth-config) - Configuration Library for Minecraft Mods
- [**Continuity**](https://modrinth.com/mod/continuity) - A Fabric mod that allows for efficient connected textures
- [**Custom Entity Models**](https://modrinth.com/mod/cem) - Custom Entity Models suport on Fabric
- [**Dynamic Fullbright**](https://modrinth.com/mod/dynamic-fullbright) - A simple alternative to standard fullbright/gamma mods, offering the ability to scale or clamp light levels to a desired range.
- [**Enhanced Block Entities**](https://modrinth.com/mod/ebe) - Reduce FPS lag with block entities, as well as customize them with resource packs
- [**Exordium**](https://modrinth.com/mod/exordium) - Render the GUI and screens at a lower framerate to speed up what's really important: the worldrendering.
- [**Fabric API**](https://modrinth.com/mod/fabric-api) - Lightweight and modular API providing common hooks and intercompatibility measures utilized by mods using the Fabric toolchain.
- [**Fabric Language Kotlin**](https://modrinth.com/mod/fabric-language-kotlin) - Fabric Language Kotlin
- [**FabricSkyBoxes Interop**](https://modrinth.com/mod/fabricskyboxes-interop) - FabricSkyBoxes Interoperability for MCPatcher/OptiFine Skies
- [**FabricSkyboxes**](https://modrinth.com/mod/fabricskyboxes) - Allows resource packs to define custom skyboxes.
- [**FancyMenu**](https://modrinth.com/mod/fancymenu) - Minecraft menus, but much more fancy! Customize menu screens with animations, buttons, texts, images and more!
- [**Fastload**](https://modrinth.com/mod/fastload) - Modifies how worlds are loaded to speed up loading times.
- [**FerriteCore**](https://modrinth.com/mod/ferrite-core) - Memory usage optimizations
- [**ImmediatelyFast**](https://modrinth.com/mod/immediatelyfast) - Speed up immediate mode rendering in Minecraft
- [**Indium**](https://modrinth.com/mod/indium) - Sodium addon providing support for the Fabric Rendering API, based on Indigo
- [**Iris Shaders**](https://modrinth.com/mod/iris) - A modern shaders mod for Minecraft intended to be compatible with existing OptiFine shader packs
- [**Konkrete**](https://modrinth.com/mod/konkrete) - Just another boring library mod.
- [**LambDynamicLights**](https://modrinth.com/mod/lambdynamiclights) - A dynamic lights mod for Fabric.
- [**Lithium**](https://modrinth.com/mod/lithium) - No-compromises game logic/server optimization mod
- [**Load My Resources**](https://modrinth.com/mod/load-my-resources) - Load resources on game start, like a resource pack, but enabled by default.
- [**Logical Zoom**](https://modrinth.com/mod/logical-zoom) - A simple zoom key for Minecraft
- [**Memory Leak Fix**](https://modrinth.com/mod/memoryleakfix) - A mod that fixes random memory leaks for both the client and server
- [**Mod Menu**](https://modrinth.com/mod/modmenu) - Adds a mod menu to view the list of mods you have installed.
- [**Model Gap Fix**](https://modrinth.com/mod/modelfix) - Fixes gaps in Block Models and Item Models
- [**ModernFix**](https://modrinth.com/mod/modernfix) - All-in-one mod that improves performance, reduces memory usage, and fixes many bugs. Compatible with all your favorite performance mods!
- [**Monumenta Item Dictionary**](https://modrinth.com/mod/monumenta-item-dictionary) - A QOL mod for Monumenta, adding an in-game item dictionary. (1.18.2)
- [**More Culling**](https://modrinth.com/mod/moreculling) - A mod that changes how multiple types of culling are handled in order to improve performance
- [**No Chat Reports**](https://modrinth.com/mod/no-chat-reports) - Makes chat unreportable (where possible)
- [**Phosphor**](https://modrinth.com/mod/phosphor) - No-compromises lighting engine optimization mod
- [**Shulker Box Tooltip**](https://modrinth.com/mod/shulkerboxtooltip) - View the contents of shulker boxes from your inventory
- [**Smooth Boot (Fabric)**](https://modrinth.com/mod/smoothboot-fabric) - Improve Minecraft CPU scheduling
- [**Sodium**](https://modrinth.com/mod/sodium) - A modern rendering engine for Minecraft which greatly improves frame rates and micro-stutter, while fixing graphical issues
- [**Tooltip Scroll**](https://modrinth.com/mod/tooltip-scroll) - The premier Fabric mod that allows you to move/scroll tooltips.
- [**ToroHealth Damage Indicators (retrixe's 1.19.4 fork)**](https://github.com/ToroCraft/ToroHealth/pull/171) - With ToroHealth Damage Indicators a health bar will appear in the top left corner for the entity in the player's crosshairs.
- [**Unofficial Monumenta Mod**](https://modrinth.com/mod/unofficial-monumenta-mod) - An unofficial client-side mod for the Monumenta MMO server (www.playmonumenta.com).
- [**Very Many Players (Fabric)**](https://modrinth.com/mod/vmp-fabric) - A Fabric mod designed to improve server performance at high playercounts.
- [**Xaero's Minimap (Fair-Play)**](https://modrinth.com/mod/xaeros-minimap-fair) - Fair-play edition of the Xaero's Minimap mod, designed for fair PVP against players without a minimap.
- [**Xaero's World Map**](https://modrinth.com/mod/xaeros-world-map) - Adds a full screen world map which shows you what you have explored in the world. Works great together with Xaero's Minimap.
- [**[ETF] Entity Texture Features**](https://modrinth.com/mod/entitytexturefeatures) - Emissive, Random & Custom texture support for entities in resourcepacks just like Optifine but for Fabric
- [**Mouse Tweaks**](https://modrinth.com/mod/mouse-tweaks) - Enhances inventory management by adding various functions to the mouse buttons. 
- [**Krypton**](https://modrinth.com/mod/krypton) - A mod to optimize the Minecraft networking stack