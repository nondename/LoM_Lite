# LoM Lite

Lightweight managed Minecraft profile for Legends of Medieval Launcher.

- Minecraft: 1.20.1
- Forge: 47.4.22
- Java: 17
- Managed profile ID: `legends-of-medieval-lite`
- Pack version: 0.2.0

## Distribution

`distribution.json` contains the launcher-managed Lite manifest.

Lite intentionally ships only its selected mods, required dependencies and managed configs. It does not inherit the full Legends of Medieval modpack, shaders or resource packs.

Selected custom LoM components include the LoM skin loader, Legendary Tabs, InkSpellBooks LoM Addon, the LoM Map Atlases build and the modified GlitchCore used with Serene Seasons.

The 0.2.0 manifest pins source artifacts to an immutable Legends of Medieval repository revision so later changes to the main pack do not silently alter Lite.
