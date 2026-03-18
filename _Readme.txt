Some of these scripts are made with PowerShell, if they do not run, run PowerShell as administrator, 

Paste this into your terminal:
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser -Force

Once done, try the tools again.
=============



1. Dialogue Case Fixer - Fixes dialogue capitilzation, this is helpful as SHAR doesn't like improperly capitalized audio file names. 
Simply place this in either the root of your NPC dialogue folder or a step behind your conversations folder. 
This assumes you have each individual character's sounds in their own folder.

There is now a .NET C# version of this with a GUI which is much easier to use and doesn't require the tool to be rooted in a soundbank.

================================================================================================

2. Simpsons Knife - 
This scans your directory for non game related file types, only use this when you are preparing for release. 
Place this at the root of your mod, i.e.: The folder before CustomFiles aka the root.

================================================================================================

3. MFK2LUA - 
Open up a terminal in this folder, type:
MFK2LUA.exe [paste path of the MFK level folder you wish to convert here]

Side notes: This tool works flawlessly on everything but level files = if there's a GagSetPosition with 
a named position instead of coords, you need to wrap these in quotes to fix.

This also implies you're loading Game.lua from CustomFiles.lua.

================================================================================================

4. Mod Creator -
Really old tool that generates a mod folder for you and template hack documents.

All tools created in PowerShell and signed by me, if you get an anti-virus prompt, just mark an exemption in Windows Settings.