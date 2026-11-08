# CyberPhunk

> _the fook is in the machine_
> _that's P-Funk in the machine. that's funkadelic, baby._

<p align="center">
  <img src="preview.png" width="560" alt="CYBERPHUNK — the neon wordmark this theme paints everywhere">
</p>

It's 2077 on your desktop, and the neon is the new black. The Mothership glow meets a funky James Brown "Cold Sweat" groove run through a synthesizer. We don't get it — we *got* it.

CyberPhunk is a desktop theme for [Omarchy](https://omarchy.org): a shared cyan, pink and amber palette, neon Hyprland borders, matching icons and cosmic-funk wallpapers. The root `colors.toml` is the palette source; Omarchy applies it across the desktop, terminals, editors, bar and lock screen.

**[![omarchytheme.com](https://img.shields.io/badge/omarchytheme.com-in%20the%20gallery-blue?style=flat-square)](https://omarchytheme.com)**
[![License: MIT](https://img.shields.io/badge/license-MIT-green?style=flat-square)](LICENSE)

## Desktop preview

![CyberPhunk running on Omarchy with Neovim and btop](desktop.png)

## The palette

One hex, the whole rig. The signature is **cyan `#22e4ff` → magenta `#ff6bd6`** on the active border:

| | | | | | | |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| <img src="https://img.shields.io/badge/CYAN-22E4FF-22e4ff?style=flat-square&label=" width="132"> | <img src="https://img.shields.io/badge/MAGENTA-FF6BD6-ff6bd6?style=flat-square&label=" width="132"> | <img src="https://img.shields.io/badge/ORANGE-FF7A33-ff7a33?style=flat-square&label=" width="132"> | <img src="https://img.shields.io/badge/GREEN-44FFAA-44ffaa?style=flat-square&label=" width="132"> | <img src="https://img.shields.io/badge/BLUE-3AC8FF-3ac8ff?style=flat-square&label=" width="132"> | <img src="https://img.shields.io/badge/RED-FF3B6B-ff3b6b?style=flat-square&label=" width="132"> | <img src="https://img.shields.io/badge/PAPER-E8FCFF-060a14?style=flat-square&label=" width="132"> |
| `#22e4ff` | `#ff6bd6` | `#ff7a33` | `#44ffaa` | `#3ac8ff` | `#ff3b6b` | `#e8fcff` |

All sixteen colors live in `colors.toml`.

## Install

Open the Omarchy menu with **Super + Space**, choose **Install → Style → Theme**, and paste this repository's GitHub URL. Then select CyberPhunk from the theme menu.

```text
https://github.com/derejealemu/omarchy-cyberphunk-theme
```

## What's included

- `colors.toml` — the desktop palette.
- `hyprland.conf` — the neon cyan-to-magenta active-window border.
- `backgrounds/*.webp` — four cosmic-funk wallpapers.
- `preview.png`, `preview-unlock.png`, `unlock.png` — theme and unlock artwork.
- `icons.theme` — the icon-set preference.
- `lazygit.yml` — an optional matching lazygit palette.

## Uninstall

Select the theme you used before in Omarchy, then remove CyberPhunk's theme directory:

```sh
rm -rf ~/.config/omarchy/themes/cyberphunk
```

## Repo layout

```
colors.toml              # desktop palette
hyprland.conf            # active-window border
backgrounds/*.webp       # compressed wallpapers
preview.png              # theme preview
preview-unlock.png       # unlock preview
unlock.png               # unlock artwork
icons.theme              # icon-set preference
lazygit.yml              # optional lazygit palette
README.md  LICENSE  AGENTS.md
```

## Develop

Edit the theme files and preview them with Omarchy's theme menu. Keep the gallery screenshot current when the desktop's appearance changes.

## License

MIT — see `LICENSE`.
