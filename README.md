# 🏴‍☠️ BlackJoker Luffy Fire Glass

![BetterDiscord](https://img.shields.io/badge/BetterDiscord-Theme-5865F2?style=flat-square) ![Version](https://img.shields.io/badge/version-1.2.1-E54835?style=flat-square) ![CSS](https://img.shields.io/badge/CSS-only-222?style=flat-square)

A pirate-inspired theme for BetterDiscord, with red highlights and translucent panels that leave room for your own wallpaper. 🔥

## ✨ Features

- 🖤 Dark glass channel, chat and member panels
- 🔥 Red accents and selected-channel highlights
- 🖼️ Custom wallpaper setting
- 💬 Transparent chat view with darker controls for legibility
- ⚡ Pure CSS; no additional plugin dependencies

## 📸 Preview

Add a screenshot under `screenshots/` and link it here. Screenshots should not be assumed to be included in the theme package.

## 📥 Installation

1. Install [BetterDiscord](https://betterdiscord.app/).
2. Download [`BlackJoker-Luffy-Fire-Glass.theme.css`](./BlackJoker-Luffy-Fire-Glass.theme.css).
3. Open **Discord → Settings → BetterDiscord → Themes → Open Themes Folder**.
4. Copy the `.theme.css` file into that folder and enable it.
5. Disable conflicting Custom CSS if colors or transparency look wrong.

## 🖼️ Use your own wallpaper

Open the `.theme.css` file in a text editor. Near the top, look for:

```css
--bj-wallpaper: linear-gradient(125deg, #09070c 0%, #300609 47%, #611809 72%, #120911 100%);
```

Replace that entire declaration with a link to an image **you have permission to use**:

```css
--bj-wallpaper: url("https://example.com/your-wallpaper.jpg");
```

The default is a dark red gradient so the theme works without an external image. Some image hosts block hotlinking; use a reliable direct HTTPS image URL. Local `file:///` images may be blocked in Discord.

For personal use, you can also locally embed an image as a data URI, but do not commit copyrighted artwork to this repository without permission.

## 🎨 Other settings

In `:root` you can adjust `--bj-fire`, `--bj-border`, `--bj-pane`, and `--bj-pane-strong` for the colors and opacity.

## 🛠️ Notes

- Discord updates can break theme selectors. Report rendering bugs under **Issues** and include your BetterDiscord/Discord version.
- The theme is unofficial and not affiliated with Discord, BetterDiscord, or One Piece rights holders.
- **No One Piece artwork is bundled in this release.**

## 💜 Credits

Made by **BlackJoker Studio**.
