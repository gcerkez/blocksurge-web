# ComboCrush: Combo Blast ⚡

> **A GAME BY A JERRY — ENGINEERED FOR FUN**

Welcome to the official public web distribution of **ComboCrush: Combo Blast**!

## 🕹️ [PLAY ONLINE NOW (Web Browser)](https://gcerkez.github.io/combocrush-web/)

* Play immediately in your browser on iOS, Android, macOS, Windows, and Linux.
* No downloads or app store installation required.

## Build versions (tabs)

The landing page has a version switcher (driven by `versions.json`) so
several published builds of the game can be tried side by side:

| Tab | Folder | Source branch |
| --- | --- | --- |
| React Upgrade (default) | `/react-upgrade/` | `muse/react-framework-upgrade` — React UI, per-special board effects, combo fever |
| Classic (main) | `/main/` | `main` — the original vanilla TypeScript build |

The game repo is private, so the tabs switch between **published builds**,
not live private branches. To publish another branch build: deploy its
`dist/` into a new folder here with asset paths rewritten to `../assets/`
(all builds share the root `/assets/` folder), then add one entry to
`versions.json`.
