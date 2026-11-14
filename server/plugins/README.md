# DonutSMP-Style Server Plugins Folder

This folder is structured for a **DonutSMP-like** Paper / Purpur / Folia server.

Drop your `.jar` plugin files into the correct category folders (or just into the root `plugins/` if you prefer the classic layout).

---

## Recommended Folder Structure

```
server/
├── plugins/                          ← Put all .jar files here (or use subfolders)
│   ├── core/                        # Essential dependencies + Via*
│   ├── economy/                     # Money, sell, shop, worth, pay
│   ├── player/                      # Homes, teams, TPA, profiles
│   ├── teleport/                    # RTP, warps, portals
│   ├── pvp/                         # Combat, bounties, duels, safezones
│   ├── crates/                      # Crates & keys
│   ├── marketplace/                 # Auction House, Orders, Billford
│   ├── staff/                       # Staff mode, punishments, vanish
│   ├── visuals/                     # Scoreboard, tablist, holograms, cosmetics
│   ├── world/                       # Multiverse, claims, spawn protection
│   └── utility/                     # Voice chat, misc QoL plugins
├── config/                          # Optional: backup of important configs
└── docs/
    └── plugin-list.md                # Full recommended list
```

> **Note:** Most Paper servers expect `.jar` files directly in `plugins/`.  
> The subfolders above are for organization only (you can move jars into the root `plugins/` folder when starting the server).

---

## Core Plugins (Install First)

| Plugin              | Purpose                          | Required? |
|---------------------|----------------------------------|-----------|
| **PlaceholderAPI**  | Placeholders for almost everything | Yes      |
| **ProtocolLib**     | Packet handling                  | Yes      |
| **Vault**           | Economy API                      | Yes      |
| **LuckPerms**       | Permissions                      | Highly recommended |
| **ViaVersion**      | Newer clients can join           | Recommended |
| **ViaBackwards**    | Older clients can join           | Recommended |
| **spark**           | Performance monitoring           | Recommended |

---

## Voice Chat

| Plugin                  | Purpose                     | Notes |
|-------------------------|-----------------------------|-------|
| **Simple Voice Chat**   | Proximity voice chat        | Place in `utility/`. Players also need the client mod. |

---

## Feature Categories

### Economy & Selling
- Economy provider (EssentialsX Economy, or custom like UltraPAY / PerfPay)
- Sell / Worth plugin (DonutSell, PerfSell, etc.)
- Shop GUI

### Player Systems
- Homes (DonutHomes / PerfHomes / HuskHomes)
- Teams / Clans (DonutTeams / PerfTeams)
- TPA system
- Private messages

### Teleportation
- RTP (Random Teleport) with GUI (DonutRTP style)
- Warps
- Spawn / AFK areas

### Marketplace
- Auction House
- Player Orders board
- Optional: Billford rotating trades

### PvP & Combat
- Combat logger / Combat tag
- Bounties
- Safezone protection
- Optional: Duels / FFA arenas

### Crates & Rewards
- Crates system with virtual keys
- Keyall / daily rewards

### Staff Tools
- Staff mode + Vanish
- Punishments (AdvancedBan, LiteBans, or built-in)
- Reports / Helpop
- Invsee / ECsee

---

## Quick Start Recommendation

**Minimal DonutSMP-like stack:**
1. PlaceholderAPI + ProtocolLib + Vault + LuckPerms
2. ViaVersion + ViaBackwards
3. Simple Voice Chat
4. A good Economy + Sell/Worth plugin
5. Homes
6. Teams
7. RTP
8. Auction House
9. Crates
10. Combat + Bounty

**All-in-one alternative:**  
Many people use **UltimateDonutSMP** (free, open source) which packs most of the above into one plugin.

---

## How to use this folder

1. Download the plugin `.jar` files you want.
2. Place them in `server/plugins/` (or the category subfolders for organization).
3. Start the server once so configs generate.
4. Edit the generated config folders (they will appear next to the jars).
5. Restart or use `/reload` where supported.

### Suggested placement
- **ViaVersion** + **ViaBackwards** → `core/`
- **Simple Voice Chat** → `utility/`

Happy server building! 🍩
