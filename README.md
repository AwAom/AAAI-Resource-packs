# AAAI Resource Packs

Optional resource packs for the **Island SMP** Minecraft server (Java Edition). They are downloaded by the game from the release links below and toggled by players with `/rp` on the server. Every pack is optional: the server works without them and uses only vanilla textures.

| Pack | Folder | What it does |
|---|---|---|
| XP Tome | (moved) | Source now lives in `plugins-src/AAAI-Original-Tome/resourcepack` (XP Tome + Ancient Tome in one pack); release `xp-tome-1.0.0` stays online until the new pack is released |
| XP Tome (Bedrock) | (moved) | Source now lives in `plugins-src/AAAI-Original-Tome/resourcepack-bedrock` |

| Glass Pane Fix (Bedrock) | `glass-pane-fix-bedrock/` | Bedrock-only `.mcpack` + Geyser mapping: renamed glass panes (chest-GUI fillers) show as flat icons like Java instead of isometric blocks; points at Bedrock's own glass textures, no Mojang files bundled |
| Pegasus | `pegasus/` | Coat + premium saddle for the Pegasus mount (equipment assets `aaaimob:pegasus_coat`, `aaaimob:pegasus_saddle`); the coat is based on "Pegasus" by DibArts (**CC BY 4.0**, own licence file in the folder) |
| Goblin Trader | `goblin-trader/` | 3D goblin head (green) / horned vein goblin head (red) worn by the goblin traders; moss / nether wart block item overrides keyed on `custom_model_data`, original art (MIT) |
| Background Music | `background-music/` (Java), `background-music-bedrock/` (Bedrock) | Optional music for server events; first track: the throne boss fight ("Battle of the Ages" by NoCopyrightSound633, Pixabay Content License, see the pack's `CREDITS.txt`); stereo Ogg, sound event `aaai:music.throne_boss` |
| Advanced Netherite | `advanced-netherite/` | Textures/models for the AAAI-RM-AdvanceNetherite tiers (**GPL-3.0**, own licence file in the folder) |
| Advanced Netherite (Bedrock) | `advanced-netherite-bedrock/` | Native Bedrock pack + Geyser mapping for those items (**GPL-3.0**) |

Each pack is released separately (tag `<pack>-<version>`, e.g. `xp-tome-1.0.0`) with its own zip. A released zip is never edited; a change means a new release.

Build a zip: zip the pack folder's contents (no top-level folder, without its README). See `CREDITS.md` for texture credits.
