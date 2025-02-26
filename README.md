# FS25 Lua API

This repository contains **Lua scripts** for Farming Simulator 25 (FS25), organized into folders. It serves as an **API** to access Lua scripts via raw GitHub URLs.

---

## 📂 **Repository Structure**
The repository is structured as follows:

```
fs25-lua-api/
│── gui/
│    ├── base/
│    │    ├── Gui.lua
│    │    ├── GuiOverlay.lua
│    ├── AnimalScreen.lua
│    ├── ConstructionScreen.lua
│── vehicles/
│    ├── engine.lua
│    ├── physics.lua
│── index.json
```

---

## 🔗 **How to Access Lua Scripts**
All scripts are available as **direct links** via GitHub RAW URLs.

- **Index File (JSON API)**:  
  [📄 Click Here to View `index.json`](https://raw.githubusercontent.com/MyGameSteamOfficial/fs25-lua-api/main/index.json)

- **Example Script Access (AnimCurve.lua)**:  
  [📜 AnimCurve.lua](https://raw.githubusercontent.com/MyGameSteamOfficial/fs25-lua-api/main/AnimCurve.lua)

---

## ⚙️ **How to Use This API**
### **1️⃣ Fetch All Scripts**
You can fetch all scripts using the **index.json** file:
```
https://raw.githubusercontent.com/MyGameSteamOfficial/fs25-lua-api/main/index.json
```
It provides a structured JSON output containing script names and their direct URLs.

### **2️⃣ Fetch a Specific Script**
To access a single Lua script, use:
```
https://raw.githubusercontent.com/MyGameSteamOfficial/fs25-lua-api/main/<folder>/<script>.lua
```
Example:
```
https://raw.githubusercontent.com/MyGameSteamOfficial/fs25-lua-api/main/gui/AnimalScreen.lua
```

---

## 🚀 **How to Update the API**
If you add more scripts, update the `index.json` file by running:

```sh
python generate_index.py
```
Then push the changes to GitHub.

---

## 🤝 **Contributions**
Want to improve this API? Feel free to contribute! Fork this repo and submit a pull request.

---

## 📢 **License**
This repository is open-source. However, respect the **Farming Simulator Modding Guidelines** when using these scripts.

---

🎮 **Created by [MyGameSteamOfficial](https://github.com/MyGameSteamOfficial)**
