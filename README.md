# Sprite Sheet Studio

> A browser-based sprite sheet studio for video, image sequences, and sprite slicing.

Sprite Sheet Studio is a browser-based sprite production tool for turning image sequences, videos, or existing sprite sheets into clean export assets.

## Live Preview

- [https://heymelo.github.io/sprite-sheet-studio/](https://heymelo.github.io/sprite-sheet-studio/)

It is designed to be easy to open locally, fast to iterate on, and practical for everyday asset prep work such as:

- extracting frames from video
- slicing existing sprite sheets
- removing flat-color backgrounds
- trimming transparent bounds
- exporting PNG, WebP, GIF, JSON metadata, and ZIP bundles

## Features

- Import image sequences, video files, or sprite sheets
- Adjustable sprite sheet columns, padding, playback FPS, hue, and saturation
- Video extraction controls for start time, duration, and sampling FPS
- Background color picking with tolerance-based transparency removal
- Optional trim with padding and alpha threshold controls
- Optional export-time frame deduplication
- Export sprite sheets as PNG, WebP, or transparent GIF
- Export frame sequences as PNG or WebP
- Export metadata JSON and ZIP bundles with sheet + frames + metadata

## Quick Start

This project is a static web app. You can use it without a build step.

### Option 1

Open [`index.html`](./index.html) directly in a browser.

### Option 2

Serve the folder with any static file server, for example:

```bash
cd /path/to/sprite-sheet-studio
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## Project Structure

- [`index.html`](./index.html): the entire app UI and logic
- [`others/`](./others): app icons and supporting static assets

## Fork Origin

This repository is a cleaned-up and extended fork of:

- [xieyoujune/GBG-Sprite-Sheet-Maker-For-Godot](https://github.com/xieyoujune/GBG-Sprite-Sheet-Maker-For-Godot)

The fork direction is to make the tool more neutral, reusable, and production-friendly for general sprite workflows rather than a personal-branded project page.
