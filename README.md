# ⚔️ D2 Survivors Save Editor v10.9 — Web DEMO

A browser-based save editor for **D2 Survivors**. Load your save, change gold, see what Charsi's upgrades cost and check every item with the game's own rules. No installation needed: it runs in your browser.

🌍 **Available in:** English · Polski · Deutsch · Français · 한국어 · 简体中文

> ### 🆓 This is the DEMO — the full version is free on Discord
> The web editor is **v10.9 Demo** and works with D2 Survivors **2026.1102.1**. Gold & Charsi, items (view), stash, reference, save check and export work here.
> The Item Generator, Runewords, Charms, COPY ITEM, DESIGN, Skills and Belt editors are **previews**.
>
> **👉 Get the full version (free) on our Discord: https://discord.gg/nENzQxTh4**

<p align="center">
  <a href="https://justplguy.github.io/D2-Survivors-Save-Editor-Web/">
    <img src="https://img.shields.io/badge/OPEN_EDITOR-Edit_Your_Save-CB9B36?style=for-the-badge" alt="Open Save Editor">
  </a>
  &nbsp;
  <a href="https://d2survivors.lol/" target="_blank" rel="noopener noreferrer">
    <img src="https://img.shields.io/badge/PLAY_NOW-Official_Game-6B4BA1?style=for-the-badge" alt="Play D2 Survivors">
  </a>
</p>

---

<p align="center">
  <a href="https://discord.gg/nENzQxTh4">
    <img src="https://img.shields.io/badge/⚔️_JOIN_OUR_DISCORD-COMMUNITY-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Join the D2 Survivors Save Editor Discord Community">
  </a>
</p>

<h2 align="center">💜 Join the Community!</h2>

<p align="center">
  <strong>The full editor is free on Discord — and so are updates, help and item requests.</strong>
  <br>
  Connect with other players, share feedback, report issues, and follow project updates.
  <br><br>
  <a href="https://discord.gg/nENzQxTh4">
    <img src="https://img.shields.io/badge/💬_JOIN_THE_DISCORD-You're_Invited!-5865F2?style=for-the-badge" alt="Join Discord">
  </a>
</p>

---

## 🌐 Open the Editor

