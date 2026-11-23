# Rolleys Plugin Market

Official default Plugin Market repository for **Rolleys Android** (`https://github.com/Towartz/Rolleys_Plugin`).

## Zero-Config Drop-In Publishing

No `market.json` or manual index edits required:
1. Drop any valid Rolleys `.json` plugin file into **`plugins/`** (or a subfolder like `plugins/tools/`).
2. Rolleys Android automatically scans `plugins/` on refresh and lists every valid plugin by its JSON `id`, `name`, `description`, `version`, and `author`.

## Install in Rolleys Android

1. Open **Plugins** -> tap the **Market** icon (`Storefront`).
2. `Towartz/Rolleys_Plugin` is pre-configured as the default market source.
3. Tap **Install** (or **Update**) on any plugin, review permissions, and enable it.

## Also Supports Any Other Provider

You can add your own GitHub repo (`owner/repo`), GitHub Gist, Pastebin, Rentry, dpaste, Hastebin, `paste.rs`, GitLab, Codeberg, Bitbucket, or any raw HTTPS JSON/text URL.
