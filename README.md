# Jellybeans for Obsidian

A dark theme for [Obsidian](https://obsidian.md) combining the classic **Jellybeans** color scheme with **Flexoki** backgrounds.

![Jellybeans Theme Preview](screenshots/preview.png)

## Features

- **Jellybeans Vibrant** accent colors for syntax highlighting and UI elements
- **Flexoki dark** backgrounds for comfortable extended reading
- **Rainbow headings** - each heading level has a distinct color
- **QuillCode-style tabs** with rounded corners
- **Graph view** styled with Jellybeans colors
- **No font overrides** - respects your font settings

## Color Philosophy

This theme marries two beloved color schemes:

| Component | Source | Why |
|-----------|--------|-----|
| Backgrounds | [Flexoki](https://stephango.com/flexoki) | Warm, paper-like darks that reduce eye strain |
| Accents | [Jellybeans](https://github.com/WTFox/jellybeans.nvim) | Classic vim colors, vibrant but not harsh |

## Installation

### From Obsidian Community Themes (Coming Soon)

1. Open **Settings** → **Appearance** → **Themes**
2. Click **Manage** and search for "Jellybeans"
3. Click **Install and use**

### Manual Installation

1. Download `manifest.json` and `theme.css` from this repository
2. Create a folder called `Jellybeans` in your vault's `.obsidian/themes/` directory
3. Copy both files into the `Jellybeans` folder
4. Open **Settings** → **Appearance** → **Themes** and select **Jellybeans**

### For Development

```bash
# Clone the repository
git clone https://github.com/imrellx/jellybeans-obsidian.git

# Symlink to your vault's themes folder
ln -s /path/to/jellybeans-obsidian /path/to/vault/.obsidian/themes/Jellybeans
```

## Color Palette

### Backgrounds (Flexoki Dark)

| Variable | Hex | Preview |
|----------|-----|---------|
| Base | `#100F0F` | ![#100F0F](https://via.placeholder.com/20/100F0F/100F0F) |
| Surface | `#1C1B1A` | ![#1C1B1A](https://via.placeholder.com/20/1C1B1A/1C1B1A) |
| Overlay | `#282726` | ![#282726](https://via.placeholder.com/20/282726/282726) |
| Text | `#CECDC3` | ![#CECDC3](https://via.placeholder.com/20/CECDC3/CECDC3) |

### Accents (Jellybeans Vibrant)

| Color | Hex | Use | Preview |
|-------|-----|-----|---------|
| Red | `#cc4d4d` | Errors, tags | ![#cc4d4d](https://via.placeholder.com/20/cc4d4d/cc4d4d) |
| Green | `#99ad6a` | Strings, success | ![#99ad6a](https://via.placeholder.com/20/99ad6a/99ad6a) |
| Yellow | `#fad07a` | Numbers, warnings | ![#fad07a](https://via.placeholder.com/20/fad07a/fad07a) |
| Blue | `#8197bf` | Links, keywords | ![#8197bf](https://via.placeholder.com/20/8197bf/8197bf) |
| Purple | `#c6b6ee` | Properties | ![#c6b6ee](https://via.placeholder.com/20/c6b6ee/c6b6ee) |
| Cyan | `#668799` | Comments | ![#668799](https://via.placeholder.com/20/668799/668799) |
| Orange | `#e6a75a` | Values | ![#e6a75a](https://via.placeholder.com/20/e6a75a/e6a75a) |

### Heading Colors

| Level | Color | Hex |
|-------|-------|-----|
| H1 | Bright Blue | `#8fbfdc` |
| H2 | Purple | `#c6b6ee` |
| H3 | Green | `#99ad6a` |
| H4 | Yellow | `#fad07a` |
| H5 | Orange | `#e6a75a` |
| H6 | Cyan | `#668799` |

## Credits

This theme stands on the shoulders of giants:

- **[Jellybeans.vim](https://github.com/nanotech/jellybeans.vim)** by nanotech - The original Jellybeans color scheme
- **[jellybeans.nvim](https://github.com/WTFox/jellybeans.nvim)** by WTFox - Modern Neovim port with multiple variants
- **[Flexoki](https://stephango.com/flexoki)** by Steph Ango - The inky background palette
- **[flexoki-obsidian](https://github.com/kepano/flexoki-obsidian)** by kepano - Flexoki implementation for Obsidian
- **[QuillCode](https://github.com/theaayushpatel/quillcode)** by Aayush Patel - Tab styling inspiration

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

[MIT](LICENSE) - Use it, modify it, share it.

## Support

If you enjoy this theme, consider:

- Starring this repository
- Sharing it with others
- [Reporting issues](https://github.com/imrellx/jellybeans-obsidian/issues) if you find bugs
