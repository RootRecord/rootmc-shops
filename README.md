# RootMC-Shops

RootMC chest shops with dynamic price caps, /buy, and /sell

| Field | Value |
|-------|-------|
| **Folder / artifact** | `rootmc-shops` |
| **Version** | `1.7.0` |
| **Bukkit name** | `RootMC-Shops` |
| **Paper API** | `26.1` |
| **Author** | Root Record |
| **Website** | https://rootmc.net |
| **Main class** | `com.rootrecord.minecraft.rootmcshops.RootMcShopsPlugin` |

## Install

1. Install **[Root-Core](https://github.com/RootRecord/root-core)** first (license/cloud spine for the suite).
2. Download `rootmc-shops-1.7.0.jar` from [Releases](https://github.com/RootRecord/rootmc-shops/releases) or the [plugin catalog](https://rootmc.net/plugins/).
3. Remove any older `rootmc-shops-*.jar` from `plugins/`.
4. Drop the new jar into `plugins/` and restart (or use Root-Core suite updater when this plugin is on the public manifest).
5. Shared config and secrets live under `plugins/RootMC/` (not a per-plugin data folder unless documented otherwise).

### Dependencies

| Type | Plugins |
|------|---------|
| Hard depend | _none_ |
| Soft depend | RootMC, Vault, Root-Essentials, Root-Bonds |

## Configuration

Most RootMC plugins store operator YAML under `plugins/RootMC/`. After first boot, check that folder for new keys. Never commit live `cloud.yml` / database passwords to git.

## Build (monorepo)

Primary compilation is the RootMC Gradle workspace (not this standalone repo alone):

```bat
cd "D:\.1 Work Stations\RootMC\Plugin Building\Minecraft"
.\build-with-server-jdk.bat :plugins:rootmc-shops:jar
```

This repository mirrors sources for GitHub browsing and release distribution. It depends on `rootrecord-common` inside the monorepo.

## Commands (summary)

| Command | Description |
|---------|-------------|
| `/buy` | Buy from the cheapest in-stock player chest shop |
| `/sell` | Sell to the highest-paying player buy shop |
| `/shop` | Create and manage player chest shops |
| `/shops` | Browse all items a player has for sale |
| `/items` | Open your shops browse GUI |
| `/market` | Open the shops browse GUI |

Full command and permission tables: [docs/COMMANDS.md](docs/COMMANDS.md).

## Links

| Resource | URL |
|----------|-----|
| Website | https://rootmc.net |
| Plugin catalog | https://rootmc.net/plugins/ |
| This plugin page | https://rootmc.net/plugins/rootmc-shops/ |
| Suite wiki | https://rootmc.net/wiki/plugins/ |
| Player wiki | https://rootmc.net/wiki/player/ |
| Constitution | https://rootmc.net/wiki/constitution/ |
| Economy guide | https://rootmc.net/wiki/economy/ |
| Developer keys | https://rootmc.net/developer/keys/ |
| Manifest | https://rootmc.net/plugins/manifest.json |
| Play | `play.rootmc.net` |
| Live map | https://map.rootmc.net |
| API | https://api.rootmc.net |
| Discord | https://discord.gg/rFFQYrNaqS |
| GitHub (this repo) | https://github.com/RootRecord/rootmc-shops |
| Releases | https://github.com/RootRecord/rootmc-shops/releases |

**Discord:** RootMC community - join for support, announcements, and governance: https://discord.gg/rFFQYrNaqS


## Documentation in this repo

- [docs/COMMANDS.md](docs/COMMANDS.md) - commands and permissions from `plugin.yml`
- [docs/LINKS.md](docs/LINKS.md) - canonical RootMC web and Discord links
- [CHANGELOG.md](CHANGELOG.md) - version history seed

## License

Copyright Root Record. All rights reserved. Source is published for transparency; no license to copy, modify, or redistribute is granted unless Root Record provides written permission.

