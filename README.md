# OpenConstruction Desktop downloads

Public macOS installers for OpenConstruction Desktop. This repository contains release assets and installation information only; the development source is maintained separately.

## Current Mac preview

[Download OpenConstruction 0.3.2 Preview 5 for Apple Silicon](https://github.com/Ben11304/OpenConstruction-downloads/releases/download/v0.3.2-preview.5/OpenConstruction-0.3.2-preview.5-mac-arm64.dmg)

Preview 5 replaces Preview 4, which could exit at launch because of an ad hoc signing error.

Requires macOS 13 or later and an Apple Silicon Mac (M1 or newer). Quit any previous copy, open the DMG, drag **OpenConstruction** into **Applications**, eject the DMG, then open the app. The first launch needs an internet connection to install locked research dependencies. Existing projects and settings remain in `~/Library/Application Support/OpenConstruction` when the app is replaced.

The app includes the research engine, Codex CLI, Claude Code runtime, and offline catalog. Connect Codex from **Research → Models** to start. Claude account login is available as a beta. OpenConstruction MCP is included by default.

This preview is ad hoc signed and is not Apple notarized. If macOS blocks it, try opening it once, then choose **Open Anyway** in **System Settings → Privacy & Security**. The release page provides a SHA-256 checksum for the DMG. The installer contains no personal projects, datasets, accounts, or credentials.

[View release notes and checksum](https://github.com/Ben11304/OpenConstruction-downloads/releases/tag/v0.3.2-preview.5)
