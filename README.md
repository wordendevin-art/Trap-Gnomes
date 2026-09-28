# Trap Gnomes V1

A private mod menu for Burglin' Gnomes. The **Free Version** needs no key; a license key from
the owner unlocks the stronger mods.

> **This is not open-source software.** Personal use only. Do not re-upload the mod or pass your
> key to anyone. See `LICENSE.txt`.

---

## Install

You need the game with **BepInEx** already installed.

1. Download **`GnomeCheats.dll`** from the [latest release](../../releases/latest).
2. Put it in your game's `BepInEx\plugins` folder:
   ```
   Steam\steamapps\common\Burglin' Gnomes\BepInEx\plugins\
   ```
3. Start the game.
4. Press **F1** (the default menu key — you can change it later, see [Keybinds](#keybinds)).
   The menu opens on the **Free Version** — no key needed.
5. Got a key? **Info tab → Enter license key**, paste it and click **Activate**.
   You only do this once; it's remembered after that.

> Your mouse is free while the menu is open, so there's no need to pause the game. Keys and
> clicks don't move your gnome while it's open, so you can type in it safely.

---

## Roles

Everyone starts on the Free Version. Keys are handed out by the owner and unlock a higher role:

| Role | What you get |
|------|--------------|
| **Free Version** (no key) | FOV, Third Person, Performance Mode, Middle Finger, basic Gnome Customization, player list, keybinds |
| **Customer** | the above + God Mode, Infinite Stamina, Unbreakable Limbs, Silent Movement, Immunity, NPC/Item ESP, On-Screen Info, full Gnome Customization (items, effects, Size) |
| **Admin** | everything (Speed, No Clip, Moon Boots, Spectator Mode, Player ESP/Info, Player Inventory ESP, Teleport, spawners, Host tools) |

If a feature shows `[Admin]` or `[Customer]` next to it and is greyed out, your key's role
doesn't include it yet — ask the owner about an upgrade.

---

## Keybinds

**Menu Settings → Keybinds.** Click a key box, then press the key (or extra mouse button) you
want. Esc cancels.

- Only the mods your role can use are listed.
- The menu key can be changed but never removed, so you can't lock yourself out.
  **Reset all keybinds** puts it back to F1.
- Hotkeys don't fire while you're typing, and a small popup shows ON/OFF when one does.
- Your keybinds are saved between launches.

---

## Gnome Customization

**Player tab → Gnome Customization** opens its own window. Everything you change applies
and saves straight away — there's no Save button.

- **Gnome tab:** pick a part on the left, then a colour on the right. Your outfit is split into
  **Hat, Robe, Sleeves** and **Belt and Boots** to colour one by one, or all at once with
  **All clothes**. Skin and beard get their own palettes. One click on a **Preset** dresses the
  whole gnome.
- **Items tab:** every item on your gnome, equipped ones first. Pick one and the preview shows that
  item on its own, in its current colours; colour each of its parts separately.
- **Effects:** fine-tune with hue/saturation/brightness, or make a part **Solid**, **Rainbow** or **Glow**.
- **Size** (50–200%) makes your gnome grow or shrink, and your camera moves with your gnome's head
  in first and third person. Your hitbox grows and shrinks with it. Size starts at 100% each
  time you launch the game; your colours are kept.
- Your view stays as it is — first or third person — while you customize.
- The middle shows your gnome live. Drag it (or use **Spin**) to see it from every side; scroll to zoom.
- **Undo changes** puts back how it looked when you opened the window. **Custom look: ON/OFF**
  switches to the normal gnome without losing anything. **Reset Gnome** clears your look completely.

| | Free Version | Customer and up |
|---|---|---|
| Palette colours on clothes, skin, beard | ✓ | ✓ |
| Presets | 3 | all 9 |
| Fine-tune sliders, Solid / Rainbow / Glow, clothes areas | | ✓ |
| Items tab, Size | | ✓ |

**Who sees it:** everyone in your lobby who also has the mod sees your look — colours, size
and your Middle Finger — on your gnome, and you see theirs, live as you edit. It only ever
changes the gnome of the person who set it. Players without the mod see the normal gnome.

---

## Spectator Mode

**Player tab → Spectator Mode** puts your camera on a teammate, like when you're dead (**Next
player** switches). A panel at the top of the screen shows who you're watching, their health and
what they're carrying.

- **3rd person** (default): a free-look camera behind them — move the mouse to look around, scroll
  to zoom. Click it to switch to **1st person** (through their eyes).
- Only your camera moves — nobody can see it. With **Hide me: ON** (the default) your gnome is also
  tucked away out of sight for everyone while you watch (the panel says **Hidden**), and put back
  exactly where it was when you stop.
- Both choices are remembered.

---

## Updates

The mod updates itself. When a newer version is out it downloads it in the background,
checks that it's the official release, and installs it - the menu then says
**"ready - restart the game"**, and the new version runs from your next launch.

Don't want that? Turn off **Install updates automatically** in the Info tab. You'll get a green
**"Update available"** notice with a **Download** button instead - grab the new
`GnomeCheats.dll` from the releases page and replace the old one in your `plugins` folder.

On v1.4.0 or older? Download v1.4.1 by hand once - after that it's automatic.

---

## Found a bug?

Press **Report a Bug** (Info tab or Changelog tab). It copies a short report to your clipboard -
the mod and game version and any errors the mod ran into, nothing personal - and opens our
Discord server. Join, then paste the report in the bug reports channel and say what happened.

The **Changelog** tab lists what changed in each version. If you're on an old version, the mod
will remind you to update - older versions may have bugs that are already fixed.

---

## Notes

- Your key can be turned off by the owner at any time.
- Don't run this in public lobbies with strangers — it's meant for private games with friends.
  Sharing your look with other mod users works through the Steam lobby, so anyone in the lobby
  with the right tools could tell you're running a mod.
