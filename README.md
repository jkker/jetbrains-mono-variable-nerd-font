# JetBrains Mono Nerd Font

<p align="center">
  <b>JetBrains Mono + Nerd Fonts glyphs</b><br>
  <sub>A programmer's font with all the icons you need</sub>
</p>

<p align="center">
  <a href="../../releases/latest/download/JetBrainsMonoNerdFont-Regular.ttf">
    <img src="https://img.shields.io/badge/Download-Regular-00D4AA?style=for-the-badge&logo=download&logoColor=white" alt="Download Regular">
  </a>
  <a href="../../releases/latest/download/JetBrainsMonoNerdFont-Italic.ttf">
    <img src="https://img.shields.io/badge/Download-Italic-FF6B6B?style=for-the-badge&logo=download&logoColor=white" alt="Download Italic">
  </a>
</p>

<p align="center">
  <a href="../../releases"><img src="https://img.shields.io/github/v/release/jkker/jetbrains-mono-variable-nerd-font?color=blue&label=Latest%20Release&style=flat-square" alt="Latest Release"></a>
  <a href="https://github.com/JetBrains/JetBrainsMono"><img src="https://img.shields.io/badge/Upstream-JetBrains%20Mono-orange?style=flat-square" alt="Upstream"></a>
  <a href="https://github.com/ryanoasis/nerd-fonts"><img src="https://img.shields.io/badge/Patched%20with-Nerd%20Fonts-purple?style=flat-square" alt="Nerd Fonts"></a>
</p>

---

## About

This repository automatically patches [JetBrains Mono](https://github.com/JetBrains/JetBrainsMono) — a typeface for developers — with thousands of extra glyphs from [Nerd Fonts](https://github.com/ryanoasis/nerd-fonts), including:

- Programming ligatures
- File type icons
- Powerline symbols
- Devicons, Font Awesome, and more

## How It Works

```
JetBrains Mono ──► Variable Fonts ──► Static Instances ──► Nerd Fonts Patch ──► Release
```

| Step | Description |
|------|-------------|
| 1. **Monitor** | Watch [JetBrains Mono](https://github.com/JetBrains/JetBrainsMono) for new releases |
| 2. **Download** | Fetch the latest variable font files |
| 3. **Convert** | Generate static Regular & Italic instances |
| 4. **Patch** | Add complete Nerd Fonts glyph set |
| 5. **Publish** | Create GitHub Release matching upstream version |

## Versioning

This project follows upstream versioning. When JetBrains releases `v2.305`, this repo automatically publishes `v2.305`.

## Installation

### Quick Install

1. Download both font files above ☝️
2. Install on your system:
   - **macOS**: Double-click → "Install Font"
   - **Linux**: Copy to `~/.local/share/fonts/` or `/usr/share/fonts/`
   - **Windows**: Right-click → "Install"

### Via Release Page

Browse all releases: [**Releases**](../../releases)

## Manual Release

```bash
gh workflow run patch.yml
```

## Fonts Included

| File | Style | Glyphs |
|------|-------|--------|
| `JetBrainsMonoNerdFont-Regular.ttf` | Regular | JetBrains Mono + Nerd Fonts Complete |
| `JetBrainsMonoNerdFont-Italic.ttf` | Italic | JetBrains Mono + Nerd Fonts Complete |

## License

| Component | License |
|-----------|---------|
| JetBrains Mono | [OFL-1.1](https://github.com/JetBrains/JetBrainsMono/blob/master/OFL.txt) |
| Nerd Fonts | [MIT](https://github.com/ryanoasis/nerd-fonts/blob/master/LICENSE) |

---

<p align="center">
  <sub>Automatically updated daily • <a href="../../actions">View Workflow Runs</a></sub>
</p>
