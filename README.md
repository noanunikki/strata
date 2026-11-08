# Strata

A 2D and 3D game engine with a real code editor. Make games with scenes, components, inspectors, physics,
tilemaps, 3D models and C# scripts that hot reload.

**[Download Strata Hub for macOS](https://github.com/noanunikki/strata/releases/latest/download/Strata-Hub-macOS-arm64.zip)**
(Apple Silicon, macOS 11 or newer, 70 MB) &middot; [Website](https://noanunikki.github.io/strata/)

## Install

1. Download the zip and move **Strata Hub** to your Applications folder.
2. The first launch is blocked because the app is not notarized yet. Open **System Settings → Privacy & Security** and click **Open Anyway**, or run once:
   ```
   xattr -dr com.apple.quarantine "/Applications/Strata Hub.app"
   ```
3. Strata keeps itself up to date. When you open the Hub it installs a newer version and restarts by itself (if you close the Hub during a download, it finishes first). You can turn this off in Preferences.
4. Create a project in the Hub. Opening a project starts the editor as a separate app called Strata (like Unity Hub and Unity); the Hub stays open. The *2D Platformer demo* template is a good start.

## About this repository

This repository contains the website and the downloads (see **Releases**). The source code is not published.

Strata is free to use, including for commercial games, but it is not open source. See [LICENSE](LICENSE)
and [THIRD-PARTY-NOTICES.md](THIRD-PARTY-NOTICES.md).

Version 0.4.1, early release, provided as is.
