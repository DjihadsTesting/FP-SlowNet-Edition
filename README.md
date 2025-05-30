# FortnitePorting Slow Internet Edition

> [!WARNING]
> This Project is archived, FortnitePorting v3.2.0 has fixed the request timeout lenght allowing you to put any amount and get HD Textures on slow internet connections
>![image](https://github.com/user-attachments/assets/d59ee7d7-2b51-40a0-895d-55038eee47a6)





Made for fellow slow internet artists, by changing the https timeout of streamed textures from 30 seconds to 5 minutes!
------------------------------------------

#### Powered by [Avalonia UI](https://avaloniaui.net/) and [CUE4Parse](https://github.com/FabianFG/CUE4Parse)

[![Discord](https://discord.com/api/guilds/866821077769781249/widget.png?style=shield)](https://discord.gg/DZ5YFXdBA6)
[![Blender](https://img.shields.io/badge/Blender-4.2+-blue?logo=blender&logoColor=white&color=orange)](https://www.blender.org/download/)
[![Unreal](https://img.shields.io/badge/Unreal-5.4+-blue?logo=unreal-engine&logoColor=white&color=white)](https://www.unrealengine.com/en-US/download)
[![Release](https://img.shields.io/github/release/DjihadsTesting/FP-SlowNet-Edition)]()
[![Downloads](https://img.shields.io/github/downloads/halfuwu/FortnitePorting/total?color=green)]()
***

![image](https://github.com/user-attachments/assets/87fc86c1-20f2-4da8-98c6-5914ceb9681a)


## Building FortnitePorting Slow Internet Edition

To build FortnitePorting from source, first clone the repository and all of its submodules.

```
git clone -b v3 https://github.com/DjihadsTesting/FP-SlowNet-Edition --recursive
```

Then open the project directory in a terminal window and publish

```
dotnet publish FortnitePorting -c Release --no-self-contained -r win-x64 -o "./Release" -p:PublishSingleFile=true -p:DebugType=None -p:DebugSymbols=false -p:IncludeNativeLibrariesForSelfExtract=true
```
