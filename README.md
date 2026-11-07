# Clock Tower 3 Recompiled

**Native PC port of Clock Tower 3 (PS2, USA SLUS-20633) — by ThyHeroOfTime**

The original PlayStation 2 program is statically recompiled from MIPS R5900 code into C++ and built
for 64-bit Windows, with native replacements for the PS2 kernel, sound processor, graphics and movie
hardware. It is not an emulator. **No game files are included: you need your own legally obtained
Clock Tower 3 (USA) disc image.**

> ⚠️ **Early access.** The game boots, plays its movies and is playable, but there are known bugs (see
> below). Please report anything you find — that is how it gets fixed.

## Install

**With Quiver Launcher:** find *Clock Tower 3 Recompiled*, install, and Quiver keeps it updated.

**Manually:** download `ClockTower3Recompiled-<version>-win-x64.zip` from
[Releases](../../releases), unzip it anywhere, run `ClockTower3Recompiled.exe`.

Then, in the launcher:
1. **Setup** → *Select Game ISO* → choose your `Clock Tower 3 (USA).iso`.
2. Choose an install folder (any drive, ~4.5 GB free).
3. **Unpack Game**, then **Start Game**. Steps 1–3 are needed once.

Requirements: Windows 10/11 64-bit, a Direct3D 11 graphics card. Saves stay in your install folder
and survive updates. PCSX2 memory-card saves can be brought over in *Settings → Import PS2 Save*.

## In game
- **F1** — PC Settings (display mode, render resolution up to 4×, texture filtering, sharpening, VSync, volume).
- **F9** — frame capture for bug reports.
- **F11** / Alt+Enter — fullscreen.

## Known issues (early access)
- Walls/floors very close to the camera can disappear (being investigated in the vector-unit emulation).
- Some shadows are drawn incorrectly.
- A door movie early in the game may freeze; the title-screen demo may show a black screen.
- Very demanding rooms can run below 30 fps on slower CPUs.

## Reporting bugs
Use **About → Report a Bug** in the launcher, or [open an issue](../../issues/new/choose).
Please attach **`ct3_log.txt`** from your install folder (*About → Open Log Folder*) and say what
you were doing. A screenshot or F9 capture helps a lot.

## Legal
Unofficial fan project, not affiliated with or endorsed by Capcom or Sunsoft. Clock Tower 3 and all
game content belong to their rights holders. This repository and its releases contain no disc data.
Third-party components: SDL2 (zlib), miniaudio (MIT-0 / public domain), Cinzel and Cormorant Garamond
fonts (SIL OFL) — licences in the `Licenses` folder of every release.
