# Tutorial: How to Get Gorilla Tag Mods 

**Disclaimer:** Getting mods, even legal ones, can have of the risk of getting banned. 

---

## **Step 1: Install Gorilla Tag on PC**
1. Make sure you have Gorilla Tag installed on your PC through **Steam** or **Quest PC**.
2. Ensure that your PC meets the minimum requirements for running both the game and mods.

**Minimum Specs (according to the steam description):**

**OS:** Windows 10

**Processor:** Intel Core i5-4590 / AMD FX 8350

**Memory:** 4 GB RAM

**Graphics:** NVIDIA GTX 970 / AMD Radeon R9 290

**Network:** Broadband Internet connection

**Storage:** 140 MB available space

**Sound Card:** n/a

**VR Support:** SteamVR or Oculus PC

**Additional Notes:** This runs on a Quest, so it should probably run on any reasonable computer that can run Oculus or SteamVR at all that isn't literally a toaster

---

## **Step 2: Download and Install BepInEx**
BepInEx is usually the mod loader used for Gorilla Tag.

1. Go to the [BepInEx GitHub page](https://github.com/BepInEx/BepInEx/releases).
2. Download `BepInEx_win_x64_5.4.23.2.zip`.
   - It should be a `.zip` file.
3. Extract the zip file to your Gorilla Tag installation folder:
   - Default path for Steam: `C:\Program Files (x86)\Steam\steamapps\common\Gorilla Tag`
   - Default path for Quest PC: `C:\Program Files\Oculus\Software\Software\another-axiom-gorilla-tag`
4. After extraction, run Gorilla Tag once to generate the necessary BepInEx files.

---

## **Step 3: Download Mods**
1. Go to a trusted place for Gorilla Tag Mods. For example, [MonkeMod.](https://discord.gg/b2MhDBAzTv)

**Recommended Mods**
- [GorillaShirts](https://github.com/developer9998/GorillaShirts), by Dev9998 - Adds custom shirts to the game
- [GorillaWatch](https://github.com/developer-cody/GorillaWatch), by Cody - Bundle of mods
- [CustomCosmetics](https://github.com/defaultuser0-nerd/CustomCosmetics), by wryser - Adds custom cosmetics to the game
- [Grate](https://github.com/The-Graze/Grate), by Graze - Fixed bark
- [WhoIsTalking](https://github.com/The-Graze/WhoIsTalking), by Graze - Name tags
- [BananaOS](https://github.com/HuskyGT/Banana-OS/tree/main), by Husky - Recreation of the old quest mod
- [NoMoreWind](https://github.com/defaultuser0-nerd/NoMoreWind), by defaultuser0 - Removes wind
- [Utilla](https://github.com/developer9998/Utilla), by Bobbie - Adds modded gamemodes - Fixed by Dev9998
- [Newtilla](https://github.com/Loafiat/Newtilla), by Loafiat - Adds modded gamemodes - I recommend this more as its more robust
- [Gsabers](https://github.com/LEPHROGFISH/Gsabers-Remastered), by LEPHROGFISH - Adds light sabers

**Notes:** 
- You can use Utilla and Newtilla together.
- You need to set HideGameManager to true for Newtilla which is explained in step 4.5.
  
---

## **Step 4: Install Mods**
1. Place the downloaded `.dll` mod files into the `BepInEx/plugins` folder inside your Gorilla Tag directory.
   - Default Steam Path: `C:\Program Files (x86)\Steam\steamapps\common\Gorilla Tag\BepInEx\plugins`
   - Default Quest PC Path: `C:\Program Files (x86)\Steam\steamapps\common\Gorilla Tag\BepInEx\plugins`
---
## **Step 4.5: How to Set `HideGameManager` to True**
- Go to the BepInEx Config folder:  
  `C:\Program Files (x86)\Steam\steamapps\common\Gorilla Tag\BepInEx\config` or
  
  `C:\Program Files\Oculus\Software\Software\another-axiom-gorilla-tag\BepInEx\config`
- Open `BepInEx.cfg` using a text editor like Notepad.
- Find `HideGameManager` or add it under `[Logging.Console]`, then set it to:
  
  ```plaintext
  HideGameManager = true
---

## **Step 5: Launch Gorilla Tag with Mods**
1. Open Steam or Quest PC and launch Gorilla Tag.
2. The mods should now be active.
3. **Important:** Only use mods in modded lobbies unless it doesn't give an advantage. Cheat menus are also not allowed **anywhere.** Even if it's a modded or private.

---

## **Optional: Troubleshooting**
- **Issue:** Mods are not working.  
  - Ensure BepInEx is installed correctly and run the game once to generate its files.
  - Check the mod’s compatibility with the current version of Gorilla Tag.
  
- **Issue:** Game crashes on startup.  
  - Remove recently added mods from the `plugins` folder and try launching the game again.

- **Tip:** Ping **@Helpers** in [MonkeMod](https://discord.gg/b2MhDBAzTv) if you need help. Be sure to be kind to the helpers :)

---

Have fun! :)
