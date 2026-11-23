# Rolleys Plugin Market

Official default Plugin Market repository for **Rolleys Android** (`https://github.com/Towartz/Rolleys_Plugin`).

## Install in Rolleys Android

1. Open **Plugins** -> tap the **Market** icon (`Storefront`).
2. `Towartz/Rolleys_Plugin` is pre-configured as the default market source (or add `https://github.com/Towartz/Rolleys_Plugin` / `Towartz/Rolleys_Plugin`).
3. Tap **Install** (or **Update**) on any plugin below, then review its permissions and switch it on.

## Available Plugins

| ID | Name | Version | Author | Description |
|---|---|---|---|---|
| `rpg_addictive_adventure` | **RPG Addictive Adventure** | `v1.0.0` | You | RPG WhatsApp adiktif: combo, crit/jackpot, boss raid, gacha senjata, daily streak, level-up. Bisa dipakai pemilik (fromMe) dan orang lain (sender). |
| `dmsg_plugin` | **DMSG Plugin** | `v1.0.0` | Owner | Delete Message (dmsg) and React Revocation Plugin (Command & 🗑️ Reaction) |
| `spr_dmsg_plugin` | **SPR & SPR2 Plugin** | `v1.0.0` | Owner | Stealth Private Relay (SPR), SPR2 with dmsg integration, and reaction delete |

## Adding Your Own Plugins or Alternative Markets

- See `market.json` for the catalog format (`plugins` array with `id`, `name`, `description`, `version`, `author`, and `url` or inline `rules`).
- Standalone `.json` files in `plugins/` are also auto-discovered when no manifest is present.
- Rolleys also supports **GitHub Gists**, **Pastebin**, **Rentry**, **dpaste**, **Hastebin**, **paste.rs**, **GitLab**, **Codeberg**, **Bitbucket**, and raw HTTPS JSON/text URLs.
