# MaTo - Torrent Client

> **Created by esc's Services** — a small, clean, terminal-based torrent client for Windows using `aria2c`.
> https://discord.gg/uJVGveeZEd

## Features

- CMD interface with a **Main Menu** you can drive with arrow keys **and** your mouse
- **Install Torrent** – paste a magnet link, pick a folder, download starts
- **Catalogue** – browse a paginated list of torrents getting update daily/weekly
- **Download list** – live progress, speed, peers; pause/resume/delete
- **History view** – finished downloads with size, date and folder (`T` to toggle)
- **Crash-proof** – state is mirrored to `history.json`; **resume** interrupted downloads on next start
- Version footer (`MaTo 0.1.1 (BETA)`) bottom-right, no extra dependencies (standard library only)

## Requirements

- Windows
- Python 3.7+
- `aria2c.exe` in the `reqs/` folder

## Setup

1. Install Python 3.7+ (add it to your PATH).
2. Download the Windows build of **aria2** from the [official site](https://aria2.github.io/)
   or the [GitHub releases](https://github.com/aria2/aria2/releases).
3. Place `aria2c.exe` inside `reqs/` so that `reqs/aria2c.exe` exists.
4. Double-click **`run.bat`**.

## Usage

- `UP` / `DOWN` — navigate
- `ENTER` — select
- `ESC` — back / exit
- Mouse: hover to highlight, click to select/activate, wheel to scroll, double-click to install from the catalogue
- `T` — toggle Download list / History in the downloads view
