# AAAI Resource Packs

Optional resource packs for the **Island SMP** Minecraft server (Java Edition). They are downloaded by the game from the release links below and toggled by players with `/rp` on the server. Every pack is optional: the server works without them and uses only vanilla textures.

| Pack | Folder | What it does |
|---|---|---|
| Tomes | `tome/` (Java), `tome-bedrock/` (Bedrock) | XP Tome (purple) and Ancient Tome (isometric rune book) textures (MIT) |
| Mob (Pegasus) Bedrock | `mob-bedrock/` | Bedrock-only: overrides the horse client entity (name / leather-armour keyed) with the pearl Pegasus coat and wings; based on "Pegasus" by DibArts (**CC BY 4.0**) |
| Mob (Pegasus, Java) | `pegasus/` | Coat + premium saddle for the Pegasus mount (equipment assets `aaaimob:pegasus_coat`, `aaaimob:pegasus_saddle`); the coat is based on "Pegasus" by DibArts (**CC BY 4.0**, own licence file in the folder) |
| Goblin Trader | `goblin-trader/` | 3D goblin head (green) / horned vein goblin head (red) worn by the goblin traders (1.1.0: isometric GUI view for menu icons); moss / nether wart block item overrides keyed on `custom_model_data`, original art (MIT) |
| Background Music | `background-music/` (Java), `background-music-bedrock/` (Bedrock) | Optional music for server events; first track: the throne boss fight ("Battle of the Ages" by NoCopyrightSound633, Pixabay Content License, see the pack's `CREDITS.txt`); stereo Ogg, sound event `aaai:music.throne_boss` |
| Original Content | `content/` (Java), `content-bedrock/` (Bedrock) | Original 16x16/32x32 pixel-art item textures for the server's own items: Skill XP Bottles 1k-500k, Seeker Eye, Route Fragment, Heavy Core Fragment, Disarm Slime, Immortal Heart, Elytra Fragment, Salty Bedrock, Horcrux (MIT, made for this server). The glass-pane fix for Bedrock now lives in the Menu pack (`menu-bedrock/`); the Content Bedrock pack (`content-bedrock/`, 1.3.0) only carries the item textures |
| Menu | `menu/` (Java), `menu-bedrock/` (Bedrock) | Flat 32x32 icons for the server's chest menus (travel, shop, bank, TPA, settings ...) via `custom_model_data: menu_*`, plus flat glass-pane fillers on Bedrock; all art is original (MIT). First public release 1.0.0 |
| HUD | `hud/` (Java) | RPG-style health + armour bar drawn from a font, vanilla hearts/armour hidden; original art (MIT). First public release 1.0.0 (Bedrock bar tiles ship inside the Menu Bedrock pack) |
| Advanced Netherite | `advanced-netherite/` | Textures/models for the AAAI-RM-AdvanceNetherite tiers (**GPL-3.0**, own licence file in the folder) |
| Advanced Netherite (Bedrock) | `advanced-netherite-bedrock/` | Native Bedrock pack + Geyser mapping for those items (**GPL-3.0**) |

Each pack is released separately (tag `<pack>-<version>`, e.g. `xp-tome-1.0.0`) with its own zip. A released zip is never edited; a change means a new release.

Build a zip: zip the pack folder's contents (no top-level folder, without its README). See `CREDITS.md` for texture credits.
