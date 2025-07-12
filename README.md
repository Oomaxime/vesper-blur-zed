# VesperBlur - Zed Theme with macOS Transparency

An elegant dark theme for the Zed editor, inspired by Vesper with transparency.

## 🎨 Overview

VesperBlur combines the signature "peppermint and orange" color palette from the original Vesper theme with transparency and blur effects, creating a modern and aesthetic coding experience.

### Key Features

- ✨ **Transparency** with automatic blur effects
- 🍑 **Authentic Vesper palette**: peach orange (#FFC799) and turquoise (#99FFE4)
- 🔍 **Optimized readability** with carefully adjusted contrast ratios
- 🎯 **All UI elements** adapted for transparency

## 📦 Installation

### Method 1: Quick Installation

1. Download `vesper-blur.json` from the `themes/` folder
2. Copy to your Zed themes directory:
   ```bash
   # macOS
   cp themes/vesper-blur.json ~/Library/Application\ Support/Zed/themes/

   # Linux
   cp themes/vesper-blur.json ~/.config/zed/themes/

   # Windows
   # Copy to %APPDATA%\\Zed\\themes\\
   ```

3. In Zed: `Cmd+,` → Theme → "VesperBlur Dark"

### Method 2: As Zed Extension (Recommended)

1. Clone this repository
2. Copy the entire folder to Zed extensions directory:
   ```bash
   # macOS
   cp -r . ~/Library/Application\ Support/Zed/extensions/vesper-blur/
   ```

3. Restart Zed and select the theme in preferences

### Method 3: Via Zed Extensions Registry

Coming soon! This theme will be submitted to the official Zed extensions registry.

## 🎨 Color Palette

| Element | Color | Usage |
|---------|--------|--------|
| Primary Orange | `#FFC799` | Functions, types, keywords |
| Turquoise | `#99FFE4` | Strings, links, hints |
| Pure White | `#FFFFFF` | Primary text, variables |
| Light Gray | `#A0A0A0` | Secondary text, operators |
| Medium Gray | `#7E7E7E` | Placeholders, line numbers |
| Transparent Black | `#10101080` | Backgrounds with 50% alpha |

## 🔧 Customization

To adjust transparency levels, modify the alpha values in `themes/vesper-blur.json`:

- `80` = 50% transparency (recommended for panels)
- `60` = 63% transparency (inactive tabs)
- `40` = 75% transparency (subtle elements)

## 🤝 Contributing

Suggestions and improvements are welcome! Feel free to open issues or submit pull requests.

## 📄 License

MIT License - Inspired by the original Vesper theme by Rauno Freiberg.

## 🙏 Credits

- Original Vesper theme: [raunofreiberg/vesper](https://github.com/raunofreiberg/vesper)
- Rich Vesper Zed: [zezic/rich-vesper-zed](https://github.com/zezic/rich-vesper-zed)
- Vesper Zed: [bdsqqq/vesper-zed](https://github.com/bdsqqq/vesper-zed)
