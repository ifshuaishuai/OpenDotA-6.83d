## DOTA ALLSTARS v6.83d - OPEN VERSION

All credit goes to IceFrog. 
Thank you for bringing my friends and me the purest joy of gaming during our youth. 
I still find myself deeply longing for those good old days.

---

## 📌 Project Overview
The **OpenDotA** project aims to reconstruct a freely editable version of the legendary *DotA Allstars* map. 

It is intended **SOLELY** for educational purposes, allowing creators to open the map in the World Editor to study how it was built. Map theft or plagiarism is strongly discouraged. Please respect the original creators and use this resource responsibly.

## 🛠️ What Has Been Done
To make the map readable and editable, the following reverse-engineering and restoration tasks were performed:
- **Listfile Recovery:** Fully restored the `(listfile)` for the map archive.
- **Editor File Reconstruction:** Rebuilt editor-only files including regions, cameras, variables, and metadata.
- **Script Segmentation:** Split the massive monolithic map script into structured trigger sections.
- **Code Beautification:** Indented code blocks properly for effortless reading and understanding.
- **Human-Readable Refactoring:** Renamed global variables, functions, and Hashtable parentKey/childKey pairs into intuitive, human-readable names.
- **Anti-Widgetization:** Restored core object data files (units, abilities, items, etc.) from raw `.txt`/`.slk` files back into the editor format.

## ⚠️ Known Limitations & Compatibility
- **Warcraft III Versions:** You can use ** v1.24b or higher** of Warcraft III World Editor to open and view the map.
- **8MB Limit Crash:** Because the *DotA v6.83d* map size exceeds the classic 8MB limit, saving the map in a standard World Editor may cause a crash.
- **WTS Inlining Required:** If you save the map with the restored data, you **must** run a WTS inlining tool on it before playing. Otherwise, the map loading time will be agonizingly slow (up to 50 minutes).

Given the limitations above, I highly recommend using **YDWE** (https://github.com/actboy168/YDWE) to open, view, save, and test the map smoothly.

Enjoy! 🎮

---

## 👥 Credits & Contributors
**Map Deprotection & Restoration Team:**

### Version 6.83d
*   **if:**
    *   Listfile recovery
    *   All the heavy lifting and "dirty work"
*   **Claude Opus:**
    *   Splitting map script into trigger sections
    *   Refactoring function and global variable names

---

## 🌐 Project Homepage
Check here for the latest releases, updates, and discussions:  
🔗 https://github.com/ifshuaishuai/OpenDotA-6.83d
