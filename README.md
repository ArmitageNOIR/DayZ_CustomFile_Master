# DayZ_CustomFile_Master
When you want to Start / Create a New Custom File

if you want to use this file simply copy/paste it w/out changing the files name... or change the name to what ever you want, just put ( .json ) at the end of the file name... example AdminBase.json

for this to work you will need the following Files/Folders:

-the "Custom" Folder ( this folder sits at the Top of the "DayZOffline.Enoch" Folder when you open it, in this Folder "Upload" the File as it is or w/ a name you decided to give to it )

-cfgGameplay.json ( this File is Located in the "DayZOffline.Enoch" Folder, scroll down untill you see this file in the list, when you open this File, scroll down to 
"worldsData" and look for the "objectSpawnerArr" and copy/paste the AdminBase.json file or what ever name you gave to it, here an Example:

"objectSpawnersArr": ["custom/AdminBase.json","custom/AdminRoger.json","custom/GlnskFUEL.json"],

as you can see i put in 3x Custom Files, this way you can see what code to use when you want multiple CustomFiles... 
only want 1x CustomFile? heres an Example

"objectSpawnerArr":["AdminBase.json"],

thas it, always "SAVE" and now restart the server, if it works you will now have a tree house-ish near Glaniaska Bridge next to the house on the left... 
if it does not work, all that will be "gone" or not "appearing" is the stuff i. this file and the rest of the server "should" be fine... 

if nothing works, deleted the custom file that you added and the line of code in the cfgGamePlay.json File

SAVE and Restart and everything is back to normal
