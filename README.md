## dxvk-async for guild wars
A Fork of https://github.com/Sporif/dxvk-async for use with Guild wars 1

This fork contains Specific patches and configurations specific to Guild wars 1


##DXVK for Guild wars
DXVK for guild wars is a Translation wrapper for translating DirectX 9 to Vulkan, using a fork [https://github.com/Sporif/dxvk-async] of a fork [https://github.com/doitsujin/dxvk] with performance optimisations such as Asynchronous compute and Fast path algorithm.
This Boosts performance or lowers power consumption, while retain compatibility with other 3rd party tools and Operating systems such as Windows XP through windows 11 and Linux.

Compatible with:
* DSOAL-GW1
* Reshade
* GW toolbox
* GW Armory 
* GW Launcher (No uMod or TPF support)

![image](https://user-images.githubusercontent.com/69606814/191030227-76c6d666-4f07-4ff6-95d4-875a2405c7dc.png)
![image](https://user-images.githubusercontent.com/69606814/190917152-de836a28-5d10-4460-903d-e3e20b6ee7fb.png]

## Gpu Compatability status
* Amd : great
* Nvidia : great
* Intel : Bad

Please note, i have tested DXVK on a intel UHD 630 with the latest driver 30.101. however vulkan support is limited / Train wreck.
Intel Graphics 4400 and below don't support Vulkan. feel free to try other Intel GPUs however there is a good chance it wont work.

My experiance on drivers 25 through 30.101:
![image](https://user-images.githubusercontent.com/69606814/191081676-7eb1e69e-bbb0-473d-8415-532bcb1d1e79.png)


## Instructions:

1. Copy d3d9.dll and DXGI.dll to your guild wars installation folder.
2. Copy DXVK.Conf and Gw.dxvk-cache to your guild wars folder.
3. (optional) find your Guildwars shortcut and right click, Properties. in the target field change "C:\Program Files (x86)\Guild Wars\Gw.exe" to "C:\Program Files *(x86)\Guild Wars\Gw.exe" -d3d9.dll
4. run the game and enjoy.

Credits
* https://github.com/Sporif/dxvk-async For DXVK Async
* https://github.com/doitsujin/dxvk For creating DXVK
* https://github.com/Deadsimon/dxvk-async
* https://www.reddit.com/user/simonhazel00

