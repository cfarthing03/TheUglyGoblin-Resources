# The Ugly Goblin – Foundry VTT Resources

A curated collection of **Items, Skill Trees, and Information Journals** for **Foundry VTT**, built using the **dnd5e** system.  
All content is based on the game system created by **TheUglyGoblin**.

This module is designed to be flexible:
- **Items and Information Journals** can be used **standalone**
- **Skill Trees** require an additional module (see below)

---

## System Compatibility

- **Foundry VTT:** v11+ (verified through v13)
- **Game System:** dnd5e

---

## Installation

Paste the following URL into  
**Foundry VTT → Install Module → Manifest URL**
https://raw.githubusercontent.com/cfarthing03/Ugly-Goblin-Try-2/main/module.json

---

## Recommended Modules

These modules are **optional**, but strongly recommended depending on how you plan to use the content.

- **Skill Trees by TheRipper93**  
  Required to use the Skill Trees included in this module.

- **Midi-QOL by Tim Posney**  
  Optional, but recommended if you would like to utilize automated macros and effects that will be added in future updates.

> All Items and Information Journals included in this module are fully usable **without** any other modules installed.  
> These additional modules simply allow for expanded functionality and automation.

---

## How to Use the Skill Trees

1. Open the **Compendium** tab in Foundry VTT.
2. Locate the compendium titled **Skill Trees and Information**.
3. Drag the desired **Skill Trees** into your **Journals** tab.
4. Drag **Features / Abilities** into your **Items** tab.
5. With **Skill Trees by TheRipper93** installed and active, the module will automatically:
   - Detect imported skill trees
   - Establish node connections
   - Enable purchasing and progression
   - Automatically add most items to the character sheet when a node is purchased

Due to module limitations, some items may need to be added manually. These items are clearly organized and spaced out to make them easy to locate.

If a skill tree appears to be missing connections, see the **Known Issues** section below for steps to resolve the issue.

---

## ⚠️ Known Issues

### Combat Skill Tree Missing Connections on Import

When importing skill trees into a world, the **Combat Skill Tree** may occasionally load without visible node connections.

- **Status:** Unintended behavior

**Workaround:**
1. Open Configure Settings
2. Scroll Down till you see "Skill Tree" and click it
3. Configure Skill Trees
4. Click the edit button next to the Combat Skill Tree

This will re-establish the node connections. Once done, the skill tree should function as intended.

---

### Unable to Remove the Last Point from a Node

The final point of a node cannot currently be removed once spent.

- **Cause:** This is a known bug within the Skill Trees module itself.
- **Status:** Not something I am able to fix directly at this time.

**Workaround:**
1. In the Configure Skill Trees menu, disconnect the node you want to modify from the ones surrounding it
2. In the character sheet itself, right-click the node to remove the point
3. Reconnect the node to the tree in the Configure Skill Trees menu

While not ideal, this has been the most reliable solution found so far.

---

## Feedback & Support

This is my first time publishing a Foundry VTT module, so feedback is always welcome.

If you encounter bugs, missing content, or unexpected behavior:
- Please open an **Issue** on GitHub, or
- Reach out with details so I can take a look

---

## Credits

- **Content & Design:** TheUglyGoblin  
- **Skill Tree Framework:** Skill Trees by TheRipper93  
- **Automation Support:** Midi-QOL by Tim Posney


