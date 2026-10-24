# ⚔️ D2 Survivors Save Editor v8.12 — Web

A browser-based save editor for **D2 Survivors**. Edit your save on desktop or mobile without installing a desktop application.

<p align="center">
  <a href="https://justplguy.github.io/D2-Survivors-Save-Editor-Web/">
    <img src="https://img.shields.io/badge/OPEN_EDITOR-Edit_Your_Save-CB9B36?style=for-the-badge" alt="Open Save Editor">
  </a>
  &nbsp;
  <a href="https://d2survivors.lol/" target="_blank" rel="noopener noreferrer">
    <img src="https://img.shields.io/badge/PLAY_NOW-Official_Game-6B4BA1?style=for-the-badge" alt="Play D2 Survivors">
  </a>
</p>

## 🌐 Open the Editor

**[Launch D2 Survivors Save Editor →](https://justplguy.github.io/D2-Survivors-Save-Editor-Web/)**

## ✨ Features in v8.12

- 💰 **Gold Editor** — change your character's gold.
- 🛡️ **Equipment Editor** — browse equipped items and inventory.
- ⚔️ **Item Modifiers** — edit supported item modifier values.
- 🧙 **Character Classes** — browse available character classes.
- 🏹 **Mercenary Equipment** — inspect and edit supported mercenary items.
- 🔮 **Skills & Passives** — search, filter, and stage supported skill-level changes.
- 🧪 **Belt & Potions** — edit four existing belt slots; choose Potion or Rejuvenation and set each quantity from 0 to 3.
- 🔍 **Change Preview** — review changes before exporting.
- 💾 **Save Export** — generate a modified save code and download it as a file.
- 📱 **Responsive Interface** — use the editor on desktop and mobile browsers.
- 🔒 **Local Processing** — save data is processed in your browser; the editor does not require uploading your save to a backend server.

Feature availability depends on the structure of the loaded save. The editor does not automatically create missing belt data.

## 🚀 How to Use

1. Open the [web editor](https://justplguy.github.io/D2-Survivors-Save-Editor-Web/).
2. Paste a save code beginning with `D2S1:` and click **Load Save Code**, or use **Load from File…**.
3. Select the character class you want to edit.
4. Use the tabs to edit gold, equipment, item modifiers, skills, or belt contents.
5. For potions, open **Belt & Potions**. For each of the four slots, choose **Potion** or **Rejuvenation** and set the quantity from **0 to 3**. Set quantity to **0** to empty a slot.
6. Click **Apply Belt Changes** and confirm the summary. Belt changes are held in the editor until you generate the updated save.
7. Open **Preview & Export** and click **Preview Changes** to review the edits.
8. Click **Generate Save Code**, then copy the result or save it to a file.
9. Load the edited save into the game using the game's supported import method and verify the result.

### 🧪 Potion Editing Notes

- Select a character class before opening the belt editor.
- The editor needs compatible belt data already present in the save. It will not create a missing belt automatically.
- Each of the four visible slots supports `potion` or `rejuvenation` with a quantity from 0 to 3.
- If the save contains an unexpected belt structure, editing is disabled for safety.
- The game may enforce its own stack limits. Always inspect the result in-game.

## ⚠️ Important: Leaderboards

**Editing a save may flag your character. Runs made with an edited character will not count toward leaderboards.** Use the editor at your own discretion. If leaderboard participation matters to you, keep a separate unmodified character/save.

Always keep an untouched backup of your original save. Test edits on a copy first, especially after modifying skills or belt contents. Incorrect or unsupported changes may cause unexpected results or prevent a save from loading correctly.

## 🛠️ Technology

The web editor uses HTML, CSS, and JavaScript, plus browser compression/decompression APIs for the `D2S1:` save format. It is designed to run as a static website through GitHub Pages.

## 👨‍💻 Developer & Socials

Created by **Just a Polish Guy**.

- 🌐 **Web Editor:** https://justplguy.github.io/D2-Survivors-Save-Editor-Web/
- 💻 **Web Editor Repository:** https://github.com/justPLguy/D2-Survivors-Save-Editor-Web
- 🖥️ **Windows Desktop Editor:** https://github.com/justPLguy/D2-Survivors-Save-Editor
- ▶️ **YouTube:** https://www.youtube.com/@justPLguy
- 📘 **Facebook:** https://www.facebook.com/justPLguy/
- 🧑‍💻 **GitHub Profile:** https://github.com/justPLguy

## ⚖️ Disclaimer

This is an unofficial, community-made tool. It is not affiliated with, endorsed by, or sponsored by the developers or publishers of D2 Survivors. Use it at your own risk and always keep a backup of your original save.

---

**Made for the D2 Survivors community ⚔️**
