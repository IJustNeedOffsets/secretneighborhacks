# secretneighborhacks
Open sourced visual mods for the game Secret Neighbour

In the next few days you will get my Visual Studio project uploaded here. Btw the visual mods only affect you,other players will see you normaly.
I added one option to enable "Fake Ghost". It just makes the player invisible for you. I will maybe also release my skin changer.

# Easy
even people with no coding skills can understand how this "hack" works. We are just unloading or reloading specific assets.
The Assets which we are load or unload are stored here: YOURDRIVE:\Program Files (x86)\Steam\steamapps\common\Secret Neighbor\Secret Neighbour_Data\StreamingAssets\aa\StandaloneWindows64
To see which Assets i have to target i used AssetStudio (https://github.com/Perfare/AssetStudio/releases)

Why we can not easly make a Skin changer by renaming Assets? The Asstes are .bundle files in this case and we can not replace them with UABE. (https://github.com/DerPopo/UABE)

The Solution i though about is, to find out how to compile .bundle files. So we gonna extract the real .bundle files, past them in a folder and rename the skin we want, like the default skin is named. Than we recompile the extracted Assets and replace them. The problem here is that this requires a lot of power bc the Assets are big and secondly i could not find information about making .bundle files for Assets.
If you figure out anything, please tell me on Twitter or make a pull request. 
Twitter: @IUnl0ck1
 UPDATE: UABE can edit and recompress the file data.unity3d which seems to store some intresting models. Im already looking in it, it could maybe be used to change the skin or to remove specific objects only.
 
 
 
   
