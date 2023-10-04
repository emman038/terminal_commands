# **Cheatsheet**
>man = shows all the commands

>pwd = prints path

- ls = lists files
- ls-a = lists files including the config files and git files
- ls-l = long list - gives you more infor about the files
- ls -la = gives a long listing of all files (including config and git files etc.)

- cd ./XYZ = move down into the XYZ file
Or you can just do cd XYZ (You don't necessarily need the ./)
- cd ../ OR cd .. OR .. = Go up a level
- cd ../../../../ = Go up (4) levels
- cd - = Takes you to where you were last
- cd = Takes you to the root directory

>mkdir = make a directory

> Naming Coventions 
it is a convention to use SnakeCase
Tend to avoid starting with a number. Use underscores or letters etc. First

- touch = makes a file
- mv = Changes an item. I.e. If you wanted to change the filename from diy_2 to day_2 you would write the mv command followed by the filename, a space then the name you want to change it to. mv diy_2 day_2
You can also use it to move folders around
E.g. mv xyz ../week_02
You need to be in the parent directory for xyz and the .. Allows you to go up a level to move it to the week_02 folder with is on the same level as the parent of the xyz file.
The / tells the terminal it is a directory

- cp = Copies a file.
E.g. cp day_02 ../week_02
You need to be in the parent directory for day_02 then you need the .. To allow the terminal to go up a level and copy it to the week_02 folder (on the same level as the parent directory for day_02)
- cp r = Copies folder and everything in it
- rm = Deleting FILES
- rm -r = means delete everything inside the directory. Recursive - meaning delete this level and every level after it 
- rm -rf = forcibly do it and override warnings. ******* Becareful when you use -rf as nothing will stop you completing the process and once you lose it you lose it for good
open . = Opens in finder (GUI) where you are
git init = initializes a git repo locally
- rm -r .git = removes the git from a file but doesn't delete the file. However, it will delete the timeline of the file (so all the history of the previous files)

- gst or git status = to check the status of a git repo
- git add = Stages the file to be committed
- git commit -m "message to go with the commit" = Commits the file
- git log = displays all of the commits in a repository's history (timeline)
- ß--all = used to select all the files in a directory