# poe-diff

A lightweight, standalone CLI item diff tool for Path of Exile. Built specifically for Wayland users who want quick item comparisons without overlay overhead.

## Requirements
* Python 3
* `wl-clipboard` (Wayland) or `xclip` (X11)

## Usage
```bash
# Compare 1 new item against equipped
poe-diff

# Compare 3 new items against 1 equipped
poe-diff -n 3

# Ring Mode: Compare 1 new ring against Ring 1 & Ring 2
poe-diff -r
