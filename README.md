# Hillware
GUI for the Roblox to Brick Hill connector game

GAME LINK: https://www.roblox.com/games/7414406513

SETUP: https://pastebin.com/raw/j5h5wFPX

VTS: https://pastebin.com/raw/7skuAuu7


- Player
  - Walk speed changer
  - Jump power changer
  - Gravity changer
  - Infinite jump/Fly (Keybind)
  - Noclip/Air walk (Keybind)
  - Click TP (Keybind)
- Render
  - ESP (WIP)
- Misc.
  * IP Address:
    - Display server IP + port
    - Copy IP + port to clipboard (exploit support needed)
    * Settings:
    - Rejoin server

I still want to update this a bit, for example fix the ESP and make it more customizable, I might also potentially add autofarms for popular games like the glass bridge
After you installed Tampermonkey as well as the Joindata copier JavaScript get a game's join data, hop into the Roblox game and paste it in, you can run the script there already but I recommend to wait until you're fully loaded in

TODO:
- fix bugs:
  - [X] airjump stops working after respawning
  - [X] click tp doesnt work
  - [ ] ESP boxes dont get applied to newly spawned players
  - [ ] ESP boxes dont get destroyed properly
- improve ESP 
  - [X] color selection (only for chams for now)
  - [ ] roundness/size modifier
- switch to a better ui lib (things like minimizing are buggy in current one)
