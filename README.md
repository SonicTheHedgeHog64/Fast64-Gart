# Fast64 Gart Edition

Modification of Fast64, Supports Blender 3.6 to 4.3.
Keep in mind that 4.3 mostly crashes.

Mainly used for Coop and Also supports V6 Mats.

# Features

# Coop Recolorability

Yes you don't have to manually add them anymore. you set Player Parts for materials in blender:
![image](https://github.com/user-attachments/assets/7df8d560-8bb0-4850-b9c1-05ba70a58ba8)
 
You'll have to Add that geo_mario_set_player_colors GEO_ASM bone in blender so you only have to export the model and not edit anything; The Mario.blend in this repository already has that bone set up for you.

# Use Light for Recolorability

This Options makes it so the Material's Lights gets recolored but not the Ambient. You can make it do some cool Effects!
![image](https://github.com/user-attachments/assets/cc9d45bc-5f92-4ae2-ae6a-da1e48f340f3)


Blender default light with custom ambient:
![Screenshot 2024-09-10 005409](https://github.com/user-attachments/assets/2bec3301-bad5-419a-ae86-d7eaceda76b4)


In SM64 With Light recolored but Ambient kept:

![Screenshot 2024-09-10 005336](https://github.com/user-attachments/assets/ec5c5cd7-b779-4157-a1bb-afa80e01bcc9)

Thanks to SwagSkeleton95 for letting me use the model By the way!!!

# Use Ambient for Recolorability

This Options makes it so the Material's Ambient gets recolored but not the Light. You can make it do some cool Effects!
![image](https://github.com/user-attachments/assets/c6d73da1-a150-40b0-8500-0e32166e3bb3)


Blender default light with custom Light:


![image](https://github.com/user-attachments/assets/52f26fd9-b22b-468b-ace9-f75b4f7198f8)


In SM64 With Ambient recolored but Light kept:

![image](https://github.com/user-attachments/assets/379b3f56-7b06-40c5-8a1c-27f7291afc2a)

Thanks to SwagSkeleton95 for letting me use the model in both examples By the way!!!

Selecting both Use Light and Use Ambient will result in a shaded and fully recolorable material.

# SMLUA Anim Exporter (WIP)

There's a New option called "SMLUA Animation" in the Animation Exporter:
![image](https://github.com/user-attachments/assets/7788c9bb-46bc-42ec-8cda-1ec100686161)

It allows you to export the anims as lua files in your Custom Export Path Folder:
![image](https://github.com/user-attachments/assets/5e6a37cb-d33c-4dd1-b03b-a292e2964ab4)

# Metal Material Preset (For non-template users)

You can make a material and set the Preset to Sm64 Metal Texture:


![image](https://github.com/user-attachments/assets/575eb393-df11-4bbc-ab27-bf10db7a9eab)



For Texture 0, select the custom_mario_metal_shade.png from the repo's coop-metal-textures folder.

For Texture 1, select the custom_mario_metal_light.png from the repo's coop-metal-textures folder.

(This Preset was made by FluffaMario)

# Fix Coop Fog

There's a new option under the "Disable Scrolling Textures" option, it fixes fog materials for levels automatically:
![Screenshot 2024-09-17 174137](https://github.com/user-attachments/assets/168e7b52-1439-4612-b916-81ce4be3d854)

# Fix Reverts for Coop

There's a new option under the "Fix Coop Fog" option, it adds the revert that Coop needs to work properly (for new Metal in romhacks); this also fixes the Vanish cap not affecting some parts of the body.
![Screenshot 2024-09-19 102951](https://github.com/user-attachments/assets/17e04012-9500-41bb-ab96-e01c8563a11b)

# New Geolayout Command(s)

In this Fast64, there's a new Bone command:
![image](https://github.com/user-attachments/assets/b65e1cb7-e8c8-432f-9aeb-3c156fa48cf9)

If you enable it in a bone, it exports these that are needed for recolorability:
![image](https://github.com/user-attachments/assets/d945d3ff-7b3b-4f03-bb87-89d6aa3ceb60)

There are also 2 others for mirror mario:

![image](https://github.com/user-attachments/assets/4f6a8a6e-ab7d-49a8-a8a5-ef0c776945d6)

If you enable it in a bone, it exports these for mirror mario:
![image](https://github.com/user-attachments/assets/b5a1904c-9f46-4e0b-b419-7e5c1f10d4bc)

![image](https://github.com/user-attachments/assets/f84e62b0-7e75-4aa8-942a-83149abef9ce)

# Delete all .bins and .cols

If you enable these under SM64 Combined Exporter in Export Graphics when you have Custom as the export type, your bin and col files will get deleted respectively:


![image](https://github.com/user-attachments/assets/7940ff9b-6b25-4520-9560-bed7bac5cb3c)




