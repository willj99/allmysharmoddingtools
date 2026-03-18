# Tools Overview

Some of these scripts are made with PowerShell. If they do not run, run PowerShell as **Administrator**.

Paste this into your terminal: 
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser -Force

Once done, try the tools again.

## 1. Dialogue Case Fixer

Fixes dialogue capitalization — useful because SHAR does not accept improperly capitalized audio file names. 

**Usage:**
- Place this in the root of your NPC dialogue folder  
  **or** one step above your conversations folder.
- Assumes each character’s sounds are stored in their own folder.

A **.NET C# GUI version** now exists, which is easier to use and does not require placing the tool inside the root of a soundbank.

## 2. Simpsons Knife

Scans your directory for **non–game-related file types**.  
Use this only when preparing your mod for release.

**Usage:**
- Place this at the **root of your mod**, e.g., the folder before `CustomFiles`.

---

## 3. MFK2LUA

Converts MFK level folders into Lua.

**Usage:** MFK2LUA.exe [path to the MFK level folder you want to convert]


**Notes:**
- Works flawlessly on everything except level files.
- If a `GagSetPosition` uses a **named position** instead of coordinates, wrap the name in quotes.
- This also implies you are loading `Game.lua` from `CustomFiles.lua`.

---

## 4. Mod Creator

An older tool that generates:
- A mod folder  
- Template hack documents

---

## Additional Notes

All tools were created in PowerShell and signed by me.  
If you receive an anti‑virus prompt, add an exemption in Windows Settings. 



