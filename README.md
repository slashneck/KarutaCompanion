<p align="center">
  <img src="docs/banner.png" alt="Karuta Companion" width="100%">
</p>

<p align="center">
  <a href="https://github.com/slashneck/KarutaCompanion/releases/latest"><img src="https://img.shields.io/github/v/release/slashneck/KarutaCompanion?style=flat-square&label=release&color=8b5cf6&labelColor=161018" alt="Latest release"></a>
  <a href="https://github.com/slashneck/KarutaCompanion/releases"><img src="https://img.shields.io/github/downloads/slashneck/KarutaCompanion/total?style=flat-square&color=8b5cf6&labelColor=161018" alt="Downloads"></a>
  <img src="https://img.shields.io/badge/status-early%20access-8b5cf6?style=flat-square&labelColor=161018" alt="Early access">
  <img src="https://img.shields.io/badge/Windows-10%20%26%2011-f4f2fa?style=flat-square&labelColor=161018" alt="Windows 10 and 11">
</p>

<p align="center">
  <a href="https://github.com/slashneck/KarutaCompanion/releases/latest"><b>Download for Windows</b></a>
  &nbsp;&nbsp;|&nbsp;&nbsp;
  <a href="#what-it-does">What it does</a>
  &nbsp;&nbsp;|&nbsp;&nbsp;
  <a href="#what-it-never-does">What it never does</a>
  &nbsp;&nbsp;|&nbsp;&nbsp;
  <a href="#updates">Updates</a>
</p>

---

**Karuta Companion** is a desktop app for your [Karuta](https://karuta.io/) card collection. You export your cards in Discord with `k!sheet`, import the file once, and then browse, sort and plan with your whole collection in front of you — with each card rebuilt as closely as we can to how it looks in game.

> **Early access.** Karuta Companion is still being built. Things will change, and a few are still rough (dyes and morphs aren't drawn yet). It updates itself as new versions land.

## Download

1. Grab the latest **`KarutaCompanionSetup-*.exe`** from the [**releases page**](https://github.com/slashneck/KarutaCompanion/releases/latest).
2. Run it. It installs for your account only — **no admin prompt**.
3. Windows may show a SmartScreen warning because the app isn't signed yet: click **More info → Run anyway**.

Your collection and settings are kept in `%AppData%\com.karutacompanion.app`, separate from the program, so updates and uninstalling never touch them.

## What it does

- **Your collection, accurately.** Import your `k!sheet` and see every card, rebuilt from its artwork, frame, quality and text.
- **Automatic artwork.** Card art and frames are fetched from Karuta's own image server as needed and cached on your PC.
- **Frame tester** *(early access)* — try any of Karuta's frames on your own cards.
- **Burn pile** — tag the cards you plan to burn and keep them in one place.
- **Wishlist** — paste your `k!wl` pages (or screenshot them) and see what you own, plus your most-wished cards.
- **Shop** — put cards up for trade, set prices, and copy a ready-made ad for Discord.
- **Command list** — buttons copy the right `k!` command for you to paste in Discord.

## What it never does

Karuta Companion is a **companion**, not a bot. Everything you do in Discord is done by **you**.

- It **never connects to Discord**, logs in, or asks for your account or token.
- It **never** plays, drops, grabs, trades, or sends messages for you.
- It doesn't automate anything or touch Karuta's economy. It only reads the spreadsheet file you give it and puts commands in a list for you to paste yourself.

The card images in the app are **recreations** made as closely as we can — not the images Karuta shows in game — so frames, dyes, wear and text can differ. Use `k!view` in Discord to see the real card.

## Updates

The app checks here for new versions, downloads them in the background, and installs them when you close it (or right away from **Settings → Updates**). You can turn automatic updates off there. Every download is verified against its checksum before anything is changed.

---

<sub>Not affiliated with or endorsed by Karuta or Discord. Character art belongs to its respective owners and is only shown on your own PC. This repository hosts the Windows download and updates only; Karuta Companion is closed source.</sub>
