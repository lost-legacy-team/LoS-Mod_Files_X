# Legacy of Solaris (Xbox 360)
This repository holds the Xbox 360 version of Legacy of Solaris. For more repositories, visit the ones listed below:
- [PlayStation 3 Version](https://github.com/LostLegacyTeam/LoS-Mod_Files_PS)
- [Additional Content](https://github.com/LostLegacyTeam/LoS-Additional_Content)
- [Miscellaneous](https://github.com/LostLegacyTeam/LoS-Miscellaneous)

# Usage
If you haven't already, extract your ISO for SONIC THE HEDGEHOG using [XBOX 360 ISO EXTRACT](https://github.com/LostLegacyTeam/LoS-Miscellaneous/raw/master/Advanced%20Tools/Xbox%20360%20ISO%20Extractor/XBOX360%20ISO%20Extract.exe).

To install Legacy of Solaris onto your copy of SONIC THE HEDGEHOG, you will need to use [Sonic '06 Toolkit](https://github.com/HyperPolygon64/Sonic-06-Toolkit)'s ARC Studio. This is a temporary solution until we have a tool to automate this process.

In ARC Studio, set the Source archive to the retail (unmodified) ARC and the Merge archive to the modified ARC you downloaded from here. Then set the Output to a memorable location and click Merge.

Your Output file will be the one used to play Legacy of Solaris. Create a backup of the file you used as the Source file and replace it with the Output file.

# Xenia
You can play SONIC THE HEDGEHOG using Xenia emulator, but there are some additional steps required if you want to use the Vulkan API. First of all, you must have at least Windows 8 or above to use this emulator. If so, you may continue.

### Vulkan
For Vulkan, we use [Xenia 1.05-MLBS](https://github.com/LostLegacyTeam/LoS-Miscellaneous/raw/master/Emulators/Performance/Xenia%201.05-MLBS%20(2314f25f)%20[22nd%20June%202018].exe), a custom build of Xenia which generally performs better than the latest Vulkan builds. However, you may notice just by using this version that half the screen is black and the world is rendered very dark. This is where the modified [`cache.arc`](https://github.com/LostLegacyTeam/LoS-Miscellaneous/raw/master/Emulators/Performance/cache.arc) comes in; this doesn't require merging, so just backup the retail (unmodified) `cache.arc` and put this new one in it's place.

### DirectX 12
For DirectX 12, no additional steps are required to run Sonic '06 optimally, but please note that this branch of Xenia doesn't quite work well with SONIC THE HEDGEHOG. So, you may notice texture memory corruptions and/or vertex explosions. This is why we generally stick to Vulkan.
