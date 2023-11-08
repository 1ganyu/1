# 4.2 NEWS
ORFif and offset broke in this update. Fixes will be released soon.

# LeoTools
Modding tools for GIMI, SRMI and HIMI (Most likely applicable to 3dmigoto modding in general yet not directly supported)

- **DailyLumine.py**:** Despite its name is not only for lumine. It's a script meant to deactivate all the folders within a specific directory(assuming you have your mods organized by character folder) and randomly reactivate only one of them, hence swapping active mod on launch. It is better to use this script in the launch =  clause of your 3dm and then have the script launch the game for you. You might need to set python as the default exe for .py files.

- **FixXXXX.py:** Specific scripts to fix mods that have been broken by updates or complex shaders like dashes, 4.0 characters and so on.

- **JoinMeshes.py:** Blender plugin that eases the repetitive tasks of mod exporting. Includes auto modifier application, shapekeys and even exporting every frame of animation as an unique mod folder.

- **multiplyweight.py:** Blender plugin that multiplies the weight of all vertices in a model. Useful to scale up your mod. [Read this guide to change character sizes](https://github.com/leotorrez/LeoTools/blob/main/guides/ChangeSizeGuide.md)  

- **quickBlenderImport.py:** Eases the process of importing models from dumps, applies materials to each corresponding meshes and does some clean-up tasks on the mesh leaving it in nice quads.

- **speedControl.py:** Complementary task for animation mods. After merging all the frames, run this script in the animation folder to generate the animation controller and optimize the RAM usage of the animated mod.

- **ORFix.ini:** This is a global ini to fix reflection and outline in 3.0+ characters. [Read this guide to know how to use it in your mods.](https://github.com/leotorrez/LeoTools/blob/main/guides/ORFixGuide.md)  