# Schulte Table Trainer

A browser-based [Schulte table](https://en.wikipedia.org/wiki/Schulte_table) trainer for improving peripheral vision, attention, and reading speed. No install needed — open `index.html` directly or visit the live site.

**Live site:** http://www.artkpv.net/schulte/

Fork of [qqwref/schulte](https://github.com/qqwref/schulte).

## Features

**Grid & rounds**
- Grid size from 2×2 to 30×30
- Multiple rounds (1, 2, 3, 5, 10, 25, 100) with optional breaks between rounds
- 1–5 number groups with configurable colors; inverse, divergent, and various-count modes
- Number offset

**Display modes**
- Shuffle Numbers — reshuffle the grid on every correct click
- Turn / Spin Numbers — rotate individual symbols
- Spin Table — rotate the whole grid (6 speed/direction options)
- Flashlight Mode — only the area near the cursor is visible
- Blind Mode — numbers disappear after the first click
- Hover Mode — advance by hovering instead of clicking
- Frenzy Mode — click the same number multiple times before it advances (React variant: click appears without a number)
- Left/Right Click Colors — color-code cells by which mouse button was used

**Feedback & sound**
- Show Hover highlight
- Show Correct Cells (trace)
- Empty Correct Cells after clicking
- Click animation and result indicator
- Optional click sound
- Center dot guide
- Start Timer on Click (timer starts with the first click, not when the dialog closes)
- No Errors mode — wrong clicks are ignored

**Stats (after each game)**
- Total time and personal best per category
- Per-click breakdown table with times
- Round-by-round time graph (multi-round games)
- Mouse heatmap

**History (persistent, stored in `localStorage`)**
- Every completed game is saved (up to 1000 entries)
- Per-category aggregates: games played, best time, average time
- Scrollable recent-games table across all categories
- Clear History button

## Usage

Open `index.html` in any modern browser. Configure settings in the dialog, press **Start Test**, click the numbers in order (1 → 2 → 3 … or as configured). The dialog reopens automatically when the game ends.

Keyboard shortcuts: `Esc` to resume/skip round break, `Space` to open settings, `Enter` to close the dialog.
