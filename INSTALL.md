# Installing the launcher patch

This fork ships a patched launcher only. The game, `bb-probe.exe`, DLLs and all game files come
from the official bbport 1.9.7 package.

1. Download and unpack the official **1.9.7** Windows package from
   [Supermedo/bloodborne_pc releases](https://github.com/Supermedo/bloodborne_pc/releases).
2. Download `bbport-hunters-dream-launcher-*.zip` from
   [this fork's releases](https://github.com/Klonty/bloodborne-pc-hunters-dream/releases).
3. Close the launcher and the game.
4. Extract the patch into the folder that contains `Bloodborne.exe`, replacing
   `Bloodborne.exe` and the `_internal` folder.
5. Start `Bloodborne.exe`. In **Online play** the co-op pool now defaults to
   **The Hunter's Dream (recommended)**. Press **Sign in with Discord** and approve the code on
   [thehuntersdream.com](https://thehuntersdream.com).

SuperMedo Server remains available as a second choice. `BB_HUNTERS_DREAM=0` restores the
upstream behaviour and hides The Hunter's Dream.

## What the patch contains

- `Bloodborne.exe` and `_internal/` — the launcher rebuilt from this repository's source.
- `LICENSE`, `FORK-NOTICE.md`, this file.

It does not contain game files, `bb-probe.exe`, or any DLL from the official package.

## Updates

The fork disables the launcher's built-in updater: upstream releases would replace the patched
launcher with the stock one. To update, download a newer launcher patch from this fork.

## Uninstalling

Replace `Bloodborne.exe` and `_internal/` with the files from the official package again, or
install the official package over the same folder.
