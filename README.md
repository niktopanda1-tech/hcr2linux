
````markdown
# Hill Climb Racing 2 for Linux
#PLS JOIN discord.gg/YD5YUHCzD
An unofficial experimental Linux x86_64 launcher for HCR2 1.76.1 (743).
Starting currency is granted once. Restarting the game does not restore spent currency.

## Installation on Arch Linux

1. Open the **Releases** section.
2. Download **HCR2_Linux_With_XAPK.zip**.
3. Extract the archive and open the **HCR2-Linux** folder.
4. Open a terminal in that folder.
5. Install the dependencies:

```bash
sudo pacman -S --needed python glfw libglvnd cairo freetype2 curl
```

6. Launch the game:

```bash
bash launch.sh
```

The XAPK is already included. The first launch automatically prepares the game resources.

To start in fullscreen:

```bash
bash launch.sh --fullscreen
```

## Controls

| Key | Action |
|---|---|
| D | Right pedal — accelerate |
| A | Left pedal — brake |
| Space | Both pedals simultaneously |
| S | Vehicle ability, when available |
| F11 | Toggle fullscreen |
| Mouse | Navigate menus |

Pedal and ability bindings can be changed in `controls.json`.

## Save Files

Save files are stored in `game/save/`.
A backup is created in `game/backups/` before progress modifications are applied.

## Limitations

- Audio is not implemented yet.
- Online features and network game modes are unavailable.
- Use the **Adventure** section.
- Compatibility with every Linux configuration has not been verified.

The original game and its assets belong to Fingersoft and their respective owners.
````
