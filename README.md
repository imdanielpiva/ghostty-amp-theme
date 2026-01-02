# ghostty-amp-theme

A Ghostty terminal color theme based on the [Amp Code](https://ampcode.com) website color palette. Includes warm dark and light variants optimized for extended coding sessions.

## Features

- **Amp Color Palette**: Uses the official Amp Dark and Amp Light theme colors
- **Two Variants**: `amp-dark` and `amp-light`
- **Warm Accents**: Orange/red accents for UI elements and selection
- **Complete ANSI Colors**: Full set of regular and bright color variants for TUI applications

## Installation

### Quick Install

Copy the theme file to your Ghostty config directory:

```bash
mkdir -p ~/.config/ghostty/themes
cp amp-dark amp-light ~/.config/ghostty/themes/
```

### Ghostty Configuration

Add to your `~/.config/ghostty/config`:

```
theme = amp-dark
# or
theme = amp-light
```

## Colors

**Amp Dark**

| Element | Color | Usage |
|---------|-------|-------|
| Background | `#0F0F0F` | Terminal background |
| Foreground | `#F2ECDD` | Default text color |
| Cursor | `#E7894C` | Cursor/selection |
| Primary Accent | `#E7894C` | UI highlights |

**Amp Light**

| Element | Color | Usage |
|---------|-------|-------|
| Background | `#F8F8F8` | Terminal background |
| Foreground | `#2A2A2A` | Default text color |
| Cursor | `#D9634F` | Cursor/selection |
| Primary Accent | `#D9634F` | UI highlights |

The theme includes a complete set of ANSI colors (0-15) for compatibility with TUI applications and syntax highlighting.

## About Amp Code

This theme is inspired by the design language of [Amp Code](https://ampcode.com), an AI-powered coding agent with a beautiful, thoughtful color palette.

## License

MIT License - See LICENSE file for details
