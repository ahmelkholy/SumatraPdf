# SumatraPDF Enhanced Configuration

A custom configuration for SumatraPDF with Vim-like key bindings and optimized workflows.

## Features

- **Vim-style Navigation**: Complete navigation with `h`, `j`, `k`, `l` keys and enhanced scrolling
- **Advanced Key Bindings**: Custom shortcuts for all common PDF operations
- **Dark Theme**: Optimized dark theme for comfortable reading
- **Folder Navigation**: Open folders directly with `o` key
- **Annotation Tools**: Quick access to annotations with customizable colors
- **Tab Management**: Vim-style tab navigation with `gt` and `gT`
- **Command Palette**: Access to command palette via `Ctrl+k`

## Key Bindings

### Navigation

- `h` / `l` - Scroll left/right
- `j` / `k` - Scroll down/up (3 lines at a time)
- `Ctrl+d` / `Ctrl+u` - Scroll half page down/up
- `gg` - Go to first page
- `G` - Go to last page
- `space` - Next page
- `b` - Previous page

### File Operations

- `o` - Open selected document/folder
- `Ctrl+o` - Open file browser
- `q` - Close document
- `w` - Save as

### Search

- `/` - Find text
- `n` / `N` - Find next/previous

### Zoom

- `zp` - Zoom to fit page
- `zw` - Zoom to fit width
- `zf` - Zoom to fit content
- `zz` - Zoom to 100%
- `+` / `-` - Zoom in/out

### Annotations

- `a` - Highlight (yellow)
- `Shift+a` - Highlight (green) with edit
- `u` - Underline
- `dd` - Delete annotation
- `e` - Edit annotations
- `s` - Save annotations

### View Options

- `f` - Toggle fullscreen
- `i` - Invert colors
- `r` / `R` - Rotate right/left
- `c` - Toggle continuous view

## Installation

1. Install SumatraPDF from [the official website](https://www.sumatrapdfreader.org/)
2. Copy the `SumatraPDF-settings.txt` file to:
   - Windows: `%APPDATA%\SumatraPDF` or `C:\Users\<username>\AppData\Local\SumatraPDF`

## Customization

You can further customize the settings by editing the `SumatraPDF-settings.txt` file. For more information on available options, see the [SumatraPDF documentation](https://www.sumatrapdfreader.org/settings/settings3-6.html).

## Version

This configuration is optimized for SumatraPDF version 3.6+.

Last updated: April 2025
