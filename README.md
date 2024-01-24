# PalworldModdingGuide
A guide on how to mod Palworld. I will be honest I am mainly putting this here so I can keep reminding myself.

# THIS (CURRENTLY) IS FOR CREATING REPLACEMENT MODS ONLY

# Extracting Files
Use FModel - https://fmodel.app

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


# Packaging
Packaging settings for your mod Unreal Engine 5.1.1 project

Use Pak file only
Packaging --> Advanced ---> Cook everything  in the project content directory

# Cool Stuff
Modding Kit - https://github.com/Hecking-Heck/PalworldModdingKit
Original Modding Kit - https://github.com/localcc/PalworldModdingKit

# Credits
LocalCC - https://github.com/localcc
Huge thanks to NorskPL on the [Palworld Modding Community Discord Server](https://discord.gg/qHTZNcvYsv)

# Help
For more help go here
[Palworld Modding Community Discord](https://discord.gg/qHTZNcvYsv)

