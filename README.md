# Fast64 Gart Edition

Modification of Fast64, Supports Blender 3.6 to 4.2.

Mainly used for Coop and Also supports V6 Mats.

# Features

# Coop Recolorability

Yes you don't have to manually add them anymore. you set Player Parts for materials in blender:
![image](https://github.com/user-attachments/assets/7df8d560-8bb0-4850-b9c1-05ba70a58ba8)
 
You'll have to Add that geo_mario_set_player_colors GEO_ASM bone in blender so you only have to export the model and not edit anything; The Mario.blend in this repository already has that bone set up for you.

# SMLUA Anim Exporter (WIP)

There's a New option called "SMLUA Animation" in the Animation Exporter:
![image](https://github.com/user-attachments/assets/7788c9bb-46bc-42ec-8cda-1ec100686161)

It allows you to export the anims as lua files in your Custom Export Path Folder:
![image](https://github.com/user-attachments/assets/5e6a37cb-d33c-4dd1-b03b-a292e2964ab4)

# Create Metal Material Option (For non-template users)

A new option under the Create Fast3D material option is added:
![image](https://github.com/user-attachments/assets/0e6bbd66-efb1-43fe-bf98-c903532bc1d6)

If you click it, It will generate a Fast3D Material With these properties:
![image](https://github.com/user-attachments/assets/1c7d1d25-0035-4b8a-ba12-8be4175810af)

For Texture 0, select the custom_mario_metal_shade.png from the repo's coop-metal-textures folder.
For Texture 1, select the custom_mario_metal_light.png from the repo's coop-metal-textures folder.

Or you can make a material and set the Preset to Sm64 Metal Texture:
![image](https://github.com/user-attachments/assets/575eb393-df11-4bbc-ab27-bf10db7a9eab)

(This Preset was made by FluffaMario)
