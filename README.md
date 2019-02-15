# Introduction to Coding for GIS

## Description

If you fooled with GIS applications such as QGIS or ArcGIS long enough, you have probably faced unsolvable problems that either took long enough or resulted in a crash. This repository is made for users that giving their first steps on programming and want to start using commands and scripts instead of interfaces. 

## Basic Navigation

First of all, you should know how to get your way around folders using commands directly on cmd (for windows users) or bash (for linux users). I'll try to be as indepth as possible, but bear in mind that our focus here is the GIS commands. Any doubt you have on how to use a certain command can be researched on [Stack Exchange](https://stackexchange.com/) or all over the web. Let's begin:

After opening the cmd, you will pretty much be facing a black box with some trademark information and a line with a flashing underscore that says:

> **"(Hard Drive letter):\Users\(username)_"**

This is called the **PATH**. It basically tells ou where the action is going to take place. It means you are currently inside that folder. You can navigate through other ones using the "cd" (it stands for Change Directory) command. eg: "cd C:\User\Documents" will take you to your Documents folder. Keep in mind that pressing tab will autocomplete the folder name, so you don't need to write it entirely. If you press tab without starting a folder name, it will browse all existing folders inside your location.

### Basic cmd commands (Windows users):


- "cd\" will take you to the top of the path (on our example, C:\)
- "cd .." will take you one folder above (on our example, C:\User\)
- "copy" copies a directory or file
- "dir" lets you see the data information on a certain folder; files and sizes
- "mkdir" or "md" creates folders on a given folder. eg: "md new_folder" would create a folder called "new_folder" under C:\User\ (remember our last example?)
- "ren" renames a already existing folder. eg: "ren new_folder useful_folder" would rename it to "useful_folder"
- "rmdir" deletes a directory
- "type nul (filename.format)" creates an empty file
- "move" moves a file from one place to another



### Basic bash commands (Linux users):


- "ls" lets you see the data information on a certain folder. You can combine it with a folder name to see what's inside that folder, even if your path isn't there.
- "cd/" will take you to the top of the path (on our example, C:/). You can write additional folders after it to navigate to that path.

