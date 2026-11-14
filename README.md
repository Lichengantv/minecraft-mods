# Minecraft Mods & Server Setup

A repository for Minecraft mods, modding resources, and **DonutSMP-style server** plugin organization.

## Structure

```
minecraft-mods/
├── mods/                 # Individual client/server mods
├── resources/            # Shared assets, textures, models
├── docs/                 # Documentation and guides
├── templates/            # Starter templates for new mods
└── server/
    └── plugins/           # DonutSMP-style plugin folder structure
        ├── core/
        ├── economy/
        ├── player/
        ├── teleport/
        ├── pvp/
        ├── crates/
        ├── marketplace/
        ├── staff/
        ├── visuals/
        ├── world/
        ├── utility/
        ├── README.md         # How to use the plugin folders
        └── plugin-list.md    # Recommended plugins list
```

## Server Plugins (DonutSMP Style)

Go to **[server/plugins/](server/plugins/)** for a ready-to-use folder structure and recommended plugin list for a DonutSMP-like server.

Key features covered:
- Economy, Sell, Worth, Shop
- Teams, Homes, TPA
- RTP (Random Teleport)
- Auction House & Orders
- Crates
- Combat / Bounties / Safezones
- Staff tools

## Client Modding

### Prerequisites
- Minecraft (Java Edition)
- A mod loader (Forge, Fabric, Quilt, or NeoForge)
- Java Development Kit (JDK 17 or 21 depending on version)

### Recommended Tools
- [IntelliJ IDEA](https://www.jetbrains.com/idea/) or VS Code
- [ModDevGradle](https://github.com/neoforged/ModDevGradle) or Fabric Loom
- [Minecraft Development](https://plugins.jetbrains.com/plugin/8327-minecraft-development) plugin for IntelliJ

## Useful Links

**Modding**
- [Fabric Documentation](https://docs.fabricmc.net/)
- [Forge Documentation](https://docs.minecraftforge.net/)
- [NeoForge Documentation](https://docs.neoforged.net/)
- [CurseForge](https://www.curseforge.com/minecraft/mc-mods)
- [Modrinth](https://modrinth.com/)

**Server**
- [Paper](https://papermc.io/)
- [Purpur](https://purpurmc.org/)
- [Folia](https://papermc.io/software/folia)
- [PlaceholderAPI](https://www.spigotmc.org/resources/placeholderapi.6245/)

---

Happy modding & server building! 🔧🎮🍩
