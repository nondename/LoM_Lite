# LoM: disable MineColonies natural settlements (Forge 1.20.1)

Forge 47.4.22-compatible port of the **resource-based mechanism** from
[Hamderber/disableminecoloniesabandonedstructures](https://github.com/Hamderber/disableminecoloniesabandonedstructures) (MIT).

The original mod overrides `minecolonies:empty_colony` structure set to an empty list.
This addon packages overrides for **both** `minecolonies:empty_colony` and
`minecolonies:empty_nether_colony` in the **mod JAR**, bypassing Paxi pack loading.

Not a replacement for MineColonies. Player-placed colonies and workers remain.
New terrain only; does not retroactively remove already generated structures.

Test via `/datapack list enabled` (mod resource packs generally show as mod packs),
then create a new world. In the resource pack stack, the addon must win over MineColonies
for `data/minecolonies/worldgen/structure_set/empty_colony.json`.

No prebuilt NeoForge JAR is redistributed. Forge mod assembled from source.
