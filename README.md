<p align="center">
    <a href="https://github.com/LostLegacyTeam/LoS-Mod_Files_X/blob/master/">
        <img height="180px" src="https://github.com/LostLegacyTeam/LoS-Mod_Files_X/blob/master/logo.png" />
    </a>
</p>

<h1 align="center">Legacy of Solaris (Xbox 360)</h1>

This repository holds the Xbox 360 version of Legacy of Solaris. For more repositories, visit the ones listed below:
- [PlayStation 3 Version](https://github.com/LostLegacyTeam/LoS-Mod_Files_PS)
- [Additional Content](https://github.com/LostLegacyTeam/LoS-Additional_Content)
- [Miscellaneous](https://github.com/LostLegacyTeam/LoS-Miscellaneous)

# Usage
If you haven't already, extract your ISO for SONIC THE HEDGEHOG using [Sonic '06 Toolkit](https://github.com/HyperPolygon64/Sonic-06-Toolkit).
### Sonic '06 Mod Manager (recommended)
To install Legacy of Solaris onto your copy of SONIC THE HEDGEHOG, you will need [Sonic '06 Mod Manager](https://github.com/Knuxfan24/Sonic-06-Mod-Manager). Clone to repository to your drive (or just click Download ZIP) and put the Legacy of Solaris folder in your mods directory. Then tick the mod from Sonic '06 Mod Manager and click Save and Play (or Install Mods for FTP).
### Manual Installation
To install Legacy of Solaris onto your copy of SONIC THE HEDGEHOG, you simply just replace the files in the extracted ISO with the ones you downloaded from here. However, for ``object.arc``, you will need to use [Sonic '06 Toolkit](https://github.com/HyperPolygon64/Sonic-06-Toolkit)'s ARC Studio. This is a temporary solution until we have a tool to automate this process.

In ARC Studio, set the Source archive to the retail (unmodified) `object.arc` and the Merge archive to the modified `object.arc` you downloaded from here. Then set the Output to a memorable location and click Merge.

Your Output file will be the one used to play Legacy of Solaris. Create a backup of the archive you used as the Source file and replace it with the Output file.

# Xenia
### Vulkan
For Vulkan, we use [Xenia 1.05-MLBS](https://github.com/lost-legacy-team/LoS-Miscellaneous/tree/master/Emulators/Performance), a custom build of Xenia which generally performs better than the latest Vulkan builds. However, you may notice just by using this version that half the screen is black and the world is rendered very dark. Download the Vulkan Patches mod included in the Performance folder and put it in your mods directory and enable it in Sonic '06 Mod Manager.
### DirectX 12
For DirectX 12, no additional steps are required to run Sonic '06 optimally, but please note that this branch of Xenia doesn't quite work well with SONIC THE HEDGEHOG. So, you may notice texture memory corruptions and/or vertex explosions. This is why we generally stick to Vulkan.

# Contributors
### Main Developers
- Jotaro Powered - Lead Developer, Backstage Graphics Designer and Additional Content
- [HyperPolygon64](https://github.com/HyperPolygon64) - Lead Graphics Designer, Software Engineer, Trailer Editor, Lost Legacy Helper Developer and PlayStation 3 Optimisation
- Nonami - Graphics Designer, E3 HUD Creator and Tokyo Game Show Ring Shaders
- Sable - PlayStation 3 Compatibility and Loading Screen Designer
- darkhero1337 - Control Tweaking and Action Gauge Replenishment
- [Fate For Windows](https://github.com/FateForWindows) - Iblis Tweaks, Vehicle Health Meter Restoration and Action Gauge Restoration
- Xeno Esquire - Mach Speed Sonic Improvements

### Console Maintenance
- Sable - PlayStation 3 Compatibility
- [HyperPolygon64](https://github.com/HyperPolygon64) - PlayStation 3 Optimisation

### Designers
- [HyperPolygon64](https://github.com/HyperPolygon64) - Lead Graphics Designer
- Jotaro Powered - Backstage Graphics Designer
- Sable - Loading Screen Designer
- Nico_ - Logo Illustrator and New Sonic the Hedgehog Eye Textures
- Toru - E3 Loading Screen Assets and Kingdom Valley Cubemap
- Bacon - New Kingdom Valley Skyboxes
- Nonami - Graphics Designer, E3 HUD Creator and Tokyo Game Show Ring Shaders
- VolcanoTheBat - Graphics Designer and E3 HUD Creator
- [Knuxfan24](https://github.com/Knuxfan24) - Tropical Jungle Extra Layout

### Tool Developers
- [HyperPolygon64](https://github.com/HyperPolygon64) - [Sonic '06 Toolkit](https://github.com/HyperPolygon64/Sonic-06-Toolkit)
- [Knuxfan24](https://github.com/Knuxfan24) - [Sonic '06 Mod Manager](https://github.com/Knuxfan24/Sonic-06-Mod-Manager)
- [Shadow LAG](https://github.com/lllsondowlll) - Sonic '06 SDK
- g0ldenlink - ARC Unpacker
- xose - ARC Repacker
- [Skyth](https://github.com/blueskythlikesclouds) - Various Tools
