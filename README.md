# Live-Like ORBIT – Full Config + Routes

A complete, ready-to-import preset that combines ORBIT behaviour settings with matching routes for more varied and believable raids.

## Information

### OVERVIEW

The config and route pack are tuned as one setup for PvP traffic, looting, quest movement, extraction and personality-driven decisions.

The download contains two preset files. It does not include ORBIT, SAIN or their dependencies, and it does not modify bot gear, ammunition, health, spawns or combat difficulty.

> **Current version:** 1.1.0  
> **Included:** Full ORBIT config + 13-map route pack


### INSTALLATION

**Before installing**

1. Install ORBIT 2.0 and all of its required dependencies.
2. Apply the recommended SAIN settings listed on the ORBIT mod page.
3. Extract the downloaded ZIP anywhere. It contains:

   - `orbit-live-like-config-x.x.x.json`
   - `orbit-live-like-zones-x.x.x.orbitzones.json`

**Importing the preset**

1. Start the SPT server.
2. Launch the game and wait until you reach the main menu.
3. Open the ORBIT web interface through **F12 → Open web config UI**, or open `https://127.0.0.1:6969/orbit` in your browser.
4. Optional but recommended: create backups before importing:

   - On the ORBIT Overview page, use **Generate export** and download your current config.
   - Open **Zone editor → Share zone packs**, select **All maps**, generate a pack and download it.

5. On the ORBIT Overview page, click **Import a config (.json)** and select `orbit-live-like-config-x.x.x.json`.
6. Open **Zone editor**, scroll down to **Share zone packs**, click **Choose a pack file (.json)** and select `orbit-live-like-zones-x.x.x.orbitzones.json`.
7. Both imports will appear as unsaved changes. Click the global **Save** button in the top-right corner of the ORBIT page.
8. The preset takes effect from the next raid. The two files can be imported in either order.


### UNINSTALLATION

Import the config and all-map zone backups you made before installation, click **Save**, and start a new raid.

Without backups, use **Reset page** in every ORBIT config section and **Reset map** for each map. Save the changes and start a new raid.


### DETAILED CHANGES

**More natural map flow**

Routes across all supported maps were reworked so squads do not follow the same pattern every raid. Main PvP areas remain important, while secondary locations and connecting routes create more varied movement around the map.

**Active PvP hotspots without forced encounters**

Locations such as Dorms, Stronghold, Resort, KIBA, LexOs and Sawmill remain strong destinations. They should attract action regularly without forcing every squad into the same place in every raid.

**Personalities have a stronger role**

Timmy and cautious personalities focus more on quests, loot and safer movement. Chads and GigaChads are more likely to hunt, move aggressively, open locked rooms and stay in dangerous areas for longer.

**Questing, looting and extraction work together**

Squads can visit quest locations, search valuable areas, investigate corpses and extract once their objectives are complete or their equipment is valuable enough. A less attractive route is never completely blocked.

**Smoother indoor movement**

Looting and squad splitting were adjusted to reduce unnecessary movement between floors. This is especially useful in locations such as Resort, Dorms, Interchange and Reserve.

**Safer Ghost Mode behaviour**

Ghost movement, looting and simulated fights remain enabled. Sleep and wake behaviour was adjusted to reduce rapid switching, while bots not fully controlled by ORBIT are kept awake to avoid frozen encounters.

### CREDITS & SUPPORT


[ORBIT 2.0](https://sp-mod.com/mod/2706/orbit-20) was created by **Chazut**. Special thanks to Chazut for permission, technical explanations and feedback that helped improve the zone variation and same-floor behaviour in version 1.1.0.

Feedback is welcome. When reporting unexpected bot movement, please include:

- Map and location
- Bot faction or personality, if known
- Approximate raid time
- What happened
- Whether the behaviour occurred more than once

