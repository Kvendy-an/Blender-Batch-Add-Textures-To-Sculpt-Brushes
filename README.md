# Blender-Batch-Add-Textures-To-Sculpt-Brushes
A simple python script to batch apply Texture Masks to Sculpt Brushes then mark them as Asset.

I found many cheap brushpacks for Zbrush, and I wanted to use them with Blender, though adding them one by one to Blender is long repetitive process. so this script automated it.

How To Use:
1. Create a .Blend file.
2. Create a Folder Named Masks Next to the Blend file.
3. Add the Textures jpg/png/tiff/etc... to Masks Folder.
4. Open the Blend file
5. Go to the Scripting Tab.
6. Press New.
7. Copy and paste the Script download Script.txt.
8. Press Run Script.

Or use the Template.zip it has everything setup with few masks as example.

The Blend file will populate with sculpt brushes. You can now in the preferences select the Blend file path as Asset Library. Make sure the Mask Folder is always with the Blend file because it use relative path for the textures.

By default the created brushes are using "Anchored" method, modify the script to change how the brushes should behave.

__Tested on Blender 5.1.2__

__ALWAYS BE CATION RUNNING SCRIPTS MADE WITH CHATGPT!!__
