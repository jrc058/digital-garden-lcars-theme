# LCARS Theme for Obsidian Digital Garden

An authentic Star Trek LCARS (Library Computer Access/Retrieval System) interface theme for the Obsidian Digital Garden plugin.

![LCARS Theme Preview](preview.png)

## Features

- **Authentic LCARS Design**: Based on the official Star Trek color palette and design language
- **Responsive**: Works on desktop and mobile devices
- **Optimized for Reading**: High contrast text with carefully chosen colors
- **Animated Elements**: Subtle animations that enhance the LCARS feel
- **Typography**: Uses condensed fonts similar to the original LCARS displays

## Installation

### Method 1: Direct URL (Recommended)

Add this to your Digital Garden settings in Obsidian:

```json
{
  "theme": {
    "name": "LCARS",
    "author": "jrc058",
    "repo": "jrc058/digital-garden-lcars-theme",
    "cssUrl": "https://raw.githubusercontent.com/jrc058/digital-garden-lcars-theme/main/theme.css"
  }
}
```

### Method 2: Custom CSS

1. Copy the contents of `theme.css`
2. Paste into your Digital Garden's `styleSettingsCss` field in the plugin settings

## Color Palette

The theme uses the official LCARS color scheme:

- **Primary Orange**: `#ff9933` (Neon Carrot)
- **Secondary Purple**: `#664466` (Eggplant)
- **Accent Blue**: `#99ccff` (Anakiwa)
- **Success Green**: `#99dd66` (Martian)
- **Danger Red**: `#e10e10` (Red Alert)
- **Background**: `#000000` (Pure Black)

## Typography

The theme works best with these fonts (automatically loaded):
- Antonio (headings)
- Oswald (body)
- Ubuntu Mono (code blocks)

Fallbacks are provided for systems without these fonts.

## Customization

You can override any CSS variable in your custom CSS:

```css
:root {
  --color-primary: #your-color;
  --gap: 2rem; /* Adjust spacing */
}
```

## Credits

- Based on [Pi-hole LCARS Next Generation](https://github.com/MichalSvatos/pi-hole-lcars-next-gen) by @MichalSvatos
- LCARS design © Paramount Pictures
- Built for [Obsidian Digital Garden](https://github.com/oleeskild/obsidian-digital-garden)

## License

MIT License - See LICENSE file for details

## Support

Found a bug or have a suggestion? [Open an issue](https://github.com/jrc058/digital-garden-lcars-theme/issues)
