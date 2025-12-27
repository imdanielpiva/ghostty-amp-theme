# ghostty-amp-theme

A Ghostty terminal color theme based on the [Amp Code](https://ampcode.com) website color palette. Features a warm, carefully-crafted dark theme optimized for extended coding sessions.

## Features

- **Amp Color Palette**: Uses the official Amp Dark theme colors
- **High Contrast**: Dark background (#0F0F0F) with warm foreground (#F2ECDD)
- **Warm Accent**: Primary accent color #E7894C (warm orange) for UI elements
- **Complete ANSI Colors**: Full set of regular and bright color variants for TUI applications

## Installation

### Quick Install

Copy the theme file to your Ghostty config directory:

```bash
mkdir -p ~/.config/ghostty/themes
cp amp-dark ~/.config/ghostty/themes/
```

### Ghostty Configuration

Add to your `~/.config/ghostty/config`:

```
theme = amp-dark
```

## Colors

| Element | Color | Usage |
|---------|-------|-------|
| Background | `#0F0F0F` | Terminal background |
| Foreground | `#F2ECDD` | Default text color |
| Cursor | `#E7894C` | Cursor/selection |
| Primary Accent | `#E7894C` | UI highlights |

The theme includes a complete set of ANSI colors (0-15) for compatibility with TUI applications and syntax highlighting.

## About Amp Code

This theme is inspired by the design language of [Amp Code](https://ampcode.com), an AI-powered coding agent with a beautiful, thoughtful color palette.

## License

MIT License - See LICENSE file for details
