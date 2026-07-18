README — Tails_Modgen_SuperHyper_v1
-----------------------------------
Author: ElijahAWilson3000-dot
Version: 1.0.0
Target: Sonic 3 AIR v26.03.28.0
License: Personal use only — do not redistribute without permission.

Contents:
- sprites/tails_super.png — PNG atlas for Super Tails (Standard animations) — TO BE ADDED
- sprites/tails_hyper.png — PNG atlas for Hyper Tails (Standard animations) — TO BE ADDED
- palette.act — Modgen-style palette (32 colors) — TO BE ADDED
- palette.txt — palette hex list
- frames.txt — frame coordinate map
- mod.json — mod metadata

Installation (S3AIR v26.03.28.0)
1. Backup:
   - Before installing: backup your S3AIR Mods folder and any original Tails sprites. Recommended: copy %APPDATA%\S3AIR\Mods to something like Mods-backup or copy the original sprites in the game folder to a safe place.
2. Install:
   - Place the extracted folder "TailsModgen_SuperHyper" into your S3AIR Mods folder:
     %APPDATA%\S3AIR\Mods\TailsModgen_SuperHyper\
   - After placing the folder, run Sonic 3 AIR. In the Mod Manager (if present) enable "Tails_Modgen_SuperHyper" or ensure the mod is higher priority than others replacing the same sprites.
   - If S3AIR uses direct file replacement (deploying into a mod-sprite folder), ensure sprites are in:
     %APPDATA%\S3AIR\Mods\TailsModgen_SuperHyper\sprites\tails_super.png
     %APPDATA%\S3AIR\Mods\TailsModgen_SuperHyper\sprites\tails_hyper.png
3. Verify:
   - Launch the game and collect rings/transform to Super and Hyper forms with Tails. Verify animation frames are aligned visually. If frames appear offset, you may need to adjust the frame offsets in the game's mod config or rename/lay out frames per your other installed mods.
4. Uninstall:
   - Remove the folder %APPDATA%\S3AIR\Mods\TailsModgen_SuperHyper\ or disable it in the Mod Manager.
   - Restore your backups if needed.

Troubleshooting:
- If the sprites look misaligned or cut off, confirm the game expects the exact sprite frame dimensions and pivot points listed in the atlas spec in frames.txt.
- If colors look wrong, import palette.act into your editor to ensure the PNG atlases use the same indexed palette (some mod loaders expect indexed PNGs).

Contact:
- For changes, color tweaks, or public releases contact ElijahAWilson3000-dot.
