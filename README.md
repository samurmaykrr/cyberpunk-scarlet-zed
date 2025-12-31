# 🔴 Cyberpunk Scarlet for Zed

<p align="center">
  <a href="https://github.com/samurmaykrr/cyberpunk-scarlet-zed/stargazers">
    <img src="https://img.shields.io/github/stars/samurmaykrr/cyberpunk-scarlet-zed?colorA=161620&colorB=ea3355&style=for-the-badge">
  </a>
  <a href="https://github.com/samurmaykrr/cyberpunk-scarlet-zed/issues">
    <img src="https://img.shields.io/github/issues/samurmaykrr/cyberpunk-scarlet-zed?colorA=161620&colorB=faf968&style=for-the-badge">
  </a>
  <a href="https://github.com/samurmaykrr/cyberpunk-scarlet-zed/contributors">
    <img src="https://img.shields.io/github/contributors/samurmaykrr/cyberpunk-scarlet-zed?colorA=161620&colorB=64d98c&style=for-the-badge">
  </a>
</p>

<p align="center">
  A cyberpunk-inspired theme for <a href="https://zed.dev">Zed</a> with scarlet red accents
</p>

## 📸 Preview

<details>
<summary>🌙 Cyberpunk Scarlet Protocol (Dark)</summary>
<!-- Add screenshot here -->
<img src="assets/preview-dark.png" alt="Cyberpunk Scarlet Protocol Dark Theme">
</details>

<details>
<summary>✨ Cyberpunk Scarlet Protocol (Dark + Blur)</summary>
<!-- Add screenshot here -->
<img src="assets/preview-dark-blur.png" alt="Cyberpunk Scarlet Protocol Dark Blur Theme">
</details>

<details>
<summary>☀️ Cyberpunk Scarlet Light (Light)</summary>
<!-- Add screenshot here -->
<img src="assets/preview-light.png" alt="Cyberpunk Scarlet Light Theme">
</details>

<details>
<summary>💫 Cyberpunk Scarlet Light (Light + Blur)</summary>
<!-- Add screenshot here -->
<img src="assets/preview-light-blur.png" alt="Cyberpunk Scarlet Light Blur Theme">
</details>

## ✨ Features

- **Dark Mode**: Deep cyberpunk aesthetics with scarlet red highlights
- **Light Mode**: Clean, futuristic light variant with scarlet accents
- **Blur Variants**: Both dark and light themes include blur variants for a modern, translucent effect
- **Terminal Support**: Carefully crafted ANSI colors based on the Cyberpunk Scarlet Protocol iTerm2 theme
- **Syntax Highlighting**: Optimized for readability with vibrant cyberpunk-inspired colors

> **Note**: The blur effect may not work on all operating systems. This is a limitation of Zed's window transparency implementation. If you experience issues with blur, please use the standard (non-blur) variants or report issues to the [Zed repository](https://github.com/zed-industries/zed).

## 📦 Installation

### From Zed Extensions

1. Open Zed
2. Open the command palette (<kbd>Cmd</kbd>+<kbd>Shift</kbd>+<kbd>P</kbd> / <kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>P</kbd>)
3. Type _zed: extensions_ and press Enter
4. Search for _Cyberpunk Scarlet_ and click Install
5. Open the command palette again and type _theme selector: toggle_
6. Select your preferred variant:
   - **Cyberpunk Scarlet Protocol** - Dark theme
   - **Cyberpunk Scarlet Protocol (Blur)** - Dark theme with blur effect
   - **Cyberpunk Scarlet Protocol Light** - Light theme
   - **Cyberpunk Scarlet Protocol Light (Blur)** - Light theme with blur effect

### Manual Installation (Development)

1. Clone this repository:
   ```bash
   git clone https://github.com/samurmaykrr/cyberpunk-scarlet-zed.git
   ```
2. Open Zed and navigate to Extensions panel
3. Click "Install Dev Extension" and select the cloned repository folder
4. Restart Zed and activate the theme

## 🎨 Color Palette

The theme features a carefully selected color palette inspired by cyberpunk aesthetics:

### Dark Variant
- **Primary**: `#ea3355` - Scarlet Red
- **Background**: `#101116` - Deep Space
- **Editor**: `#161620` - Midnight Blue
- **Text**: `#c7c7c7` - Silver
- **Accent**: `#d13454` - Crimson

### Light Variant
- **Primary**: `#d13454` - Crimson
- **Background**: `#f5f5f5` - Ghost White
- **Editor**: `#ffffff` - Pure White
- **Text**: `#2a2a35` - Charcoal
- **Accent**: `#ea3355` - Scarlet Red

## 🔧 Development

To modify or contribute to this theme:

1. Fork this repository
2. Make your changes to the theme files in `themes/`
3. Test the theme in Zed using "Install Dev Extension"
4. Submit a pull request with your improvements

### Project Structure

```
cyberpunk-scarlet/
├── .github/
│   └── workflows/     # CI/CD workflows
├── assets/            # Screenshots and preview images
├── themes/            # Theme JSON files
│   ├── cyberpunk-scarlet.json
│   └── cyberpunk-scarlet-blur.json
├── extension.toml     # Extension metadata
├── LICENSE            # MIT License
└── README.md          # This file
```

## 📄 License

This theme is licensed under the MIT License. See [LICENSE](LICENSE) for more information.

## 🙏 Acknowledgments

- Based on the [Cyberpunk Scarlet Protocol iTerm2 theme](https://github.com/Cyberpunk-Scarlet-Protocol/iTerm2-Color-Schemes)
- Inspired by cyberpunk aesthetics and neon-lit cityscapes
- Special thanks to the Zed community

## 💬 Feedback

Found a bug or have a suggestion? Please [open an issue](https://github.com/samurmaykrr/cyberpunk-scarlet-zed/issues) on GitHub.

---

<p align="center">
  Made with ❤️ for the cyberpunk community
</p>
