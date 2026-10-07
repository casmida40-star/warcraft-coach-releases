# Warcraft Coach — Windows releases

An independent, experimental companion for World of Warcraft: Forever. It watches a window the player explicitly shares, offers periodic spoken and written advice, and reviews recorded gameplay. It cannot control the game.

[Download the latest Windows release](https://github.com/casmida40-star/warcraft-coach-releases/releases/latest)

## Install

Download the `Warcraft-Coach-Setup-…-x64.exe` asset from the latest release and install it on Windows 10 or 11 (64-bit). Open **Settings → Set up Local AI** once. Setup downloads about 4.8 GB; allow at least 12 GB of free space. No API key, subscription or AI credits are required for Local AI. Performance depends on the PC; GPU and memory are shared with the game.

Select your class, specialization, race, role, level and coaching focuses. Choose the game window, inspect the preview, then consent and start coaching. Local sessions can run until stopped, with selectable analysis intervals. Closing the app stops its managed AI engine. Emergency screen-sharing stop: **Ctrl + Shift + F12**.

## Updates

From version 0.6, use **Settings → Update software → Check for updates**. The app connects to this repository, verifies the release signature, and offers a download. Installation happens only when the player chooses it. Installer size and SHA-256 are checked, then checked again before launch.

The feed is [latest.json](https://github.com/casmida40-star/warcraft-coach-releases/releases/latest/download/latest.json). For an offline update, put the installer and its matching `.update.json` in one folder and choose **Install downloaded update**. Earlier versions without this updater need the new installer once.

This repository contains releases and documentation. No player recordings, API keys or private signing keys belong here. The app’s Ed25519 update signature is separate from Windows Authenticode: the current installer is not Authenticode-signed.

## Knowledge and voices

The searchable library includes beta spell ranks, talent prerequisites, racials, reference-only Legacy summaries and selected patch/profession/dungeon facts. Relevant entries support live advice; dates and source builds are shown. Public spell/talent data refreshes hourly while the app is open, with a bundled offline fallback. Curated notes update through software releases.

Data adapted from **Chris Baldwin / [Talents Forever](https://talentsforever.com/)** under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Source artwork, Classic/demo fallback spells and placeholders are excluded. See the release’s knowledge notices for details and other sources.

Orc commander and Undead ranger presets use installed local Windows voices. They are character-inspired styles, not Thrall or Sylvanas recordings or voice clones.

## Experimental limits

The app reads screen images only: no game injection, memory inspection, game-file changes, addon installation or automated inputs. **These boundaries do not establish Blizzard permission for live assistance; approval has not been obtained.** This project is not affiliated with Blizzard Entertainment.

Screenshots cannot establish hidden cooldowns or accurately measure every rotation. Advice can arrive seconds late and is unsuitable for split-second raid mechanics. Current beta references may lag hotfixes. Complete verified farming routes, live auction prices, drop rates, raid strategies and universally optimal builds are not yet covered. Real WoW gameplay accuracy and game-FPS impact have not been validated.