**[Launch D2 Survivors Save Editor →](https://justplguy.github.io/D2-Survivors-Save-Editor-Web/)**

Works with D2 Survivors **2026.1102.1** (saves from 2026.1101.1 load too). The first visit downloads about 12 MB (the editor's Python engine); after that your browser keeps it.

## 🚀 Choose Your Version

| Version | Description | Repository |
|---|---|---|
| 🌐 **Web** | Runs in your browser, nothing to install. | [Web Repository](https://github.com/justPLguy/D2-Survivors-Save-Editor-Web) |
| 💻 **EXE** | Standalone Windows application. | [EXE Repository](https://github.com/justPLguy/D2-Survivors-Save-Editor-EXE) |
| 🐍 **Python** | Run the Python script directly. | [Python Repository](https://github.com/justPLguy/D2-Survivors-Save-Editor-PY) |

## 🆕 New Since 10.5

- **10.9: weapon damage and 한국어 game texts.**
  - Weapon tooltips show **One-Hand / Two-Hand Damage** like the game (checked on 12,905 weapons), armor shows a **Base Defense** line.
  - In **한국어**, item names and stat lines can be shown exactly like D2 Survivors shows them: click the globe and pick your game's `resources\app.asar`. It is read in your browser and kept only there.
  - Full version: **Undo Last Change**, **Delete item**, **Copy with a new roll** from a chosen difficulty, and a **50-100% slider** for wanted rolls.
- **10.8: game 2026.1102.1 support.** The editor's tables come from the new game, and every check matches it again.
  - **Second weapon set:** Items & Modifiers shows both sets, e.g. "weapon (set I, in hand)" and "weapon (set II)", and Check save covers both.
  - Item tooltips show **Required Level** like the game.
  - Bul-Kathos' Sacred Charge, Famine and Naj's Circlet read as legit from both Diablo II and Resurrected files.
  - Full version: weapons and shields can go into either set; runewords on class bases keep the base's own property; Civerb's Cudgel and Trang-Oul's Claws come with their new fixed bonuses.
- **10.7: DEV GENERATION** (full version): any unique or set item with up to 48 stats of your choice, values 1-1000, for testing builds offline.
- **10.6: Set values directly beyond the game's ranges** (full version): any value the game still reads, up to ±1000, for testing builds offline.

Items made with DEV GENERATION or Set values directly are always **NOT LEGIT** (red border in the game; worn, they keep runs off the ladder).

## 🌍 Languages

🇬🇧 English (default) · 🇵🇱 Polski · 🇩🇪 Deutsch · 🇫🇷 Français · 🇰🇷 한국어 · 🇨🇳 简体中文

Click the **globe and flag** in the top-right corner. The page switches at once and your browser remembers the choice. Item, stat, affix, skill and class names stay exactly as the game shows them. In 한국어 you can load the game's own Korean texts from your D2 Survivors install (globe → `D2 Survivors app.asar`); nothing is bundled with the editor. Native speaker who spots an odd line? Send a screenshot and a better wording on our [Discord](https://discord.gg/nENzQxTh4).

## ✨ Features (v10.9)

| Feature | Web Demo (here) | Full version (Discord) |
|---|:---:|:---:|
| Load / export save codes (paste, .txt file or the game's `save.json`) | ✅ | ✅ |
| **Gold & Charsi**: gold editing, every Charsi upgrade with gold spent, next price and gold to max, "how much gold for…" calculator | ✅ | ✅ |
| Character & Mercenary: level, skills, mercenary | ✅ | ✅ |
| Items & Modifiers: tooltips like in the game (with Required Level and weapon damage), every stat with its range, **LEGIT / NOT LEGIT** status | 👁️ view | ✅ edit |
| **한국어 game texts** read from your own D2 Survivors files | ✅ | ✅ |
| **Undo Last Change**, **Delete item** | — | ✅ |
| **Both weapon sets** shown and checked | ✅ | ✅ |
| Stash: shared, personal and uniques tabs | ✅ | ✅ |
| Reference: every unique, set item and runeword with its ranges | ✅ | ✅ |
| Check save with the game's own rules (items + hero builds) | ✅ | ✅ |
| **Update notice**: shows the newest stable version | ✅ | ✅ |
| **Languages**: English, Polski, Deutsch, Français, 한국어, 简体中文 | ✅ | ✅ |
| **Item Generator**: unique, set, rare, magic and white items made exactly like the game makes them | 👁️ preview | ✅ |
| Rares with up to 6 chosen affixes | 👁️ preview | ✅ |
| **Runewords** and **Charms** generators | 👁️ preview | ✅ |
| **COPY ITEM** (exact copy or a new roll from a chosen difficulty) and **DESIGN** (ring, amulet and charm pictures) | 👁️ preview | ✅ |
| Re-roll items to the values you want (stays legit) | 👁️ preview | ✅ |
| Put weapons and shields into **either weapon set** | 👁️ preview | ✅ |
| **Set values directly**, also beyond the game's ranges (up to ±1000, Not legit) | 👁️ preview | ✅ |
| **DEV GENERATION**: unique or set items with up to 48 stats of your choice (Not legit) | 👁️ preview | ✅ |
| **Skills** editor, **Belt & Potions** editor | 👁️ preview | ✅ |

## 🧭 How to Use

1. Open the [web editor](https://justplguy.github.io/D2-Survivors-Save-Editor-Web/) and wait until it says **Ready**. Pick your language with the globe in the top-right corner if you like.
2. In the game open **SAVES** and copy your save code (it starts with `D2S1:`).
3. Paste it into the editor and click **Load Save Code** (or **Paste Clipboard** / **Load from File…**).
4. Pick your hero in the bar above the tabs.
5. Change your gold in **Gold & Charsi**, look through **Items & Modifiers**, **Stash** and **Reference**, or run **Check save**.
6. Open **Preview & Export**, check the change list and click **Generate Save Code**.
7. Click **Copy Code**, then paste the new code into the game's **SAVES** menu.

**Always keep a copy of your original save code before making changes.** Not sure where to start? Open the red **HOW TO USE EDITOR** tab inside the editor.

## 🔒 Your Data

- Your save is processed **in your browser**: it is not uploaded to load or edit it.
- After every export the editor asks whether you want to share the save code with the editor's database to help improve the editor. **Nothing is sent unless you click Yes.**
- The update notice only reads the newest version number from GitHub. Nothing is sent.
- Your language choice is kept only in your own browser. So are the Korean game texts, if you load them from your app.asar.

## ⚠️ Important: Leaderboards

**The editor is made for offline fun, not for the ladder.** The game marks edited saves, and runs made with an edited character do not count toward leaderboards. If the leaderboard matters to you, keep a separate untouched save.

## 🛠️ Technology

A static page on GitHub Pages: `index.html` (the page and its translations) plus `py.zip`, the editor's Python core (the same code and game tables as the Windows editor), run in the browser with [Pyodide](https://pyodide.org/). Both files must stay together in the repository; opening `index.html` straight from your disk will not work.

## 👨‍💻 Developer & Socials

Created by **Just a Polish Guy**.

- 💜 **Discord Community (full version):** https://discord.gg/nENzQxTh4
- 🌐 **Web Editor:** https://justplguy.github.io/D2-Survivors-Save-Editor-Web/
- 💻 **Windows EXE Editor:** https://github.com/justPLguy/D2-Survivors-Save-Editor-EXE
- 🐍 **Python Editor:** https://github.com/justPLguy/D2-Survivors-Save-Editor-PY
- ▶️ **YouTube:** https://www.youtube.com/@justPLguy
- 📘 **Facebook:** https://www.facebook.com/justPLguy/
- 🧑‍💻 **GitHub Profile:** https://github.com/justPLguy

## ⚖️ Disclaimer

This is an unofficial, community-made tool. It is not affiliated with, endorsed by, or sponsored by the developers or publishers of D2 Survivors. Use it at your own risk and always keep a backup of your original save.

---

**Made for the D2 Survivors community ⚔️**
