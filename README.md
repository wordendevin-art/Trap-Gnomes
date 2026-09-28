# Trap Gnomes V1

A private mod menu for **Burglin' Gnomes**. The **Free Version** needs no key. A license key
from the owner unlocks the stronger mods.

> **This is not open-source software.** Personal use only. Don't re-upload the mod or pass your
> key to anyone. See `LICENSE.txt`.

---

## Install

You need the game with **BepInEx 5** already installed.

1. Download **`GnomeCheats.dll`** from the [latest release](../../releases/latest).
2. Put it in your game's `BepInEx\plugins` folder:
   ```
   Steam\steamapps\common\Burglin' Gnomes\BepInEx\plugins\
   ```
3. Start the game and press **F1** to open the menu. It opens on the **Free Version** - no key needed.
4. Got a key? Go to **Info tab → Enter license key**, paste it and click **Activate**.
   You only do this once - it's remembered after that.

You only install once. After that the mod **updates itself** (see [Updates](#updates)).

> Your mouse is free while the menu is open, so there's no need to pause. Keys and clicks don't
> move your gnome while the menu is open, so you can type in it safely.

---

## Roles

Everyone starts on the Free Version. A key from the owner unlocks a higher role.

| | Free Version | Customer | Admin |
|---|:---:|:---:|:---:|
| FOV, Third Person, Performance Mode, Middle Finger | ✓ | ✓ | ✓ |
| Basic Gnome Customization (palette colours, 3 presets) | ✓ | ✓ | ✓ |
| Player list, keybinds, Changelog, Report a Bug | ✓ | ✓ | ✓ |
| **God Mode**, Infinite Stamina, Unbreakable Limbs | | ✓ | ✓ |
| Silent Movement, Immunity (Fire / Potions / Tied) | | ✓ | ✓ |
| NPC ESP, Item ESP, On-Screen Info | | ✓ | ✓ |
| Full Gnome Customization (fine-tune, effects, Items tab, Size) | | ✓ | ✓ |
| Speed, No Clip, Moon Boots, Jump Height Boost, AI Undetectable | | | ✓ |
| Player ESP, Player Inventory ESP, Spectator Mode | | | ✓ |
| Teleport, spawners, Host tools, blue **ADMIN** tag | | | ✓ |

- Mods your role doesn't include are greyed out with a `[Customer]` or `[Admin]` tag. Ask the
  owner about an upgrade.
- A role change from the owner reaches you by itself within about 15 minutes - no restart needed.
- The **Changelog** tab only lists changes for mods your role can use.

---

## Keybinds

Go to **Menu Settings → Keybinds**. Click a key box, then press the key (or extra mouse button) you
want. Esc cancels.

- Only the mods your role can use are listed.
- The menu key can be changed but never removed, so you can't lock yourself out.
  **Reset all keybinds** puts it back to F1.
- Hotkeys don't fire while you're typing, and a small popup shows ON/OFF when one fires.
- Your keybinds are saved between launches.

---

## Gnome Customization

**Player tab → Gnome Customization** opens its own window. Everything you change applies and
saves straight away - there's no Save button.

- **Gnome tab:** pick a part on the left, then a colour on the right. Your outfit is split into
  **Hat, Robe, Sleeves** and **Belt and Boots** so you can colour them one by one, or all at once
  with **All clothes**. Skin and beard get their own palettes. One click on a **Preset** dresses
  the whole gnome.
- **Items tab:** every item on your gnome, equipped ones first. Pick one and the preview shows
  just that item, so you can colour each of its parts separately.
- **Effects:** fine-tune with hue / saturation / brightness, or make a part **Solid**,
  **Rainbow** or **Glow**.
- **Size** (35-200%): your gnome grows or shrinks, your camera follows your gnome's head, and your
  hitbox, speed and jump grow and shrink with it. Size resets to 100% each launch. Your colours
  are kept.
- The middle of the window shows your gnome live. Drag it (or use **Spin**) to see every side, and
  scroll to zoom.
- **Undo changes** goes back to how it looked when you opened the window.
  **Custom look: ON/OFF** switches to the normal gnome without losing anything.
  **Reset Gnome** clears your look completely.

**Who sees it:** everyone in your lobby who also has the mod sees your colours, size and Middle
Finger on your gnome, live, and you see theirs. Players without the mod see the normal gnome.

---

## Spectator Mode *(Admin)*

**Player tab → Spectator Mode** puts your camera on a teammate. Use **Next player** to switch.
A panel at the top of the screen shows who you're watching, their health and what they're carrying.

- **3rd person** (the default) is a free-look camera behind them: move the mouse to look around
  and scroll to zoom. Switch to **1st person** to see through their eyes.
- With **Hide me: ON** (the default), your gnome is tucked out of sight for everyone while you
  watch, and put back exactly where it was when you stop.

---

## Updates

**The mod updates itself.** At launch (and every 30 minutes after that) it checks for a new
version. If there is one, it downloads it in the background, checks that it's the official
release, and installs it. The menu then says **"ready - restart the game"**, and the new version
runs from your next launch. Nothing changes in the middle of a game.

- Don't want automatic updates? Turn off **Install updates automatically** in the Info tab.
  You'll get an **Update available** notice with a **Download** button instead. Grab the new
  `GnomeCheats.dll` from the [releases page](../../releases/latest) and replace the old one in
  your `plugins` folder.
- On **v1.4.0 or older**? Those versions can't update themselves. Download the
  [latest release](../../releases/latest) by hand once - after that it's automatic.

---

## Found a bug?

Press **Report a Bug** (Info tab or Changelog tab). It copies a short report to your clipboard -
the mod and game version and any errors the mod ran into, nothing personal - and opens our
Discord server. Paste the report in the bug reports channel and say what happened.

---

## Notes

- The owner can turn your key off at any time. You then drop back to the Free Version.
- Keep this to private games with friends, not public lobbies with strangers. Mod users share
  their looks through the Steam lobby, so anyone in the lobby with the right tools could tell
  you're running a mod.
