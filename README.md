# Palworld Modding Guide
An extensive guide on how to mod Palworld. I will be honest I am mainly putting this here so I can keep reminding myself.

HUGE NOTE: Nearly everything here has been parroted by me since I am using this as my own personal notes. So go thank NorskPL and the [Palworld Modding Community Discord Server](https://discord.gg/qHTZNcvYsv) for being the ones to make this all possible.

# My Mods
[Nexus Mods](https://www.nexusmods.com/users/56638927)

# Requisites
[FModel](https://fmodel.app)

[UnrealPak](https://github.com/allcoolthingsatoneplace/UnrealPakTool)

[Unreal Engine](https://www.unrealengine.com/en-US)

# Extracting Files
Use [FModel](https://fmodel.app)

# FModel Tutorial
Run Fmodel, click on "Add Undetected game", type any name and enter the directory path to Palworld game. Click on the blue plus button.
Unreal Engine version of the Palworld game is 5.1.1, so use GAME_UE5_1 setting.
Go to settings and enable Local Mapping File
Select Mappings.usmap file under Mapping file path
Now you're able to explore game files and export textures/models and stuff!

Note: Fmodel requires .NET 8.0 Desktop Runtime installed on your computer!

Credit NorskPL on the [Palworld Modding Community Discord Server](https://discord.gg/qHTZNcvYsv)

# Get the right version of Unreal Engine
Current version -> Unreal Engine 5.1.1

# Creating the Unreal Engine Project
Creating Unreal Engine 5.1.1 mod project and preparing it

Select these settings and click create:
![image](https://github.com/Hecking-Heck/PalworldModdingGuide/assets/33295627/4b96b8ac-c793-4290-b463-c140732670f4)

After loading process something like this will show up:
![image](https://github.com/Hecking-Heck/PalworldModdingGuide/assets/33295627/eecee855-12f9-4134-bc2c-86d619212c72)

Click on platforms and select this setting:
![image](https://github.com/Hecking-Heck/PalworldModdingGuide/assets/33295627/df2191c0-8cf8-43b6-bd78-5981e0159049)

Now go to packaging settings:
![image](https://github.com/Hecking-Heck/PalworldModdingGuide/assets/33295627/aa4c01a4-a775-4bb7-bc4a-8dad2cfc466b)

Advanced:
![image](https://github.com/Hecking-Heck/PalworldModdingGuide/assets/33295627/7efa7e52-b083-4596-bbb7-2587649fecd1)

Now you can start recreating folder structure in your project and import your assets like png textures and stuff

# Folder Structure
Proper folder structure example:
![image](https://github.com/Hecking-Heck/PalworldModdingGuide/assets/33295627/fe05a961-6227-4f5b-be56-fb0c7dc0ac60)

If you've added all the resources you wanted, you can now cook content.
![image](https://github.com/Hecking-Heck/PalworldModdingGuide/assets/33295627/f9ad0d2a-7559-4b75-b578-0e4cf20ce6d9)

When cooking process is done, go to your project folder, open Saved folder, then open Cooked folder.
![image](https://github.com/Hecking-Heck/PalworldModdingGuide/assets/33295627/5f45b76e-e6e5-4523-83e1-254e5c736609)
![image](https://github.com/Hecking-Heck/PalworldModdingGuide/assets/33295627/44e763c5-8afe-40fa-97d2-3c6d8240e96a)

Your uasset and uexp files gonna be here.

# Creating a PAK file
Mod .pak file creation

You gonna need UnrealPak for this.

Unpack UnrealPak zip and create new folder with projectnamehere_P name

Recreate folder structure to look the same way you see it in fmodel.

Drop uasset and uexp files from your cooked folder to the appropriate folders.

Now drop folder with projectnamehere_P name into UnrealPak-With-Compression.bat

It will generate your mod pak file with name projectnamehere_P

Move that mod pak file into Palworld\Pal\Content\Paks and run the game.

![image](https://github.com/Hecking-Heck/PalworldModdingGuide/assets/33295627/3e5d53c4-6dab-458c-b309-1b464fce7fd9)
![image](https://github.com/Hecking-Heck/PalworldModdingGuide/assets/33295627/b3ce77af-cc9b-4a04-b451-99fefd6bad40)
![image](https://github.com/Hecking-Heck/PalworldModdingGuide/assets/33295627/53b45ef5-c7c6-485d-9f03-3600a2c62d8e)
![image](https://github.com/Hecking-Heck/PalworldModdingGuide/assets/33295627/a2c84d0d-dce0-4ad0-a684-0cac5cb4c4e3)

# Mod Example
Mod Example (folder structure and unrealpak included)
These can be found in the repo, they are named UnrealPak.zip and PalworldModExample.zip

# Packaging Notes
Packaging settings for your mod Unreal Engine 5.1.1 project

Use Pak file only
Packaging --> Advanced ---> Cook everything  in the project content directory

# Notes on Texture Names
Texture names:

<Texturenamehere>_B = Base texture
<Texturenamehere>_M = MRAO (MetallicRoughnessOcclusionSpecular)
<Texturenamehere>_N = Normal Map

Normal map can be created with online software or Crazybump
MRAO creation tutorial: https://dev.epicgames.com/community/learning/tutorials/6Gn5/creating-mrao-textures-using-free-software

(I will continue to add to this as I learn and understand more about what I am doing)

# Modding Kit
Original Modding Kit - https://github.com/localcc/PalworldModdingKit

My personal Fork of the Modding Kit - https://github.com/Hecking-Heck/PalworldModdingKit

# A cool video on how to model swap with Palworld
Made by Sleepyhead08 on the [Palworld Modding Community Discord Server](https://discord.gg/qHTZNcvYsv)

[Watch the video](https://youtu.be/NESKhITrbgI?si=lNH2VNSbBFYKQ-Hc)

# Want to mod a Palworld Steam Dedicated Server?
[Palworld Steam Dedicated Server Modding Guide](https://forums.nexusmods.com/topic/13466235-how-to-enable-steam-dedicated-server-mods-for-palworld/)

# Credits
[LocalCC](https://github.com/localcc)

Huge thanks to NorskPL on the [Palworld Modding Community Discord Server](https://discord.gg/qHTZNcvYsv)
Images are from NorskPL on the [Palworld Modding Community Discord Server](https://discord.gg/qHTZNcvYsv)

[FModel](https://fmodel.app)

[UnrealPak](https://github.com/allcoolthingsatoneplace/UnrealPakTool)

[Unreal Engine](https://www.unrealengine.com/en-US)

# Help
For more help go here
[Palworld Modding Community Discord](https://discord.gg/qHTZNcvYsv)

